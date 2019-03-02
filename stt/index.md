---
layout: stt
title: Speaking Times Tables
bodyclass: stt
---


{::nomarkdown}

<div id="fb-root"></div>
<script async defer src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v3.2&appId=262704357963522&autoLogAppEvents=1"></script>

<div class="row intro-panel">
	<div class="col-sm-6 col-xs-12">
		<div class="intro-left">
			<div class="intro">
				Using the spoken word, interactive learning and fun multiple choice testing, Speaking Times Tables helps kids pass those all important tests.
			</div>
			<div class="intro-app-btn">
				{% include sttdownloadbtn.html %}
			</div>
		</div>
	</div>
	<div class="col-sm-6 col-xs-12">
		<div class="intro-device">
			{% include sttdownloadbtn.html imagepath='static/stt/home/device_shot.png' width=300 %}
			<div class="fb-like pt-20" data-href="https://www.facebook.com/speakingtimestablesapp" data-layout="button_count" data-action="like" data-size="small" data-show-faces="false" data-share="true"></div>
		</div>
	</div>
</div>

<div class="col-sm-5 hidden-sm visible-xs">
	<h3>Watch the app in action</h3>
	<a href="https://www.youtube.com/watch?v=D6GpOqsAeZI"><br>
		{% responsive_image path: static/stt/home/YouTube.png title: "Speaking Times tables video" width: 300 %}
		<br></a>
</div>
<div class="second-row">
	<div class="youtube-panel row">
		<div class="col-sm-5 hidden-xs youtube-dekstop-panel">
				<div class="video">
					<a href="https://www.youtube.com/watch?v=D6GpOqsAeZI"><br>
						{% responsive_image path: static/stt/home/YouTube.png title: "Speaking Times tables video" width: 300 %}
						<br></a>
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


<div class="recent_post">
	<h3>Features</h3>
	<ul>
	{% for user in site.stt_features %}
	{%  if user.type != "design" %}
	    <li>
	    	<a href="{{ site.baseurl }}{{ user.url }}">
	  			<u>{{ user.subtitle }}</u>
	  		</a> - {{ user.content | markdownify | strip_html | truncatewords: 30 }}
	  	</li>
	 {% endif %}
	{% endfor %}
	</ul>
</div>


