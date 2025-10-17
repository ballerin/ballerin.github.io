---
layout: blog
page: "blog"
title: "Blog"
---

<div class="w3-container">
    <h2 class="w3-text-grey w3-padding-16 w3-center">
        <i class="fa fa-pen-nib fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Posts
    </h2>

    {% if site.posts and site.posts.size > 0 %}

    <div class="w3-row-padding">
        {% for post in site.posts %}
        <div class="w3-col l4 m6 s12 w3-margin-bottom">
            <div class="w3-card w3-white">
                {% if post.image %}
                <div class="w3-container w3-padding-0">
                    <img src="{{ post.image | absolute_url }}" alt="{{ post.title }}" style="width:100%; height:180px; object-fit:cover;">
                </div>
                {% endif %}
                <div class="w3-container">
                    <h3 class="w3-margin-top"><a href="{{ post.url }}" class="w3-text-teal">{{ post.title }}</a></h3>
                    <p class="w3-small w3-text-grey">{{ post.date | date: "%B %d, %Y" }}</p>
                    <p>
                        {% if post.excerpt %}
                            {{ post.excerpt | strip_html | truncate: 160 }}
                        {% else %}
                            {{ post.content | strip_html | truncate: 160 }}
                        {% endif %}
                    </p>
                    <p class="w3-right">
                        <a class="w3-button w3-teal w3-small" href="{{ post.url }}">Read</a>
                    </p>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>

    {% else %}

    <p class="w3-center">No posts found.</p>
    {% endif %}

</div>