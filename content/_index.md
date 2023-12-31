---
# Leave the homepage title empty to use the site title
title: ""
date: 2023-08-23
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
          company: The Viterbi Faculty of Electrical & Computer Engineering, Technion
          company_url: 'https://ece.technion.ac.il/'
          company_logo: ECE_logo
          location: 'Haifa, Israel'
          date_start: '2016-11-01'
          date_end: ''
          description: |2-
            * Teaching Assistant in Three-Dimensional Imaging and Reconstruction, Graduate.
            * HW Grader in Algorithms and Applications in Computer Vision, Graduate & Undergrad.
            * Laboratory Moderator in Introduction to Image Processing and Analysis, Undergraduate.
            * Laboratory Moderator in Elementary lab course of the ECE program, Undergraduate.
            * Mentor in Introduction to ECE, Undergraduate.
            * Supervisor of Undergraduate final projects.
        - title: Research Engineer 
          company: Hybrid Imaging Lab, Electrical and Computer Engineering Faculty, Technion
          company_url: 'https://webee.technion.ac.il/people/yoav/lab-and-group/'
          company_logo: lab-logo
          location: 'Haifa, Israel'
          date_start: '2019-09-01'
          date_end: '2020-04-01'
          description: |2-
            * Active part in [CloudCT](cloudct.space), a 3D optical scattering tomography space mission to probe clouds.
                        
            * Collaborated on developing an atmospheric lidar simulator & deep-learning-based calibration method.
        - title: Algorithms Engineer 
          company: Mobileye 
          company_url: 'https://www.mobileye.com'
          company_logo: Mobileye_logo 
          location: 'Jerusalem, Israel'
          date_start: '2014-04-01' # correct dates needed dates needed 
          date_end: '2014-12-01'
          description: |2-
            * Analyzing the autonomous vehicle performance using machine learning and image processing algorithms.
            
            * Embedding of detection algorithms into a semi-automated marking system.
        - title: Software Graphics Engineer 
          company: Intel 
          company_url: 'https://www.intel.com/content/www/us/en/homepage.html'
          company_logo: Intel_logo
          location: 'Yakum, Israel'
          date_start: '2013-03-01' 
          date_end: '2014-04-01'
          description: |2-
            * Power management enhancement of the graphics driver on Windows and Android platforms.
            * Developing statistics test tools to analyze 3D applications and games.
        - title: Board designer - student position
          company: Rafael Advanced Defense Systems 
          company_url: 'https://www.rafael.co.il'
          company_logo: Rafael_logo
          location: 'Israel'
          date_start: '2009-11-01' 
          date_end: '2011-12-01'
          description: |2-
            * Development and production of analog and digital boards.
            * Design, construction, and operation of automated testing systems of FPGA boards.
        
        - title: Lieutenant, Information and Communication Technology Officer.
          company: Israel Defence Force.
          company_url: 
          company_logo: # add company logo here
          location: ''
          date_start: '2001-10-01' 
          date_end: '2004-04-01'
          description: |2-
            * Cadet team Commander at the training base of the C4I Corps. Elected as an outstanding commander of the Cadet training course.

            * Commander of Communication and Computer departments.

    design:
      columns: '2'

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

  - block: collection
    id: featured
    content:
      title: Student projects
      filters:
        folders:
          - student_projects
    design:
      columns: '2'
      view: card

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Contact me at:
      # Contact (add or remove contact options as necessary)
      email: Addalin@campus.technion.ac.il
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
