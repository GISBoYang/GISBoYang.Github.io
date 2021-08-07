---
permalink: /
title: ""
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
 <img align="center"  src="/images/DJI_0894.JPG">
 
Dr. Bo Yang is an Assistant Professor of GIS in the Department of Urban and Regional Planning at San José State University. Yang's GIS page aims to share research progress and resources of Geographical Information Science (GIS), Remote Sensing, and Environmental Science. 

I have interdisciplinary education background with a B.S. degree in Applied Mathematics, an M.S. in Computer Science. I received my Ph.D. in Geography advised by Dr. Hongxing Liu at University of Cincinnati (UC). My research interests are: **_GIScience, Unmanned Aerial Vehicle (UAV), Remote Sensing, Human-environment Interactions, and Citizen Science_**. 

I work with [Dr. Timothy Hawthorne](https://sciences.ucf.edu/sociology/person/timothy-hawthorne/) co-leading an NSF&Smithsonian collaborative coastal mapping project. This [project](https://gis-yang.github.io//Projects/) is one of the earliest attempts to employ UAV remote sensing in coastal management and conservation across 23 degrees of latitude. 

The other part of my research focuses on spatial statistics and machine learning algortihm. I developed and implemented a new geo-statistical ([ST-Cokriging](https://doi.org/10.1016/j.rse.2020.112190)) method to assimilate multi-scale data for forecasting and hindcasting spatio-temporal environmental & societal processes, such as urban heat island effects measured with remote sensing. Compared with previous data assimilation algorithms, this machine learning method is more accurate with its additional capabilities in filling missing data and uncertainty estimates. 

I am an FAA part 107 remote pilot maintaining an open-access UAV/drone [training course](https://gis-yang.github.io/DroneMapping/) for coastal UAV mapping. Besides of doing research and teaching, I like fiddling with tech gadgets and playing basketball. 

Pronouns: he/him/his 

**Contact:**\
Bo Yang\
[Bo.Yang02[a]SJSU.edu](mailto:Bo.Yang02@SJSU.edu) \
408-924-5882\
Washington Square Hall, San José, CA 95192\
San José State University 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

