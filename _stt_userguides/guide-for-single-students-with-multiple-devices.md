---
layout: stt
title: Speaking Times Tables
subtitle: Guide for single students with multiple devices
bodyclass: stt
date: 2018-10-15 10:50:39
---

{% assign multiuserpageurl = "" %}{% for t in site.stt_features %}{% if t.ident == 'msds' %}{% assign multiuserpageurl = t.url %}{% endif %}{% endfor %}

As well as using iCloud sync for <a href="{{ site.baseurl }}{{ multiuserpageurl }}">multiple students</a>, you can also use multiple devices with a single student.

By default the app is setup to work in single student mode, without internet access. However if you wish to use multiple devices, use the multiple student features with iCloud enabled.

{% include sttuserguidepagnation.html %}
