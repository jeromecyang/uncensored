---
---

2026年8月起，從自己出發，沒有濾鏡沒有社群考量的簡短內容創作。

{% for post in site.posts %}
  <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
  <span>— {{ post.date | date_to_string }}</span>
{% endfor %}