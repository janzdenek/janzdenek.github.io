---
title: ""
type: landing

sections:
  # Biography
  - block: markdown
    id: about
    content:
      title: Jan Zdenek
      subtitle: PhD Student at the University of Tokyo
      text: |
        ![Profile Picture](img/portrait.jpg)

        Jan is a third-year Ph.D. student in information science and technology particularly interested in artificial intelligence, computer vision, and machine learning. He is a member of the Machine Perception Group (Nakayama Laboratory) at the University of Tokyo, which he joined in 2015. Before commencing his graduate studies at the University of Tokyo, he earned his bachelor's degree in computer and information science at the Czech Technical University in Prague, Czech Republic, where he was born and grew up.

        His research focuses on computer vision, in particular on image generation and text in natural scene images. Recently, he has been interested in application of generative adversarial networks for handwritten text and text in natural scene images.

        **Interests:** Computer Vision • Machine Learning • Artificial Intelligence • Image Generation
    design:
      columns: '2'

  # Publications (peer-reviewed)
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: with peer review
      text: ""
      filters:
        folders:
          - publication
        tags:
          - peer-reviewed
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  # Other Publications (non-peer-reviewed)
  - block: collection
    id: other-publications
    content:
      title: Other Publications
      subtitle: without peer review
      text: ""
      filters:
        folders:
          - publication
        tags:
          - non-peer-reviewed
    design:
      columns: '2'
      view: citation

  # Competitions (custom markdown)
  - block: markdown
    id: competitions
    content:
      title: Competitions
      text: |
        - 3rd place in the [ICDAR 2017 Robust Reading Competition on Multilingual Scene Text Detection and Script Identification](http://rrc.cvc.uab.es/?ch=8) in the task of script identification
    design:
      columns: '2'

  # Awards (custom markdown)
  - block: markdown
    id: awards
    content:
      title: Awards
      text: |
        - MIRU 2020 Student Paper Award (Hataya R., Zdenek J., Yoshizoe K., Nakayama H.)
        - The Japanese Society for Artificial Intelligence (JSAI) Annual Conference Student Incentive Award 2017
        - Japanese Government (MEXT) Scholarship for Research Students
        - Dean's Award for an Outstanding Bachelor Thesis, Czech Technical University, 2014
    design:
      columns: '2'

  # Teaching (custom markdown)
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        I have worked as a teaching assistant for the following courses at the University of Tokyo, Graduate School of Information Science and Technology:

        - Data Science
    design:
      columns: '2'

  # Contact section
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      email: jan@nlab.ci.i.u-tokyo.ac.jp
      phone: ''
      address:
        street: 1-1-1 Yayoi, Bunkyo
        city: Tokyo
        region: ''
        postcode: '113-0032'
        country: Japan
        country_code: JP
      coordinates:
        latitude: '35.715826'
        longitude: '139.761044'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: https://twitter.com/jan_zde
        - icon: github
          icon_pack: fab
          name: Github
          link: https://github.com/kurapan
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: https://www.linkedin.com/in/jan-zdeněk-3907b74a
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: https://scholar.google.co.jp/citations?user=qylVL6wAAAAJ
        - icon: researchgate
          icon_pack: ai
          name: ResearchGate
          link: https://www.researchgate.net/profile/Jan_Zdenek
    design:
      columns: '2'
---
