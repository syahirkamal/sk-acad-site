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

  - block: markdown
    id: teaching
    content:
      title: Teaching 
      subtitle: and Supervision
      date_format: Jan 2006
      text: |
        ## **2020 @ TU Darmstadt**
        - PNS: Protection in Networked Systems ‒ Trust, Resilience, and Privacy
        - Seminar: Protection in Infrastructures and Networks (PIN)
            - Topic supervisor
        - Thesis Supervision
        - Bachelor Students Traineeship / Bachelorpraktikum 
        - Internet Praktikum

        ## **2019**
        - Introduction To Real Time Operating Systems And Applications
        - Internet Governance 
        - Internet Security
        - Dissertation

        ## **2018**
        - Introduction To Real Time Operating Systems And Applications
        - Special Topics in Next Generation Internet 
        - Dissertation
        - Final Year Project - CS@USM
        - Internship / Research Project

        ## **2017**
        - Introduction To Real Time Operating Systems And Applications
        - Special Topics in Next Generation Internet 
        - Internet Communications Protocol
        - Dissertation
        - Final Year Project - CS@USM
        - Internship / Research Project

        ## **2016 @ USM**
        - Internet Communications Protocol
        - Final Year Project - CS@USM
        - Internship / Research Project
            
        ## **Prior to 2016 @ TU Darmstadt**
        - Simulation and Evaluation of Computer Networks (SECoN)
        - Seminar Telekooperation
        - Seminar Security, Privacy, and Trust
        - Projectpraktikum
        - Bachelor Students Traineeship / Bachelorpraktikum 
        
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'


  - block: accomplishments
    id: accomplishments
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
        - name: Cyber Security 
          tag: Cyber Security
        - name: Internet of Things
          tag: Internet of Things 
        - name: Botnets
          tag: Botnets
        - name : Others 
          tag : Others
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

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
      sort_by: 'Date'
    design:
      columns: '2'
      view: citation

  - block: markdown
    id: recognition
    content:
      title: Recognition 
      date_format: Jan 2006
      text: |
        ## **2023@IEEE Indonesia/Universitas Nusa Putra**
        - Invited Speaker
        - The P2P Botnet Threat Mitigation Lifecycle
        - Secure and Intelligent Future: The Confluence of AI, IoT, and Cyber Resilience - Online Webinar
    design:
      columns: '2'
      view: compact

#  - block: accomplishments
#    id: recognition
#    content:
#      title: Recognition
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant recognition by [filtering recognition](./recognition/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - recognition
#        exclude_featured: false
#    design:
#      columns: '2'
#      view: compact

  - block: markdown
    id: services
    content:
      title: Services
      date_format: Jan 2006
      text: |
        ## **Journal Reviewer**
        - [IEEE Transactions on Information Forensics & Security](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206) 
        - [ACM Computing Surveys](https://dl.acm.org/journal/csur)
        - [Computer Networks - Elsevier](https://www.journals.elsevier.com/computer-networks)
        - [Information Systems - Elsevier](https://www.journals.elsevier.com/information-systems) 
        - [IEEE Access](https://ieeeaccess.ieee.org/)
        - [International Journal of Network Management](https://onlinelibrary.wiley.com/journal/10991190)
        - [IEEE Communications Magazine](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=35)
        - [Journal of Information Security and Applications - Elsevier](https://www.journals.elsevier.com/journal-of-information-security-and-applications)
        - [Peer J Computer Science](https://peerj.com/computer-science/)

        ## **TPC/Reviewer**
        - Center for Communication, Media and Information technologies (CMI), Aalborg University - [2019](https://www.conf.cmi.aau.dk/12th+CMI+conference+2019/)
        - International Conference on Advances in Computing, Communication & Automation (ICACCA) - 2018
        - International Conference on Parallel, Distributed and Grid Computing (PDGC) - [2018](http://www.juit.ac.in/pdgc-2018/index1.php) 
        - International Conference on Availability, Reliability and Security (ARES) - [2017](https://www.ares-conference.eu/ares2017/conference2017/index.html), [2020](https://www.ares-conference.eu/)
        - International Conference on Computing and Informatics (ICOCI) - [2017](http://www.icoci.cms.net.my/icoci2017/)
        - IEEE/IFIP Workshop on Security for Emerging Distributed Network Technologies (DISSECT) - [2017](http://www.inf.ufrgs.br/dissect/2017/), [2020](http://www.inf.ufrgs.br/dissect/2020/)

    design:
      columns: '2'

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
