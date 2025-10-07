---
layout: default
page: "publ"
title: "Publications"
---

<div class="w3-container w3-content w3-center">
  <h2 class="w3-text-grey w3-padding-16 w3-center">
      <i class="fa fa-pencil fa-fw w3-margin-right w3-xxlarge w3-text-teal"></i>Publications
    </h2>

  <div class="w3-container w3-card w3-white" style="padding: 32px 32px;">

    {% for p in site.data.publications %}
    
    <div class="w3-container">
      <div class="w3-row">
        <div class="w3-col l4 m12 s12 w3-container w3-center">
          <h3>{{ p.title }}</h3>
        </div>
        <div class="w3-col l3 m4 s4 w3-container w3-center" style="padding-top:6px; padding-left:0;">
          <h5>{{ p.authors }}</h5>
        </div>
        <div class="w3-col l3 m6 s6 w3-container w3-center" style="padding-top:6px;">
          <h5>
            <a href="{{ p.handle }}" style="word-break:break-all;">{{ p.handle }}</a>
          </h5>
        </div>
        <div class="w3-col l2 m2 s2 w3-container w3-center" style="padding-top:6px; padding-right:0;">
          <h5>{{ p.year }}</h5>
        </div>
      </div>
    </div>
    {% unless forloop.last %}<hr>{% endunless %}
    {% endfor %}
  </div>
</div>