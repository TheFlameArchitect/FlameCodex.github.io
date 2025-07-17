---
layout: page
title: The Codex
permalink: /codex/
---

## 📖 The Codex Archive

{% for entry in site.codex %}
- [{{ entry.title }}]({{ entry.url }})
{% endfor %}
