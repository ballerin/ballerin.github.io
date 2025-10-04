---
layout: blog
page: "blog"
title: "Blog"
---

<div class="w3-container w3-card w3-white">
    <h2 class="w3-text-grey w3-padding-16 w3-center">
        <i class="fa fa-pencil fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Posts
    </h2>
    <ul>
    <hr>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}"> {{ post.title }} ({{ post.date }})</a>
    </li>
    {% unless forloop.last %}<hr>{% endunless %}
    {% endfor %}
    </ul>
</div>