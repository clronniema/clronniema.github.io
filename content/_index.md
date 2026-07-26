---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  - block: resume-biography
    id:
    content:
      username: me
      text: GIS analyst with extensive working experience in GIS, proven proficiency in GIS data ETL and developing GIS applications. Familiar with Esri products such as ArcGIS Pro, ArcGIS Online and geoprocessing tools, as well as open source tools such as QGIS on a regular basis. Looking forward to my next challenge in Canada and is excited for upcoming challenges and problems to solve.
      button:
        url: uploads/resume.pdf
        text: "Resume" 
    design:
      avatar:
        size: large
        shape: circle
      biography:
        style: "max-width: 60ch; "

  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      categories:
        - name: GIS
          items:
            - name: QGIS
              icon: brands/qgis
            - name: ArcGIS
              icon: brands/esri
            - name: FME
              icon: hero/arrows-right-left
            - name: 3D (ContextCapture and Pix4D)
              icon: hero/cube
            - name: MapLibreJS
              icon: brands/maplibre
            - name: LeafletJS
              icon: brands/leaflet
        - name: Languages
          items:
            - name: TypeScript
              icon: devicon/typescript
            - name: Python
              icon: devicon/python
            - name: Javascript
              icon: devicon/javascript
        - name: Frontend
          items:
            - name: React
              icon: devicon/react
            - name: Angular
              icon: devicon/angular
            - name: Vue
              icon: devicon/vuejs
        - name: Backend
          items:
            - name: Node.js
              icon: devicon/nodejs
            - name: PostgreSQL
              icon: devicon/postgresql
            - name: MongoDB
              icon: devicon/mongodb
        - name: DevOps
          items:
            - name: Docker
              icon: devicon/docker
            - name: AWS (EC2, S3 and more...)
              icon: devicon/amazonwebservices
    design:
      style: grid
      show_levels: true

  - block: resume-experience
    id: work
    content:
      username: me
      text: Highlights from my recent roles and education.
    design:
      date_format: Jan 2006
      is_education_first: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

  #       I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.

  #       Please reach out to collaborate 😃
  #   design:
  #     columns: '1'
  - block: portfolio
    id: projects
    content:
      title: Featured Projects
      count: 6
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: "*"
        - name: Work
          tag: Work
        - name: QGIS
          tag: QGIS
        - name: Casual
          tag: Casual
        - name: Esri
          tag: Esri
        - name: Remote Sensing
          tag: Remote Sensing
        - name: 3D
          tag: 3D
        - name: R
          tag: R
      default_button_index: 0
      archive:
        enable: true
        text: View All Projects
    design:
      columns: 3
  - block: collection
    id: blog
    content:
      title: Technical Blog
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

---
