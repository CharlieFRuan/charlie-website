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
  - block: collection
    id: publications
    content:
      title: Publications
      # text: |-
      #   {{% callout note %}}
      #   Quickly discover relevant content by [filtering publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: experience
    id: projects
    content:
      title: Projects
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Core Contributor
          company: MLC LLM
          company_url: https://github.com/mlc-ai/mlc-llm
          company_logo: mlc-icon
          location: Pittsburgh, PA
          date_start: '2023-06-01'
          date_end: ''
          description: Enable universal native deployment for LLMs through machine learning compilation techniques
        - title: Project Lead
          company: Web LLM
          company_url: https://github.com/mlc-ai/web-llm
          company_logo: mlc-icon
          location: Pittsburgh, PA
          date_start: '2023-06-01'
          date_end: ''
          description: Leading the project to bring LLMs to run locally in client-side browser with WebGPU acceleration
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Industry Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineer Intern
          company: Google
          company_url: https://www.tensorflow.org/
          company_logo: google-icon
          location: Sunnyvale, CA
          date_start: '2023-06-01'
          date_end: '2023-08-31'
          description: Worked on Core ML’s Distributed Runtime team, optimizing Tensorflow's checkpoint to reduce wasted TPU cycles
        - title: Software Engineer Intern
          company: Google Cloud
          company_url: https://techsysinfra.google/
          company_logo: google-icon
          location: Sunnyvale, CA
          date_start: '2022-08-01'
          date_end: '2022-10-31'
          description: Worked on Technical Infrastructure's Platform team, deploying accelerators in Google data centers using OpenBMC, implementing Linux daemon and firmware update APIs
        - title: Software Engineer Intern
          company: Amazon Robotics
          company_url: https://www.amazon.jobs/en/teams/amazon-robotics
          company_logo: amazon-icon
          location: Greater Boston, MA
          date_start: '2022-05-01'
          date_end: '2022-07-31'
          description: Worked on Robotic Storage Technologies team, improving worker's interaction with autonomous warehouse robots
        - title: Software Engineer Intern
          company: XPENG Motors
          company_url: https://www.xpeng.com/
          company_logo: xpeng-icon
          location: Shanghai, China
          date_start: '2021-06-01'
          date_end: '2021-08-31'
          description: Optimized sensor fusion algorithms for XPeng's self-driving cars
        - title: Software Engineer Intern
          company: Morgina Information Technology
          company_url: http://www.morgina.com.cn/
          company_logo: morgina-icon
          location: Shanghai, China
          date_start: '2020-06-01'
          date_end: '2020-07-31'
          description: Optimized multi-object tracking algorithm with millimeter-wave radar
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        I will be applying for Fall 2025 PhD programs in Computer Science. Please feel free to contact me!
      # Contact (add or remove contact options as necessary)
      email: cfruan@andrew.cmu.edu
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: https://www.linkedin.com/in/charlie-ruan/
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/charlie_ruan'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
