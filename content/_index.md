---
# Leave the homepage title empty to use the site title
title: 
date: 2023-03-18
type: landing

sections:
#--------------------------------------------------------

  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: tore
      # Override your bio text from `authors/admin/_index.md`?
      text:
    #design:
      #background:
        #image:
          #filename: 'header_hero.svg'
          #filters:
            #brightness: 0.
        #gradient_end: '#1976d2'
        #gradient_start: '#004ba0'
        #text_color_light: false

#--------------------------------------------------------

  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: Mathematica
  #        description: 90%
  #        icon: laptop-code
  #        icon_pack: fas
  #      - name: Python
  #        description: 80%
  #        icon: python
  #        icon_pack: fab
  #      - name: Linux
  #        description: 70%
  #        icon: linux
  #        icon_pack: fab
  #      - name: Fishing
  #        description: 40%
  #        icon: fish
  #        icon_pack: fas
  #      - name: Guitar
  #        description: 20%
  #        icon: guitar
  #        icon_pack: fas
  #    design:
  #      columns: '2'

  #--------------------------------------------------------
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/##date-format
      date_format: 'Jan 2, 2006'
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` #multi-line prefix.
      items:
      
        - title: Tenured track associated professor in Physics of matter
          company: Università degli studi di Palermo
          company_url: ''
          company_logo: unimi
          #location: California
          date_start: '2018-01-01'
          date_end: ''

        - title: Postdoctoral researcher
          company: Università degli studi di Milano
          company_url: ''
          company_logo: unimi
          #location: California
          date_start: '2016-01-01'
          date_end: '2017-01-01'
          
        - title: Postdoctoral researcher
          company: Università della Calabria
          company_url: ''
          company_logo: unimi
          #location: California
          date_start: '2015-01-01'
          date_end: '2016-01-01'
          description:
          
        - title: Postdoctoral researcher
          company: Università degli studi di Palermo
          company_url: ''
          company_logo: unimi
          #location: California
          date_start: '2013-01-01'
          date_end: '2015-01-01'
          description:
    design:
      columns: '2'

#--------------------------------------------------------

  #- block: accomplishments
  #  content:
  #    # Note: `&shy;` is used to add a 'soft' hyphen in a long #heading.
  #    title: 'Accomplish&shy;ments'
  #    subtitle:
  #    # Date format: https://wowchemy.com/docs/customization/##date-format
  #    date_format: Jan 2006
  #    # Accomplishments.
  #    #   Add/remove as many `item` blocks below as you like.
  #    #   `title`, `organization`, and `date_start` are the #required parameters.
  #    #   Leave other parameters empty if not required.
  #    #   Begin multi-line descriptions with YAML's `|2-` #multi-line prefix.
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
  #        description: Formulated informed blockchain models, #hypotheses, and use cases.
  #        organization: edX
  #        organization_url: https://www.edx.org
  #        title: Blockchain Fundamentals
  #        url: https://www.edx.org/professional-certificate/#uc-berkeleyx-blockchain-fundamentals
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
  #- block: markdown
  #  id: section-1
  #  content:
  #    title: Section 1
  #    subtitle: A subtitle
  #    text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
#--------------------------------------------------------
  - block: portfolio
    id: research-about
    content:
      title: Research Lines
      subtitle: 
      text: 
      filters:
        # Folders to display content from
        folders:
          - research
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: OQS 
      #    tag: OQS
      #  - name: QT
      #    tag: QT
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true



  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ([complete list](./post/))
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
      columns: '1'
      view: compact
      #background:
      #    gradient_end: '#6198a4'
      #    gradient_start: '#004ba0'
      #    text_color_light: true
  
#--------------------------------------------------------

  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'

#--------------------------------------------------------

  - block: collection
    id: featured
    content:
      title: Featured Publications
      subtitle: ([See all](./publication/))
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: masonry

#--------------------------------------------------------

  - block: collection
    content:
      id: recent
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
      columns: '1'

#--------------------------------------------------------

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
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'

#--------------------------------------------------------

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: salvatore.lorenzo@unipa.it
      phone: '+3909123891721'
      appointment_url: 'https://calendly.com/salvatore-lorenzo'
      address:
        street: Via Archirafi 36
        city: Palermo
        region: 
        postcode: '90123'
        country: Italy
        country_code: IT
      office_hours:
        - 'Tuesday 13:00 to 15:00'
        - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      #autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'

#--------------------------------------------------------

---
