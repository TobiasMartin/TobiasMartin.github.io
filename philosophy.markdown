---
layout: page
title: Philosophy
permalink: /philosophy/
---

In 2021, I enrolled in philosophy courses at the University of Oslo to better reflect upon ethical questions regarding technology and its impact on nature - an aspect which was missing in my previous degrees. Ultimately, I decided to align my actions with my core beliefs about the importance of the humanities for solving environmental issues by studying philosophy at the University of Oslo.

Here, my main interest is philosophy of nature which includes philosophy of mind and environmental philosophy to me. Here, I focus on ontopoetics and how it informs ecocentrical ethics. I am also interested in the cultural dimension of philosophy and how intercultural thinking can contribute to the Western tradition of continental philosophy.

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
