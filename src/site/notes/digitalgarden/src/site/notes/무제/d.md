---
{"dg-publish":true,"permalink":"//d/","title":"Home","tags":["gardenEntry"],"noteIcon":"","created":"2025-02-17T02:15:09.897+09:00","updated":"2025-02-18T23:41:43.280+09:00"}
---

--
# Duwon

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note\|Your first note]]</span> to get started on your exploration.
</p>

Hello there! yes!
<img src="{{ site.baseurl }}/assets/dudu.png"/>
<img src="{{ /assets/dudu.png"/>


![Pasted image 20250218231236.png](/img/user/Pasted%20image%2020250218231236.png)

<strong>Recently updated notes</strong>
dd
<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
