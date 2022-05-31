---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About 


{% for member in site.data.pi %}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h3>{{ member.name }}</h3>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.linkedin %}<a href="mailto:{{ member.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-3x"></i></a> {% endif %}
  {% if member.twitter %} <a href="{{ member.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}
  <ul style="overflow: hidden">
  
  <li> 09/2014 - 08/2018, Ph.D. <br> 
       Electrical and Electronic Engineering (EEE), The University of Hong Kong <br> 
       Supervisor: <a href="https://www.eee.hku.hk/people/vli/" target="_blank">Prof. Victor O.K. Li</a> </li>
  <li> 09/2010-07/2014, B.Eng. <br> 
       Electronic Engineering (EE), Tsinghua University </li>

  </ul>
</div>

{% endfor %}

### Professional Experience
-------
* **Senior Research Scientist**
  * 08/2018 - Present
  * FAIR Labs @ Meta AI, New York, NY, USA

* **Research Intern**
  * 09/2017 - 12/2017
  * Salesforce Research, Palo Alto, CA, USA
  * Advisor: Dr. Richard Socher

* **Research Intern**
  * 04/2017 - 08/2017
  * Microsoft Research, Redmond, WA, USA
  * Advisor: Dr. Hany Hassan

* **Visiting Scholar**
  * 06/2016 - 01/2017
  * Courant Institute of Mathematical Sciences, New York University, New York, NY, USA
  * Advisor: Prof. Kyunghyun Cho

* **Student Collaborator**
  * 08/2015 - 05/2016
  * Huawei Noah's Ark Lab, Hong Kong, China
  * Advisor: Dr. Zhengdong Lu

* **Software Engineer Intern**
  * 10/2013 - 04/2014
  * Renren Inc., Beijing, China

* **Exchange Student**
  * 10/2012 - 03/2013
  * Information and Communication Engineering, The University of Tokyo, Tokyo, Japan
  * Advisor: Prof. Hitoshi Iba

## Collaborators

<!-- * <a href="http://colonius.caltech.edu/" target="_blank">Professor Tim Colonius (Department of Mechanical and Civil Engineering, Caltech)</a>
* <a href="https://www.imperial.ac.uk/people/g.rigas" target="_blank">Professor Georgios Rigas (Department of Aeronautics, Imperial College London)</a>
* <a href="http://flowphysics.ucsd.edu/" target="_blank">Professor Oliver Schmidt (Department of Mechanical and Aerospace Engineering, UC San Diego)</a>
* <a href="http://atowne.com/" target="_blank">Professor Aaron Towne (Department of Mechanical Engineering, University of Michigan)</a>
* <a href="https://scholar.google.fr/citations?user=X7P6FUEAAAAJ&hl=fr" target="_blank"> Dr. Peter Jordan (Institut Pprime, CNRS, Universit ́e de Poitiers )</a>
* <a href="http://denissipp.free.fr/" target="_blank"> Dr. Denis Sipp (Research Director at ONERA)</a>
* <a href="http://www.ita.br/~cavalieri" target="_blank"> Professor Andre Cavalieri (Engenharia Aeronáutica, Instituto Tecnológico de Aeronáutica)</a>
* <a href="https://www.cascadetechnologies.com/" target="_blank"> Dr. Guillaume Brès (Director of Operations and Senior Research Scientist, CASCADE Technologies)</a> -->





