---
layout: stt
title: Speaking Times Tables
bodyclass: stt
---

{::nomarkdown}


<div class="row intro-panel">
	<div class="col-sm-6 col-xs-12">
		<div class="intro-left">
			<div class="intro">
				Using the spoken word, interactive learning and fun multiple choice testing, Speaking Times Tables helps kids pass those all important tests.
			</div>
			<div class="intro-app-btn">
				<a href="http://itunes.apple.com/app/id917585923?mt=8&amp;at=1l3voF5&amp;ct=web_home">
					<img src="/static/img/Download.png" title="Download Speaking Times Tables for iPad" width="206" height="61" />
				</a>
			</div>
		</div>
	</div>
	<div class="col-sm-6 col-xs-12">
		<div class="intro-device">
			<a href="http://itunes.apple.com/app/id917585923?mt=8&amp;at=1l3voF5&amp;ct=web_home">
				<img src="/static/stt/home/device_shot_300.png" title="Download Speaking Times Tables for iPad" width="300" height="212" />
			</a>
		</div>
	</div>
</div>

<div class="col-sm-5 hidden-sm visible-xs">
	<h3>Watch the app in action</h3>

	<a href="https://www.youtube.com/watch?v=D6GpOqsAeZI"><br><img src="/static/stt/home/YouTube.png" alt="app video" width="300" height="169"><br></a>
</div>
<div class="second-row">
<div class="youtube-panel row">
	<div class="col-sm-5 hidden-xs youtube-dekstop-panel">
			<div class="video">
				<a href="https://www.youtube.com/watch?v=D6GpOqsAeZI"><br><img src="/static/stt/home/YouTube.png" alt="app video" width="300" height="169"><br></a>
			</div>
	</div>

	<div class="col-sm-7 col-xs-12 bullets-right">
		<h3 class="hidden-xs">Watch the app in action</h3>
		<ul>
			<li>
				Learn and then be tested on times tables, with amazing speaking sums.
			</li>
			<li>
				Simple and clear making it easy to understand.
			</li>
			<li>
				Fun and engaging sounds, with a cute monkey theme across the app.
			</li>
			<li>
				Tells your child when they get a sum wrong straight away, showing the correct answer to make sure they remember it.
			</li>
			<li>
				Final scoreboard with results to show kids if they went wrong.
			</li>
			<li>
				No links to email, web pages, adverts or in-app purchases!
			</li>
		</ul>
	</div>
</div>
</div>

{:/}


This is a test blog page where we can explore how to embedd images in the blog. 

## Image example 1

Here, I will embedd image from local assets which goes into `assets` directory in project's `root` directory. Choose a specific image, related to particular post. I chose to name the image `test-page-image-1.jpg`, which I will embedd as:

```markdown
![my alternate text](/assets/test-page-image-1.jpg);
``` 

![my alternate text](/assets/test-page-image-1.jpg);

Ofcourse, you can load images from web as well. Just point to image direct URL. For ex, here is one placeholder image:

```markdown
![my alternate text](http://lorempixel.com/400/200);
``` 

![my alternate text](http://lorempixel.com/400/200);

One cool thing about this is the fact that images adapt themselves to the screen size of device. Try to resize your browser window and check for yourself, Have fun.



<h1>Latest Post</h1>
{% for post in site.posts limit:1 %}

{{ post.title }}

{% endfor %}

<h1>Recent Posts</h1>
{% for post in site.posts offset:1 limit:2 %}

{{ post.title }}

{% endfor %}




