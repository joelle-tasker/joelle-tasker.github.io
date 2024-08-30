---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

<h2>Pages</h2>
{% for post in site.pages %}
  {% if post.title == "about" or post.title == "publications" or post.title == "404" or post.title == "cv" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

