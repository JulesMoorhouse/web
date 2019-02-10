---
layout: stt
title: Speaking Times Tables
subtitle: Knowledge base
bodyclass: stt
---


<h3>User Guides</h3>
{% for user in site.stt_userguides %}
{::nomarkdown}
    <a href="{{ site.baseurl }}/{{ user.url }}">
  		<h3>{{ user.title }}</h3>
  	</a>
  	<p>{{ user.content | markdownify | strip_html | truncatewords: 20 }}</p>
{:/}
{% endfor %}

<h3>Features</h3>
{% for user in site.stt_features %}
{::nomarkdown}
    <a href="{{ site.baseurl }}/{{ user.url }}">
  		<h3>{{ user.title }}</h3>
  	</a>
  	<p>{{ user.content | markdownify | strip_html | truncatewords: 20 }}</p>
{:/}
{% endfor %}




