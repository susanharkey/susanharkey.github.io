---
layout: post
title:  "New CSS Knowledge"
date:   2014-10-04 
categories: development tools
---
<h2 class="learn-title">Inline-block</h2>
<div class="learn-list">I always saw this being used on nav elements, but never really understood why. It is used to add width and height to inline elements.
</div>
<h2 class="learn-title">Border Box</h2>
<div class="learn-list">Most of the Wordpress themes I work with already had all elements set up with border box:
{% highlight css %}
* {
	border-box: box-sizing;
}
{% endhighlight %}
This makes it so the padding and border are included within the set width instead of adding to it.
</div>
<h2 class="learn-title">Mobile First Media Queries</h2>
<div class="learn-list">
I’ve always wrote media queries using max-width and was frustrated when working with sites utilizing min-width. It is interesting to think of designing for mobile first and building on for bigger screens, I don't know if I'll be able to integrate this into Think's wordpress workflow.
</div>




