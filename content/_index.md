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
        text: GitHub
        url: https://github.com/Tangent0308
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
      username: me
    design:
      date_format: '2006'
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
        - Email: [tanyue@stu.pku.edu.cn](mailto:tanyue@stu.pku.edu.cn)
        - GitHub: [Tangent0308](https://github.com/Tangent0308)
    design:
      columns: '1'
---
