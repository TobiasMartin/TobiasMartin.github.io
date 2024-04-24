---
layout: page
title: Philosophy
permalink: /philosophy/
---

In 2021, I enrolled in philosophy courses at the University of Oslo to better reflect upon ethical questions regarding technology and its impact on nature. I finished a bachelor degree in philosophy in 2023.

My main interest is philosophy of nature which includes philosophy of mind and environmental philosophy. Here, I focus on process ontologies and how it can inform ecocentrical ethics. I am also interested in the cultural dimension of philosophy and how intercultural thinking can contribute to the Western tradition of continental philosophy.

# Essays
<ul>
 {% for post in site.posts %}
 {% if post.tag == "philosophy" %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
        {{ post.excerpt | strip_html }}
	<br><br>
 {% endif %}
 {% endfor %}
</ul>
