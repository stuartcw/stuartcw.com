---
layout: post
title:  "What I learned this month - October 2013"
date:   2013-10-15 12:52:00
categories: bash shell-scripting
---


## Shell Scripting

You can grep inside gzipping files directly using zcat. See below:

{% highlight bash %}
find . -name "acc*.gz" -exec zcat "{}" + |grep "error"
{% endhighlight %}

This is especially useful for grepping logfiles that have been compressed.

