---
# Leave the homepage title empty to use the site title
title: Homepage
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      #title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: markdown
    content:
      title: International Collaboration
      #subtitle: My subtitle
      text: |-
          - Advisory Board, “A coordinated framework for Cyber Resilient Supply Chain Systems Over Complex ICT Infrastructures”, Horizon 2020 (Grant agreement ID: 952644), 1/9/2020-31/08/2023
          - Advisory Board, “Towards an Open, Secure, Decentralized and Coordinated Fog-to-Cloud Management Ecosystem”, Horizon 2020 (Grant agreement ID: 730929), 1/1/2017-31/12/2019
          - Inventor Advisory Board, Xinova, 2017-2018
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

      
  - block: markdown
    content:
      title: Professional Services
      #subtitle: My subtitle
      text: |-
          - Associate Editor, IEEE Transactions on Emerging Topics on Computational Intelligence (2023-present)
          - Associate Editor, IEEE Transactions on Parallel and Distributed Systems (2022-present)
          - Associate Editor, IEEE Transactions on Cloud Computing (2020-present)
          - Associate Editor, IEEE Internet of Things journal (2020-present)
          - Associate Editor, IEEE Transactions on Mobile Computing (2012-2018)
          - Associate Editor, Optical Switching and Networking (2013-present)
          - Associate Editor, Wiley's Security and Communication Networks (SCN) Journal (2012-2016)
          - Associate Editor, IEEE Communication Letters (Jan. 2012-Dec. 2013)
          - Co-Area associate editor, JSAC special issue on Emerging Technologies in Communications, Area 7: Fiber and Wireless Integration
          - Co-guest editor， IEEE Networks special issue on Information-Centric Networking beyond baseline scenarios: research advances and Implementation 
          - Co-guest editor, OSN special issue on Resilient Virtual Infrastructure Design and Recovery
          - TPC co-chair, IEEE IWQOS, 2017
          - Program co-Chair, ICIST 2017
          - Student Travel Grant chair, ACM ICN 2017.
          - TPC Symposium co-chair, IEEE Globecom 2014 Optical Networks and Systems Symposium
          - Sponsorship co-chair, IEEE INFOCOM 2015. 
          - Publicity chair, Fifth IEEE International Workshop on Sensor Networks and Systems for Pervasive Computing, 2009
          - Session chair, 5TH Annual IEEE Consumer Communications & Networking Conference, Special session on Service-Oriented Wireless Ad Hoc and Sensor Networks, 2009
          - Registration chair, ACM MobiHoc'08
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1' 
      
  - block: markdown
    content:
      title: Research Grants in the capacity of PI
      #subtitle: My subtitle
      text: |-
          - “Modelling and Handling Uncertainties in Autonomous Driving Systems”, Hong Kong RGC, GRF, project duration: Jan. 2023-Dec. 2025, Amount: HK$1,110,576, Approved date: June 30th 2022. 
          - “Age of Information Centric Task Scheduling in Autonomous Driving Systems”, Hong Kong RGC, GRF, project duration: Jan. 2022-Dec. 2024, Amount: HK$ 1,036,800, Approved date: June 30th 2021. 
          - “Mobile Application Engine: 5G Network Slice Management Platform”, ITF, project duration: March 2022-Feb 2024, Amount: HK$8,303,877 +hk1,988,252 in-kind equipment support, Approved date: Feb.  2022. 
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1' 
  - block: markdown
    content:
      title: Keynotes
      #subtitle: My subtitle
      text: |-
          - IEEE DRCN 2022
          - EAI MONAMI 2020 
          - IEEE International Workshop on Smart Multimedia 2017
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 
      
  - block: markdown
    content:
      title: IETF RFC
      #subtitle: My subtitle
      text: |-
          - S. Lederer, D. Posch, C. Timmerer, C. Westphal, Aytac Azgin,  S. Liu,C. Mueller, A.Detti, D. Corujo, J. Wang, Marie-Jose Montpetit, Niall Murray, “Adaptive Video Streaming over ICN”,  RFC 7933, https://datatracker.ietf.org/doc/html/rfc7933
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2' 
  - block: collection
    content:
      archive:
        enable: true
        text: List of all publications
        link: publication
      title: Recent Publications
   #   text: |-
   #    {{% callout note %}}
   #    Quickly discover relevant content by [filtering publications](./publication/).
   #    {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation 
     
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-

      # Contact (add or remove contact options as necessary)
      email: jianwang@cityu.edu.hk
      phone: +852 3442 7737
      
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
      columns: '1'
---
