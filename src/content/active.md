---
id: "active"
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:active
title: :active
description: 'Esta pseudoclase representa al elemento que está siendo activado por el usuario.  Si se utiliza el ratón para hacerlo, la activación ocurre solo cuando se presiona el botón principal.  Si es por el teclado, la activación ocurre cuando un elemento que pueda tener el foco recibe a la tecla Enter o la Barra Espaciadora.<br>
A diferencia de <a href=#focus">:focus</a>, esta pseudoclase no permanece en el elemento, dura solo mientras ocurre el proceso de activación.'
---

<pre is:raw>
button:active {
  background-color: lightblue;
}
</pre>
<div class="codebox">
  <button>Click</button>
  <button>Click</button>
</div>

<style>
  .codebox {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    text-align: center;

  }

  button {
    padding: 1rem 2rem;
  }

  button:active {
    background-color: lightblue;;
  }
</style>
