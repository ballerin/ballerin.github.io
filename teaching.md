---
layout: default
page: "teaching"
title: "Publications"
---

<h2 class="w3-text-grey w3-padding-16 w3-center"><i class="fa fa-book fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Teaching duties</h2>

<div class="w3-container w3-card w3-white" style="padding: 32px 32px;">
  {% for t in site.data.teaching %}
  <div class="w3-container">
    <div class="w3-row">
      <div class="w3-col l6 m12 s12 w3-container w3-center">
        <h3>{{ t.title }}</h3>
      </div>
      <div class="w3-col l2 m4 s4 w3-container w3-center" style="padding-top:6px; padding-left: 0px;">
        <h5>{{ t.location }}</h5>
      </div>
      <div class="w3-col l2 m4 s4 w3-container w3-center" style="padding-top:6px;">
        <h5>{{ t.date }}</h5>
      </div>
      <div class="w3-col l2 m4 s4 w3-container w3-center" style="padding-top:6px; padding-right: 0px;">
        <h5>{{ t.role }}</h5>
      </div>
    </div>
  </div>
  {% unless forloop.last %}<hr>{% endunless %}
  {% endfor %}
</div>