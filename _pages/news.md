---
layout: page
permalink: /news/
title: News
description: Long Cheng, news
---

<h4><strong>News</strong></h4>
<div class="news2">
  {% if site.news %}
    <table>
    {% assign news = site.news | reverse %}
    {% for item in news %}
      <tr class="no-top-border">
        <td class="date">{{ item.date | date: "%b, %Y" }}</td>
        <td class="announcement">
          {% if item.inline %}
            {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
          {% else %}
            <a class="news-title" href="{{ item.url | prepend: site.baseurl }}">{{ item.title }}</a>
          {% endif %}
        </td>
      </tr>
    {% endfor %}
    </table>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>