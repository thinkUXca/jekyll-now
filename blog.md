---
layout: page
description: The ThinkUX blog covers a range of UX topics including User Experience (UX) Design, Information Architecture (IA), UX Tools, Design Theory, and more!
---
<div class="posts">
  {% for post in site.posts %}
    <div class="row">
      <div class="col-xs-10 col-xs-offset-1 col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
        <article class="post">
          <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
          <div class="entry">
            {{ post.excerpt }}
          </div>
          <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
        </article>
      </div>
    </div>
  {% endfor %}
</div>
