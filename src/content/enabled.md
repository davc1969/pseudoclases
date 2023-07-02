---
id: enabled
idn: 35
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:enabled
title: :enabled
description: 'Representa a cualquier elemento que esté habilitado.  Un elemento está habilitado si se puede activar, hacer click sobre él, escribir o interactuar con él o si es capaz de recibir el foco.<br>
Por defecto todos los elementos dentro de un documento están habilitados.<br>
Esta pseudoclase equivale al caso opuesto de <a href="disabled">:disabled</a>.
'
---

<pre is:raw>
html:
  &lt;label for="text1"&gt;Ingrese su nombre (habilitado)&lt;/label&gt;
  &lt;input type="text" id="text1"&gt;

  &lt;label for="text2"&gt;Ingrese correo (deshabilitado)&lt;/label&gt;
  &lt;input type="text" id="text2" disabled&gt;


css:
input[type = "text"]:enabled {
&nbsp;&nbsp;border: 2px solid gold;
&nbsp;&nbsp;background: yellow;
}

</pre>
<div class="codebox">
  <form id="frm_enabled">
    <label for="text1"></label>Ingrese su nombre (habilitado)</label>
    <input type="text" id="text1">
    <br>
    <label for="text2">Ingrese correo (deshabilitado)</label>
    <input type="text" id="text2" disabled>
  </form>
</div>

<style>
  #frm_enabled {
    background-color: #eee;
    color: black;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #frm_enabled input[type = "text"] {
    width: 70%;
  }

  #frm_enabled input[type = "text"]:enabled {
    border: 2px solid gold;
    background: yellow;
  }

  pre {
    white-space: pre-line;
  }

</style>
