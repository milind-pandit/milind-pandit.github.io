---
title: Publications
type: landing
cms_exclude: true

design:
  spacing: '4rem'

sections:
  - block: collection
    id: journal-articles
    content:
      title: Journal Articles
      count: 0
      filters:
        folders:
          - publications
        publication_type: article-journal
      archive:
        enable: false
    design:
      view: citation
      css_class: pubs
  - block: collection
    id: conference-proceedings
    content:
      title: Conference Proceedings
      count: 0
      filters:
        folders:
          - publications
        publication_type: paper-conference
      archive:
        enable: false
    design:
      view: citation
      css_class: pubs
  - block: collection
    id: patents
    content:
      title: Patents
      count: 0
      filters:
        folders:
          - publications
        publication_type: patent
      archive:
        enable: false
    design:
      view: citation
      css_class: pubs
  - block: collection
    id: thesis
    content:
      title: Thesis
      count: 0
      filters:
        folders:
          - publications
        publication_type: thesis
      archive:
        enable: false
    design:
      view: citation
      css_class: pubs
---
