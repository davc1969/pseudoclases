---
id: disabled
idn: 25
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:disabled
title: :disabled
description: 'Esta pseudoclase se utiliza para dar estilos a cualquier elemento que esté desahibilitado.  Un elemento deshabilitado está presente en el DOM pero no puede ser accesado por el usuario, por ejemplo un input, un botón, o cualquier otro elemento.<br>
La deshabilitación de un element se puede hacer directo en la etiqueta html correspondiente utilizando el atributo booleano <strong>disabled</strong>.<br>
Esta pseudoclase equivale al caso opuesto de <a href="enabled">:enabled</a>.
'
---

<pre is:raw>
html:
  &lt;label for="text1"&gt;Ingrese su nombre (habilitado)&lt;/label&gt;
  &lt;input type="text" id="text1"&gt;

  &lt;label for="text2"&gt;Ingrese correo (deshabilitado)&lt;/label&gt;
  &lt;input type="text" id="text2" disabled&gt;


css:
input[type = "text"]:disabled {
&nbsp;&nbsp;outline: 2px solid gray;
&nbsp;&nbsp;background: lightgray;
}

</pre>
<div class="codebox">
  <form id="frm_disabled">
    <label for="text1"></label>Ingrese su nombre (habilitado)</label>
    <input type="text" id="text1">
    <br>
    <label for="text2">Ingrese correo (deshabilitado)</label>
    <input type="text" id="text2" disabled>
  </form>
</div>

<style>
  #frm_disabled {
    background-color: #eee;
    color: black;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  #frm_disabled input[type = "text"] {
    width: 70%;
  }

  #frm_disabled input[type = "text"]:disabled {
    outline: 2px solid gray;
    background: lightgray;
  }

  pre {
    white-space: pre-line;
  }

</style>
