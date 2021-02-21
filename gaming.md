---
layout: page
title: Gaming
permalink: /gaming/
updated: 2-20-2021
---

I play a lot of games on PC, Playstation, and the Nintendo Switch. I'll keep this page as an updated archive of all the games I've completed, potentially paired with some content around them.

# Completed Games in 2021

* Spider-man Remastered (PS5)
* Spider-man: Miles Morales (PS5)
* Astro's Playroom (PS5)

# Blog Posts
<!-- TODO: Update these links. -->
Below are my most recent blog posts specific to gaming - check them out here or at [the gaming category](), or at my [general blog page](/blog).

<ul>
    {%- for post in site.categories.gaming limit:5 -%}
        <li>
        <a href="{{ post.url }}">
            <b>
              {{ post.title }}
            </b>
          </a>-
          <time>{{ post.date | date: "%B %-d, %Y" }}</time>
    </li>
    {%- endfor -%}
<ul>