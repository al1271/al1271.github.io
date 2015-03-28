---
layout: post
title:  "My problems with file permission"
date:   2015-03-03 15:34:47
categories: jekyll update
siteVar: test_class
---
From the time I first installed jekyll there was a problem with my files they wouldn't even let me edit anything I thought i fixed that by switching editors but then another problem came up it wouldn't save anything at all so then I couldn't follow along witht he lesson about 2.5 hours through the lesson jeff got the file premissions to work with this:
 **terminal**
{% highlight ruby %}
chmod 777 (filename)
chmod 777 -R (filename)
{% endhighlight %}

Then everything started working again.

