---
id: default
idn: 20
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:default
title: :default
description: 'Representa la opción activada por defecto de un elemento binario de entrada de datos como un input tipo <strong>radio</strong> o <strong>checkbox</strong>.<br>
Esta pseudoclase se activa cuando el elemento está encendido, es decir tiene su estado <em>on</em>, lo cual se logra incialmente con el atributo <strong>checked</strong> presente en la etiqueta HTML correspondiente.<br>
También sirve para elementos <strong>option</strong> dentro de una etiqueta <strong>select</strong>.  También puede aplicarse a botones (<strong>button</strong>) dentro de un formulario.
El estilo permanece en el elemento para indicar que fue la opción por defecto.'
---

<pre is:raw>
html:
  &lt;input type="checkbox" id="checkbox1" checked&gt;
  &lt;label for="checkbox1"&gt;Opción activada por defecto&lt;/label&gt;

  &lt;input type="checkbox" id="checkbox2" &gt;
  &lt;label for="checkbox2"&gt;segunda opción&lt;/label&gt;

css:
input[type = "checkbox"]:default {
&nbsp;&nbsp;outline: 2px dashed gold;
}

</pre>
<div class="codebox">
  <form id="frm_default">
    <input type="checkbox" id="checkbox1" checked>
    <label for="checkbox1">Opción activada por defecto</label>
    <br>
    <input type="checkbox" id="checkbox2" >
    <label for="checkbox2">segunda opción</label>
  </form>
</div>

<style>
  #frm_default {
    background-color: #eee;
    color: black;
  }

  #frm_default input[type = "checkbox"]:default {
    outline: 2px dashed gold;
  }

  pre {
    white-space: pre-line;
  }

</style>
