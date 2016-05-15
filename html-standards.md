---
layout: page
title: HTML Standards
permalink: /html-standards/
---

When writing HTML for Jibe products, pay special attention to writing semantic markup, and following accessibility best practices.

## Lean Markup
Whenever possible, avoid superfluous parent elements when writing HTML. Many times this requires iteration and refactoring, but produces less HTML. For example:

{% highlight html %}
<!-- Not so great -->
<span class="avatar">
  <img src="...">
</span>

<!-- Better -->
<img class="avatar" src="...">

{% endhighlight %}
_source: [Github Primer](http://primercss.io/guidelines/#html)_

## Semantic Markup
When possible, use HTML5 semantic elements to provide more context to your document. This [section](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_section) of the Mozilla Developer's Network provides documentation on these elements.

Follow common sense rules when composing a page. Examples include:

* All pages should have one `<h1>` tag that describes the content on the page.

## Images
When using images in design, evaluate whether the image should be used in the HTML or CSS. If the image is decorative, it should be included as a background image. If the image is being used to add understanding to the page content, it should be included in the HTML. See the section on responsive images for guidelines and examples of responsive images.

* All images MUST include an `alt` attribute that describes the content of the image.

## Accessibility
Write HTML with accessibility in mind. Some resources include:

* [A11y Project](http://a11yproject.com/)
* [Aria on MDN](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)
