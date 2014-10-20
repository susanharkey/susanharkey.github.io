---
layout: post
title:  "New CSS Knowledge"
date:   2014-10-04 
categories: development tools
---
<div class="learn-list"><h3 class="learn-title">Inline-block</h3>
<p>I always saw this being used on nav elements, but never really understood why. It is used to add width and height to inline elements.</p>
</div>
<div class="learn-list"><h3 class="learn-title">Border Box</h3>
<p>Most of the Wordpress themes I work with already had all elements set up with border box:</p>
{% highlight css %}
* {
	border-box: box-sizing;
}
{% endhighlight %}
This makes it so the padding and border are included within the set width instead of adding to it.
</div>
<div class="learn-list">
<h3 class="learn-title">Mobile First Media Queries</h3>
<p>I’ve always wrote media queries using max-width and was frustrated when working with sites utilizing min-width. It is interesting to think of designing for mobile first and building on for bigger screens, I don't know if I'll be able to integrate this into Think's wordpress workflow.</p>
</div>




