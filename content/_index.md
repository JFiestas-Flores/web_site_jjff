---
date: "2023-07-07"
sections:
- block: about.biography
  content:
    title: Welcome!
    username: admin
  id: about

- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    
    title: Research
  id: research
  design:
    columns: "2"
  view: citation
   
    

- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: University of Alberta
      company_url: "https://www.ualberta.ca"
      date_end: "2024-04-15"
      date_start: "2019-09-01"
      description: |2-
          * Strategic Management in Food and Resource Businesses
          * Environmental and Resource Economics
          * Linear Models to Food, Resources and the Environment
          * History and Fundamentals of Environmental Protection and Conservation
          * Economic Valuation of Ecosystem Services
      location: Edmonton, AB
      title: Teaching Assistant
    - company: Universidad Antornio Ruiz de Monyoya
      company_url: "https://www.uarm.edu.pe/"
      date_end: "2018-12-31"
      date_start: "2017-07-01"
      description: |2-
          * Econometrics II
          * Microeconomics II
      location: Lima, PE
      title: Part-time Professor
    - company: Universidad Del Pacífico
      company_url: "https://www.up.edu.pe/"
      date_end: "2011-03-31"
      date_start: "2014-08-01"
      description: |2-
         * Introduction to   Microeconomics
         * Microeconomics I
         * Microeconomics II
      location: Lima, PE
      title: Teaching Assistant
    title: Teaching
  design:
    columns: "1"
  id: teaching  


- block: features

  content:
    items:
    - description: 
      icon: r-project
      icon_pack: fab
      name: R
    - description:
      icon: chart-line
      icon_pack: fas
      name: Stata
    - description: 
      icon: earth-americas
      icon_pack: fa
      name: ArcGis, QGis
    - description: 
      icon: tree
      icon_pack: fa
      name: Ztree, Otree
    - description: 
      icon: github
      icon_pack: fab
      name: GitHub, OSF
    - description: 
      icon: language
      icon_pack: fa
      name: Spanish, English, Basic German
    title: Skills
  id: skills
 


- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Conference Presentations
      date_end: ""
      date_start: "2020-06-01"
      description: |2-
          * Society for Benefit-Cost Analysis (SBCA) European conference, September 2024
          * Society for Benefit-Cost Analysis (SBCA) conference, April 2024
          * Canadian Agricultural Economics Association (CAES), July 2023
          * Canadian Resource and Environmental Economics (CREEA) Early Scholar Workshop, June 2023
          * Association of Environmental and Resource Economists (AERE) Conference, June 2022
          * Alberta Chapter of the Canadian Land Reclamation Association (CLRA), May 2022
          * Environmental Studies Association of Canada Conference (ESAC), June 2021
          * The Canadian Society for Ecological Economics Biennial Conference (CSEE), May 2021
          * Sloan/Berkeley Environmental and Energy Economics Summer School, June 2020
    - company: Community Engagement
      date_end: ""
      date_start: "2020-05-01"
      description: |2-
          * Earthshot Prize, Cross-cutting enabler expert, August 2023 - Ongoing
          * AERE Grad Student Engagement Committee, January 2023 - June 2024
          * Plant Based U - Canada, September 2022 - March 2024
          * ALES Graduate Student Association, July 2021 - June 2022
          * REES Student Association, July 2020 - June 2023
    title: Conferences and engagement
  design:
    columns: "2"
  id: conferences

- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Animal Welfare
      tag: Animal Welfare
    - name: Plant-Based preferences
      tag: Plant-Based
    - name: Environmental education
      tag: Environment
    default_button_index: 2
    filters:
      exclude_featured: true
      folders:
      - project
    title: Additional activities
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: more    
  
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Companion animals
  design:
    columns: "1"



- block: contact
  content:
    email: fiestas@umwelt.uni-hannover.de
    address:
        street: Institut fur Umweltplanung E202
        city: Hannover
        region: Lower Saxony
        postcode: '30419'
        country: Germany
        country_code: DE
    
    title: Contact
  design:
    columns: "2"
  id: contact
    

title: null
type: landing
---

# gallery_item:
# - album: "demo"
#   image: Pancho.jpg
#   caption: Pancho
# - album: "demo"
#   image: Zelda_Midna.jpg
#   caption: Zelda and Midna
