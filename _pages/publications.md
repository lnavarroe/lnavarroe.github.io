---
title: "Lucio Navarro - Publications"
layout: gridlay
excerpt: "Lucio Navarro -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
