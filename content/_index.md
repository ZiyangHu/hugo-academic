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
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: R
  #        description: 90%
  #        icon: r-project
  #        icon_pack: fab
  #      - name: Statistics
  #        description: 100%
  #        icon: chart-line
  #        icon_pack: fas
  #      - name: Photography
  #        description: 10%
  #        icon: camera-retro
  #        icon_pack: fas
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
        - title: Government Staff
          company: Wuhan E.&T. Development Zone
          company_url: 'http://www.whkfq.gov.cn/'
          company_logo: whetdz
          location: Wuhan, Hubei Province
          date_start: '2021-07-01'
          date_end: '2022-08-15'
          description: |2-
              Responsibilities include:

              * Economic Analysis
              * Industrial Research
              * Scientific & Technological Innovation
        #- title: Professor of Semiconductor Physics
        #  company: University X
        #  company_url: ''
        #  company_logo: org-x
        #  location: California
        #  date_start: '2016-01-01'
        #  date_end: '2020-12-31'
        #  description: Taught electronic engineering and researched semiconductor physics.
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
        - certificate_url: https://www.coursera.org/account/accomplishments/verify/7A6AARJMQPMP
          date_end: '2022-11-09'
          date_start: '2022-01-21'
          description: 'A very famous introductory course in machine learning'
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Machine Learning
          url: 'https://www.coursera.org/specializations/machine-learning-introduction'
        #- certificate_url: https://www.edx.org
        #  date_end: ''
        #  date_start: '2021-01-01'
        #  description: Formulated informed blockchain models, hypotheses, and use cases.
        #  organization: edX
        #  organization_url: https://www.edx.org
        #  title: Blockchain Fundamentals
        #  url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        #- certificate_url: https://www.datacamp.com
        #  date_end: '2020-12-21'
        #  date_start: '2020-07-01'
        #  description: ''
        #  organization: DataCamp
        #  organization_url: https://www.datacamp.com
        #  title: 'Object-Oriented Programming in R'
        #  url: ''
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
        - name: Computer Science
          tag: Computer Science
<<<<<<< HEAD
        - name: Mechanics
=======
		    - name: Mechanics
>>>>>>> 706f434df5fc53e9327693accc58340822f812fd
          tag: Mechanics
        - name: Other
          tag: Other
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
        # {{< gallery album="demo" >}}
<<<<<<< HEAD
        {{< gallery album="1" >}}
=======
		    {{< gallery album="1" >}}
>>>>>>> 706f434df5fc53e9327693accc58340822f812fd
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
        Whether you have questions about my experience above or want to further communicate with me, don't hesitate to contact me immediately.
      # Contact (add or remove contact options as necessary)
      email: tzuyanghu@gmial.com
      # phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: No.932 South Lushan Road
        city: Changsha
        region: Hunan Province
        postcode: '410083'
        country: P.R. China
        country_code: CN
      directions: Office 417 on 4th floor of the Information Building
      office_hours:
        - 'Weekdays 09:00 AM to 10:00 PM'
        - 'Weekends 10:00 AM to 06:00 PM'
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
          name: Meeting Me
          link: 'https://www.tencent.com/en-us/index.html'
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
