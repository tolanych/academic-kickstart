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
      title: Навыки
      items:
        - name: PHP
          description: backend-разработчик
          icon: php
          icon_pack: fab
        - name: JavaScript
          description: vanilla JS, jQuery, VueJs
          icon: js
          icon_pack: fab
        - name: Базы данных
          description: MySQL, SQLite, Redis
          icon: database
          icon_pack: fas
        - name: MODX
          description: как CMS или как Framework
          icon: modx
          icon_pack: fab
        - name: ГИС
          description: OSM, YandexMap API, Leaflet
          icon: map-marked-alt
          icon_pack: fas
        - name: WP
          description: создание шаблонов, настройка компонентов
          icon: wordpress
          icon_pack: fab
        - name: Linux
          description: Администрирование систем на базе Debian, конфигурирование ПО
          icon: linux
          icon_pack: fab
        - name: Виртуализация
          description: VMWare, Docker
          icon: docker
          icon_pack: fab
        - name: Прототипирование
          description: 'Microsoft Visio, Figma'
          icon: figma
          icon_pack: fab
  - block: features
    content:
      title: Soft skills
      subtitle: и как я их применял на деле
      items:
        - name: Решение проблем
          description: Работа с нештатными ситуациями. Обладаю навыками и личными качествами для адекватного реагирования на инциденты.
          icon: cog
          icon_pack: fa
        - name: Принятие решений
          description: Способен выбрать подходящие решения на основе имеющихся данных и исходя из ситуации.
          icon: question-circle
          icon_pack: fa
        - name: Ориентация на пользователя
          description: Тесно сотрудничал непосредственно с клиентом. Активно участвовал в консультировании пользователей и реагировал на имеющиеся проблемы.
          icon: users
          icon_pack: fa
        - name: Гибкость
          description: Определять потребности и разрешал конфликты, занимался координацией процессов для синхронизации их действий. Работал с неполными и изменяющимися требованиями
          icon: plug
          icon_pack: fa
        - name: Проницательность
          description: "Обладаю пониманием, что в процессе сбора требований, под словами могут скрываться сопутствующие вещи. Например, фраза «Нам просто нужно добавить кнопку» может заключать в себе обширную функциональность, и это повод для обсуждения и выяснения требований"
          icon: refresh
          icon_pack: fa
        - name: Коммуникабельность
          description: Обучал молодёжь, предлагал и продвигал собственные решения, проводил планирование с учетом всех интересов для прихода к соглашению, презентовал новые возможности аудитории, не обладающей технической подготовкой
          icon: comments
          icon_pack: fa
  - block: features
    content:
      title: Роли в командной работе
      subtitle: релевантный опыт
      items:
        - name: Реализация
          description: '6 лет'
          icon: file-code
          icon_pack: far
        - name: Решение задач
          description: '3 года'
          icon: balance-scale
          icon_pack: fas
        - name: Исследование
          description: '6 лет'
          icon: microscope
          icon_pack: fas
        - name: ''
          description: ''
          icon: ''
          icon_pack: fas
        - name: Координирование
          description: '6 месяцев'
          icon: code-branch
          icon_pack: fas
        - name: ''
          description: ''
          icon: ''
          icon_pack: fas
  - block: markdown
    content:
      title: 'Говорить нет'
      subtitle: ''
      text: |-
        <blockquote class="otro-blockquote">
          Рабы не могут сказать «Нет», а наёмные работники могут. Если же вы профессионал — это ваша обязанность
          <span>— Роберт Мартин. Идеальный программист</span>
        </blockquote>
  - block: experience
    id: experience
    content:
      title: Опыт
      subtitle: Профессиональная деятельность
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan-2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Техник-программист/Инженер-программист
          company: "КУП \"Центр информационных технологий\""
          company_url: 'https://it-minsk.by'
          company_logo: org_itminsk
          location: Беларусь, Минск
          date_start: '2014-05-01'
          date_end: '2018-10-12'
          description: |2-
              КУП \"Центр информационных технологий\" - один из важных игроков локального рынка, отвечающий за IT-оснащенность белорусского государственного сектора и специализирующийся на создании, разработке и сопровождении прикладных программных решений.

              За время моей работы в компании я разрабатывал общедоступные и внутренние продукты для G2C (электронное правительство), занимался разработкой технической и регламентирующей документации, взаимодействием с пользователями и службой поддержки. Разработка ПО по "рассказу пользователя", работа с неточными и неполными требованиями. Требования собирались в том числе методами пользовательских историй, сценариев использования и "полевых" наблюдений за пользователем. Поэтому, в том числе занимался и задачами бизнес-аналитика.

              Начал работать как техник, позже перешел на позицию Full-Stack веб-разработчика (MySQL, PHP, Perl, jQuery):
              * Настройка и сопровождение серверов для разработки
              * Рефакторинг, сопровождение и написание новых сервисов для Legacy проекта [minsk.gov.by](https://minsk.gov.by) ([2-ое место](https://www.liveinternet.ru/rating/#rating=by/state;page=1;nick=minsk.gov.by) в категории "Государство"), перевод проекта с языка Perl на PHP
              * Участие в разработке Front-End (jQuery, JS)
              * Проектирование баз данных
              * Конвертация данных, парсинг неструктурированных массивов информации
              * Разработка онлайн-инструментария для организации процесса сбора требований и координации работы экспертной группы
              * Обеспечение DevTools для оптимальной работы команды
              * Разработка веб-сервисов (БД, Back-end)
                * резервирование приёма через интернет под потребности клиентов: [торговые места на рынках](https://it-minsk.by/ru/produkty/internet-servis-bronirovanie-torgovykh-mest-na-rynkakh), [органы ЗАГС](https://it-minsk.by/ru/produkty/zapis-na-registratsiyu-braka), [поликлиника спецмедосмотров](https://it-minsk.by/ru/produkty/internet-servis-zapis-v-polikliniku)
                * система-справочник [корпоративных контактов](https://it-minsk.by/ru/produkty/korporativnyj-telefonnyj-spravochnik), спроектирована для общего назначения, и под задачи органов территориального управления
                * гео-информационные сервисы (инструменты: OSM, Leaflet), в том числе для [органов территориального управления](https://it-minsk.by/ru/produkty/20190917-interaktivnaya-karta), [бизнес-портала](https://invest.minsk.gov.by/ru/zemelnye-uchastki-goroda-minska)
                * информационные ресурсы и сервисы: [Национальная литературная премия](http://litpremia.by/), [очередь на жильё](https://it-minsk.by/ru/produkty/internet-servis-ochered-na-zhile), [счастливые лики семьи](https://gorod.gov.by/zags100/minsk/)
              * Написание документации разработчика и руководств пользователя для службы информационного сопровождения веб-ресурсов
              * Настольные приложения на C# / .NET
        - title: Программист PHP
          company: "«ЭЛЕКТРОСЕРВИС и Ко»"
          company_url: https://sila.by
          company_logo: org_silaby
          location: Беларусь, Минск
          date_start: '2019-09-02'
          date_end: '2020-10-28'
          description: |2-
              ««ЭЛЕКТРОСЕРВИС и Ко» - один из наиболее посещаемых белорусских интернет-магазинов бытовой техники и электроники. Компания имеет более чем 29-летнюю историю, свыше 1000 сотрудников и 33 действующих магазина и супермаркета.

              Доработка и поддержка веб-ресурсов торговой сети «ЭЛЕКТРОСИЛА», специализирующейся на бытовой технике.

              * сопровождение и внедрение нового функционала в самописный PHP-проект
              * разработка внутреннего инструментария для отладки "на живую" в production-окружении
              * обмен данными между сайтом и внутренней системой коммерции
              * разработка новой [мобильной версии](https://m.sila.by/) в соответствии с дизайн-макетом
        - title: Мастер-класс по управлению проектами
          company: "Парк высоких технологий"
          company_url: 'http://www.park.by/?lng=en'
          location: Беларусь, Минск
          date_start: '2014-04-01'
          date_end: '2014-04-01'
          description: |2-
              Участник практического мастер-класса "Управление изменениями проекта" проходившего на базе Белорусского Парка высоких технологий
        - title: Свободный художник
          company: ''
          company_url: ''
          company_logo: 
          location: Беларусь, Борисов
          date_start: '2018-10-12'
          date_end: '2020-10-28'
          description: |2-
              Разноплановая деятельность

              #### Open Source:
              * вносил [вклад](https://github.com/modxcms/revolution/pulls?q=is%3Apr+author%3Atolanych+is%3Aclosed) в ядро MODX
              * разработка [решений для MODX](https://github.com/stars/tolanych/lists/modx)
              * занимался сопровождением компонента MODX Tickets (другого автора)

              #### Разработки на заказ:

              * внедрение системы поиска Sphinx в проект
              * доработки действующих недокументированных проектов на Bitrix, Wordpress, MODX
              * интеграция веб-ресурсов со сторонними API (платежные системы, SMS, CRM)
              * внедрение микроразметки

              #### Изучал для личного пользования технологии:

              * Процессы: TDD
              * Фронтэнд: Webpack, ExtJS, VueJS
              * Бекэнд: Golang
              * Инструменты: Redis, Sphinx
    design:
      columns: '2'
  - block: experience
    id: activity
    content:
      title: Деятельность
      subtitle: Прочие мои занятия
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan-2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Сайт фестиваля Winterend
          company: "winterendblues.com"
          company_url: http://winterendblues.com
          location: Беларусь, Минск
          date_start: '2016-08-01'
          date_end: '2020-02-01'
          description: |2-
              Создание сайта для фестиваля блюзовых танцев (CMS WordPress). Каждый год для проекта менялся фирменный стиль и оформление фестиваля. В предверии фестиваля получал новый макет по которому создавал новый шаблон.
        - title: Смена движка сайта
          company: 'Школа танцев "Качели"'
          company_url: 'https://lindy.by'
          location: Беларусь, Минск
          date_start: '2015-12-01'
          date_end: '2016-06-01'
          description: |2-
              Действующий веб-ресурс с MODX перенёс на Wordpress. Решенные задачи:

              * Сохранение ссылочной базы, редирект URL на новый формат
              * Разработка скрипта для автоматической конвертации контента между БД, из таблицы modx_site_content в wp_posts
              * Доработка шаблона под адаптив
              * Интеграция внутренней кухни с Google Sheets API и Google Calendar
        - title: Поэтическое соревнование \"Рухавiк\"
          company: "Арт Сядзiба"
          company_url: 'https://www.facebook.com/artsiadziba'
          location: Беларусь, Минск
          date_start: '2015-09-01'
          date_end: '2016-12-06'
          description: |2-
              В 2015 году участвовал в первом туре поэтического конкурса "Рухавiк". В 2016 дошел до полуфинала.
        - title: Осваивал веб, игромодинг
          company: "юность"
          company_url: ''
          location: Беларусь, Борисов
          date_start: '2006-01-01'
          date_end: '2009-01-01'
          description: |2-
              С 2006 по 2009 разбирался с некоторыми вещами в компьютерной области:

              * HTML/CSS Web 2.0
              * Adobe Flash анимация
              * Цифровая графика в Adobe Photoshop, Corel Draw
              * Скриптовый моддинг на Sanny Builder (CLEO)
              * Разработка игр на Game Maker/GML
        - title: ZX Spectrum
          company: "детство"
          company_url: ''
          location: Беларусь, Борисов
          date_start: '2000-01-01'
          date_end: '2001-06-01'
          description: |2-
              Мой первый ПК Sinclair - [ZX Spectrum](https://en.wikipedia.org/wiki/ZX_Spectrum)

              * Начал свой программистский путь на BASIC
              * Изучал алгоритмы
              * Играл и веселился
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Сертификаты'
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
          description: Курс описывает фундаментальные принципы устройства и реализации операционных систем.
          organization: Intuit
          icon: 'sololearn'
          organization_url: https://www.intuit.ru
          title: Основы операционных систем
          url: ''
        - certificate_url: http://ude.my/UC-RZUQXZFJ
          date_end: ''
          date_start: '2019-03-01'
          description: ''
          organization: Udemy
          organization_url: https://www.udemy.com
          title: 'Бинарное дерево поиска. Полная теория с кодом'
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
      title: Проекты
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
        - name: Все
          tag: '*'
        - name: Веб
          tag: Веб
        - name: Образование
          tag: Образование
        - name: Игры
          tag: Игры
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
      title: Публикации
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
