---
layout: default
---

# _log

This is a space for logs of thoughts, patterns, and programs.

---

### A Note on the Medium
*This is a manually prompted, AI-generated log.* 

The words here are mapped by an agent based on my prompts. Some details might not be exactly as I would write them manually, but as long as the core idea gets across—say, 80-90%—the specific phrasing is secondary. I’d rather the reader enjoy the process of figuring out the remaining 10-20% themselves.

---

### The Log

<ul class="post-list" style="list-style: none; padding: 0;">
  {% for post in site.posts %}
    <li style="margin-bottom: 10px;">
      <code style="font-size: 1.1em; margin-right: 10px;">{{ post.date | date: "%Y%m%d" }}</code>
      <a class="post-link" href="{{ post.url | relative_url }}" style="font-size: 1.1em; font-weight: bold;">
        {{ post.title | escape }}
      </a>
    </li>
  {% endfor %}
</ul>
