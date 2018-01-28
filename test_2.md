---
title: "Typography"
layout: page
permalink: "test_2/index.html"
sitemap: false
---

# Header one

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Header two

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum..

### Header three

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

#### Header four

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

##### Header five

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

###### Header six

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<p class="mb0">&nbsp;</p>

## Blockquotes

Single line blockquote:

> Stay hungry. Stay foolish.

Multi line blockquote with a cite reference:

<blockquote>
<p class="mb1"> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.</p>
<footer><cite>Steve Jobs, Apple Worldwide Developers&rsquo; Conference, 1997</cite></footer>
</blockquote>

<p class="mb0">&nbsp;</p>

## Tables

| Employee                            | Salary |                                                              |
| ----------------------------------  | ------ | ------------------------------------------------------------ |
| [John Doe](http://example.org/)     | $1     | Because that's all Steve Jobs needed for a salary.           |
| [Jane Doe](http://example.org/)     | $100K  | For all the blogging she does.                               |
| [Fredd Bloggs](http://example.org/) | $100M  | Pictures are worth a thousand words, right? So Jane x 1,000. |
| [Jane Bloggs](http://example.org/)  | $100B  | With hair like that?! Enough said...                         |

<p class="mb0">&nbsp;</p>

## Definition Lists

<dl>
<dt>Definition List Title</dt>
<dd>Definition list division.</dd>

<dt>Startup</dt>
<dd>A startup company or startup is a company or temporary organization designed
to search for a repeatable and scalable business model.</dd>

<dt>#dowork</dt>
<dd>Coined by Rob Dyrdek and his personal body guard Christopher "Big Black"
Boykins, "Do Work" works as a self motivator, to motivating your friends.</dd>

<dt>Do It Live</dt>
<dd>I'll let Bill O'Reilly will <a title="We'll Do It Live"
href="https://www.youtube.com/watch?v=O_HyZ5aW76c">explain</a> this one.</dd>
</dl>

## Unordered Lists (Nested)

* List item one
    * List item one
        * List item one
        * List item two
        * List item three
        * List item four
    * List item two
    * List item three
    * List item four
* List item two
* List item three
* List item four

## Ordered List (Nested)

1. List item one
    1. List item one
        1. List item one
        2. List item two
        3. List item three
        4. List item four
    2. List item two
    3. List item three
    4. List item four
2. List item two
3. List item three
4. List item four

<p class="mb0">&nbsp;</p>

## HTML Tags

**Address Tag**

<address>
1 Infinite Loop<br>
Cupertino, CA 95014<br>
United States
</address>

**Anchor Tag (aka. Link)**

This is an example of a [link](http://apple.com).

**Abbreviation Tag**

The abbreviation <abbr title="Seriously">srsly</abbr> stands for "seriously".

**Cite Tag**

<q cite="https://automattic.com/">Code is poetry.</q> -- <cite>Automattic</cite>

**Code Tag**

`Code tag test`

You will learn later on in these tests that `word-wrap: break-word;` will be
your best friend.

**Delete Tag**

This tag will let you <del>strikeout text</del>, but this tag is no longer
supported in HTML5 (use the `<strike>` instead).

**Emphasize Tag**

The emphasize tag should *italicize* text.

**Insert Tag**

This tag should denote <ins>inserted</ins> text.

**Keyboard Tag**

Use the `<kbd>` tag to indicate input that is typically entered via keyboard.

<span class="text-muted small">EXAMPLE</span><br>
To switch directories, type <kbd>cd</kbd> followed by the name of the directory.<br>
To edit settings, press <kbd><kbd>ctrl</kbd> + <kbd>,</kbd></kbd>

**Preformatted Tag**

This tag styles large blocks of code.

{% highlight css %}
.post-title {
    margin: 0 0 5px;
    font-weight: bold;
    font-size: 38px;
    line-height: 1.2;
    and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
{% endhighlight %}

**Quote Tag**

<q>Developers, developers, developers...</q> -- <cite>Steve Ballmer</cite>

**Strong Tag**

This tag shows **bold** text.

**Subscript Tag**

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

**Superscript Tag**

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

**Variable Tag**

This allows you to denote <var>variables</var>.

<div class="float-right">
  <a href="#top" class="back-to-top-link" title="Back to top">
    <svg class="icon-up" viewBox="0 0 24 24" version="1.1" width="24" height="24" aria-label="Back to top" role="img"><path d="M4 12l1.41 1.41L11 7.83V20h2V7.83l5.58 5.59L20 12l-8-8-8 8z"/></svg>
  </a>
</div>
