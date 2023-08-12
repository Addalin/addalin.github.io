---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing
editable: true

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Teaching
          company: Faculty of Data & Decision Sciences, Technion
          company_url: 'https://dds.technion.ac.il/'
          company_logo: ''
          location: ''
          date_start: '2021-10-01'
          date_end: '2023-09-30'
          description: |2-
            * Head Teaching Assistant for Language, Computation & Cognition (Joint course; Spring 2022 and Spring 2023).
            * Teaching Assistant for Database Management (Undergraduate course; Winter 2022 and Winter 2023).
            * Mentoring undergrad final project (Spring 2023).
        - title: Research Assistant
          company: Hybrid Imaging Lab, Electrical and Computer Engineering Faculty, Technion
          company_url: 'https://webee.technion.ac.il/people/yoav/lab-and-group/'
          company_logo: lab-logo
          location: ''
          date_start: '2019-09-01'
          date_end: '2021-09-30'
          description: |2-
            * Active part in [CloudCT](cloudct.space), a 3D optical scattering tomography space mission to probe clouds.
                        
            * Collaborated on developing an atmospheric lidar simulator & deep-learning-based calibration method.
        - title: Multiple Roles
          company: Watteam (Start-Up Company)
          company_url: ''
          company_logo: 'watteam-logo'
          location: ''
          date_start: '2015-03-01'
          date_end: '2018-11-30'
          description: |2-
            * Head of Business Development, China.
            
            * Customer Satisfaction Manager.
            
            * Project & Lab Manager.
    design:
      columns: '2'

  - block: collection
    id: featured
    content:
      title: Student projects
      filters:
        folders:
          - student_projects
        #featured_only: true
    design:
      columns: '2'
      view: card

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
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    content:
      count: 10
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me at:
      # Contact (add or remove contact options as necessary)
      email: <last_name>(at)campus.technion.ac.il
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
