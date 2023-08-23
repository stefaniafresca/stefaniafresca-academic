---
# Leave the homepage title empty to use the site title
title:
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
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: Future Artificial Intelligence Research (FAIR) Foundation
          company_url: 'https://future-ai-research.it'
          company_logo: org-gc
          location: Milano, Italy
          date_start: '2023-02-09'
          date_end: ''
          description: ''

        - title: Visiting
          company: Isaac Newton Institute for Mathematical Sciences, University of Cambridge
          company_url: 'https://www.newton.ac.uk'
          company_logo: INI
          location: Cambridge, UK
          date_start: '2023-03-01'
          date_end: '2023-04-01'
          description: |2-
              Participation to the program "The mathematical and statistical foundation of future data-driven engineering"

        - title: Risk Advisory Intern
          company: Ernst & Young
          company_url: 'https://www.ey.com/it_it?WT.mc_id=10817933&AA.tsrc=paidsearch&gad=1&gclid=CjwKCAjwloynBhBbEiwAGY25dAu0cZBZcGoy7-vBpcdVI7cpPDfQDdv8cdl38FSYYp46K-ZcNs0hzhoCXrIQAvD_BwE'
          company_logo: EY
          location: Milano, Italy
          date_start: '2017-06-01'
          date_end: '2017-11-01'
          description: |2-
              Responsibilities include:

              * Design and data modelling of a Datamart
              * Data extraction activities through SQL
              * Automation of Data Quality processes through Access and VBA
        - title: Exchange Program
          company: Université Pierre et Marie Curie (Sorbonne Universités)
          company_url: 'https://www.sorbonne-universite.fr/en'
          company_logo: Sorbonne
          location: Paris, France
          date_start: '2015-09-01'
          date_end: '2016-03-01'
          description: ''
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false #per vederle tutte o meno
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Upcoming &shy; Dates
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  #- block: accomplishments
  #  content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
  #    date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #    items:
  #      - certificate_url: https://www.coursera.org
  #        date_end: ''
  #        date_start: '2021-01-25'
  #        description: ''
  #        organization: Coursera
  #        organization_url: https://www.coursera.org
  #        title: Neural Networks and Deep Learning
  #        url: ''
  #      - certificate_url: https://www.edx.org
  #        date_end: ''
  #        date_start: '2021-01-01'
  #        description: Formulated informed blockchain models, hypotheses, and use cases.
  #        organization: edX
  #        organization_url: https://www.edx.org
  #        title: Blockchain Fundamentals
  #        url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #      - certificate_url: https://www.datacamp.com
  #        date_end: '2020-12-21'
  #        date_start: '2020-07-01'
  #        description: ''
  #        organization: DataCamp
  #        organization_url: https://www.datacamp.com
  #        title: 'Object-Oriented Programming in R'
  #        url: ''
  #  design:
  #    columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Media & Communications
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
        - name: Research Talks
          tag: Research Talks
        - name: Outreach
          tag: Outreach
        - name: Blog Posts
          tag: Blog Posts
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured News
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  ### PRESO IN CONSIDERAZIONI PER I PREMI!!!! ###    
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
      # Filter on criteria
  #    filters:
  #      folders:
  #        - post
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
      # Choose how many pages you would like to offset by
  #    offset: 0
      # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
      # Choose a layout view
  #    view: compact
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me! \
        Reach out to me with scientific opportunities and deep learning projects.
      # Contact (add or remove contact options as necessary)
      email: stefania.fresca@polimi.it
      phone: +39 02 2399 4628
      address:
        street: P.zza Leonardo Da Vinci, 32
        city: Milano
        region: MI
        postcode: '20133'
        country: Italy
      directions: Building 14
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
