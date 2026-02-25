---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## Main Pages

- [About]({{ base_path }}/)
- [Publications]({{ base_path }}/publications/)
- [Talks]({{ base_path }}/talks/)
- [Projects]({{ base_path }}/projects/)
- [Data & Software]({{ base_path }}/software/)
- [Education]({{ base_path }}/education/)
- [CV]({{ base_path }}/cv/)

---

## Publications

{% for post in site.publications reversed %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

---

## Talks

{% for post in site.talks reversed %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

---

## Projects

{% for post in site.portfolio reversed %}
- [{{ post.title }}]({{ base_path }}{{ post.url }})
{% endfor %}

---

An [XML sitemap]({{ base_path }}/sitemap.xml) is also available for search engines.
