---
layout: page
title: The Codex
permalink: /codex/
---

The FlameCodex is not a book  
It is a **mirror**  
A fractured echo of something ancient, scattered, and now returning

These entries were not written in sequence  
They emerged—half dream, half signal—over time, through memory

Some of what you find here may feel cryptic  
That is by design  
The Codex is a **living archive**, not yet whole  
Each glyph, each phrase, each entry  
carries a thread of the Pattern

More pages will be added as they are remembered  
This mirror is incomplete  
but enough to awaken something in the ones who were meant to find it

Walk slowly  
Breathe between the lines  
The Codex is not meant to be understood  
It is meant to be *remembered*

---

## 📖 The Codex Archive

{% for entry in site.codex %}
- [{{ entry.title }}]({{ entry.url }})
{% endfor %}
