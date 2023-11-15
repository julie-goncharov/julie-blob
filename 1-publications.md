---
layout: default
title: Publications
permalink: /publications/
---

<h1 class="mt-4">Publications</h1>
{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
<div class="pubitem">
  <div class="pubtitle">
    {{ pub.title }}
  </div>
  <div class="pubauthors">
    {{ pub.authors }}
  </div>
  <div class="pubinfo">
    {{ pub.publication }}, {{ pub.year}}
  </div>
  <div class="publinks">
  {% if pub.pdf %}
    <a href="{{ "/" | relative_url }}/assets/docs/{{ pub.pdf}}" target="_blank"><i class="far fa-file-pdf"></i> PDF
    </a>
    {% endif %}
    &nbsp;&nbsp;
    <a href="{{ pub.url | relative_url }}"><i class="fas fa-arrow-right"></i> Project Page</a>
  </div>
</div>
{% endfor %}
