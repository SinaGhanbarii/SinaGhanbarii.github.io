---
title: ''
summary: 'Chemical engineering research, academic activities, and recent updates.'
date: 2026-06-29
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About Me
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: news
    content:
      title: Recent News
      text: Recent academic, research, and professional updates.
      page_type: blog
      count: 6
      filters:
        exclude_featured: false
        exclude_future: true
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: card
      columns: 2
      spacing:
        padding:
          - '0'
          - '0'
          - '0'
          - '0'

  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: Research collaboration and professional enquiries
      text: |-
        The most reliable way to reach me is by email at
        [mohammadsina.ghanbaripakdehi@mail.polimi.it](mailto:mohammadsina.ghanbaripakdehi@mail.polimi.it).

        You can also find my code and technical projects on [GitHub](https://github.com/SinaGhanbarii) and connect with me on [LinkedIn](https://www.linkedin.com/in/sinaaghanbari/).
    design:
      columns: '1'
---