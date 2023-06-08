---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
share: true

sections:
  - block: hero
    content:
      title: 
      image:
        filename: hero-academic.png
      # cta:
      #   label: '**Get Started**'
      #   url: https://wowchemy.com/templates/
      # cta_alt:
      #   label: Ask a question
      #   url: https://discord.gg/z8wNYzb
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        ***Hello, I'm now looking for a job in IT industry***

        **After the 2020 riot in Belarus, I was in prison, and now I'm forced to leave the country to get a job and a legalization in a EU country.**

        I would be very happy to be a part of a company with Belarusian roots.

        I prefer a job from my web-stack: Backend or Full-Stack developer. But I would also consider a position of an intern-Junior at GameDev which is new to me.

        <!--Custom spacing-->
        <div class="mb-3"></div>

        Please share this page with your network.
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: PHP
          description: backend-developer
          icon: php
          icon_pack: fab
        - name: JavaScript
          description: vanilla JS, jQuery, VueJs
          icon: js
          icon_pack: fab
        - name: Databases
          description: MySQL, SQLite, Redis
          icon: database
          icon_pack: fas
        - name: MODX
          description: as CMS or as Framework
          icon: modx
          icon_pack: fab
        - name: GIS
          description: OSM, YandexMap API, Leaflet
          icon: map-marked-alt
          icon_pack: fas
        - name: WP
          description: create templates, customizing components
          icon: wordpress
          icon_pack: fab
        - name: Linux
          description: Debian-based system administration, config and tuning soft
          icon: linux
          icon_pack: fab
        - name: Virtualization
          description: VMWare, Docker
          icon: docker
          icon_pack: fab
        - name: Prototyping
          description: 'Microsoft Visio, Figma'
          icon: figma
          icon_pack: fab
  - block: features
    content:
      title: Soft skills
      subtitle: and how I applied them in fact
      items:
        - name: Problem-solving
          description: Handled emergency situations with resilience and composure. Possessed the skills and qualities of an incident responder.
          icon: cog
          icon_pack: fa
        - name: Decision-making
          description: Found feasible solutions based on data, logic and situation.
          icon: question-circle
          icon_pack: fa
        - name: User-oriented
          description: Collaborated closely with the client. Engaged actively in consulting users and registering issues.
          icon: users
          icon_pack: fa
        - name: Adaptability
          description: Demonstrated the ability to identify needs and resolve conflicts, integrate processes with each other to synchronize their actions. Worked with incomplete and changing requirements.
          icon: plug
          icon_pack: fa
        - name: Insightfulness
          description: "While gathering project needs, I realized that words can imply different things. e.g., “I’d like a button” could mean a broader functionality and it indicated the importance of discussing and clarifying requirements."
          icon: refresh
          icon_pack: fa
        - name: Communication
          description: Taught young adults, proposed and promoted convincing tech development plan to build consensus, presented features to non-technical audiences.
          icon: comments
          icon_pack: fa
  - block: markdown
    content:
      title: 'Saying No'
      subtitle: ''
      text: |-
        <blockquote class="otro-blockquote">
          Slaves are not allowed to say no.<br>Laborers may be hesitant to say no.<br>But professionals are expected to say no.
          <span>— Robert C. Martin. The Clean Coder</span>
        </blockquote>
  - block: features
    content:
      title: my Team Roles
      subtitle: years of relevant experience
      items:
        - name: Implementer
          description: '6 years'
          icon: file-code
          icon_pack: far
        - name: Solver
          description: '3 years'
          icon: balance-scale
          icon_pack: fas
        - name: Researcher
          description: '6 years'
          icon: microscope
          icon_pack: fas
        - name: ''
          description: ''
          icon: ''
          icon_pack: fas
        - name: Coordinator
          description: '6 months'
          icon: code-branch
          icon_pack: fas
        - name: ''
          description: ''
          icon: ''
          icon_pack: fas
  - block: experience
    id: experience
    content:
      title: Experience
      subtitle: Professional
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan-2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Technical Engineer/Software Engineer
          company: "Municipal Unitary Enterprise \"Information Technologies Center\""
          company_url: 'https://it-minsk.by'
          company_logo: org_itminsk
          location: Belarus, Minsk
          date_start: '2014-05-01'
          date_end: '2018-10-12'
          description: |2-
              The Information Technology Center is one of the important companies in the local market, takes an active part in developing and supporting IT solutions for the Belarusian government public service.

              During my time with the company, I developed public and local G2C solutions, wrote software and regulatory documentation, took part in consulting with users and customer-support. The poor culture of digitalization among governance customers leaded to the work with incomplete requirements. Requirements were gathering via user stories, use cases and user observation. So, I had to perform part of the Business-analyst’s work.

              Started working as a technical employee and then was promoted to a position of a Full-Stack web-developer (MySQL, PHP, Perl, jQuery):
              * Configured and maintained servers for development
              * Refactored and added new services in legacy project [minsk.gov.by](https://minsk.gov.by) ([2nd place](https://www.liveinternet.ru/rating/#rating=by/state;page=1;nick=minsk.gov.by) in category "State"), migrated from Perl to PHP
              * Participated in coding Front-End on jQuery and vanilla JS
              * Designed databases
              * Converted data formats, parsed unstructured data
              * Developed online tool-box for organizing the process of collecting requirements and coordinating work with an expert group
              * Integrated DevTools to enhancing team productivity for product analysis and testing
              * Developed new web apps and APIs (DB, Back-end)
                * online appointment booking according to customers’ needs: [retail locations in the markets](https://it-minsk.by/ru/produkty/internet-servis-bronirovanie-torgovykh-mest-na-rynkakh), [the civil registry office](https://it-minsk.by/ru/produkty/zapis-na-registratsiyu-braka), [polyclinic of special medical examinations](https://it-minsk.by/ru/produkty/internet-servis-zapis-v-polikliniku)
                * catalog system of [corporate contacts](https://it-minsk.by/ru/produkty/korporativnyj-telefonnyj-spravochnik), designed for general and territorial subunits' purposes
                * geo-information resources (tools: OSM, Leaflet), designed for the tasks of [territorial subunits](https://it-minsk.by/ru/produkty/20190917-interaktivnaya-karta), [business-portal](https://invest.minsk.gov.by/ru/zemelnye-uchastki-goroda-minska)
                * information resources and services: [National Literary Prize](http://litpremia.by/), [waiting list for housing](https://it-minsk.by/ru/produkty/internet-servis-ochered-na-zhile), [happy family faces](https://gorod.gov.by/zags100/minsk/)
              * Wrote technical docs for developers and guides for content-managers
              * Made desktop apps on C# / .NET
        - title: PHP Developer
          company: "«Electroservice and Co»"
          company_url: https://sila.by
          company_logo: org_silaby
          location: Belarus, Minsk
          date_start: '2019-09-02'
          date_end: '2020-10-28'
          description: |2-
              «Electroservice and Co» is one of the most visited Belarusian online stores of home appliances and electronics. The company has more than 29 years history, more than 1000 employees and 33 store and supermarket at present.

              Supported and developmed household appliances sales network "ELEKTROSILA" Internet resources.

              * supported and developed new features for a custom-made PHP project
              * created internal developer-tools for debugging on live production environment
              * exchanged data between the client-side web-resource and internal commerce systems
              * implemented a new [design for mobile version](https://m.sila.by/)
        - title: Workshop on Project management
          company: "HighTech Park Belarus"
          company_url: 'http://www.park.by/?lng=en'
          location: Belarus, Minsk
          date_start: '2014-04-01'
          date_end: '2014-04-01'
          description: |2-
              Participated in the workshop "Control of the project changes" within the educational project on the basis of HighTech Park Belarus
        - title: Freelancer
          company: ''
          company_url: ''
          company_logo: 
          location: Belarus, Borisov
          date_start: '2018-10-12'
          date_end: '2020-10-28'
          description: |2-
              Diverse activity

              #### Open Source:
              * [contribution](https://github.com/modxcms/revolution/pulls?q=is%3Apr+author%3Atolanych+is%3Aclosed) to MODX core
              * development of [solutions for MODX](https://github.com/stars/tolanych/lists/modx)
              * support of MODX Tickets component (third party author)

              #### Freelance development:

              * adding the Sphinx search engine to the project
              * work with existing undocumented projects in Bitrix, Wordpress, MODX
              * integration of web resources with third-party APIs (payment systems, SMS, CRM)
              * adding microdata markup
              * ...and more small tasks

              #### Mastering tech skills on pet projects:

              * Processes: TDD
              * Frontend: Webpack, ExtJS, VueJS
              * Backend: Golang
              * Tools: Redis, Sphinx
    design:
      columns: '2'
  - block: experience
    id: activity
    content:
      title: Activities
      subtitle: My other activities
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan-2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Website of the Blues Festival in Minsk
          company: "winterendblues.com"
          company_url: http://winterendblues.com
          location: Belarus, Minsk
          date_start: '2016-08-01'
          date_end: '2020-02-01'
          description: |2-
              Created a website for a blues dance festival (on CMS WordPress). Every year the festival changed its own identity and design. I created a new templates in accordance with the design and layouts update.
        - title: Change a CMS of website
          company: '"Kacheli" dance studio'
          company_url: 'https://lindy.by'
          location: Belarus, Minsk
          date_start: '2015-12-01'
          date_end: '2016-06-01'
          description: |2-
              Made the migration of existing website from MODX to Wordpress. Solved tasks:

              * keeping URLs when migrating, redirecting from URLs with unsupported format
              * writing script to automatically migrate content between BD tables from modx_site_content to wp_posts
              * changing existing template to responsive
              * integration of inner workings into Google Sheets API and Google Calendar
        - title: Poetry competition \"Rukhavik\"
          company: "Art Siadziba"
          company_url: 'https://www.facebook.com/artsiadziba'
          location: Belarus, Minsk
          date_start: '2015-09-01'
          date_end: '2016-12-06'
          description: |2-
              Participated in a poetry reading contest "Rukhavik" - first round in 2015, semi-final in 2016.
        - title: Simple web-technologies, mods-making
          company: "adolescence"
          company_url: ''
          location: Belarus, Borisov
          date_start: '2006-01-01'
          date_end: '2009-01-01'
          description: |2-
              Studied some technologies and tools in digital area:

              * HTML/CSS Web 2.0
              * Adobe Flash animation
              * Digital graphics using Adobe Photoshop, Corel Draw
              * Scripts modding on Sanny Builder (CLEO)
              * Game developing on Game Maker/GML
        - title: ZX Spectrum
          company: "childhood"
          company_url: ''
          location: Belarus, Borisov
          date_start: '2000-01-01'
          date_end: '2001-06-01'
          description: |2-
              My first Sinclair-based PC - [ZX Spectrum](https://en.wikipedia.org/wiki/ZX_Spectrum)

              * started my coding way on BASIC
              * studied algorithms
              * had fun and played games
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certs'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.sololearn.com/Certificate/1059-7748574/pdf/
          date_end: ''
          date_start: '2018-01-01'
          description: ''
          organization: Sololearn
          organization_url: https://www.sololearn.com
          title: PHP Tutorial course
          url: ''
        - certificate_url: https://www.intuit.ru/verifydiplomas/100686226
          date_end: ''
          date_start: '2013-05-08'
          description: The course describes the fundamental principles of design and implementation of operating systems.
          organization: Intuit
          icon: 'sololearn'
          organization_url: https://www.intuit.ru
          title: The basics of operating systems
          url: ''
        - certificate_url: http://ude.my/UC-RZUQXZFJ
          date_end: ''
          date_start: '2019-03-01'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com
          title: 'Binary search trees. Code and Theory'
          url: ''
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
        - name: Games
          tag: Games
        - name: Web
          tag: Web
        - name: Education
          tag: Education
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: compact
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
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
  #     # Contact (add or remove contact options as necessary)
  #     email: test@example.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
  #     address:
  #       street: 450 Serra Mall
  #       city: Stanford
  #       region: CA
  #       postcode: '94305'
  #       country: United States
  #       country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
