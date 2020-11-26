---
layout: default
title: "Happy Jekylling!"
---


## You're ready to go!

Start developing your Jekyll website.

 {{site.data.test.name.husband}} 
 
 
 {% assign facolta = site.data.universita.facolta %}

{% for annoaccademico in facolta %}
	{{annoaccademico.anno}} {{ annoaccademico.nome }}
{% endfor %}
