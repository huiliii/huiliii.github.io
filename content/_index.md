---
title: ""
date: 2026-04-10
type: landing

sections:

  - block: resume-biography
    id: about
    content:
      username: me
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      biography:
        style: ""
      banner:
        filename: ""

  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ""
      text: |
        My research focuses on understanding how the human brain develops during the earliest stages of life — from the fetal period through infancy and toddlerhood. I combine tools from **network control theory**, **connectomics**, and **machine learning** to investigate the emergence and maturation of brain network architecture.

        ### Network Controllability in the Developing Brain
        I use control-theoretic frameworks to characterize how structural brain networks in neonates and fetuses can drive transitions between neural states. This work has revealed how controllability properties of white-matter networks at birth predict later social and language outcomes.

        ### Brain Age and Normative Modeling
        I develop computational models to predict brain age from neonatal connectomes and identify deviations from normative developmental trajectories. These deviations relate to maternal factors and predict later cognitive performance.

        ### Fetal-Maternal Brain Interactions
        My recent work explores how fetal network controllability co-develops with synaptic density and synchronizes with maternal brain controllability during pregnancy, bridging prenatal neurobiology with postnatal developmental outcomes.
    design:
      columns: "1"

  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: ""
      text: ""
      filters:
        folders:
          - publication
      count: 20
      sort_by: "Date"
      sort_ascending: false
    design:
      view: citation

  - block: markdown
    id: awards
    content:
      title: Awards & Honors
      subtitle: ""
      text: |
        - **2026** — Rising Stars in Computational and Data Sciences, Santa Fe Institute
        - **2025** — Wharton Summer Fellowship, Nathaniel Wharton Fund
        - **2024** — Google PhD Fellowship (Finalist)
        - **2024** — ISDP Travel Award
        - **2023** — FIT'NG Young Investigator Award
        - **2023** — Flux Student Travel Award
        - **2023** — Yale WFF Seed Grant
        - **2020** — Outstanding Graduates, Department of Education, Sichuan, China
        - **2018** — National Scholarship, Ministry of Education, China
    design:
      columns: "1"
---
