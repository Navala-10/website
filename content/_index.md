---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  # ---
title: ''
summary: ''
date: 2026-05-23
type: landing

sections:
  # ────────────────────────────────────────────────────────────────────────────
  # EN-TÊTE CENTRÉ (Exactement comme le site de Léo Dutriaux)
  # ────────────────────────────────────────────────────────────────────────────
  - block: about-avatar
    content:
      username: me
      # On laisse le texte vide ici pour que ce bloc ne serve que d'en-tête centré
      text: '' 
    design:
      background:
        gradient_mesh:
          enable: true

  # ────────────────────────────────────────────────────────────────────────────
  # BIOGRAPHIE ET PRÉSENTATION EN DESSOUS (Pleine largeur)
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '👋 About Me'
      subtitle: ''
      text: |-
        Master's graduate specializing in **English Studies, Neurodevelopmental Disorders, and Linguistics**. Passionate about metacognition, speech, and language acquisition, I am currently seeking **Ph.D. positions for next year** in **psycholinguistics and neuroscience** to further explore the intersection of mind, brain, and language.

        With an academic journey driven by a fascination with how the brain processes language, I blend linguistic theory with a deep understanding of cognitive differences. I am eager to leverage my interdisciplinary training to explore how language shapes—and is shaped by—the human brain, contributing to research that bridges the gap between language acquisition, cognitive processing, and neurodiversity.
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
