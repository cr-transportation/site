---
---

# Meeting agendas and minutes

<ul>
  {% for meeting in site.meetings reversed %}
  <li><a href="{{ meeting.url | relative_url }}">{{ meeting.date | date: '%B %d, %Y' }}</a></li>
  {% endfor %}
</ul>
