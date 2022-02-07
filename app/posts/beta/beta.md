---
tags: false
layout: collection
title: Beta
description: Beta
pagination:
  data: collections.beta
  reverse: true
  size: 50
permalink: "beta/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"

eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---