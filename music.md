---
layout: page
title: Music
permalink: /music/
updated: 2-20-2021
---

I've been learning guitar and making playlists for the past few months!

# Playlists
<!-- TODO: Update me -->
I'll start to update this page soon with playlists as I create them.

# Blog Posts
<!-- TODO: Update these links. -->
Below are my most recent blog posts specific to music - check them out here or at [the music category](), or at my [general blog page](/blog).

<ul>
    {%- for post in site.categories.music limit:5 -%}
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