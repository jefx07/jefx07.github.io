---
title: "Html Elements"
layout: page
permalink: "test_2/index.html"
sitemap: false
---

<div style="font-family:'PT Sans', sans-serif;">

<p>Below is just about every <abbr title="HyperText Markup Language">HTML</abbr>
element you might want to use in your blog posts. Check the source code to see
the many embedded elements within paragraphs.</p>

<h1>h1. Heading 1</h1>
<h2>h2. Heading 2</h2>
<h3>h3. Heading 3</h3>
<h4>h4. Heading 4</h4>
<h5>h5. Heading 5</h5>
<h6>h6. Heading 6</h6>

<hr style="margin: 2.5rem 1rem">

<p>Lorem ipsum dolor sit amet, <a href="#" title="test link">test link</a>
adipiscing elit. <strong>This is strong.</strong> Nullam dignissim convallis
est. Quisque aliquam. <em>This is emphasized.</em> Donec faucibus. Nunc iaculis
suscipit dui. 5<sup>3</sup> = 125.  Water is H<sub>2</sub>O. Nam sit amet sem.
Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl.
<cite>The New York Times</cite> (That’s a citation). Underline. Maecenas ornare
tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante.
Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi
imperdiet augue quis tellus. <abbr title="HyperText Markup Language">HTML</abbr>
and <abbr title="Cascading Style Sheets">CSS</abbr> are our tools. Mauris
a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc.
Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum,
turpis mi volutpat justo, eu volutpat enim diam eget metus. To copy a file type
<code>COPY <var>filename</var></code>.</p>

<p><del>Dinner’s at 5:00.</del> <mark>Let’s make that 7.</mark></p>

<p>This <span style="text-decoration:line-through;">text</span> has been
struck.</p>

<hr style="margin: 2.5rem 1rem">

<h2>Definition List</h2>
<dl>
<dt>Definition List Title</dt>
<dd>This is a definition list division.</dd>

<dt>Definition</dt>
<dd>An exact statement or description of the nature, scope, or meaning of
something: <em>our definition of what constitutes poetry.</em></dd>
</dl>

<h2>Ordered List</h2>
<ol>
  <li>List Item 1</li>
  <li>List Item 2
    <ol>
      <li>Nested list item A</li>
      <li>Nested list item B</li>
    </ol>
  </li>
  <li>List Item 3</li>
</ol>

<h2>Unordered List</h2>
<ul>
  <li>List Item 1</li>
  <li>List Item 2
    <ul>
      <li>Nested list item A</li>
      <li>Nested list item B</li>
    </ul>
  </li>
  <li>List Item 3</li>
</ul>

<hr style="margin: 2.5rem 1rem">

<h2>Table</h2>
<table>
  <thead>
    <tr>
      <th>Table Header 1</th>
      <th>Table Header 2</th>
      <th>Table Header 3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Division 1</td>
      <td>Division 2</td>
      <td>Division 3</td>
    </tr>
    <tr>
      <td>Division 1</td>
      <td>Division 2</td>
      <td>Division 3</td>
    </tr>
    <tr>
      <td>Division 1</td>
      <td>Division 2</td>
      <td>Division 3</td>
    </tr>
  </tbody>
</table>
<p>&nbsp;</p>

<h2>Preformatted Text</h2>
<p>Typographically, preformatted text is not the same thing as code. Sometimes,
a faithful execution of the text requires preformatted text that may not have
anything to do with code. For example:</p>

<pre>“Beware the Jabberwock, my son!
    The jaws that bite, the claws that catch!
Beware the Jubjub bird, and shun
    The frumious Bandersnatch!”
</pre>

<h2>Code</h2>
<p>Code can be presented inline, like <code class="highlighter-rouge">&lt;?php
bloginfo('stylesheet_url'); ?&gt;</code>, or within a <code
class="highlighter-rouge">&lt;pre&gt;</code> block.</p>

<div class="language-css highlighter-rouge"><pre class="highlight"><code><span class="nf">#container</span> <span class="p">{</span>
  <span class="nl">float</span><span class="p">:</span> <span class="nb">left</span><span class="p">;</span>
  <span class="nl">margin</span><span class="p">:</span> <span class="m">0</span> <span class="m">-240px</span> <span class="m">0</span> <span class="m">0</span><span class="p">;</span>
  <span class="nl">width</span><span class="p">:</span> <span class="m">100%</span><span class="p">;</span>
<span class="p">}</span>
</code></pre>
</div>

<p>or</p>

<div class="language-html highlighter-rouge"><pre class="highlight"><code><span class="nt">&lt;html</span> <span class="na">lang=</span><span class="s">"en"</span><span class="nt">&gt;</span>
  <span class="nt">&lt;head&gt;</span>
    <span class="nt">&lt;meta</span> <span class="na">charset=</span><span class="s">"utf-8"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;meta</span> <span class="na">name=</span><span class="s">"viewport"</span> <span class="na">content=</span><span class="s">"width=device-width, initial-scale=1, shrink-to-fit=no"</span><span class="nt">&gt;</span>
    <span class="nt">&lt;meta</span> <span class="na">http-equiv=</span><span class="s">"x-ua-compatible"</span> <span class="na">content=</span><span class="s">"ie=edge"</span><span class="nt">&gt;</span>
</code></pre>
</div>

<hr style="margin: 2.5rem 1rem">

<h2>Blockquotes</h2>
<p>Let's keep it simple.</p>

<blockquote>
<p>Good afternoon, gentlemen. I am a HAL 9000 computer. I became operational at
the H.A.L. plant in Urbana, Illinois on the 12th of January 1992. My
instructor was Mr. Langley, and he taught me to sing a song. If you’d like to
hear it I can sing it for you. <cite>— <a href="http://en.wikipedia.org/wiki/HAL_9000">HAL 9000</a></cite></p>
</blockquote>

<p>And here’s a bit of trailing text.</p>

<hr style="margin: 2.5rem 1rem">

<h2>Buttons</h2>
<p>Here are some standard buttons if you need them:</p>

<a class="button" href="#" role="button">Link</a>
<button class="button" type="submit">Button</button>

<p>&nbsp;</p><p>&nbsp;</p>
</div>
