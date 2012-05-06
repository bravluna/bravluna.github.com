---
layout: page
title: Bravluna
tagline:
---
{% include JB/setup %}

我终于看见了那座城堡。它位于一个高丘的丘顶，落日的些微余晖照在旗帜飘扬的塔楼上，堡身是白色的，白白的，很漂亮。不知为什么，我觉得只有在梦中才能见到如此美丽且难以抵达的地方。在那样的梦中，你会焦急地奔跑在一条浓密森林间的蜿蜒道路上，想要赶到山丘顶上明亮的白色建筑物那里去，就好像那里举办着一场你也想要参加的晚会，有着你所不想错过的幸福。但是，你以为马上就要到头的路却怎么也走不会。

*摘自《白色城堡》*

### 文章列表

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
