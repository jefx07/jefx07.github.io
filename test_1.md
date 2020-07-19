---
layout: page
title: "Html Elements"
description: "Below is just about every HTML element you might want to use in
your blog posts."
permalink: /test_1/
sitemap: false
---

Below is just about every <abbr title="HyperText Markup Language">HTML</abbr>
element you might want to use in your blog posts. Check the source code to see
the many embedded elements within paragraphs.

# h1. Heading 1

## h2. Heading 2

### h3. Heading 3

#### h4. Heading 4

##### h5. Heading 5

###### h6. Heading 6

<hr style="margin: 2.5rem 0">

Lorem ipsum dolor sit amet, [test link](# "test link") adipiscing elit. **This
is strong.** Nullam dignissim convallis est. Quisque aliquam. *This is
emphasized.* Donec faucibus. Nunc iaculis suscipit dui. 5<sup>3</sup> = 125.
Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at,
tincidunt nec, gravida vehicula, nisl. <cite>The New York Times</cite> (That’s a
citation). Underline. Maecenas ornare tortor. Donec sed tellus eget sapien
fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo
vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. <abbr
title="HyperText Markup Language">HTML</abbr> and <abbr title="Cascading Style
Sheets">CSS</abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat
at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent
mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim
diam eget metus. To copy a file type <code>COPY <var>filename</var></code>.

<del>Dinner’s at 5:00.</del> <mark>Let’s make that 7.</mark>

This <span style="text-decoration:line-through;">text</span> has been struck.

<hr style="margin: 2.5rem 0">

## Definition List

<dl>
<dt>Definition List Title</dt>
<dd>This is a definition list division.</dd>

<dt>Definition</dt>
<dd>An exact statement or description of the nature, scope, or meaning of
something: <em>our definition of what constitutes poetry.</em></dd>
</dl>

## Ordered List

1. List Item 1
2. List Item 2
    1. Nested list item A
    2. Nested list item B
3. List Item 3

## Unordered List

- List Item 1
- List Item 2
    - Nested list item A
    - Nested list item B
- List Item 3

<hr style="margin: 2.5rem 0">

## Tables

Using the most basic table markup, here’s how tables look.

<p class="mb-0">&nbsp;</p>

<table class="table table-bordered">
<tr>
<th>Table Header 1</th>
<th>Table Header 2</th>
<th>Table Header 3</th>
</tr>
<tr>
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
<tr class="even">
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
<tr>
<td>Division 1</td>
<td>Division 2</td>
<td>Division 3</td>
</tr>
</table>

<p>&nbsp;</p>

## Preformatted Text

Typographically, preformatted text is not the same thing as
code. Sometimes, a faithful execution of the text requires preformatted text
that may not have anything to do with code. For example:

<pre>“Beware the Jabberwock, my son!
    The jaws that bite, the claws that catch!
Beware the Jubjub bird, and shun
    The frumious Bandersnatch!”
</pre>
<p class="mb-0">&nbsp;</p>

### Code

Code can be presented inline, like `<?php bloginfo('stylesheet_url'); ?>`, or
within a `<pre>` block.

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

<hr style="margin: 2.5rem 0">

## Blockquotes

Let's keep it simple.

<blockquote>
<p class="mb-2">Good afternoon, gentlemen. I am a HAL 9000 computer. I became
operational at the H.A.L. plant in Urbana, Illinois on the 12th of January 1992.
My instructor was Mr. Langley, and he taught me to sing a song. If you’d like to
hear it I can sing it for you.</p>
<footer class="blockquote-footer">
  <cite><a href="http://en.wikipedia.org/wiki/HAL_9000">HAL 9000</a></cite>
</footer>
</blockquote>

And here’s a bit of trailing text.

<hr style="margin: 2.5rem 0">

## Buttons

We also have some buttons, if you need them.

<button class="btn btn-primary" type="button">Button 1</button> &nbsp; <button class="btn btn-success" type="button">Button 2</button>

<hr style="margin: 2.5rem 0">

## Forms

<form class="formspree" accept-charset="utf-8" method="POST" action="https://formspree.io/YOUREMAILHERE">
  <div class="form-group">
    <label for="inputName">Name<span class="required">*</span></label>
    <input id="inputName" class="form-control" type="text" name="name" required>
  </div>
  <div class="form-group">
    <label for="inputEmail">Email address<span class="required">*</span></label>
    <input id="inputEmail" class="form-control" type="email" name="_replyto" required>
  </div>
  <div class="form-group">
    <label for="inputMessage">Message</label>
    <textarea id="inputMessage" class="form-control" rows="3" name="message" required></textarea>
  </div>
  <input type="hidden" name="_subject" value="Contact Form Submission!">
  <input type="text" name="_gotcha" aria-hidden="true" style="display:none">
  <button class="btn btn-primary" type="submit">Send</button>
</form>

<hr style="margin: 2.5rem 0">

{% include scrolltop.html %}
