---
tags: false
layout: collection
title: Alpha
description: alpha stuff
pagination:
  data: collections.alpha
  reverse: true
  size: 50
permalink: "alpha/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"

eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---