---
id: autofill
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:autofill
title: :autofill
description: 'En cualquier elemento de entrada de información (&lt;input&gt;, &lt;select&gt;, &lt;textarea&gt;, por ejemplo), representa al elemento cuya información ha sido llenada por el navegador automáticamente.  Si el usuario edita esa información, la pseudoclase es desactivada'
---

<pre is:raw>
input:autofill {
  outline: 2px dotted orange;
}
</pre>
<div class="codebox">
  <form autocomplete="on" id="frm_autofill">
    <p>Correo:</p>
    <input name="email" id="email" type="email" autocomplete="email" placeholder="introduzca su correo">
    <p>Nombre:</p>
    <input name="name" id="name" type="text" autocomplete="name" placeholder="introduzca su nombre">
  </form>
</div>

<style>
  #frm_autofill {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    text-align: center;
    color: black;
  }

  #frm_autofill input {
    width: 70%;
    padding: 0.25rem;
  }

  #frm_autofill input:autofill {
    outline: 2px dotted orange;
  }

</style>
