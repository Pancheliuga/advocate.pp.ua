---
title: 'Архів тегів'
layout: 'layouts/feed.html'
pagination:
  data: collections
  size: 1
  alias: tag
  filter: ['all', 'nav', 'blog', 'work', 'featuredWork', 'rss']
permalink: '/tag/{{ tag | slug }}/'
---
