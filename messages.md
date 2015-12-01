---
layout: page
title: "留言板"
description: "message"
group: navigation
weight: 2
---
{% include JB/setup %}

### Hi:

这儿可没有礼物，想说点什么，就赶快留下你的足迹吧。

<section>

  {% if site.JB.comments.provider == 'duoshuo' %}
	{% include JB/comments-providers/duoshuo %}
  {% endif %}

</section>