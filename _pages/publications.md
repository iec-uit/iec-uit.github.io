---
title: "IEC Group - Publications"
layout: gridlay
excerpt: "IEC Group -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

[//]: # (## Group highlights)

[//]: # ()
[//]: # (&#40;For a full list of publications and patents see [below]&#40;#full-list-of-publications&#41; or go to [Google Scholar]&#40;https://scholar.google.ch/citations?user=TqxYWZsAAAAJ&#41;, [ResearcherID]&#40;https://www.researcherid.com/rid/D-7763-2012&#41;&#41;)

[//]: # ()
[//]: # ({% assign number_printed = 0 %})

[//]: # ({% for publi in site.data.publist %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 2 %})

[//]: # ({% if publi.highlight == 1 %})

[//]: # ()
[//]: # ({% if even_odd == 0 %})

[//]: # (<div class="row">)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<div class="col-sm-6 clearfix">)

[//]: # ( <div class="well">)

[//]: # (  <pubtit>{{ publi.title }}</pubtit>)

[//]: # (  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />)

[//]: # (  <p>{{ publi.description }}</p>)

[//]: # (  <p><em>{{ publi.authors }}</em></p>)

[//]: # (  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>)

[//]: # (  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>)

[//]: # (  <p> {{ publi.news2 }}</p>)

[//]: # ( </div>)

[//]: # (</div>)

[//]: # ()
[//]: # ({% assign number_printed = number_printed | plus: 1 %})

[//]: # ()
[//]: # ({% if even_odd == 1 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # ({% endif %})

[//]: # ({% endfor %})

[//]: # ()
[//]: # ({% assign even_odd = number_printed | modulo: 2 %})

[//]: # ({% if even_odd == 1 %})

[//]: # (</div>)

[//]: # ({% endif %})

[//]: # ()
[//]: # (<p> &nbsp; </p>)

[//]: # ()
[//]: # ()
[//]: # (## Patents)

[//]: # (<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 &#40;2020&#41;)

[//]: # ()
[//]: # (<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:&#40;Milan+ALLAN&#41;">US10439125B2 &#40;2016&#41;</a>)

## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
