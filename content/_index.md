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
  - block: features
    content:
      title: Skills
      items:
        - name: Coding
          description: R, Stata, Python, bash, git
          icon: code
          icon_pack: fa
        - name: Statistics
          description: Descriptive, inferential, meta-analysis, Bayesian
          icon: chart-line
          icon_pack: fas
        - name: Languages
          description: English, Russian, German, Spanish, French
          icon: language
          icon_pack: fa
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
        - title: Postdoctoral Scholar
          company: Institute for Health Metrics and Evaluation
          company_url: 'https://healthdata.org'
          company_logo: org-gc
          location: Seattle, WA, United States
          date_start: '2022-09-06'
          date_end: ''
          description: |2-
            * Data wrangling, aggregation and visualization with R and Python
            * Pre-processing of complex, non-standardized datasets from international collaborators for epidemiological analyses 
            * Applying metaregression tools for global health metrics estimation
            * Data seeking through systematic search and external collaborator outreach
        - title: Virtual Networking Support Manager
          company: The Core Outcome Set for Food Allergy (COMFA) Consortium
          company_url: 'https://comfa.eu'
          company_logo: org-x
          location: Remote
          date_start: '2021-07-01'
          date_end: '2022-08-31'
          description: |2-
            * Coordinated an EU-funded international consensus study
            * Drafted a global consensus study protocol to establish core outcome set to harmonise human studies of food allergy 
            * Managed grant reports and convened regular meetings with over 70 the task force members to facilitate decision-making and coordinate collaborative projects 
            * Produced 2 systematic search strategies and oversaw screening and data extraction for 2 systematic reviews to aid the long list of outcomes for the Delphi process 
            * Organised international workshop on the development of core outcome sets for clinical trials
            * Guided applicants on grant applications and reporting
            * Provided documentation to the Grant Holder Institution and the European Cooperation in Science and Technology (COST)
            * Structured activity-based budget
        - title: Research Assistant and Project Coordinator
          company: Sechenov Unversity
          company_url: 'https://www.sechenov.ru/eng/'
          location: Moscow, Russia
          date_start: '2020-07-15'
          date_end: '2021-08-01'
          description: |2-
            * Cleaned and curated data for the collaborative analysis with the GBD and was named as a co-author on 2 manuscripts currently under review
            * Budgeted two research grants from the British Embassy Moscow and ensured comprehensive reporting to lay out a long-lasting relation between the grant organization and the institution
            * Streamlined data collection from over 5000 electronic health records in the health information system to compile the largest database of hospitalized patients countrywide and curated the dataset
            * Managed a team of over 50 researchers using hierarchical leadership to conduct a prospective observational study with extremely tight deadlines 
            * Contributed data from a cohort study of the acute SARS-CoV-2 infection to the Infectious Diseases Data Observatory using CDISC Foundational Standards 
            * Initiated a national cross-sectional survey administration and executed the project at all stages providing nationwide estimates and determinants of mental health during lockdown 
            * Conveyed statistical analysis plans to statisticians, interpreted and discussed the outputs in 4 international projects ensuring mutual understanding
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
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
      view: compact
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 3980 15th Ave
        city: Seattle
        region: WA
        postcode: '98105'
        country: United States
        country_code: US
      directions: Hans Rosling Center, 6th floor, 657
      office_hours:
        - 'Monday-Friday 09:00 AM to 05:00 PM Pacific time (GMT-8)'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
