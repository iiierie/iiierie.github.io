---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-04-13
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  # # Uncomment and configure the skills block if needed
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'


  # - block: skills
  #     id: skills
  #     content:
  #       title: Skills
  #       text: ''
  #       # Choose a user to display skills from (a folder name within `content/authors/`)
  #       username: admin
  #     design:
  #       columns: '1'


  # Uncomment and configure the experience block if needed
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:
  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'


  - block: features
    id: skills
    content:
      title: <i class="fa-solid fa-bug"></i>&nbsp;Skills
      items:
        - icon: brain
          icon_pack: fas
          name: '[Artificial Intelligence](#artificial-intelligence)'
          description: ''
        - icon: laptop-code
          icon_pack: fas
          name: '[Technical Skills](#technical-skills)'
          description: ''
        - icon: tools
          icon_pack: fas
          name: '[OS and Versioning](#os-and-versioning)'
          description: ''
        - icon: language
          icon_pack: fas
          name: '[Languages](#languages)'


  - block: features
    id: artificial-intelligence
    content:
      title: <i class='fas fa-robot'></i>&nbsp;AI
      items:
        - icon: python
          icon_pack: fab
          name: Python
          description: ''
        - icon: pytorch-icon
          icon_pack: custom
          name: '[PyTorch](https://pytorch.org/)'
          description: ''
        - icon: scikitlearn-icon
          icon_pack: custom
          name: '[Scikit-Learn](https://scikit-learn.org/stable/)'
          description: ''
        - icon: opencv-icon
          icon_pack: custom
          name: '[OpenCV](https://opencv.org/)'
          description: ''
        - icon: tensorboard-icon
          icon_pack: custom
          name: '[Tensorboard](https://www.tensorflow.org/tensorboard)'
          description: ''
        - icon: streamlit-icon
          icon_pack: custom
          name: '[Streamlit](https://streamlit.io/)'
          description: ''


  - block: features
    id: technical-skills
    content:
      title: <i class='fas fa-laptop-code'></i>&nbsp;Technical Skills
      items:
        - icon: html5
          icon_pack: fab
          name: HTML5
          description: ''
        - icon: css3-alt
          icon_pack: fab
          name: CSS3
          description: ''
        - icon: bootstrap
          icon_pack: fab
          name: Bootstrap
          description: ''
        - icon: django-icon
          icon_pack: custom
          name: Django
          description: ''
        - icon: docker-icon
          icon_pack: custom
          name: Docker
          description: ''
        - icon: mysql-icon
          icon_pack: custom
          name: MySQL
          description: ''
        - icon: c-icon
          icon_pack: custom
          name: C
          description: ''
        - icon: cpp-icon
          icon_pack: custom
          name: C++
          description: ''
        - icon: python
          icon_pack: fab
          name: Python
          description: ''
        - icon: hugo-icon
          icon_pack: custom
          name: Hugo SSG
          description: ''
        - icon: pandas-icon
          icon_pack: custom
          name: Pandas
          description: ''
        - icon: numpy-icon
          icon_pack: custom
          name: Numpy
          description: ''
        - icon: matplotlib-icon
          icon_pack: custom
          name: Matplotlib
          description: ''
        - icon: seaborn-icon
          icon_pack: custom
          name: Seaborn
          description: ''
        - icon: photoshop-icon
          icon_pack: custom
          name: Photoshop
          description: ''
        - icon: davinci-icon
          icon_pack: custom
          name: Davinci Resolve
          description: ''

  - block: features
    id: os-and-versioning
    content:
      title: <i class='fas fa-tools'></i>&nbsp;OS and Versioning
      items:
        - icon: linux
          icon_pack: fab
          name: Linux
          description: ''
        - icon: git-alt
          icon_pack: fab
          name: Git
          description: ''
        - icon: github
          icon_pack: fab
          name: GitHub
          description: ''

  - block: features
    id: languages
    content:
      title: <i class="fa-solid fa-language"></i>&nbsp;Languages
      items:
        - icon: nepal-flag
          icon_pack: custom
          name: Nepali
          description: 'Native'
        - icon: united-flag
          icon_pack: custom
          name: English
          description: 'IELTS 7.5 (2021)'
        - icon: india-flag
          icon_pack: custom
          name: Hindi
          description: 'Native'


          







  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: 'Read my recent articles'
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      columns: '2'

  - block: accomplishments
    content:
      title: 'Certifications'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/da1b7a826b9f08c2c091acb113115d3b
          date_end: ''
          date_start: '2023-01-09'
          description: 'Successfully completed Supervised Machine Learning: Regression and Classification, an online non-credit course authorized by DeepLearning.ai and Stanford University and offered through Coursera.'
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Supervised Machine Learning - Regression and Classification
          url: ''

        - certificate_url: https://coursera.org/share/f81f3323b3a556f79bda84d6451b0f23
          date_end: ''
          date_start: '2023-01-07'
          description: 'Successfully completed Crash Course on Python, an online course authorized by Google and offered through Coursera.'
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Crash Course on Python
          url: ''

        - certificate_url: https://drive.google.com/file/d/1-42QVEZh9yMTSXoaYwh_Mji_PpfMM3gp/view?usp=sharing
          date_end: ''
          date_start: '2023-10-01'
          description: 'NPTEL Online Certification for Python taken as a part of MOOC during Computer Engineering (4 credits).'
          icon: nptel-icon
          organization: NPTEL
          organization_url: https://swayam.gov.in/nc_details/NPTEL
          title: The Joy of Computing Using Python
          url: ''

        - certificate_url: 'https://drive.google.com/file/d/1ES3PdrXmURjQmQXs1c64g33ZNrObVmsY/view?usp=sharing'
          date_end: ''
          date_start: '2024-04-20'
          description: 'NPTEL Online Certification for Cloud Computing taken as a part of MOOC during Computer Engineering (4 credits).'
          icon: nptel-icon
          organization: NPTEL
          organization_url: https://swayam.gov.in/nc_details/NPTEL
          title: Cloud Computing
          url: ''

    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: AI Stuffs
          tag: Deep Learning
        - name: Web Development
          tag: Web Development
        - name: Programming
          tag: Programming
        - name: Other
          tag: Other

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry 
      # view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  # Uncomment and configure the gallery block if needed
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  # Uncomment and configure the featured publications block if needed
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card

  # Uncomment and configure the recent publications block if needed
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation

  # Uncomment and configure the recent & upcoming talks block if needed
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact

  - block: tag_cloud
    id: tags
    content:
      title: "[<i class='fas fa-tags'></i>&nbsp;Tags](tags)"
      # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 20
    design:
      columns: '2'
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me at my socials or my e-mail address.

      # Contact (add or remove contact options as necessary)
      email: sandesh.cdr@gmail.com
      phone: 
      appointment_url: 
      address:
        street:  
        city: Delhi
        region: IN
        postcode: ''
        country: India
        country_code: IN
      directions: 
      office_hours:
      
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: ''
        longitude: ''  

      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/iiierie/'
        
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
---
