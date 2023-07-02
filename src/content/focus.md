---
id: focus
idn: 50
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:focus
title: :focus
description: 'Representa a un elemento cuando este tiene el foco de navegación.  El foco se obtiene cuando se hace click con el mouse sobre un elemento y el elemento puede tener el foco, o cuando se llega a él con el teclado, con la tecla de tabulación.<br>
Al contrario que <a href="#active">:active</a>, los estilos dados por esta pseudoclase se mantienen mientras el foco siga en el elemento.
'
---

<pre is:raw>
button:focus {
&nbsp;&nbsp;background-color: lightblue;
}
</pre>
<div class="codebox">
  <button class="focusable">Click</button>
  <button class="focusable">Click</button>
</div>

<style>
  .codebox {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    text-align: center;

  }

  .focusable {
    padding: 1rem 2rem;
  }

  .focusable:focus {
    background-color: lightblue;;
  }
</style>
