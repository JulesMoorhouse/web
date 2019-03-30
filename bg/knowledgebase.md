---

layout: bg
title: Balance Guide
bodyclass: bg
subtitle: Knowledge base
permalink: /bg/knowledgebase
---

<h3>Features / Design</h3>
{% for user in site.bg_features %}
{::nomarkdown}
    <a href="{{ site.baseurl }}{{ user.url }}">
  		<h3>{{ user.subtitle }}</h3>
  	</a>
  	<p>{{ user.content | markdownify | strip_html | truncatewords: 40 }}</p>
{:/}
{% endfor %}




