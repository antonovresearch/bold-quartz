---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: hero
    id: about
    content:
      title: |
        Physical Organometallic Chemistry
      text: |
        We are a research group focused on the investigation of the role of non-covalent interactions in the structural features, synthetic methodology and reactivity of main group organometallics.<br><br>
        As of now we are a subgroup of the group of Prof. Ruth Gschwind at the University of Regensburg.
      # primary_action:
        # text: Join Our Team
        # url: '#team'
        # icon: hero/user-group
      secondary_action:
        text: View Publications
        url: '#publications'
        icon: hero/academic-cap
      # announcement:
        # text: "We are hiring PhD students!"
        # link:
          # text: "Apply now"
          # url: "/opportunities"
    design:
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        # Option A: Modern gradient mesh (recommended for 2025/2026)
        gradient_mesh:
          enable: true
          style: "waves"
          animation: "pulse"
          intensity: "medium"
          colors:
            - "[#125607]"
            - "[#074300]"
            - "[#0C2703]"
            - "[#071402]"
            - "[#090804]"
        
        # Option B: Team/lab image (uncomment to use instead of gradient mesh)
        # image:
        #   filename: "team-lab-hero.jpg"
        #   filters:
        #     brightness: 0.6
        #     contrast: 1.1

  - block: stats
    content:
      items:
        - statistic: "36"
          description: Publications in top-tier journals
           #sub_metric: Nature, Science, Cell, PNAS
          icon: hero/document-text
        - statistic: "6"
          description: Brilliant team members
           #sub_metric: From 8 countries worldwide
          icon: hero/user-group
        #- statistic: "$5M"
          #description: Active research funding
           #sub_metric: NSF, NIH, DOE grants
          #icon: hero/currency-dollar
        - statistic: "4"
          description: Active research projects
           #sub_metric: Across 3 major domains
          icon: hero/academic-cap
    design:
      layout: cards
      # Section background color (CSS class)
      css_class: "bg-gradient-to-b from-[#001400] to-[#001900]"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: research-areas
    id: research-areas
    content:
      title: Research Focus Areas
      subtitle: Expanding the Frontiers of Organolithium Chemistry with Non-covalent Interactions
      text: Our lab conducts cutting-edge research across multiple domains
      items:
        - name: Organolithium Chemistry
          description: Steric effects in synthesis, structure and reactivity of organolithium compounds
          icon: hero/academic-cap
          gradient: from-green-400 to-emerald-600
          topics:
            - Directed lithiation
            - Halogen-lithium exchange
            - Aggregation and reactivity
            - Dispercion interactions
          #team_size: 12
          #publications: 45+
          #funding: $2.5M NSF/NIH
          #cta:
            #text: Explore Projects
            #url: /research/computational-biology
            
        - name: Heterocyclic chemistry
          description: Non-covalent interactions in synthesis and functionalisation of heterocyclic compounds
          icon: hero/academic-cap
          gradient: from-purple-400 to-pink-600
          topics:
            - Pyrroles 
            - Pyridines
            - Pyrimidines
            - Isoxazoles
          #team_size: 8
          #publications: 32+
          #funding: $1.8M NSF
          #cta:
            #text: View Research
            #url: /research/machine-learning
            
        - name: Pnictogen and boron chemistry
          description: New methods for the synthesis of organopnictogens
          icon: hero/academic-cap
          gradient: from-blue-400 to-indigo-600
          topics:
            - Phosphine chalcogenides
            - Arsine chalcogenides
            - Organoboranes
          #team_size: 6
          #publications: 28+
          #funding: $1.2M DOE
          #cta:
            #text: Learn More
            #url: /research/materials-science
      #cta:
        #text: Active Research Projects
        #url: /#research
        #icon: hero/arrow-right
    design:
      layout: cards
      css_class: "bg-gradient-to-b from-[#001900] to-[#001f00]"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
    
  - block: team-showcase
    id: team
    content:
      title: Meet Our Team
      #subtitle: 'World-class researchers pushing the boundaries of science'
      #text: 'Our diverse team of researchers brings together expertise from multiple disciplines to tackle the most challenging problems in computational biology and machine learning.'
      user_groups:
        - Group Leader
        - Postdoctoral Researchers and PhD Students
        - Master and Bachelor Students
      sort_by: 'Params.last_name'
      sort_ascending: true
      #cta:
        #text: View All Team Members
        #url: /authors
        #icon: user-group
    design:
      view: card
      show_logo: true
      show_status: true
      css_class: "bg-gradient-to-b from-[#001f00] to-[#002500]"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
 
  - block: collection
    id: publications
    content:
      title: "Recent Publications"
      filters:
        folders:
          - publications
      # don't need featured_only, we pick latest automatically
      count: 4                 # number of items to display
      sort_by: date            # sort by publication date
      sort_ascending: false    # newest first
    design:
      view: article-grid
      columns: 2
    
  - block: hero
    content:
      primary_action:
        text: "See All Publications"
        url: /publications
        icon: hero/document
    design:
      css_class: "bg-transparent text-center"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: research-areas
    id: funding
    content:
      title: Research Funding
      subtitle: Competitive funding supporting our research program
      items:
        - name: Organolithium reagents in the synthesis and functionalization of nitrogen heterocycles
          description: Russian Science Foundation, № 21-73-10040, 2021-2023
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: hero/currency-dollar

        - name: "Sterically assisted activation of dialkylamino group in the synthesis of fused nitrogen heterocycles"
          description: Russian Foundation for Basic Research, № 20-33-70205, 2019-2021
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: hero/currency-dollar


        - name: Superbasic non-nucleophilic polymeric materials based on proton sponges
          description: Russian Science Foundation, № 18-73-00020, 2018-2020
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: hero/currency-dollar


        - name: Organometallic derivatives of 1,8-bis(dimethylamino)naphthalene
          description: Russian Foundation for Basic Research, № 16-33-60030, 2016-2018
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: hero/currency-dollar


        - name: "Novel principle for pyrrole ring construction: synthesis of benzo[g]indoles"
          description: Russian Foundation for Basic Research, № 12-03-31172, 2016-2018
          status: finished
          gradient: from-blue-400 to-indigo-600
          icon: hero/currency-dollar

    design:
      layout: cards
      show_logo: true        
      css_class: "bg-gradient-to-b from-[#002500] to-[#002c00]"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
       
  - block: collection
    id: news
    content:
      title: Lab News & Updates
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
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
      columns: 1
    
  - block: research-areas
    id: teaching
    content:
      title: Recent Teaching Activities
      subtitle: Courses offered by our lab
      items:
        - name: "Organic chemistry: Seminar to the Lab Course" 
          description: Bachelor (in German), Regensburg University, since 2025
          status: active
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600
    
        - name: "Modern organometallic synthesis: Lecture" 
          description: Master (In English), Regensburg University, since 2025
          status: inactive
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600

        - name: "New synthetic methods in organic chemistry: Lecture" 
          description: Master (In English), Ludwig-Maximilians-Universität München, 2024 - 2025
          status: inactive
          icon: hero/book-open
          gradient: from-yellow-400 to-yellow-600
    
    design:
      layout: cards
      show_logo: true        
      css_class: "bg-gradient-to-b from-[#002c00] to-[#003400]"
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: team-showcase
    id: collaborations
    content:
      title: Collaborators & Partners
      subtitle: International research partners
      user_groups:
        - Collaborators
    design:
      spacing:
        padding: ["3rem", 0, "3rem", 0]
      css_class: "bg-gradient-to-b from-[#003400] to-[#004100]"

  - block: contact-info
    id: contact
    content:
      title: Contact Us
      subtitle: Get in touch with our research team
      visit_title: Visit Our Lab
      connect_title: Connect With Us
      address:
        lines:
          - Antonov Laboratory
          - AK Gschwind
          - Institute of Organic Chemistry
          - University of Regensburg
          - Universitätsstr. 31
          - 93053 Regensburg
          - Germany
      office_hours:
        - "Monday - Friday: 8:00 AM - 4:00 PM"
        #- "Lab Meetings: Fridays 2:00 PM"
      email: alexander.antonov@ur.de
      #phone: "+1 (555) 123-4567"
      social:
        - icon: brands/x
          url: https://x.com/Alex_S_Antonov
        - icon: brands/linkedin
          url: https://www.linkedin.com/in/alexander-antonov-98836a27b/
        - icon: brands/bluesky
          url: https://bsky.app/profile/alexanderantonov.bsky.social
        - icon: brands/orcid
          url: https://orcid.org/0000-0001-7047-789X
        - icon: assets/media/icons/custom/researchgate-brands-solid-full.svg
          url: https://www.researchgate.net/profile/Alexander-Antonov-5
      prospective:
        title: Prospective Members
        text: Interested in joining our lab? We're always looking for motivated researchers at all levels.
        button:
          text: View Open Positions
          url: /opportunities
      #map_url: https://maps.google.com/?q=University+of+Excellence
      show_form: false
    design:
      css_class: "bg-gradient-to-b from-[#004100] to-[#005a00]"
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  - block: cta-card
    content:
      title: Join Our Research Team
      text: We are always looking for talented and motivated researchers to join our lab. We have openings for PhD students, postdoctoral researchers, and research scientists.
      button:
        text: View Open Positions
        url: /opportunities
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
