---
layout: post
title: Transforming HTTPS Everywhere to Onion Everywhere
categories:
  - Onion-Services
  - Usability
---
![][intropic]

One of the . In this article

{% highlight xml %}
<ruleset name="Qubes Onion">
	<target host="qubes-os.org" />
	<target host="www.qubes-os.org" />
	<target host="deb.qubes-os.org" />
	<target host="yum.qubes-os.org" />
	<target host="ftp.qubes-os.org" />
	<rule from="^https?://(www\.)?qubes-os\.org/" to="http://qubesos4rrrrz6n4.onion/" />
	<rule from="^https?://(deb|yum|ftp)\.qubes-os\.org/" to="http://$1.qubesos4rrrrz6n4.onion/" />
</ruleset>
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[intropic]: https://web.archive.org/web/20170513092328/https://raw.githubusercontent.com/T0rUser/T0rUser.github.io/af40b27ac7c72083d8fc3053581073b1302245c5/Untitled.png
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
