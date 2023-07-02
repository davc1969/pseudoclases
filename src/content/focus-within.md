---
id: focus-within
idn: 55
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within
title: :focus-within
description: 'Representa a un contenedor que contiene a otros elementos que pueden tener el foco en algún momento.  Si cualquier elemento dentoro del contenedor obtiene el foco, por hacer click con el mouse o por el teclado, el contenedor también puede cambiar sus estilos con esta pseudoclase.
'
---

<pre is:raw>
html:
  &lt;form&gt;
  &nbsp;&nbsp;&lt;label for="text1"&gt;Ingrese su nombre&lt;/label&gt;
  &nbsp;&nbsp;&lt;input type="text" id="text1"&gt;

  &nbsp;&nbsp;&lt;label for="text2"&gt;Ingrese correo&lt;/label&gt;
  &nbsp;&nbsp;&lt;input type="text" id="text2"&gt;
  &lt;/form&gt;

  css:
form:focus-within {
&nbsp;&nbsp;outline: 2px solid gray;
&nbsp;&nbsp;background: pink;
}


</pre>
<div class="codebox" id="codebox-focus-within">
  <form id="frm_focus-within">
    <label for="text1"></label>Ingrese su nombre</label>
    <input type="text" id="text1">
    <br>
    <label for="text2">Ingrese correo</label>
    <input type="text" id="text2">
  </form>
</div>

<style>
  #frm_focus-within {
    
    color: black;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #frm_focus-within input[type = "text"] {
    width: 70%;
  }

  #codebox-focus-within:focus-within {
    outline: 2px solid gray;
    background: pink;
  }

  pre {
    white-space: pre-line;
  }

</style>
