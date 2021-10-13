---
tags: false
layout: collection
title: Public interface
description: How friends and family will book social visits online
pagination:
  data: collections.public-interface
  reverse: true
  size: 50
permalink: "public-interface/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---