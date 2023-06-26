---
id: any-link
mdn_link: https://developer.mozilla.org/en-US/docs/Web/CSS/:any-link
title: :any-link
description: 'Representa al origen de cualquier enlace dentro del documento, es decir puede representar a cualquier elemento <strong><code>&lt;a&gt;</code></strong> o <strong><code>&lt;area&gt;</code></strong> ya que ambos tienen atributo <strong><code>href</code></strong>.<br>
Coincide con las pseudoclases <a href="#link">:link</a> y <a href="visited">:visited</a>'
---

<pre is:raw>
html:
&lt;a href="#">Link con dirección (href)&lt;/a>
&lt;a>Link sin dirección (href)&lt;/a>

css:
a:any-link {
  background-color: lightblue;
  padding-inline: 0.5rem;
  color: red;
}
</pre>
<div class="codebox">
  <a href="#">Link con dirección (href)</a>
  <br>
  <a>Link sin dirección (href)</a>
</div>

<style>
  .codebox {
    margin-top: 1rem;
    padding-block: 2rem;
    background-color: #eee;
    text-align: center;
    color: black;
  }

.codebox a:any-link {
  background-color: lightblue;
  padding-inline: 0.5rem;
  color: red;
}

</style>
