---
layout: default
title: "ホーム"
---

本を読んだり、新しい技術を学んだりするなかで、
自分が理解したことや疑問に思ったことを記録しています。

## 最近の記事

{% assign posts = site.posts | sort: "date" | reverse %}
{% for post in posts %}
- {{ post.date | date: "%Y/%m/%d" }}  
  [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}


---

※このサイトにはアフィリエイトリンクが含まれています。

Amazonのアソシエイトとして、当サイトは適格販売により収入を得ています。
