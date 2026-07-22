---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: ''
      image:
        filename: welcome.jpg
      text: |
        <div style="display:flex; flex-wrap:wrap; align-items:center; gap:1.5rem; margin-bottom:1.25rem;">
          <img src="uploads/logos/bbl.png" alt="Brain, Behavior and Learning Lab" style="height:90px; width:auto;">
          <a href="https://www.crnl.fr" target="_blank" rel="noopener"><img src="uploads/logos/crnl.png" alt="Lyon Neuroscience Research Center (CRNL)" style="height:62px; width:auto;"></a>
        </div>

        The ***Brain, Behavior, and Learning lab*** studies the cognitive and neural mechanisms of human learning and development. Using behavioral methods and brain imaging, we explore how children acquire fundamental skills such as reasoning and numerical cognition. The lab is led by Jérôme Prado and is part of the EDUWELL team at the [Lyon Neuroscience Research Center (CRNL)](https://www.crnl.fr) in Lyon, France.
  - block: markdown
    content:
      title: ''
      text: |
        <div style="display:flex; flex-wrap:wrap; align-items:center; justify-content:center; gap:4rem; padding:1rem 0;">
          <a href="https://www.cnrs.fr" target="_blank" rel="noopener"><img src="uploads/logos/cnrs.png" alt="CNRS" style="height:88px; width:auto;"></a>
          <a href="https://www.inserm.fr" target="_blank" rel="noopener"><img src="uploads/logos/inserm.png" alt="Inserm" style="height:52px; width:auto;"></a>
          <a href="https://www.univ-lyon1.fr" target="_blank" rel="noopener"><img src="uploads/logos/lyon1.png" alt="Université Claude Bernard Lyon 1" style="height:84px; width:auto;"></a>
        </div>
    design:
      columns: '1'
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: compact
      columns: '1'
  - block: collection
    content:
      title: Recent Publications
      text: ''
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
  - block: markdown
    content:
      title: ''
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
