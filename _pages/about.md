---
layout: about
title: about
permalink: /
description: <a href="#">Affiliations</a>

profile:
  align: right
  image: Display-Picture.jpg
  address: >

news: false  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
years: [2021, 2020, 2019, 2018, 2017]
---

I am a Research Fellow (RF) at Microsoft Research (MSR) India. At MSR, I work closely with [Dr.&nbsp;Nishanth&nbsp;Chandran](https://www.microsoft.com/en-us/research/people/nichandr/), [Dr.&nbsp;Divya&nbsp;Gupta](https://www.microsoft.com/en-us/research/people/digup/), [Dr.&nbsp;Aseem&nbsp;Rastogi](https://www.microsoft.com/en-us/research/people/aseemr/), and [Dr.&nbsp;Rahul&nbsp;Sharma](https://www.microsoft.com/en-us/research/people/rahsha/). Prior to joining MSR as an RF, I was also an intern here for 6&nbsp;months.

I graduated from [Indian Institute of Technology (BHU) Varanasi](https://www.iitbhu.ac.in/) in 2020 with a Dual&nbsp;Degree (B.Tech.&nbsp;and&nbsp;M.Tech.) from the Department of Computer Science & Engineering.
In the summer of 2019, I interned with [Prof.&nbsp;Thomas&nbsp;Schneider](https://www.sites.google.com/site/thomaschneider/) at TU&nbsp;Darmstadt.
Before that, I did an internship at Kyushu University with [Prof.&nbsp;Masaya&nbsp;Yasuda](https://myasuda.imi.kyushu-u.ac.jp/en/) and at Waseda University with [Prof.&nbsp;Takeshi&nbsp;Koshiba](http://www.f.waseda.jp/tkoshiba/).

My research interests broadly lie in the applied and theoretical aspects of cryptography.

<div class="publications">
<h2>Publications</h2>
{% for y in page.years %}
  <h2 class="year"><b>{{y}}</b></h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
</div>
