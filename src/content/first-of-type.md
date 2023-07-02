---
id: first-of-type
idn: 45
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:first-of-type
title: :first-of-type
description: 'Representa a un elemento cuando este es el primero de su tipo en un contenedor.  A diferencia de <a href="#first-child">:first-child</a>, no es necesario que sea el primer elemento dentro del contenedor.
'
---

<pre is:raw>
html:
  &lt;div&gt;
  &nbsp;&nbsp;&lt;h2&gt;Título genérico&lt;/h2&gt;
  &nbsp;&nbsp;&lt;p&gt;Primer párrafo&lt;/p&gt;
  &nbsp;&nbsp;&lt;p&gt;Segundo párrafo&lt;/p&gt;
  &nbsp;&nbsp;&lt;p&gt;Tercer párrafo&lt;/p&gt;
  &lt;/div&gt;

css:
p:first-of-type {
&nbsp;&nbsp;background: pink;
}

</pre>
<div class="codebox">
  <div id="first-of-type">
    <h2>Título genérico</h2>
    <p>Primer párrafo</p>
    <p>Segundo párrafo</p>
    <p>Tercer párrafo</p>
  </div>
</div>

<style>
  .codebox #first-of-type {
    background-color: #eee;
    color: black;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding-left: 3rem;
  }

  .codebox #first-of-type p:first-of-type {
    background: pink;
  }


  pre {
    white-space: pre-line;
  }

</style>
