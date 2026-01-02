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
        We are a  research group focused on the investigation of the role of non-colavent interactions in the structural features, synthetic metodology and reactivity of main group organometallics 
      primary_action:
        text: Join Our Team
        url: '#team'
        icon: hero/user-group
      secondary_action:
        text: View Publications
        url: '#publications'
        icon: hero/academic-cap
      announcement:
        text: "We are hiring PhD students!"
        link:
          text: "Apply now"
          url: "/opportunities"
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
            - "primary-500/30"
            - "blue-600/20"
            - "indigo-600/15"
        
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
          icon: hero/beaker
    design:
      layout: cards
      # Section background color (CSS class)
      css_class: "bg-gradient-to-b from-primary-50 to-white dark:from-primary-900/20 dark:to-gray-800"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: research-areas
    content:
      title: Research Focus Areas
      subtitle: Expanding the Frontiers of Organolithium Chemistry with Non-covalent Interactions
      text: Our lab conducts cutting-edge research across multiple domains
      items:
        - name: Organolithium Chemistry
          description: Steric effects in synthesis, structure and reactivity of organolithium compounds
          icon: hero/beaker
          gradient: from-green-400 to-emerald-600
          topics:
            - Directed lithiation
            - Halogen-lithium exchange
            - Aggregation and reactivity
            - Dispercion interactions
          #team_size: 12
          #publications: 45+
          #funding: $2.5M NSF/NIH
          cta:
            text: Explore Projects
            url: /research/computational-biology
            
        - name: Heterocyclic chemistry
          description: Non-covalent interactions in synthesis and functionalisation of heterocyclic compounds
          icon: hero/cpu-chip
          gradient: from-purple-400 to-pink-600
          topics:
            - Pyrroles 
            - Pyridines
            - Pyrimidines
            - Isoxazoles
          #team_size: 8
          #publications: 32+
          #funding: $1.8M NSF
          cta:
            text: View Research
            url: /research/machine-learning
            
        - name: Pnictogen and boron chemistry
          description: New methods for the synthesis of organopnictogens
          icon: emoji/atom_symbol
          gradient: from-blue-400 to-indigo-600
          topics:
            - Phosphine chalcogenides
            - Arsine chalcogenides
            - Organoboranes
          #team_size: 6
          #publications: 28+
          #funding: $1.2M DOE
          cta:
            text: Learn More
            url: /research/materials-science
      cta:
        text: Active Research Projects
        url: /#research
        icon: hero/arrow-right
    design:
      layout: cards
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
    
  - block: research-areas
    id: funding
    content:
      title: Research Funding
      subtitle: Competitive funding supporting our research program
      #text: Our work is supported by national and international funding agencies.
      items:
        - name: Organolithium reagents in the synthesis and functionalization of nitrogen heterocycles
          description: Russian Science Foundation, № 21-73-10040, 2021-2023
          image: /logos/rsf-logo.png
          status: finished
          gradient: from-blue-400 to-indigo-600
          #cta:
            #text: ERC Project Page
            #url: https://erc.europa.eu

        - name: "Sterically assisted activation of dialkylamino group in the synthesis of fused nitrogen heterocycles: experimental and theoretical challenge"
          description: Russian Foundation for Basic Research, № 20-33-70205, 2019-2021 
          image: /logos/rfbr-logo.jpg
          status: finished
          gradient: from-blue-400 to-indigo-600
          #cta:
            #text: ERC Project Page
            #url: https://erc.europa.eu
          
        - name: Superbasic non-nucleophilic polymeric materials based on proton sponges
          description: Russian Science Foundation, № 18-73-00020, 2018-2020
          image: /logos/rsf-logo.png
          status: finished
          gradient: from-blue-400 to-indigo-600
          #cta:
            #text: ERC Project Page
            #url: https://erc.europa.eu
    
        - name: Organometallic derivatives of 1,8-bis(dimethylamino)naphthalene
          description: Russian Foundation for Basic Research, № 16-33-60030, 2016-2018
          image: /logos/rfbr-logo.jpg
          status: finished
          gradient: from-blue-400 to-indigo-600
          #cta:
            #text: ERC Project Page
            #url: https://erc.europa.eu
    
        - name: "Novel principle for pyrrole ring construction: synthesis of benzo[g]indoles"
          description: Russian Foundation for Basic Research, № 12-03-31172, 2016-2018
          image: /logos/rfbr-logo.jpg
          status: finished
          gradient: from-blue-400 to-indigo-600
          #cta:
            #text: ERC Project Page
            #url: https://erc.europa.eu    
    design:
      layout: cards
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
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
      cta:
        text: View All Team Members
        url: /authors
        icon: user-group
    design:
      show_role: true
      show_organizations: false
      show_interests: true
      show_social: true
      # Section background color
      css_class: "bg-gray-50 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  - block: collection
    id: projects
    content:
      title: Active Research Projects
      subtitle: ''
      text: ''
      filters:
        folders:
          - projects
      count: 0  # Number of items to show (0 = all)
      # Default filter UI (for future release)
      #default_button_index: 0
      # Filter toolbar (optional)
      # Add or remove as many filters as you like
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Machine Learning
    #       tag: ML
    #     - name: Biology
    #       tag: Biology
    #     - name: Materials
    #       tag: Materials
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 5
    design:
      view: citation
    
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

  - block: logos
    content:
      title: Collaborators & Partners
      subtitle: Leading the way together
      text: We work with top universities, research institutes, and industry leaders to advance scientific discovery
      logos:
        - name: Prof. Peter Tolstoy
          image: partners/placeholder-logo.svg
          url: https://en-chem.spbu.ru/index.php/physical-organic-chemistry/30-research/research-groups/184-research-group-of-professor-tolstoy-p
          external: true
          description: Saint Petersburg University
        - name: Prof. Elena Tupikina
          image: partners/placeholder-logo.svg
          url: https://en-chem.spbu.ru/index.php/physical-organic-chemistry/30-research/research-groups/184-research-group-of-professor-tolstoy-p
          external: true
          description: Saint Petersburg University
        
    design:
      display_mode: grid
      show_pattern: false
      css_class: "bg-gradient-to-b from-white to-gray-50 dark:from-gray-800 dark:to-gray-900"
      spacing:
        padding: ["4rem", 0, "4rem", 0]

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
          url: https://twitter.com/SmithLabResearch
        #- icon: brands/linkedin
          #url: https://linkedin.com/company/smith-lab
        #- icon: brands/github
          #url: https://github.com/smith-lab
      prospective:
        title: Prospective Members
        text: Interested in joining our lab? We're always looking for motivated researchers at all levels.
        button:
          text: View Open Positions
          url: /opportunities
      map_url: https://maps.google.com/?q=University+of+Excellence
      show_form: false
    design:
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
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
