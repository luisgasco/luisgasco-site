---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-07
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 # - block: features
 #   content:
 #     title: Skills
 #     items:
 #       - name: R
 #         description: 90%
 #         icon: r-project
 #         icon_pack: fab
 #       - name: Statistics
 #         description: 100%
 #         icon: chart-line
 #         icon_pack: fas

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
        - name: Artificial Intelligence
          tag: AI
        - name: Annotation
          tag: Annotation
        - name: Library
          tag: Library
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      
      items:
        - title: Senior Machine Learning Engineer
          company: Avature
          company_url: 'https://www.avature.net/avature-ai-recruiting-technology/'
          company_logo: org-avature
          location: Spain
          date_start: '2024-02-05'
          date_end: ''
          description: |2-  
            Working in the Machine Learning department at Avature, with a primary focus on developing multilingual Natural Language Processing (NLP) systems applied to Human Capital Management (HCM).
            Key contributions and responsibilities include:
              * Researching and developing advanced contextual entity linking (EL) systems to improve the extraction of key information from job descriptions, resumes, and HCM data. This research area focuses on exploring novel algorithms and methodologies to enhance the accuracy and efficiency of entity linking in multilingual and cross-industry contexts.
              * Collaborating in the deployment of models into production environments, ensuring their scalability and performance within Avature’s platform.
              * Developing methodologies for terminology enrichment, focused on expanding and refining controlled vocabularies to improve the accuracy and relevance of multilingual skill and competency representations.
              * Actively organizing and presenting results in shared-task challenges, conferences, and industry events, collaborating with experts and showcasing our innovations within the NLP field to researchers and students. 

        - title: Lecturer
          company: Universidad Complutense de Madrid
          company_url: ''
          company_logo: org-ucm
          location: Madrid, Spain
          date_start: '2020-09-01'
          date_end: ''
          description: |2-
              * Lecturer of the Text Mining and Social Networks modules in the Master Big Data and Business Analytics and the Master Data Science and Big Data of the Universidad Complutense de Madrid.
              * More than 600 students have been taught the basics of NLP techniques including data preprocessing, document representation and, text classification and topic modeling strategies.
        - title: Research Engineer
          company: Barcelona Supercomputing Center
          company_url: 'https://bsc.es/'
          company_logo: org-bsc
          location: Barcelona, Spain
          date_start: '2020-10-01'
          date_end: '2024-02-05'
          description: |2-  
            Worked within Martin Krallinger's research group with a primary focus on advancing the field of clinical Natural Language Processing (NLP) in the Spanish language. My work revolved around harnessing NLP systems to extract valuable biomedical insights from Electronic Health Records (EHRs) and emerging data sources, including online social networks. Key contributions and responsibilities included:
              * Development of neural entity linking systems for the Spanish language. These systems were designed to link biomedical mentions extracted from NERs to ontologies such as SNOMED-CT, ICD-10 or HPO, among others.
              * Played a key part in making Gold Standard datasets and creating clear rules for Named Entity Recognition (NER) and Entity Linking. This work helped make evaluation standards consistent in the field.
              * Actively participated in organizing and publishing results in shared-task challenges conducted within esteemed international conferences and workshops such as COLING, NAACL, CLEF, SEPLN, BioASQ, SMM4H, and IberLEF. These platforms served as valuable venues for showcasing our advancements and collaborating with fellow experts in the field.
              * Actively engaged in seeking research funding, which involved finding partners and writing grant proposals. This included applying for funding from European Union's Horizon Program and the Spanish government's PERTE initiative.
        - title: Data Scientist
          company: Atos Research and Development
          company_url: ''
          company_logo: org-atos
          location: Madrid, Spain
          date_start: '2019-11-19'
          date_end: '2020-05-31'
          description: |2-
              - Developed and integrated a suite of open-source data analysis tools to manage the machine learning lifecycle within the company's IoT solution, the Urban Data Platform.
              - Utilized TensorFlow for training time series prediction models using sensor data from Mallorca airport and deployed these models on the platform.
              - Collaborated on business consulting tasks, including creating business models for technology transfer from European projects in Computer Vision and Edge Computing.
        - title: Visiting Research Engineer
          company: Nokia Bell Labs
          company_url: ''
          company_logo: org-nokia_bell
          location: Cambridge, UK
          date_start: '2018-07-01'
          date_end: '2018-10-31'
          description: |2-
              - Research stay at the Bell Labs, with 9 Nobel prizes, under the supervision of Daniele Quercia (Social Dynamics Department director), working withing one of the projects of the initiative goodcitylife.org, which seeks to solve urban problems using open data and AI.
              - I was involved in research activities focused on data mining of geographic social media and open data, and on the impact of noise on health in the city of London
        - title: Visiting Research Engineer
          company: Télécom Paris
          company_url: ''
          company_logo: org-telecom_paris
          location: Paris, France
          date_start: '2017-09-01'
          date_end: '2017-12-31'
          description: |2-
              - Research stay in the S2A Team (Image, Data and Signal Department) under the supervision of Prof. Chloé Clavel working on topics related to opinion mining and NLP appied to detect attitudes to environmental noise written in Online Social Networks
              - Research activities focused on pre-processing twitter texts, feature extraction (part-of-speech, statistical features, sentiment features, and word embeddings), short-text classification models, and noise taxonomy creation (using WordNet and DBPedia)
        - title: Researcher
          company: Universidad Politécnica de Madrid
          company_url: ''
          company_logo: org-upm
          location: Madrid, Spain
          date_start: '2013-05-01'
          date_end: '2019-10-31'
          description: |2-
              - Developed text mining models for complaint detection and classification related to urban noise.
              - Analyzed urban data to create prediction models.
              - Designed open data-based platforms for visualizing environmental noise data.
              - Conducted statistical analysis of noise levels from smart city sensors and attitude surveys.
              - Researched noise data reporting methods in major cities and international airports (Europe, USA, Australia).
              - Implemented pattern recognition algorithms for aircraft identification software.
              - Collaborated on consultancy projects and various research initiatives.
        
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Grants & awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2021-11-01'
          organization: Universidad Politécnica de Madrid
          organization_url: https://www.upm.es/
          title: Extraordinary Doctoral Thesis Award for the promotion of 2019-2020.
          url: 'http://www.i2a2.upm.es/concedido-premio-extraordinario-tesis-doctoral-luis-gasco-sanchez/'
        - certificate_url: ''
          date_end: ''
          date_start: '2019-06-18'
          organization: "Sociedad Española de Acústica"
          organization_url: https://www.sea-acustica.es/
          title: Prize “Catedra Luis de Camoens UC3M” to the best scientific communication presented by a young researcher at Internoise 2019
          url: http://www.sea-acustica.es/becas-y-premios/premios-andres-lara/
        - certificate_url: ''
          date_end: ''
          date_start: '2018-03-16'
          organization: "Universidad Politécnica de Madrid"
          organization_url: https://www.upm.es/
          title: Award to the best speaker in the 2nd Symsium “Cuentanos tu tesis”
          url: https://eventos.upm.es/16404/files/ii-edicion-simposio-cuentanos-tu-tesis.html

        - certificate_url: ''
          date_end: ''
          date_start: '2016-03-18'
          organization: "EIT Digital"
          organization_url: https://www.eitdigital.eu/
          title: EIT Digital Doctoral School Grant

        - certificate_url: ''
          date_end: ''
          date_start: '2019-06-18'
          organization: "Sociedad Española de Acústica"
          organization_url: https://www.sea-acustica.es/
          title: Travel Grant for Young Acousticians for the congress Internoise 2019
          url: http://www.sea-acustica.es/

        - certificate_url: ''
          date_end: ''
          date_start: '2014-06-18'
          organization: "Sociedad Española de Acústica"
          organization_url: https://www.sea-acustica.es/
          title: Travel Grant for Young Acousticians for the congress Tecniacústica 2014
          url: http://www.sea-acustica.es/

        
        

        
    design:
      columns: '2'
   
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
 #     view: list
  - block: collection
    id: featured
    content:
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
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering talks](./event/).
        {{% /callout %}}
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

#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please write me here. If you want me to answer you quickly, contact me on Linkedin or Twitter!
      # Contact (add or remove contact options as necessary)
      #appointment_url: 'https://calendly.com'

      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/luisgasco'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:lgascosa?call'
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
