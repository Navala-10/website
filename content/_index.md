---
title: ""
summary: ""
date: 2026-05-23
type: landing

sections:
  # ────────────────────────────────────────────────────────────────────────────
  # BLOC BIOGRAPHIE COMPLET
  # ────────────────────────────────────────────────────────────────────────────
  - block: resume-biography-3
    content:
      username: me
      text: "" 
      button:
        text: Download CV
        url: "uploads/Nawal IbnouSaih Academic CV.pdf"
      headings:
        about: 'Professional Summary'
        education: 'Education'
        interests: 'Research Interests'
    design:
      columns: '1'
      background:
        gradient_mesh:
          enable: false
      name:
        size: medium
      avatar:
        size: medium
        shape: circle

  # ────────────────────────────────────────────────────────────────────────────
  # VOTRE BIO AVEC LE FORCEUR DE STYLE SYNTHWAVE EN CSS
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '📝 Professional Summary'
      subtitle: ''
      text: |-
        <style>
          :root, html, body, [data-theme] {
            --background: #1a1423 !important;
            background-color: #2b213a !important;
            color: #f43f5e !important;
          }
          .dark {
            background-color: #2b213a !important;
          }
          h1, h2, h3, strong {
            color: #f353bb !important;
          }
        </style>

        <script>
          localStorage.setItem('theme', 'synthwave');
          document.documentElement.setAttribute('data-theme', 'synthwave');
          document.documentElement.classList.add('dark');
        </script>

        Master's graduate specializing in **English Studies, Neurodevelopmental Disorders, and Linguistics**. Passionate about the cognitive frameworks of speech and language processing, I am currently seeking Ph.D. positions for next year in psycholinguistic and neurosciences to further explore the intersection of mind, brain, and language.
    design:
      columns: '1'

  # ────────────────────────────────────────────────────────────────────────────
  # SECTION PROPOSAL
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    content:
      title: '📚 My Proposal'
      subtitle: 'Psycholinguistics, Metacognition and Neurosciences'
      text: |-
        My research focus lies at the intersection of **Language Acquisition** and **Signal Analysis**. Currently, I am investigating how language and music impact the brain development of children with neurodevelopmental disorders.

        ### Current Projects
        * **Project Title 1:** Metacognition of Dys-: What if the timeframe between a reading task and its execution was crucial to the success of the task?
        * **Project Title 2:** Phonk Metagem: How a style of music defines a genre of individuals.

        I apply a range of qualitative, quantitative, and neuroimaging methods to comprehensively investigate these systems. Please reach out if you are interested in collaborating! 😃
    design:
      columns: '1'

  # ────────────────────────────────────────────────────────────────────────────
  # CONTACT
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
