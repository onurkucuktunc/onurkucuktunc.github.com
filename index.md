---
layout: page
title: Hello, I'm Onur Kucuktunc.
tagline: Student, scientist, etc.

---
{% include JB/setup %}

<div class="span5 pull-right clearfix">
<a href="archive.html" class="pull-right" style="margin-top:8px">see all...</a>
<h3>News and Blog posts</h3>
<dl>
  {% for post in site.posts limit:10 %}
    <dt>{{ post.date | date_to_string }}</dt><dd> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></dd>
  {% endfor %}
</dl>

<h3>Categories</h3>
<ul class="tag_box inline">
  {% assign categories_list = site.categories %}
  {% include JB/categories_list %}
</ul>
<br />

<h3>Tags</h3>
<ul class="tag_box inline">
  {% assign tags_list = site.tags %}  
  {% include JB/tags_list %}
</ul>
</div>

<img src="images/onur.jpg" class="img-polaroid span2 pull-right" />

I'm a Ph.D. candidate in [Computer Science and Engineering](http://www.cse.ohio-state.edu/) department at [The Ohio State University](http://www.osu.edu/).
I'm current working with [Umit V. Catalyurek](http://bmi.osu.edu/~umit/) at [HPC Lab](http://bmi.osu.edu/hpc/) of [Biomedical Informatics](http://bmi.osu.edu) department.
I received my B.S. and M.S. degrees from [Computer Engineering](http://cs.bilkent.edu.tr) department of [Bilkent University](http://www.bilkent.edu.tr), Ankara, Turkey in 2007 and 2009, respectively. During the masters, I worked on content-based video copy detection and visual similarity-based tag suggestion, and participated in TRECVID'08.

**Research interests.** similarity and diversity search; citation analysis; recommendation; sentiment analysis; opinion retrieval

#### Guide
If you are a Turkish student and a newcomer here in Columbus, check out my guide, [Yeni Gelecekler ve/veya İlk Günkü Heyecanını Koruyanlar için The Ohio State University ve Amerika Kılavuzu](guide.htm).

#### Blog
I was keeping a technology blog 5-6 years ago, called AçıkBilgi, which was a little popular that time (around 200 visitor per day, it was also featured in a Turkish TV program). Although it has been quite a while since I lost its domain name with all of its content, I was able to retrieve at least my entries. Since then I've been trying to bring back those writings and add them to a tumblr blog: [acikbilgi.tumblr.com](http://acikbilgi.tumblr.com/).
