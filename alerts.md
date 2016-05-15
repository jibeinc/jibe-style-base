---
layout: page
title: Alerts
permalink: /alerts/
---
#### Usability
Jibe utilizes Bootstrap Alerts. Alert messages are useful in prompting the user of actions that have been or need to be completed. Depending on the type (Success, Info, Warning, Danger), alerts can be extremely helpful in helping the user identify actions to be taken.

**When To Use**

* Add as a notification to inform users of actions that need to be taken or information they might need in the context of their current actions.
* As a validation notification to inform users that their previous action was completed or not completed.


<div class="alert alert-success alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Success!</strong> Your application has been submitted.
</div>

<div class="alert alert-info alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Don't Forget!</strong> Please check your email for resume upload instructions.
</div>

<div class="alert alert-warning alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Warning!</strong> Please include a number and special character in your password.
</div>

<div class="alert alert-danger alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Unknown Server Error</strong> Please try again later.
</div>

{% highlight html %}
<div class="alert alert-success alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Success!</strong> Your application has been submitted.
</div>

<div class="alert alert-info alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Don't Forget!</strong> Please check your email for resume upload instructions.
</div>

<div class="alert alert-warning alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Warning!</strong> Please include a number and special character in your password.
</div>

<div class="alert alert-danger alert-dismissible" role="alert">
  <button type="button" class="close" data-dismiss="alert" aria-label="Close"><span aria-hidden="true">&times;</span></button>
  <strong>Unknown Server Error</strong> Please try again later.
</div>
{% endhighlight %}
