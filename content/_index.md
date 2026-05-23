---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 1 : BANNIÈRE PRINCIPALE (Photo, Pronoms, Rôle et Liens)
  # ────────────────────────────────────────────────────────────────────────────
  - block: resume-biography-3
    content:
      # Pulle les données (liens, pronoms, avatar) depuis content/authors/me/_index.md
      username: me
      text: '' # Laissé vide ici pour éviter la surcharge à droite
      button:
        text: Download CV
        url: uploads/your-resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Fond dégradé fluide qui s'adapte automatiquement au mode sombre/synthwave
      background:
        gradient_mesh:
          enable: true
      # Ajustements pour tout centrer proprement et aérer la bannière
      columns: '1'
      name:
        size: lg
      avatar:
        size: medium
        shape: circle

  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 2 : VOTRE BIOGRAPHIE (Maintenant positionnée en dessous, bien lisible)
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '👋 About Me'
      subtitle: ''
      text: "Master's graduate specializing in **English Studies**, **Neurodevelopmental Disorders**, and **Linguistics**."
        With a academic journey driven by a fascination with how the brain processes language, I blend linguistic theory with a deep understanding of cognitive differences. I am eager to leverage my interdisciplinary training to explore how language shapes—and is shaped by—the human brain, contributing to research that bridges the gap between language acquisition, cognitive processing, and neurodiversity.
    design:
      columns: '1'

  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 3 : PROJET DE RECHERCHE & PROPOSAL
  # ────────────────────────────────────────────────────────────────────────────
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

  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 4 : CONTACT / COLLABORATION
  # ────────────────────────────────────────────────────────────────────────────
  - block: cta-card
    demo: false
    content:
      title: '🤝 Let’s Collaborate'
      text: |-
        I am always open to scientific discussions around my proposal and highly motivated to collaborate with both academic and industrial partners.
      button:
        text: Get in Touch
        url: 'mailto:ibnousaih.nawal06@gmail.com'
    design:
      card:
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
