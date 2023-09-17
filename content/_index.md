---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
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
        - title: "Area Head - Smart Protection in Infrastructures and Networks (SPIN)"
          company: "Telecooperation Group, Technische Universität Darmstadt"
          company_url: "https://www.tk.informatik.tu-darmstadt.de"
          location: "Darmstadt, Germany"
          date_start: "2021-01-01"
          date_end: "2021-06-30"
          description: |
            Responsibilities include:
            
            * Managing (2) postdocs and (4) Ph.D. students within the area
            * Contribute towards improving efficiency of the area as a whole
        - title: "Senior Researcher / PostDoc"
          company: "Telecooperation Group, Technische Universität Darmstadt"
          company_url: "https://www.tk.informatik.tu-darmstadt.de"
          location: "Darmstadt, Germany"
          date_start: "2019-07-01"
          date_end: "2021-06-30"
          description: |
            Responsibilities include:
            
            * Research in Malware Analysis and Botnet Monitoring
            * Grant and project acquisitions
            * Scientific coordination of both national and international research projects
            * Teaching and supervision of B.Sc., M.Sc., and Ph.D. students
        - title: "Senior Lecturer"
          company: "National Advanced IPv6 Centre (NAv6), Universiti Sains Malaysia"
          company_url: "https://www.nav6.usm.my"
          location: "Penang, Malaysia"
          date_start: "2016-06-01"
          date_end: ""
          description: |
            Responsibilities include:
            
            * Research in Cyber Security and Internet of Things
            * Grant and project acquisitions
            * Teaching and supervision of M.Sc. and Ph.D. students
            * Carry out industrial consultation projects
            * Carry out national/international security trainings and workshops
        - title: "Researcher"
          company: "Telecooperation Group, Technische Universität Darmstadt"
          company_url: "https://www.tk.informatik.tu-darmstadt.de"
          location: "Darmstadt, Germany"
          date_start: "2012-10-01"
          date_end: "2016-05-31"
          description: |
            Responsibilities include:
            
            * Ph.D. thesis in Advanced Monitoring of P2P Botnets
            * Teaching (B.Sc./M.Sc. courses)
            * Supervising B.Sc. and M.Sc. theses
        - title: "Researcher"
          company: "COMSYS, RWTH Aachen"
          company_url: "https://www.comsys.rwth-aachen.de/"
          location: "Aachen, Germany"
          date_start: "2010-06-01"
          date_end: "2011-05-31"
          description: |
            Responsibilities include:
          
            * M.Sc. thesis in Securing Wireless Mesh Networks (WMNs)
            * Conducting simulation and evaluation of WMNs
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - organization: "German Academic Exchange Service (DAAD)"
          organization_url: "https://www.daad.de"
          title: "DAAD Scholarship"
          url: ""
          certificate_url: ""
          date_start: "2009-07-01"
          date_end: "2011-05-31"
          description: |
            A full scholarship to pursue M.Sc. in a twinning programme between RWTH Aachen, Germany and Thai
            -German Graduate School of Engineering (TGGS), KMUTNB, Thailand
        
        - organization: "GÉANT"
          organization_url: "https://www.geant.org/"
          title: "TRANSITS I"
          url: "https://www.geant.org/Services/Trust_identity_and_security/Pages/TRANSITS-I.aspx"
          certificate_url: ""
          date_start: "2018-03-28"
          date_end: "2018-03-29"
          description: |
            TRANSITS-I course is aimed at new or potential computer security incident response team (CSIRT
            ) personnel who wish to gain a good grounding in the main aspects of working in such a team.
        
        - organization: "Universiti Sains Malaysia and Malaysian Ministry of Higher Education"
          organization_url: "https://www.usm.my"
          title: "Academic Staff Training Scheme (ASTS) Fellowship"
          url: ""
          certificate_url: ""
          date_start: "2012-10-01"
          date_end: "2016-05-31"
          description: "A full scholarship offer to pursue Ph.D. and thereafter join USM as a faculty member"
        
        - organization: "Malaysian Ministry of Higher Education"
          organization_url: "https://www.mohe.gov.my"
          title: "CEO@Faculty 2.0 Fellow"
          url: ""
          certificate_url: ""
          date_start: "2018-09-01"
          date_end: "2019-02-28"
          description: |
            An industrial attachment fellowship with Huawei (Malaysia) for a period of six months
        
        - organization: "Universiti Sains Malaysia"
          organization_url: "https://www.usm.my"
          title: "BJIM-USM Fellow"
          url: ""
          certificate_url: ""
          date_start: "2019-05-01"
          date_end: ""
          description: "Appointed as USM-BJIM (Division of Industry & Community Network) Fellow"
        
        - organization: "Malaysian Board of Technologists"
          organization_url: "https://www.mbot.org.my"
          title: "Professional Technologist (Cyber Security)"
          url: "https://www.mbot.org.my/registration/professional-technologists/"
          certificate_url: ""
          date_start: "2020-04-04"
          date_end: "2021-04-04"
          description: ""
        
        - organization: "Malaysian Board of Technologists"
          organization_url: "https://www.mbot.org.my"
          title: "Graduate Technologist (Cyber Security)"
          url: "https://www.mbot.org.my/registration/graduate-technologists/"
          certificate_url: ""
          date_start: "2019-01-23"
          date_end: ""
          description: ""
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
        - name: Cyber Security 
          tag: Cyber Security
        - name: Internet of Things
          tag: Internet of Things 
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
      email: kshankar@usm.my
      phone: +604 653 4632
      appointment_url: 'https://calendly.com'
      address:
        street:  National Advanced IPv6 Centre (NAv6), Level 6, School of Computer Sciences Building, Universiti Sains Malaysia
        city: USM
        region: Penang
        postcode: '11800'
        country: Malaysia
        country_code: MY
      directions: Take the lift to the 6th floor and turn right at the entrance to head over to NAv6.
      contact_links:
      - icon: twitter
        icon_pack: fab
        name: DM Me
        link: 'https://twitter.com/sh_nk_r'
      - icon: skype
        icon_pack: fab
        name: Skype Me
        link: 'skype:shankar.karuppayah?call'
      - icon: telegram
        icon_pack: fab
        name: Telegram Me
        link: 'https://telegram.me/@skusm'
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
