---
id: empty
idn: 30
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:empty
title: :empty
description: 'Representa a cualqueir elemento que se considera vacío.  Un elemento o etiqueta está vacío cuando no tiene a ningún hijo, descendiente o texto alguno, incluso los espacios en blanco se consideran contenido.<br>
Por razones de accesibilidad se recomeinda no tener elementos vacíos en el documento.'

---

<pre is:raw>
html:
  &lt;p&gt;Elemento sin contenido&lt;p&gt;
  &lt;div&gt;&lt;/div&gt;

  &lt;p&gt;Elemento con espacios en blanco&lt;p&gt;
  &lt;div&gt;   &lt;/div&gt;

  &lt;p&gt;Elemento con contenido&lt;p&gt;
  &lt;div&gt;&lt;p&gt;Hola&lt;p&gt;&lt;/div&gt;

css:
div {
&nbsp;&nbsp;border: 1px solid black;
&nbsp;&nbsp;background: lightblue;
}

div:empty {
&nbsp;&nbsp;border: 1px solid red;
&nbsp;&nbsp;background: pink;
}

</pre>
<div class="codebox" id="box_empty">
  <p>Elemento sin contenido</p>
  <div></div>

  <p>Elemento con espacios en blanco</p>
  <div>   </div>

  <p>Elemento con contenido</p>
  <div><p>Hola</p></div>
</div>

<style>
  .codebox {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    text-align: center;

  }

  #box_empty div {
    width: 70%;
    height: 2rem;
    border: 1px solid black;
    background: lightblue;
    margin-inline: auto;
    margin-bottom: 0.5rem;
  }

    #box_empty div:empty {
    border: 1px solid red;
    background: pink;
  }

  pre {
    white-space: pre-line;
  }

</style>
