---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      background:
        image:
          filename: wave.svg
  - block: skills
    id: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: experience
    content:
      title: Work Experience
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
              During my current PhD position, I have had the privilege of serving as a teacher assistant, where I have been actively engaged in facilitating tutorial sessions for students in the fields of **statistics** and **probabilities**. In this role, I have contributed to the academic development of students by assisting them in understanding complex statistical concepts, solving problems, and reinforcing their comprehension through practical applications. This experience has not only honed my teaching skills but has also revealed my managerial abilities and deepened my own understanding of the subject matter. It has been immensely rewarding to witness the growth and progress of students under my guidance. My course load includes: 

              - **Inferential statistics** with Pr [Anne Viallefont](https://cerdi.uca.fr/version-francaise/unite/lequipe/annuaire/anne-viallefont#/) for third-year management students. We covered topics such as:
                * estimation (definition of an estimator, bias, variance, convergence, etc.);
                * confidence intervals and significance levels (for mean, variance, bias correction, etc.);
                * hypothesis testing (comparing two means, variances, or distributions, etc.).
              - **Probabilities and mathematics** with Pr [Marie Eliette Dury](https://cerdi.uca.fr/version-francaise/unite/lequipe/annuaire/marie-eliette-dury#/) for second-year gestion students. We covered topics such as:
                * probability distributions and approximations (normal, Poisson, binomial, etc.);
                * matrix calculation (calculation of the determinant, eigenvalue, inverse, diagonalization, etc.);
                * numeric sequence (arithmetic and geometric sequence, recurrence equation, etc.).
        - title: Research Assistant - Data Analysis (fixed-term contract)
          company: UMR Aix‑Marseille School of Economics (AMSE) 
          company_url: 'https://www.amse-aixmarseille.fr/en'
          company_logo: amse-logo
          location: Marseille (France)
          date_start: '2022-09-01'
          date_end: '2023-08-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Research Assistant - Data Analysis (internship)
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
        - title: Research Assistant - Data Analysis (internship)
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
        - title: Research Scientist (internship)
          company: Senegalese Observatory of Poverty and Living Conditions (OPCV) 
          company_url: 'https://www.ansd.sn/'
          company_logo: ansd-logo
          location: Dakar (Senegal)
          date_start: '2020-03-01'
          date_end: '2020-09-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Research Scientist (internship)
          company: Nigerien National Institute of Statistics (INS) & National Information Platforms for Nutrition (NIPN) 
          company_url: 'https://pnin-niger.org/web/'
          company_logo: pnin-logo
          location: Niamey (Niger)
          date_start: '2018-07-01'
          date_end: '2018-09-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
    design:
      columns: '2'
  - block: accomplishments
    id: education
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading. #'Accomplish&shy;ments'
      title: Education 
      subtitle: 'Places: France-Senegal'
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Education.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2023-10-01'
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
          icon: cerdi-logo
          organization: University Clermont Auvergne - CERDI
          organization_url: https://cerdi.uca.fr/english-version#/admin
          title: Phd in Development Economics
          url: 'https://cerdi.uca.fr/english-version/team#/admin'
        - date_start: '2020-09-01'
          date_end: '2022-12-01'
          description: |2-
            ENSAI is one of France's most prestigious *Grandes écoles d'ingénieurs* specialized in Data Science. With close ties to the French National Institute of Statistics and Economic Studies ([INSEE](https://www.insee.fr/en/accueil)), Center for Research in Economics and Statistics ([CREST](https://crest.science/)), research centers and private partners, ENSAI trains its students to become specialized **Data Scientists** capable of complex information processing and analysis thanks to their multidisciplinary expertise. ENSAI's course content includes:

            - Machine Learning:  
              * supervised learning (e.g., regression, decision trees, neural networks, random forest, etc.);
              * unsupervised learning (e.g., k-means, hierarchical clustering, KNN, NLP, etc.);
              * deep learning (e.g., CNNs, LSTMs, RNNs, GANs etc.).
            - Statistics and Mathematics:  
              * descriptive statistics (mean, outliers, etc.) and distributions (normal, Poisson, etc.);
              * algebra and calculus (matrices, limits, optimization etc.);
              * probability and hypothesis testing (significance level, confidence interval, p-value, t-test, etc.).
            - Computer Science:  
              * database computation (with SQL and MySQL);
              * data visualization and analytics (with matplotlib, ggplot2, dashboards, etc.);
              * programming languages: Python, R, Stata and SQL.
          icon: ensai-logo
          organization: École Nationale de la Statistique et de l'Analyse de l'Information (ENSAI-Rennes)
          organization_url: https://ensai.fr/en/
          title: Engineering degree in Data science 
          url: https://ensai.fr/en/apres-lensai/les-metiers-de-la-data-2/les-territoires-et-la-sante/
        - date_start: '2020-09-01'
          date_end: '2022-10-01'
          description: |2-

            

          icon: amse-logo
          organization: Aix‑Marseille School of Economics (AMSE) 
          organization_url: https://www.amse-aixmarseille.fr/en
          title: Master degree in Theoretical and Empirical Economics (ETE) 
          url: https://www.amse-aixmarseille.fr/en/study/phd/ete-research-master
        - date_end: '2020-08-01'
          date_start: '2016-10-01'
          description: |2-
              ENSAE is a higher education institution that is a member of the Network of African Statistical Schools (RESA). It is a sub-regional education institution that welcomes around fifteen nationalities and is listed among the most recognized institutions for training statistician in Africa. As a member of the *Observatoire Economique et Statistique d'Afrique Subsaharienne* ([AFRISTAT](https://www.afristat.org/)) and affiliated with the *Institut National de la Statistique et des Etudes Economiques* ([INSEE](https://www.insee.fr/fr/accueil)), ENSAE welcomes technician and engineer students from across all Africa, as well as visiting professors from prominent European universities. Under the guidance of a pedagogical team composed of academics and professionals, the future graduate of ENSAE assimilates, throughout their course, **statistical** and **economic theories** as well as the necessary skills for their operational application. The core of this program is:

              - Statistics and Probabilities:
                * hypothesis testing (constructing a test, calculating p-values, t-tests, etc.) and analysis of variance.
                * conditional distribution and Bayesian inference.
                * estimation techniques (maximum likelihood estimator, dealing with bias and variance) and sampling methods.
              - Computer Science:
                * data mining using Python and R (data wrangling, data engineering and machine learning).
                * database management (with SQL and MySQL).
                * Introduction to web development technologies such as HTML, CSS, PHP, JavaScript, and C.
              - Machine Learning:
                * time series analysis and forecasting.
                * Multidimensional data analysis techniques (e.g., CA, PCA, MFA, AFDM, etc.).
                * various supervised and unsupervised algorithms (e.g., regression, clustering, decision trees, etc.).
          icon: ensae-logo
          organization: Ecole Nationale de la Statistique et de l’Analyse Economique (ENSAE‑Dakar) 
          organization_url: https://www.ensae.sn/accueil
          title: Bachelor's degree in Statistics and Applied Economics
          url: https://www.ensae.sn/accueil
    design:
      columns: '2'
  #- block: resume-languages
  #  content:
  #    title: Languages
      # Note: `username` refers to the user's folder name in `content/authors/`
  #    username: admin
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
  #      exclude_featured: false
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
        - name: Supervised Learning
          tag: Supervised Learning
        - name: Unsupervised Learning
          tag: Unsupervised Learning
        - name: NLP
          tag: NLP
        - name: Deep Learning
          tag: Deep Learning 
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
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
 # - block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  - block: collection
    id: talks
    content:
      title: Recent Talks
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
        Feel free to get in touch with me! Whether you have questions, suggestions or simply want to say hello, I'd love to hear from you. You can reach me through the contact form, email, or phone number provided below. Your feedback is important to me and I look forward to connecting with you.
      # Contact (add or remove contact options as necessary)
      email: Habibou.IBRAHIM_KASSOUM@doctorant.uca.fr
      phone: 04 73 17 74 08
      #appointment_url: 'https://calendly.com'
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
