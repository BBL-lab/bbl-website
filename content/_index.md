---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
sections:
  - block: markdown
    content:
      title: ''
      text: |
        <style>
        .bbl-hero{display:flex;flex-wrap:wrap;align-items:center;gap:2.5rem;}
        .bbl-hero-text{flex:1 1 340px;min-width:280px;}
        .bbl-hero-media{flex:1 1 340px;min-width:280px;}
        .bbl-logos{display:flex;flex-wrap:wrap;align-items:center;justify-content:center;gap:2rem;margin-bottom:1.5rem;}
        .bbl-slideshow{position:relative;width:100%;padding-top:66%;border-radius:14px;overflow:hidden;}
        .bbl-slideshow img{position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;opacity:0;animation:bblfade 16s infinite;}
        .bbl-slideshow img:nth-child(1){animation-delay:0s;}
        .bbl-slideshow img:nth-child(2){animation-delay:4s;}
        .bbl-slideshow img:nth-child(3){animation-delay:8s;}
        .bbl-slideshow img:nth-child(4){animation-delay:12s;}
        @keyframes bblfade{0%{opacity:0}4%{opacity:1}25%{opacity:1}29%{opacity:0}100%{opacity:0}}
        @media (prefers-reduced-motion: reduce){.bbl-slideshow img{animation:none}.bbl-slideshow img:nth-child(1){opacity:1}}
        </style>

        <div class="bbl-hero">
          <div class="bbl-hero-text">
            <div class="bbl-logos">
              <img src="uploads/logos/bbl.png" alt="Brain, Behavior and Learning Lab" style="height:135px;width:auto;">
              <a href="https://www.crnl.fr" target="_blank" rel="noopener"><img src="uploads/logos/crnl.png" alt="Lyon Neuroscience Research Center" style="height:93px;width:auto;"></a>
            </div>
            <p>The <strong><em>Brain, Behavior, and Learning lab</em></strong> studies the cognitive and neural mechanisms of human learning and development. Using behavioral methods and brain imaging, we explore how children acquire fundamental skills such as reasoning and numerical cognition. The lab is led by <a href="author/jerome-prado/">Jérôme Prado</a> and <a href="author/clea-girard/">Cléa Girard</a>, and is part of the EDUWELL team at the <a href="https://www.crnl.fr" target="_blank" rel="noopener">Lyon Neuroscience Research Center (CRNL)</a> in Lyon, France.</p>
          </div>
          <div class="bbl-hero-media">
            <div class="bbl-slideshow">
              <img src="uploads/photos/hero1.jpg" alt="A child taking part in a study">
              <img src="uploads/photos/hero2.jpg" alt="EEG recording session">
              <img src="uploads/photos/hero3.jpg" alt="The lab team">
              <img src="uploads/photos/hero4.jpg" alt="Research in the lab">
            </div>
          </div>
        </div>
    design:
      columns: '1'
  - block: markdown
    content:
      title: ''
      text: |
        <div style="display:flex; flex-wrap:wrap; align-items:center; justify-content:center; gap:4rem; padding:1rem 0;">
          <a href="https://www.cnrs.fr" target="_blank" rel="noopener"><img src="uploads/logos/cnrs.png" alt="CNRS" style="height:132px; width:auto;"></a>
          <a href="https://www.inserm.fr" target="_blank" rel="noopener"><img src="uploads/logos/inserm.png" alt="Inserm" style="height:78px; width:auto;"></a>
          <a href="https://www.univ-lyon1.fr" target="_blank" rel="noopener"><img src="uploads/logos/lyon1.png" alt="Université Claude Bernard Lyon 1" style="height:126px; width:auto;"></a>
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
