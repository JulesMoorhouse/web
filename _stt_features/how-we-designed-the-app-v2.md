---
layout: stt
title: Speaking Times Tables
subtitle: How we designed the app (v2)
bodyclass: stt
type: design
date: 2015-09-29 10:50:39
---

{% assign howwev1 = "" %}{% for t in site.stt_features %}{% if t.ident == 'hwdta' %}{% assign howwev1 = t.url %}{% endif %}{% endfor %}

Please see the blog post about the first version of the app <a href="{{ site.baseurl }}{{ howwev1 }}">here</a>.

<div class="container-table">
	<div class="row table-row">
		<div class="col-xs-12 col-sm-6 full-height" style="">
	        <div class="center-block">
	        	<a href="{{ site.baseurl }}/static/stt_features/speaking-times-tables-version-1.png" class="thickbox">
					<img title="Speaking Times Tables - version 1" height="225" width="300" src="/static/img-300/speaking-times-tables-version-1.png">
				</a>
				<div class="center-horiz">Version 1</div>
			</div>
		</div>
		<div class="col-xs-12 col-sm-6 full-height mobile-pt" style="">
			 <div class="center-block">
	        	<a href="{{ site.baseurl }}/static/stt_features/speaking-times-tables-version-2.png" class="thickbox">
					<img title="Speaking Times Tables - version 2" height="225" width="300" src="/static/img-300/speaking-times-tables-version-2.png">
				</a>
				<div class="center-horiz">Version 2</div>
			</div>
		</div>
	</div>
</div>


If you were to compare version 1 against version 2, you may notice that at first glance there isn't a great deal which looks different.

A lot of the changes have been made for technical reasons and to increase performance.

You may notice, that the monkey looks slightly different. Images do look different because they've been adjusted and converted into resizeable drawings. These changes make is possible to provide sharp / quality drawings for different size devices.

<div class="container-table">
	<div class="center-block">
		<a href="{{ site.baseurl }}/static/stt_features/iPhoneX-results.png" class="thickbox">
			<img title="Speaking Times Tables - Results" height="150" width="300" src="/static/img-300/iPhoneX-results.png">
		</a>
	</div>
</div>


The app is now available across all iPhones and iPads, including the new iPhone X.

{% assign historyurl = "" %}{% for t in site.stt_features %}{% if t.ident == 'thbta' %}{% assign historyurl = t.url %}{% endif %}{% endfor %}

Our times tables apps have grown over <a href="{{ site.baseurl }}{{ historyurl }}">several years</a> with each new version we've listened to customer feedback from parents and schools.

One of the key feature requests, was to allow multiple students / siblings to use the app and keep track of their progression through tables.

{% assign multiuserpageurl = "" %}{% for t in site.stt_features %}{% if t.ident == 'msds' %}{% assign multiuserpageurl = t.url %}{% endif %}{% endfor %}

With version 2, we have introduced iCloud support and <a href="{{ site.baseurl }}{{ multiuserpageurl }}">multiple student support</a> to make the app available to a lot more students.

We wanted to make the app available to students world wide. This was rather a large undertaking, so as well as UK English and US English we have added French, Spanish, Russian, German and Simplified Chinese languages. But this is an ongoing process and this first step provides these additional languages with Siri Support rather than voice recordings.

{% assign siriurl = "" %}{% for t in site.stt_features %}{% if t.ident == 'svr' %}{% assign siriurl = t.url %}{% endif %}{% endfor %}

This now means that you can use <a href="{{ site.baseurl }}{{ siriurl }}">Siri</a> in English too.

{% assign touchfaceurl = "" %}{% for t in site.stt_userguides %}{% if t.ident == 'artifi' %}{% assign touchfaceurl = t.url %}{% endif %}{% endfor %}

With so many new features and options, we needed some settings to allow parents and teachers to turn on these features. We have added a parent gate, which allows settings to be restricted. If your device has <a href="{{ site.baseurl }}{{ touchfaceurl }}">Touch ID or Face ID</a>, this can be employed to make access to settings easier.

<div class="container-table">
	<div class="center-block">

		{% include sttdownloadbtn.html %}
		
	</div>
</div>

{% include sttfeaturespagnation.html %}
