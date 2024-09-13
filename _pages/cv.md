---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Cell and molecular biology, University of Jyväskylä (2020)
* MSc in Cell and molecular biology, University of Jyväskylä (2016)
* BSc in Cell and molecular biology (IT as minor), University of Jyväskylä (2012)

Work experience
======
* 2022-2024: Postdoctoral Fellow
  * University of St Andrews, UK.  Malcolm White lab
  * Focus: Bioinformatic and laboratory work on type III CRISPR-Cas systems

* 2020-2022: Postdoctoral Fellow
  * University of Jyväskylä, Finland. Matti Jalasvuori lab.
  * Focus: creation of automated phage genome analysis tools.

* 2016-2020: Doctoral researcher
  * University of Jyväskylä, Finland. Lotta-Riina Sundberg lab
  * Focus: characterising CRISPR-Cas systems in Flavobacterium columnare
  
Skills
======
* Python
* Snakemake
* R
* Shell/bash
* Django fullstack development
* PostgreSQL basics
* Standard molecular biology lab skills (cultures, cloning, PCR, qPCR, Sanger sequencing, protein extraction and purification, gels...)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
 -->