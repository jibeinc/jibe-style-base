---
layout: page
title: Typography
permalink: /typography/
---

Jibe websites have common typographic needs: clear and consistent headings, highly legible body paragraphs, clear labels, and easy-to-use input fields.


### <u>Typeface</u>

Lato

<p>Lato is a sans serif typeface family started in the summer of 2010 by Warsaw-based designer Łukasz Dziedzic (“Lato” means “Summer” in Polish). In December 2010 the Lato family was published under the Open Font License by his foundry tyPoland, with support from Google.</p>

<img src="../assets/Lato-Font.png" alt="Lat-Img" />

### <u>Headings</u>
<h1 style="font-size: 3.2em;">H1</h1>

<pre style= "background-color: #f5f5f5;">
  font-size: 3.2em;
  font-weight: 700;
</pre>

<h2 style="font-size: 2em;">H2</h2>

<pre style= "background-color: #f5f5f5;">
  font-size: 2em;
  font-weight: 700;
</pre>

<h3 style="font-size: 1.5em;">H3</h3>

<pre style= "background-color: #f5f5f5;">
  font-size: 1.5em;
  font-weight: 700;
</pre>

<h4 style="font-size: 1.125em;">H4</h4>

<pre style= "background-color: #f5f5f5;">
  font-size: 1.125em;
  font-weight: 500;
</pre>

<h5 style="font-size: 1.125em;">H5</h5>

<pre style= "background-color: #f5f5f5;">
  font-size: 1.714em;
  font-weight: 700;
</pre>

<h6 style="font-size: .75em;">H6</h6>

<pre style= "background-color: #f5f5f5;">
  font-size: .75em;
  font-weight: 500;
</pre>

### <u>Body Text</u>

<p style="font-size: 16px; font-weight: 300; line-height: normal;">Paragraphs</p>

  <p style="font-size: 16px; font-weight: 300; line-height: normal;">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>

<pre style= "background-color: #f5f5f5;">
  font-size: 16px;
  font-weight: 300;
  line-height: normal;
</pre>

### <u>Links</u>

Links lead users to a different page or further information.

<b>Navigation Links</b>

<pre style= "background-color: #f5f5f5;">
  font-size: 1.14285714em;
  text-decoration: none;

  :hover {
    text-decoration: underline;
  }

  :active {
    outline: 0;
  }
</pre>

### <u>List Items</u>

Lists organize written information for users.

* List Item
* List Item
* List Item
* List Item

<p>
  List Item class of "horiz-list__item"
</p>

  {% highlight html %}
  <li class="horiz-list__item">List Item></li>
  <li class="horiz-list__item">List Item></li>
  <li class="horiz-list__item">List Item></li>
  <li class="horiz-list__item">List Item></li>
  {% endhighlight %}
