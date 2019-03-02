---
layout: stt
title: Speaking Times Tables
subtitle: Universal device support
bodyclass: stt
---

The first version of the app was designed purely for iPad. However, all of the images in that version have been converted into drawing code. This has made it possible to cater for larger devices without a loss in quality.

<div class="container-table">
<div class="row center-horiz">
<div class="col-xs-4">
	<a href="{{ site.baseurl }}/static/stt_features/iPadPro12.9-inch-main.png" class="thickbox">
		{% responsive_image path: static/stt_features/iPadPro12.9-inch-main.png title: "Speaking Times Tables on iPad Pro 12.9 inch" width: 300 %}
	</a>
</div>
<div class="col-xs-4">
  <div style="margin-top: 15%">
	<a href="{{ site.baseurl }}/static/stt_features/iPhone5s-results.png" class="thickbox">
		{% responsive_image path: static/stt_features/iPhone5s-results.png title: "Speaking Times Tables on iPhone 5s" width: 300 %}
	</a>
  </div>
</div>
  <div class="col-xs-4">
	<a href="{{ site.baseurl }}/static/stt_features/iPadAir2-learn.png" class="thickbox">
		{% responsive_image path: static/stt_features/iPadAir2-learn.png title: "Speaking Times Tables on iPad Air 2" width: 300 %}
	</a>
  </div>
</div>

<div class="hidden-xs" style="padding-top: 10px;"></div>
<div class="visible-xs" style="padding-top: 3px;"></div>

<div class="row center-horiz">
  <div class="col-xs-5 col-xs-offset-1">
	<a href="{{ site.baseurl }}/static/stt_features/iPhone6Plus-test_table.png" class="thickbox">
		{% responsive_image path: static/stt_features/iPhone6Plus-test_table.png title: "Speaking Times Tables on iPhone 6/7/8 Plus" width: 300 %}
	</a>
  </div>
  <div class="col-xs-5">
	<a href="{{ site.baseurl }}/static/stt_features/iPhoneX-wrong_answer.png" class="thickbox">
		{% responsive_image path: static/stt_features/iPhoneX-wrong_answer.png title: "Speaking Times Tables on iPhone X" width: 300 %}
	</a>
  </div>
</div>
</div>

Adding support for the <a href="https://www.apple.com/ipad-pro/">iPad Pro</a> 12 inch created some development issues. Drawing code had to be specifically modified to cater for the bigger size. We also support the iPad Pro 10.5 inch and the <a href="https://www.apple.com/uk/iphone-x/">iPhone X</a>.

The app also now supports Touch ID and Face ID, this is optionally available as an alternative to the pin login feature, which restricts access to the settings screens.

{% assign settingicloud = "" %}{% for t in site.stt_userguides %}{% if t.ident == 'sis' %}{% assign settingicloud = t.url %}{% endif %}{% endfor %}

In order to provide multiple student features, <a href="https://www.apple.com/icloud/">iCloud</a> was required to allow students to share several devices, perhaps an iPhone and iPad. Adding <a href="{{ site.baseurl }}{{ settingicloud }}">iCloud support</a> was complex and care was taken to provide easy to use features which had flexibility for use in schools.

{% assign sirivoicerecordings = "" %}{% for t in site.stt_features %}{% if t.ident == 'svr' %}{% assign sirivoicerecordings = t.url %}{% endif %}{% endfor %}

Version 1 of the app had <a href="{{ site.baseurl }}{{ sirivoicerecordings }}">voice recordings</a>, however there was no choice to use Siri. English students can now use Siri or voice recordings. With improvements to Siri, other languages were possible and have been added to the app for use primarily by non English students.

<div class="container-table">
	<div class="center-block">
		{% include sttdownloadbtn.html %}
	</div>
</div>

{% include sttfeaturespagnation.html %}
