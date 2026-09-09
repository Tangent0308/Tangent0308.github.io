---
title: ''
summary: ''
date: 2026-09-08
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Google Scholar
        url: https://scholar.google.com/citations?hl=zh-CN&user=oK4GaMYAAAAJ&view_op=list_works&sortby=title
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        Updates will be added here soon.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true

  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        Teaching information will be added here soon.
    design:
      columns: '1'

  - block: markdown
    id: misc
    content:
      title: Misc
      subtitle: ''
      text: |-
        Additional notes, service, and side projects will be added here soon.
    design:
      columns: '1'

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        - Email: [2200012743@stu.pku.edu.cn](mailto:2200012743@stu.pku.edu.cn)
        - Google Scholar: [Profile](https://scholar.google.com/citations?hl=zh-CN&user=oK4GaMYAAAAJ&view_op=list_works&sortby=title)
        - Location: Beijing, China
    design:
      columns: '1'
---
