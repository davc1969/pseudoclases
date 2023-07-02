---
id: first-child
idn: 40
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:first-child
title: :first-child
description: 'Representa a un elemento cuando este es el primer hijo de su contenedor.  Si el elemento es el primero de su tipo en el contenedor, pero no es el primer hijo de éste, no se activa esta pseudoclase.  Vea también <a href="#first-of-type">:first-of-type</a>
'
---

<pre is:raw>
html:
  &lt;div&gt;
  &nbsp;&nbsp;&lt;p&gt;Primer párrafo&lt;/p&gt;
  &nbsp;&nbsp;&lt;p&gt;Segundo párrafo&lt;/p&gt;
  &nbsp;&nbsp;&lt;p&gt;Tercer párrafo&lt;/p&gt;
  &lt;/div&gt;

css:
p:first-child {
&nbsp;&nbsp;background: lightblue;
}

</pre>
<div class="codebox">
  <div id="first-child">
    <p>Primer párrafo</p>
    <p>Segundo párrafo</p>
    <p>Tercer párrafo</p>
  </div>
</div>

<style>
  .codebox #first-child {
    background-color: #eee;
    color: black;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding-left: 3rem;
  }

  .codebox #first-child p:first-child {
    background: lightblue;
  }


  pre {
    white-space: pre-line;
  }

</style>
