---
layout: page
title: publications
permalink: /publications/
description: This page is under development and might take another week's time to be updated. Meanwhile,  consider taking a look at my <a href="https://scholar.google.com/citations?user=SJs0cZoAAAAJ&hl=en">scholar profile</a> or my <a href="https://dblp.org/pers/hd/i/Iyengar:Sudarshan">dblp page</a>. 
years: [2019, 2018, 2017, 2016, 2015,2014,2013,2012,2011,2010,2009,2008,2007,2006,2005,2004,2003] 
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
