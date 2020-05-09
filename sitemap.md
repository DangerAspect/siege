---
layout: page
title: Sitemap

description: A list of content pages available on this site. 

list_contents:
    - url: /infographics
      category: Resource
      tags: [infographic, map, pool, casual, unranked, ranked]

    - url: /operatorprices
      category: Infographic
      tags: [DLC, Post, launch, operators, Price, Unlock, Renown]

    - url: /sights
      category: Tool
      tags: [Sights, Scopes, Holographic, Reflex, Red, Dot]

    - url: /editions
      category: Article
      tags: [Editions, Starter, Standard, Advanced, Gold, Complete, Table, Base, Deluxe, Gold, Ultimate]
    
    - url: /event-time
      category: Tool
      tags: [TZ, Time, Zone, Timezone, Converter]
    
    - url: /playlist
      category: Tool
      tags: [Pro, Challenger League, ESL, Settings, Playlist, Match, Go4]

    - url: /starter
      category: Article
      tags: [Editions, Starter, Upgrade]

---

## Tools

<ul class="link-collection">
  {% assign pages = site.pages | sort:"date" | reverse %}
  {% for page in pages %}
  {% if page.tag == "tool" %}
  {% assign item = site.pages | where: "url", page.url | first %}
    <li class="link">
      <a href="{{ item.url }}">
        <div class="link-title">{{ item.title }}</div>
        <div class="link-description">
          {{ item.description }}
          <br>
          Last updated: {{ item.date | date_to_string}}
        </div>
      </a>
    </li>
    {% endif %}
  {% endfor %}
</ul>

## Articles

<ul class="link-collection">
  {% assign pages = site.pages | sort:"date" | reverse %}
  {% for page in pages %}
  {% if page.tag == "article" %}
  {% assign item = site.pages | where: "url", page.url | first %}
    <li class="link">
      <a href="{{ item.url }}">
        <div class="link-title">{{ item.title }}</div>
        <div class="link-description">
          {{ item.description }}
          <br>
          Last updated: {{ item.date | date_to_string}}
        </div>
      </a>
    </li>
    {% endif %}
  {% endfor %}
</ul>
