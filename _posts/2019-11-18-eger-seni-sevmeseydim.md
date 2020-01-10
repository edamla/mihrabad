---
layout: post
title:  "EĞER SENİ SEVMESEYDİM"
yazar: "Murat Başaran"
categories: [ Mihrabad Yayınları, Murat Başaran, ]
image: assets/images/md-image/eserler/egersenisevme.png
barcode: 9786056667862
meser: true
blog: false
dolink: true
---


“Bir ömür boyu” yetmezdi bana... Ben seni severek... Cenneti istemeyi öğrendim; ve sonsuzluğu... Uykuyu uysal bir kedi gibi yanıma alıp, şafak vakti ettiğim dualarda... Sana ve sevgime bakıp... Rabbimi öğrendim... O’nun büyüklüğünü öğrenmenin mümkün olmadığını öğrenip... Hayreti öğrendim...


{% for post in site.posts %}

    {% if post.title == 'Murat Başaran' %}

        {% include eseraltibox.html %}

    {% endif %}

{% endfor %}
