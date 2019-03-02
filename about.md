---
layout: page
title: About
permalink: /about/
subtitle: My iOS Development Journey
---

Welcome to my site, I'm called Jules to everyone who knows me, although my real name is Julian Moorhouse.

What is this site about? It's aimed to show off my projects, provide somewhere where I can add blog posts about topics which interest me. This will generally be iOS related. Although my day job is a .net web developer.

{% assign myfirstapp_url = "" %}{% for t in site.posts %}{% if t.ident == 'myfapp' %}{% assign myfirstapp_url = t.url %}{% endif %}{% endfor %}

{::nomarkdown}


<div style="float: right; width: 120px; padding-left: 20px;">
{% responsive_image path: static/img/icon-sttv1.png title: "Speaking Times Tables version 1 logo" width: 100 %}
</div>

<p>
I developed my first iPhone app  which sadly is no longer in the app store, <a href="{{ site.baseurl }}/{{myfirstapp_url}}">Speaking Times Tables</a> (not to be confused with <a href="{{ site.baseurl }}/stt">Speaking Times Tables for iPad</a> written in 2015). 
</p>
<p>

At the time I spent a couple of years full time developing apps, which I was a stay hove dad, it was a wonderful time.
</p>

<div style="clear: left;"></div>

<div style="float: left; width: 120px;">
{% responsive_image path: static/img/icon-balance-guide.png title: "The logo for Balance Guide" width: 100 %}
</div>

<p>
I developed my second iPhone app <a href="{{ site.baseurl }}/bg">Balance Guide</a> also in 2010. 
</p>
<p>
Why did I develop it? Well I wanted some way to manage my finances on my iPhone and I thought it would be cool to write an app myself. 
</p>


<div style="clear: left;"></div>

<p>
I was hooked. Since then, it's been my favourite app, I just can't drag myself away. I've been adding new features and updating it ever since, why ? because I use it myself. 
</p>

<p>	
I have to say that I've had to hold myself back adding certain features and consider my user base, it's far to easy to add everything everyone requests and make a design mistake.
</p>


<div style="clear: left;"></div>

<div style="float: right; width: 120px; padding-left: 20px;">

{% responsive_image path: static/img/icon-revenue-calc.png title: "The icon for Revenue Calc" width: 100 %}
</div>
<p>
I'm not going to say much about my third app <a href="{{ site.baseurl }}/revenuecalc">Revenue Calc</a> other than it initially took an afternoon to develop, when I wanted to do something new, after developing Balance Guide.
</p>


<div style="clear: left;"></div>



<div style="float: left; width: 120px;">
{% responsive_image path: static/img/icon-sad-face-chart.png title: "The logo for Happy / Sad Face Chart" width: 100 %}
</div>


<p>			
In 2011 I wrote <a href="{{ site.baseurl }}/sadfacechart">Sad Face Chart</a>, again this was an app primarily  written for personal use.
</p>
<p>			
Although the icon was different to that shown here.
</p>


<div style="clear: left;"></div>

<div style="float: right; width: 220px; padding-left: 20px;">

{% responsive_image path: static/img/logo-orchidsoft.png title: "Orchid Softwares Logo" width: 200 %}
<br/>
{% responsive_image path: static/img/logo-oak.png title: "The Oak Intranet Logo" width: 200 %}
</div>


<p>
Later in 2011 a took up a web development position full time, after my son started at primary school. 
</p>
<p>
I've been an application / web developer at <a href="https://orchidsoft.com">Orchid Software Ltd</a> for over 7 years. I've worked on many interesting projects, on the companines intranet products. 
</p>
<p>
In the last two years I've been a full stack web developer on the <a href="https://www.oak.com">Oak intranet</a> platform.
</p>



<div style="clear: left;"></div>

<p>
Since then I've been working on my apps in every scrap or free time, unfortunately I haven't been able to release as many new apps as I would have like, but I have added some pretty neat functionality to my existing apps.
</p>

<div style="clear: left;"></div>

<div style="float: left; width: 120px;">

{% responsive_image path: static/img/icon-speaking-times-tables.png title: "The logo for Speaking Times Tables" width: 100 %}
</div>

<p>	
My next app was <a href="{{ site.baseurl }}/stt">Speaking Times Tables</a> HD written in 2015, I've since dropped "HD", like Balance Guide this has become one of my main apps, which I've actively continued to develop and upgrade. 

</p>
<p>

Initially I wrote the app for the original iPad, later I made the app universal and added iCloud support to enabled use in class rooms.
</p>

<div style="clear: left;"></div>

<p>
Since adding iCloud sync, I've extracted the functionality into a framework and am in the process of incorporating into new apps. 
</p>

<p>
I then brought iCloud sync to Sad Face Chart, then I started work on refactoring this code into a framework, this version has yet to be released.
</p>

<p>
What as I working on now, well at long last my first swift app, using my new iCloud Sync framework, I hope this will be released later this year.
</p>

<p>
Please feel free drop me a line on twitter <a href="https://twitter.com/MindwarpJules">@MindwapJules</a>, via the <a href="{{ site.baseurl }}/contactus">contact us</a> page or via the social links in the header.
</p>

{:/}