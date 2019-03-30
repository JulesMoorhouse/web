---
layout: stt
title: Speaking Times Tables
subtitle: Universal device support
bodyclass: stt
date: 2015-10-03 10:50:39
---
{::nomarkdown}
<p>
	The first version of the app was designed purely for iPad. However, all of the images in that version have been converted into drawing code. This has made it possible to cater for larger devices without a loss in quality.
</p>
<div class="container-table">
<div class="row center-horiz">
<div class="col-xs-4">
	<a href="{{ site.baseurl }}/static/stt_features/iPadPro12.9-inch-main.png" class="thickbox">
		<img title="Speaking Times Tables on iPad Pro 12.9 inch" height="216" width="300" src="/static/img-300/iPadPro12.9-inch-main.png">
	</a>
</div>
<div class="col-xs-4">
  <div style="margin-top: 15%">
	<a href="{{ site.baseurl }}/static/stt_features/iPhone5s-results.png" class="thickbox">
		<img title="Speaking Times Tables on iPhone 5s" height="143" width="300" src="/static/img-300/iPhone5s-results.png">
	</a>
  </div>
</div>
  <div class="col-xs-4">
	<a href="{{ site.baseurl }}/static/stt_features/iPadAir2-learn.png" class="thickbox">
		<img title="Speaking Times Tables on iPad Air 2" height="211" width="300" src="/static/img-300/iPadAir2-learn.png">
	</a>
  </div>
</div>

<div class="hidden-xs" style="padding-top: 10px;"></div>
<div class="visible-xs" style="padding-top: 3px;"></div>

<div class="row center-horiz">
  <div class="col-xs-5 col-xs-offset-1">
	<a href="{{ site.baseurl }}/static/stt_features/iPhone6Plus-test_table.png" class="thickbox">
		<img title="Speaking Times Tables on iPhone 6/7/8 Plus" height="147" width="300" src="/static/img-300/iPhone6Plus-test_table.png">
	</a>
  </div>
  <div class="col-xs-5">
	<a href="{{ site.baseurl }}/static/stt_features/iPhoneX-wrong_answer.png" class="thickbox">
		<img title="Speaking Times Tables on iPhone X" height="150" width="300" src="/static/img-300/iPhoneX-wrong_answer.png">
	</a>
  </div>
</div>
</div>

<p>
	Adding support for the <a href="https://www.apple.com/ipad-pro/">iPad Pro</a> 12 inch created some development issues. Drawing code had to be specifically modified to cater for the bigger size. We also support the iPad Pro 10.5 inch and the <a href="https://www.apple.com/uk/iphone-x/">iPhone X</a>.
</p>
<p>
	The app also now supports Touch ID and Face ID, this is optionally available as an alternative to the pin login feature, which restricts access to the settings screens.
</p>
{% assign settingicloud = "" %}{% for t in site.stt_userguides %}{% if t.ident == 'sis' %}{% assign settingicloud = t.url %}{% endif %}{% endfor %}
<p>
	In order to provide multiple student features, <a href="https://www.apple.com/icloud/">iCloud</a> was required to allow students to share several devices, perhaps an iPhone and iPad. Adding <a href="{{ site.baseurl }}{{ settingicloud }}">iCloud support</a> was complex and care was taken to provide easy to use features which had flexibility for use in schools.
</p>
{% assign sirivoicerecordings = "" %}{% for t in site.stt_features %}{% if t.ident == 'svr' %}{% assign sirivoicerecordings = t.url %}{% endif %}{% endfor %}
<p>
	Version 1 of the app had <a href="{{ site.baseurl }}{{ sirivoicerecordings }}">voice recordings</a>, however there was no choice to use Siri. English students can now use Siri or voice recordings. With improvements to Siri, other languages were possible and have been added to the app for use primarily by non English students.
</p>
{:/}

<div class="container-table">
	<div class="center-block">
		{% include sttdownloadbtn.html %}
	</div>
</div>

{% include sttfeaturespagnation.html %}
