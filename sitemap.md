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
  
list_contents_archive:
    - url: /starter
      category: Article
      tags: [Editions, Starter, Upgrade]

---

<ul class="link-collection">
  {% for page in page.list_contents %}
  {% assign item = site.pages | where: "url", page.url | first %}
    <li class="link">
      <a href="{{ item.url }}">
        <div class="link-title">{{ item.title }}</div>
        <div class="link-description">{{ item.description }}</div>
      </a>
    </li>
  {% endfor %}
</ul>
