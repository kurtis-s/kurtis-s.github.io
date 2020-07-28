---
layout: post
title:  "Jekyll Notes"
date:   2020-07-28 13:09:43 -0700
categories: jekyll update
---
I always forget the Jekyll commands and project layout, so this is a conveniently located crib sheet to remind myself. 

Posts go in the `_posts` directory and need to be named as

`YEAR-MONTH-DAY-title.MARKUP`,

where `MARKUP` is the file extension, `YEAR` is four digits, and `MONTH` and `DAY` are two digits.

The website can be tested and served locally by running

{% highlight bash %}
bundle exec jekyll serve
{% endhighlight %}

in the root directory.

After pushing to github it can take a while for the GitHub CDN to show the changes, so to speed things up you can append a query string like <https://kurtis-s.github.io/?fakeparam=fakevalue> to break the cache.
