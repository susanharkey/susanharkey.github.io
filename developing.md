---
layout: default
title: Developing
permalink: /developing/
---  

  <div class="projects">
    {% for post in site.posts %}
        <h2>
          <a class="project-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        {{post.excerpt}}
    {% endfor %}
  </ul>
