---
layout: archive
title: Archive
permalink: /archive

---
archive:
    - path: /blog/:year
      layout: archive_blog
      title: Blog archive — :year
      include:
        tags: ['PHP']
      exclude:
        categories: ['news']
        tags: ['drafts']
    - path: /blog/:year/:month
      layout: archive_blog
      title: Blog archive — :month :year
      include:
        tags: ['PHP']
      exclude:
        categories: ['news']
        tags: ['drafts']
    - path: /blog/:year/:month/:day
      layout: archive_blog
      title: Blog archive — :month :day, :year
      include:
        tags: ['PHP']
      exclude:
        categories: ['news']
        tags: ['drafts']
still under construction
goal：

- [ ] tag system or categories

- [ ] pages for multi chapters

- [ ] analytics for myself

- [ ] feedback box
