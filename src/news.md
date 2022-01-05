---
title: 'Aerlytix News'
header: "Latest Company Updates"
layout: 'layouts/feed.html'
pagination:
  data: collections.news
  size: 9
permalink: 'news{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Newer posts'
paginationNextText: 'Older posts'
paginationAnchor: '#post-list'
---
