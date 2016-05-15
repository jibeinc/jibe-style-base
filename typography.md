---
layout: page
title: Typography
permalink: /typography/
---

<p>
  Jibe websites have common typographic needs: clear and consistent headings, highly legible body paragraphs, clear labels, and easy-to-use input fields.
</p>

### <u>Typeface</u>
<h3 class="jibe-h3">Lato</h3>

<p>Lato is a sans serif typeface family started in the summer of 2010 by Warsaw-based designer Łukasz Dziedzic (“Lato” means “Summer” in Polish). In December 2010 the Lato family was published under the Open Font License by his foundry tyPoland, with support from Google.</p>

<p>
  <b>Examples:</b>
</p>

<div class="row">
  <div class="col-md-6">
    <p class="weight1">
        Font Weight 100<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
  <div class="col-md-6">
    <p class="weight2">
        Font Weight 100 Italic<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
</div>

<div class="row">
  <div class="col-md-6">
    <p class="weight3">
        Font Weight 300<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
  <div class="col-md-6">
    <p class="weight4">
        Font Weight 300 Italic<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
</div>

<div class="row">
  <div class="col-md-6">
    <p class="weight5">
        Font Weight Normal 400<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
  <div class="col-md-6">
    <p class="weight6">
        Font Weight Normal 400 Italic<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
</div>

<div class="row">
  <div class="col-md-6">
    <p class="weight7">
        Font Weight 700<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
  <div class="col-md-6">
    <p class="weight8">
        Font Weight Bold 700 Italic<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
</div>

<div class="row">
  <div class="col-md-6">
    <p class="weight9">
        Font Weight Ultra-Bold 800<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
  <div class="col-md-6">
    <p class="weight10">
        Font Weight Bold Ultra-Bold 800 Italic<br>
        "Transform your career site into a recruiting engine"
    </p>
  </div>
</div>

### <u>Headings</u>
<h1 class="jibe-h1">H1</h1>

{% highlight html %}
  font-size: 3.2em;
  font-weight: 700;
{% endhighlight %}

<h2 class="jibe-h2">H2</h2>

{% highlight html %}
  font-size: 2em;
  font-weight: 700;
{% endhighlight %}

<h3 class="jibe-h3">H3</h3>

{% highlight html %}
  font-size: 1.5em;
  font-weight: 700;
{% endhighlight %}

<h4 class="jibe-h4">H4</h4>

{% highlight html %}
  font-size: 1.125em;
  font-weight: 500;
{% endhighlight %}

<h5 class="jibe-h5">H5</h5>

{% highlight html %}
  font-size: 1.714em;
  font-weight: 700;
{% endhighlight %}

<h6 class="jibe-h6">H6</h6>

{% highlight html %}
  font-size: .75em;
  font-weight: 500;
{% endhighlight %}

### <u>Body Text</u>

<p style="font-size: 16px; font-weight: 300; line-height: normal;">Paragraphs</p>

  <p style="font-size: 16px; font-weight: 300; line-height: normal;">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>

{% highlight html %}
  font-size: 16px;
  font-weight: 300;
  line-height: normal;
{% endhighlight %}

### <u>Links</u>

Links lead users to a different page or further information.

<b>Navigation Links</b>

{% highlight html %}
  font-size: 1.14285714em;
  text-decoration: none;

  :hover {
    text-decoration: underline;
  }

  :active {
    outline: 0;
  }
{% endhighlight %}

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
