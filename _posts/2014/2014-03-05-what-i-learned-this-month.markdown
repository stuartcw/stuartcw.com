---
layout: post
title:  "What I learned this month - March 2014"
date:   2014-03-05 12:00:00
categories: 
  - bash
  - shell-scripting
---


## Shell Scripting

This is Mac specific. This converts your Safari history to JSON.

{% highlight bash %}
plutil -convert json ~/Library/Safari/History.plist -o ~/History.plist.json
{% endhighlight %}


