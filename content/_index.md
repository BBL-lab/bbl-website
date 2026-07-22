---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: hero
    content:
      title: |
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The ***Brain, Behavior, and Learning lab*** studies the cognitive and neural mechanisms of human learning and development. Using behavioral methods and brain imaging, we explore how children acquire fundamental skills such as reasoning and numerical cognition. The lab is led by Jérôme Prado and is part of the EDUWELL team at the [Lyon Neuroscience Research Center (CRNL)](https://www.crnl.fr) in Lyon, France.
  
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
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
