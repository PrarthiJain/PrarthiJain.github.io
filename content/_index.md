---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📌 About My Work'
      subtitle: ''
      text: |-
        I’m a Software Development Engineer at Amazon Web Services, focusing on building an agentic platform that leverages large language models to automate AWS cloud support workflows, analyze incidents, and drive near real-time remediation across large-scale distributed systems. Previously, I led observability and telemetry platforms for robotics at Dexterity, and worked on Spark on Kubernetes at Cloudera.

        I specialize in distributed systems, real-time streaming and anomaly detection, and modern platform engineering. With published research in IEEE, ACM, and Springer, I’m passionate about taking systems from prototype to production and building platforms that improve reliability, scalability, and developer experience.

        Focus areas: GenAI & multi-agent systems · Backend & Platform Engineering · Distributed Systems & Cloud Architecture · Kubernetes · Real-Time Telemetry
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
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
    id: experience
    content:
      title: Experience
      username: admin
    design:
      date_format: 'Jan 2006'
      is_education_first: false
  - block: markdown
    content:
      title: 'News'
      text: |-
        - IIT Indore using AI to develop network to detect fires in Melghat Tiger Reserve — [Times of India](https://timesofindia.indiatimes.com/city/nagpur/iit-indore-using-ai-to-develop-network-to-detect-fires-in-melghat-tiger-reserve/articleshow/85877519.cms)
    design:
      columns: '1'
  
---
