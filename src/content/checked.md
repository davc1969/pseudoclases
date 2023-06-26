---
id: checked
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:checked
title: :checked
description: 'Representa la activación de un elemento binario de entrada de datos como un input tipo <strong>radio</strong> o <strong>checkbox</strong>, así como al elemento <strong>option</strong> dentro de un elemento <strong>select</strong>.<br>
Esta pseudoclase se activa cuando el elemento está encendido, es decir tiene su estado <em>on</em>'
---

<pre is:raw>
input[type = "checkbox"]:checked {
  outline: 2px dotted red;
}
</pre>
<div class="codebox">
  <form id="frm_checkbox">
    <input type="checkbox" id="checkbox1" >
    <label for="checkbox1">Encender para ver los cambios</label>
    <br>
    <input type="checkbox" id="checkbox2" >
    <label for="checkbox2">Encender para ver los cambios</label>
  </form>
</div>

<style>
  #frm_checkbox {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    color: black;
  }

  #frm_checkbox input[type = "checkbox"]:checked {
    outline: 2px dotted red;
  }

</style>
