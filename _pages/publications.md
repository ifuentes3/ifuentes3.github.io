---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% assign featured_publications = site.publications | where: "featured", true %}
{% for post in featured_publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% for post in site.publications reversed %}
  {% unless post.featured or post.list_last %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}

{% assign last_publications = site.publications | where: "list_last", true %}
{% for post in last_publications reversed %}
  {% include archive-single.html %}
{% endfor %}
