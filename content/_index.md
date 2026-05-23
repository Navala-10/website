---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  - block: resume-biography-3
    content:
      # This pulls profile data from `content/authors/me/_index.md`
      username: me
      text: 'Master’s graduate specializing in English Studies, Neurodevelopmental Disorders, and Linguistics. Passionate about metacognition, speech, and language acquisition, I am currently seeking Ph.D. positions for next year in psycholinguistics and neuroscience to further explore the intersection of mind, brain, and language.'
      # Show a call-to-action button under your biography
      button:
        text: Download CV
        url: uploads/your-resume.pdf # Place your PDF file in `static/uploads/your-resume.pdf`
      headings:
        about: 'About Me'
        education: 'Education'
        interests: 'Research Interests'
    design:
      # Use the Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px), large (320px)
        shape: circle # Options: circle, square, rounded

  - block: markdown
    content:
      title: '📚 My Proposal'
      subtitle: 'Psycholinguistics, Metacognition and Neurosciences'
      text: |-
        My research focus lies at the intersection of **Language Acquisition** and **Neuroscience**. Currently, I am investigating how language and music impact the brain development of children with neurodevelopmental disorders.

        ### Current Projects
        *   **Project Title 1:** Metacognition of Dys-: What if the timeframe between a reading task and its execution was crucial to the success of the task?
        *   **Project Title 2:** Phonk Metagem: How a style of music defines a genre of individuals.

        I apply a range of qualitative, quantitative, and neuroimaging methods to comprehensively investigate these systems. Please reach out if you are interested in collaborating! 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications # Pulls from `content/publications/`
        featured_only: true # Only shows publications where `featured: true` in their front matter
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events # Pulls from `content/events/`
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog # Pulls from `content/blog/` or `content/post/`
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: false # Set to false so it hides the generic HugoBlox kit promotion
    content:
      title: '🤝 Let’s Collaborate'
      text: |-
        I am always open to scientific discussions around my proposal and highly motivated to collaborate with both academic and industrial partners.
      button:
        text: Get in Touch
        url: 'mailto:ibnousaih.nawal06@gmail.com'
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
