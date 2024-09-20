
---
# Leave the homepage title empty to use the site title
title: seoharu.github.io
date: 2024-09-01
type: landing

sections:

  - block: about
    content:
      title: "<span style='font-size:70%, font-family: \"Dancing Script\", cursive;'>seoharu.github.io</span>"
      text: <br><span style="font-size:125%">최서연의 홈페이지에 오신 것을 환영합니다.</span> <br><br>
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
        content: <span style="font-size:70%">Medical AI 연계 전공 및 관련 랩실 학부연구생<span style="font-size:70%">
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Project</span>
        content: <span style="font-size:70%">여러 프로젝트 및 연구 진행</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Litmus Renewal Project 등 여러 개발에 참여</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Activity</span>
        content: <span style="font-size:70%">교환학생 등 다양한 활동</span>
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
      text: 저는 좋아하는 것들로 일상을 채우고, 발전하고 싶어하는 사람입니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">Medical AI 분야 위주로, 특히 뇌공학 분야에 AI 기술 적용해 뇌의 여러 비밀을 밝혀내고 싶습니다.</span><br><br>
        - name: 데이터 분석 (Data Science)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">여러 분야의 데이터를 분석하고 모델링하는 것에 관심 있습니다.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">여러 개발 프로젝트에 참여했습니다.</span><br><br>
        - name: Medical AI
          icon: connection
          icon_pack: fab
          description:  <span style="font-size:90%">메디컬AI 연게 전공을 하고 있고 관련 랩실에서 학부 연구생으로 있습니다.</span><br><br>
        - name: ALPS 부회장
          icon: 🖥️
          icon_pack: fab
          description:  <span style="font-size:90%">ALPS 부회장으로, Litmus Renewal Project에 참여했습니다.</span><br><br>
        - name: etc
          icon: globe
          icon_pack: fab
          description:  <span style="font-size:90%">교환학생, 동아리 부회장 등 여러 다양한 경험을 했습니다.</span><br><br>



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
        {{% cta cta_link="./contact/" cta_text="더 알아보기 →" %}}
    design:
      columns: '1'
---


