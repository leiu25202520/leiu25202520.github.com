---
layout: post
title:  "git 基本配置和使用"
date:   2016-04-10 07:56:25 +0800
---


{% highlight ruby %}
git init
ls -a
git status
{% endhighlight %}


{% highlight ruby %}
git add README
git commit -m "1st"
{% endhighlight %}


{% highlight ruby %}
git config --global user.name "leiu25202520"
git config --global user.email "leiu2520@126.com"
git log
git log -p
{% endhighlight %}


{% highlight ruby %}
git commit -a
git diff
{% endhighlight %}


{% highlight ruby %}
git config --global core.editor vim
git commit -a -v
git config --global alias.ci "commit -a -v"
{% endhighlight %}


{% highlight ruby %}
[alias]
    ci = commit -a -v
{% endhighlight %}

Check out the [参考地址][video-link]

[video-link]: http://haoduoshipin.com/v/4
