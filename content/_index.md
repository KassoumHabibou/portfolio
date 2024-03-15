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
    design:
      background:
        image:
          filename: wave.svg
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    content:
      title: Working Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Teaching Assistant (fixed-term contract)
          company: 'University Clermont Auvergne: School of Economics' 
          company_url: 'https://economie.uca.fr/'
          company_logo: uca-logo
          location: Clermont-Ferrand (France)
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Research Assistant - Data Analysis (fixed-term contract)
          company: UMR Aix‑Marseille School of Economics (AMSE) 
          company_url: 'https://www.amse-aixmarseille.fr/fr'
          company_logo: amse-logo
          location: Marseille (France)
          date_start: '2022-09-01'
          date_end: '2023-08-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Research Assistant - Data Analysis (intership)
          company: Research Institute for Development (IRD)
          company_url: 'https://www.ird.fr/sud-est'
          company_logo: ird-logo
          location: Marseille (France)
          date_start: '2022-04-01'
          date_end: '2022-08-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Data Analysis (intership)
          company: French Institute of Science and Technology for Transport Development and Networks (IFSTTAR) 
          company_url: 'https://www.univ-gustave-eiffel.fr/'
          company_logo: univ-logo
          location: Lyon-Bron (France)
          date_start: '2021-06-01'
          date_end: '2021-09-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
    design:
      columns: '2'
  - block: education
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading. #'Accomplish&shy;ments'
      title: Education 
      subtitle: 'Average level: Very good'
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Education.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.edx.org
          icon: cerdi-uca-logo
          organization: University Clermont Auvergne - CERDI
          organization_url: https://cerdi.uca.fr/english-version#/admin
          title: Phd in Development Economics
          url: 'https://cerdi.uca.fr/english-version#/admin'
          date_start: '2023-10-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying

        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
    design:
      columns: '2'
  - block: certification
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading. #'Accomplish&shy;ments'
      title: Certification 
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Certification.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
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
        Feel free to get in touch with me! Whether you have questions, suggestions, or simply want to say hello, I'd love to hear from you. You can reach me through the contact form, email, or phone number provided below. Your feedback is important to me and I look forward to connecting with you.
      # Contact (add or remove contact options as necessary)
      email: Habibou.IBRAHIM_KASSOUM@doctorant.uca.fr
      phone: 04 73 17 74 08
      appointment_url: 'https://calendly.com'
      address:
        street: 26 Avenue Léon Blum
        city: Clermont-Ferrand
        region: Auvergne-Rhône-Alpes
        postcode: '63000'
        country: France
        country_code: FR
      directions: Enter Building 1 and take the stairs to Office 427 on Floor 4
      office_hours:
        - 'From monday to saturday'
        - 'From 08 AM to 08 PM'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '45.7670656'
        longitude: '3.0998528'  
      contact_links:
        #- icon: twitter
        #  icon_pack: fab
        #  name: Tex
        #  link: 'https://twitter.com/Twitter'
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
