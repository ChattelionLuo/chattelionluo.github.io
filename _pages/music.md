---
permalink: /music/
title: "La Musique"
author_profile: true
redirect_from: 
  - /music
---
When not doing maths, I am a semi-professional violinist. I learned from Mr. Xingyan Chen from [Sichuan Conservatory of Music](http://www.sccm.cn
). Currently, I am playing at the PolyU Orchestra under the baton of [Mr. Leung Kin-fung](http://www.leungkinfung.com/bio.php), and the ASO under the baton of [Mr. Chan Man Tat](https://acohk.org/#Conductor). I am a genuine classical music fan and playing in local/university orchestras, chamber groups and studios. You can find some of my playings on stream. Feel free to drop me a message.

{% include image.html url="/images/violin.jpg" description="Me (in the back) playing at the Auditorium, Yuen Long Theatre in 2022" %}

## Events
{% include base_path %}

{% for post in site.music reversed %}
  {% include archive-single.html %}
{% endfor %}
