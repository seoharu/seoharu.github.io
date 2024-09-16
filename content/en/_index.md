---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

sections:

  - block: features
    content:
      title: "<span class='dancing-script'>seoharu.github.io</span>"
      text: <br><span style="font-size:125%">Welcome to SEOYEON's Page!</span> <br><br>
        {{% cta cta_link="./about/" cta_text="더 알아보기 →" %}}


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">About</span>
        content: <span style="font-size:70%">Interested in SEOYEON?</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Contact</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">Medical AI</span>
        content: <span style="font-size:70%">joint major - Medical AI & undergraudate student researcher in MACS<span style="font-size:70%">
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Project</span>
        content: <span style="font-size:70%">Multiple projects and research in progress</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Participated in several developments, including the Litmus Renewal Project</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Activity</span>
        content: <span style="font-size:70%">Exchange student and more</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">My Interests</span>
      text: I'm all about fun and progression.<br><br><br><br>
      items:
        - name: AI
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">Focused on Medical AI.</span><br><br>
        - name: Data Science
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">Analyzing and modeling data from multiple disciplines</span><br><br>
        - name: Development
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Working on multiple development projects.</span><br><br>
        - name: Medical AI
          icon: laptop-medical
          icon_pack: fab
          description:  <span style="font-size:90%">I am particularly interested in the field of neuroscience.</span><br><br>
        - name: ALPS 부회장
          icon: laptop-code
          icon_pack: fab
          description:  <span style="font-size:90%">the Vice President of ALPS & Participated in the Litmus Renewal Project.</span><br><br>
        - name: etc
          icon: globe
          icon_pack: fab
          description:  <span style="font-size:90%">Former UM Exchange Student.</span><br><br>


  - block: collection
    content:
      title: Project
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - side
          - course
          - collaborate
      offset: 0
      order: desc
      page_type: 
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: collection
    content:
      id: section-2
      title: Personal
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - event
          - etc
          - Blog
    design:
      view: community/custom_card
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="MORE →" %}}
      position: center
    design:
      columns: '1'
---