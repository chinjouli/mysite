---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      date_format: Jan 2006
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate researcher
          company: ChangeLing Lab, Carnegie Mellon University
          company_url: 'https://changelinglab.github.io/'
          company_logo: changeling
          location: Pittsburgh, PA
          date_start: '2024-09-01'
          date_end: ''
          description: Researching speech recognition with a phonetic/phonological focus, supervised by Prof. David R. Mortensen.
        - title: Undergraduate researcher
          company: Intelligent Agents Lab, National Taiwan University
          company_url: 'https://iagentntu.github.io/'
          company_logo: iagent
          location: Taipei, Taiwan
          date_start: '2022-09-01'
          date_end: '2024-06-30'
        - title: Research assistant
          company: Biomedical Acoustic Signal Processing Lab, Academia Sinica
          company_url: 'https://bio-asplab.citi.sinica.edu.tw/'
          company_logo: bioasp
          location: Taipei, Taiwan
          date_start: '2022-07-01'
          date_end: '2024-02-29'
          description: Research in audio-visual speech enhancement and speaker diarization, supervised by Dr. Yu Tsao and Dr. Jen-Cheng Hou.
          description: Handled data processing and model evaluation for Traditional Chinese LLM development under supervision of Prof. Jane Yung-Jen Hsu.
        - title: Research assistant
          company: Department of Neurology Neurological Institute, Taipei Veterans General Hospital
          company_url: 'https://wd.vghtpe.gov.tw/vghneuro/Index.action?mlangloc=en_US'
          company_logo: tphos
          location: Taipei, Taiwan
          date_start: '2023-01-01'
          date_end: '2023-12-31'
          description: Applied computer vision techniques to clinical seizure recording, including action recognition and privacy protection.
        - title: Teaching assistant / DNS group member
          company: NTU CSIE Network Administration and System Administration Team, National Taiwan University
          company_url: ''
          company_logo: nasa
          location: Taipei, Taiwan
          date_start: '2022-09-01'
          date_end: '2024-06-30'
          description:  Monitored network stability for the CS department and guided new members.
        - title: Teaching assistant
          company: French (I) and French (II), National Taiwan University
          company_url: ''
          company_logo: ntu
          location: Taipei, Taiwan
          date_start: '2022-09-01'
          date_end: '2024-06-30'
          description:  Facilitated learning in a class of 40 students with TA from France.
        - title: Intern
          company: Open Culture Foundation
          company_url: 'https://ocf.tw/en/'
          company_logo: ocf
          location: Taipei, Taiwan
          date_start: '2023-09-01'
          date_end: '2024-01-06'
          description: Translated articles about open technology, digital rights, and internet freedom.
    design:
      columns: '1'
    
  - block: collection
    id: publication
    content:
      title: Publications
      #  Discover relevant content by [filtering publications](./publication/).
      text: |-
        {{% callout note %}}
        Actively updating 💼
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation # list / compact / list / card / citation
  
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 1
      buttons:
        - name: All
          tag: '*'
        - name: CS
          tag: Computer Science
        - name: Multimodal
          tag: Multimodal
        - name: NLP
          tag: Natural Language Processing
        - name: Edu
          tag: Education
    design:
      columns: '2'  # Valid values: '1' or '2'
      view: compact # list / compact / list / card
      flip_alt_rows: false # for showcase, flip alternate rows or not
  
  #- block: skills
  #  content:
  #    title: Skills
  #    text: ''
  #    # Choose a user to display skills from (a folder name within `content/authors/`)
  #    username: admin
  #  design:
  #    columns: '1'
  
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me through email 📨
      # Contact (add or remove contact options as necessary)
      email: chinjoul@andrew.cmu.edu
      contact_links:
        - icon: mail-bulk
          icon_pack: fas
          name: chinjou.li@gmail.com
          link: 'mailto:chinjou.li@gmail.com'
      #phone: 888 888 88 88
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
  
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

  ### not used ###
  #
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
      # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #     exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'
  #
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  #
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #
  #- block: accomplishments
    #content:
    #  # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      #title: 'Accomplish&shy;ments'
      #subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      #date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      #items:
      #  - certificate_url: https://www.coursera.org
      #    date_end: ''
      #    date_start: '2021-01-25'
      #    description: ''
      #    organization: Coursera
      #    organization_url: https://www.coursera.org
      #    title: Neural Networks and Deep Learning
      #    url: ''
      #  - certificate_url: https://www.edx.org
      #    date_end: ''
      #    date_start: '2021-01-01'
      #    description: Formulated informed blockchain models, hypotheses, and use cases.
      #    organization: edX
      #    organization_url: https://www.edx.org
      #    title: Blockchain Fundamentals
      #    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    #design:
    #  columns: '2'
---
