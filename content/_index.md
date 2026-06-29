---
title: ''
summary: 'Chemical engineering research in process modelling, desalination, sustainable energy, and data-driven engineering.'
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
        about: About
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

  - block: markdown
    content:
      title: Research Focus
      subtitle: Sustainable processes supported by experiments, modelling, and data
      text: |-
        My research combines **chemical-engineering fundamentals**, **process simulation**, and **data-driven methods** to study sustainable technologies. My current work centres on solar-assisted humidification–dehumidification desalination, including experimental condenser enhancement and process modelling.

        I am also interested in environmental catalysis, machine-learning applications in thermodynamics and materials, techno-economic analysis, and life-cycle assessment.
    design:
      columns: '1'

  - block: collection
    content:
      title: Featured Projects
      text: Selected work in desalination, process design, sustainability, and computational chemical engineering.
      filters:
        folders:
          - projects
        featured_only: true
      count: 6
    design:
      view: article-grid
      columns: 3
      fill_image: false
      show_date: false
      show_read_time: false
      show_read_more: true

  - block: collection
    id: publications
    content:
      title: Publications
      text: Published and in-press academic work.
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

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
