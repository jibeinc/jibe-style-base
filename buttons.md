---
layout: page
title: Buttons
permalink: /buttons/
---

##### Jibe currently uses Bootstrap buttons.

##### Bootstrap Button Samples:

<div class="sample-buttons">
  <!-- Standard button -->
  <button type="button" class="btn btn-default">Default</button>

  <!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
  <button type="button" class="btn btn-primary">Primary</button>

  <!-- Indicates a successful or positive action -->
  <button type="button" class="btn btn-success">Success</button>

  <!-- Contextual button for informational alert messages -->
  <button type="button" class="btn btn-info">Info</button>

  <!-- Indicates caution should be taken with this action -->
  <button type="button" class="btn btn-warning">Warning</button>

  <!-- Indicates a dangerous or potentially negative action -->
  <button type="button" class="btn btn-danger">Danger</button>
</div>


### <u>Primary Buttons</u>

<button type="button" class="btn jibe-default-button">Default</button>
<button type="button" class="btn jibe-active-button">Active</button>
<button type="button" class="btn jibe-hover-button">Hover</button>

{% highlight html %}
<button type="button" class="btn jibe-default-button">Default</button>
<button type="button" class="btn jibe-active-button">Active</button>
<button type="button" class="btn jibe-hover-button">Hover</button>
.jibe-default-button {
  background-color: #478fcc;
  border-color: #478fcc;
  color: white;
}

.jibe-default-button:hover {
  color: white;
}

.jibe-active-button {
  background-color: #2b79ab;
  border-color: #2b79ab;
  color: white;
}

.jibe-active-button:hover {
  color: white;
}

.jibe-hover-button {
  background-color: #419cd7;
  border-color: #419cd7;
  color: white;
}
.jibe-hover-button:hover {
  color: white;
}
{% endhighlight %}
