---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Data Dillon
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: 👋 Hi, there! I'm Dillon 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: NLP
      #     tag: NLP
      #   - name: Time Series
      #     tag: time
      #   - name: Neural Networks
      #     tag: NN
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Copy Analyst
          company: Freelance
          #company_url: 'https://generalassemb.ly/students/courses/data-science-bootcamp/new-york-city'
          company_logo: icon
          location: New York, NY
          date_start: '2023-08-01'
          date_end: ''
          description: |2-
              * Leveraging 10+ years in marketing to provide data-driven insights into copywriting and designs
              * Collaborated with Pentagram to analyze and optimize Pfizer's 600+ brand style guide
        - title: Data Scientist | Apprentice
          company: General Assembly
          company_url: 'https://generalassemb.ly/students/courses/data-science-bootcamp/new-york-city'
          company_logo: ga
          location: New York, NY
          date_start: '2024-01-23'
          date_end: '2024-04-17'
          description: |2-
              Completed 700+ hours of expert-led instruction in machine learning and statistical analysis, as well as hands-on learning in predictive modeling, data visualization, and AI fundamentals.

              * 24 labs
              * 6 presentations
              * 6 stakeholder interviews
        - title: Senior Copywriter
          company: Code & Theory
          company_url: ''
          company_logo: ct
          location: New York, NY
          date_start: '2022-06-01'
          date_end: '2023-08-01'
          description: |2-
              Analyzed data to optimize client-website copy, information hierarchies, and UX modules.

              * Clients: Amazon, Microsoft, Morgan Stanley, Pfizer, Baron Capital, Simplif, +
        - title: Verbal Designer
          company: R/GA
          company_url: ''
          company_logo: rga
          location: New York, NY
          date_start: '2020-03-01'
          date_end: '2022-05-01'
          description: |2-
              Researched and extrapolated data from 50+ client competitors to build strategic brand identities for 12+ clients. 
              * Clients: Cigna, The XFL, Google, Covenant House, Racetrack, +
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.codecademy.com/profiles/ToubleDrouble/certificates/6c152bd262967f8c941c9707ed636bda
          date_end: ''
          date_start: '2024-05-21'
          description: ''
          icon: codey
          organization: Codecademy
          organization_url: https://www.codecademy.com
          title: Learn Python 3
          url: ''
        - certificate_url: https://www.codecademy.com/profiles/ToubleDrouble/certificates/5b55e668646caa552f8e4d1d
          date_end: ''
          date_start: '2023-11-08'
          description: ''
          icon: codey
          organization: Codecademy
          organization_url: https://www.codecademy.com
          title: Code Foundations Skill Path
          url: ''
        - certificate_url: https://www.codecademy.com/profiles/ToubleDrouble/certificates/11a686a7fd57b8c214f7f92749388d42
          date_end: ''
          date_start: '2023-10-31'
          description: ''
          icon: codey
          organization: Codecademy
          organization_url: https://www.codecademy.com
          title: 'Learn How to Code Course'
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2023-09-13'
          description: ''
          icon: linkedin
          organization: LinkedIn
          organization_url: https://www.linkedin.com/in/dillondiatlo/details/certifications/1708788553721/single-media-viewer/?profileId=ACoAAAPxvBoBpP2J2nAegIj4Q_1UhF7m3OY8g_E
          title: How to Research and Write Using Generative AI Tools
          url: ''
    design:
      columns: '2'
  - block: skills
    content:
      title: Super Powers
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Say Hello! 📨
      subtitle: Fill out the form and I'll get back to you ASAP 
      # Contact (add or remove contact options as necessary)
      #email: dillondiatlo@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        #street: 450 Serra Mall
        city: New York City
        region: New York
        #postcode: '94305'
        country: United States
        country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
        # - 'Monday 10:00 to 13:00'
        # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697'  
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: DM Me
          link: 'https://linkedin.com/in/dillondiatlo'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
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
