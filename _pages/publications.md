---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

The full list my publications is available [here](https://ui.adsabs.harvard.edu/search/filter_author_facet_hier_fq_author=OR&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FCho%2C%20I%2FCho%2C%20I%22&filter_author_facet_hier_fq_author=author_facet_hier%3A%221%2FCho%2C%20I%2FCho%2C%20Ilje%22&fq=%7B!type%3Daqp%20v%3D%24fq_author%7D&fq_author=(author_facet_hier%3A%221%2FCho%2C%20I%2FCho%2C%20I%22%20OR%20author_facet_hier%3A%221%2FCho%2C%20I%2FCho%2C%20Ilje%22)&p_=0&q=author%3A%22cho%2C%20ilje%22&sort=date%20desc%2C%20bibcode%20desc){:target="_blank"}.

## 2022
---

{% for publi in site.data.publications %}

 <strong> {{ publi.title }} </strong> <br />
 <span style="color:grey"> <em>{{ publi.month }} {{ publi.year }},  {{ publi.journal }}, {{ publi.volume }}, {{ publi.pages }} </em> </span> <br />
  <em>{{ publi.authors }} </em><br /> <a href="{{ publi.url }}"> DOI: {{ publi.doi }}</a>

{% endfor %}
