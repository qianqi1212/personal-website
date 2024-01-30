---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    location: University of Michigan
    date_start: '2022-09-01'
    date_end: ''
    description: |2-
      Advised by [Stella Yu](https://www1.icsi.berkeley.edu/~stellayu/)
      
      Responsibilities include:
        
        * Create a vision model which conducts image-level recognition and segmentation concurrently.
        * Construct the hierarchy of image segmentation and language entity separately, and then match them at each level of granularity to derive hierarchical semantic segmentation.
      
  - title: Summer Undergraduate Research in Engineering
    company: Situated Language and Embodied Dialogue (SLED) Lab
    company_url: 'https://sled.eecs.umich.edu/'
    company_logo: 
    location: University of Michigan
    date_start: '2022-05-01'
    date_end: ''
    description: |2-
      Advised by [Joyce Chai](https://web.eecs.umich.edu/~chaijy/)
      
      Responsibilities include:
      
        * Leverage language models to resolve uncertainty in vision (disambiguating).
      
  - title: Research Assistant
    company: Situated Language and Embodied Dialogue (SLED) Lab
    company_url: 'https://sled.eecs.umich.edu/'
    company_logo: 
    location: University of Michigan
    date_start: '2022-01-01'
    date_end: ''
    description: |2-
      Advised by [Joyce Chai](https://web.eecs.umich.edu/~chaijy/) and [Jianing "Jed" Yang](https://jedyang.com/)
      
      Responsibilities include:
      
        * Design the prompting pipeline to query GPT-3 to generate actionable plans based on the goal state and environment feedback. 
        * Collect 65k egocentric view - text description of goal state pairs from the FILM dataset and fine-tune CLIP model to match goal states with stored frames during inference.
  
  - title: Machine Learning Software Engineer Intern
    company: Initium AI
    company_url: 'https://www.initium.ai/'
    company_logo: 
    location: 
    date_start: '2022-04'
    date_end: '2022-08'
    description: |2-
      Responsibilities include:
        
        * Incorporate TextRank algorithm and fine-tune BART model on abstract summarization task. Improve ROUGE scores on DialogSum dataset from 0.44 by 7\%.
        * Deploy pipeline on TorchServe front-end to transcribe sales meeting from audio to summarized text.
        
  - title: Research Assistant
    company: Shanghai Jiao Tong University
    company_url: 'https://en.sjtu.edu.cn/'
    company_logo: 
    location: Shanghai
    date_start: '2019-09-01'
    date_end: '2020-10-31'
    description: |2-
      * Design a service robot to be applied in hospital wards which is capable of navigating itself in unknown environment based on SLAM algorithm and providing customized message to patients according to their locations in the ward.
    
design:
  columns: '2'
---
