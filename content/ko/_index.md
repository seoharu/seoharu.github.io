---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

sections:

  - block: features
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

      - title: <span style="font-size:70%">Bio</span>
        content: <span style="font-size:70%">Major - 컴퓨터공학부<br> Joint Major - 메디컬AI 연계전공</span>
        align: center
        background:
          image:
            filename: medical.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        

      - title: <span style="font-size:70%">Medical AI</span>
        content: <span style="font-size:70%">Medical AI 연계 전공 및 관련 랩실 학부연구생<span style="font-size:70%">
        align: center
        background:
          image:
            filename: lab.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: labtop-medical
          icon_pack: fas
          text: <span style="font-size:60%">MacsLAB</span>
          text-color: '#000'
          url: https://jbnu.macs.or.kr/

      - title: <span style="font-size:70%">Project</span>
        content: <span style="font-size:70%">여러 프로젝트 및 연구 진행</span>
        align: center
        background:
          image:
            filename: project.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Litmus Renewal Project 등 여러 개발에 참여</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Activity</span>
        content: <span style="font-size:70%">교환학생 등 다양한 활동</span>
        align: center
        background:
          image:
            filename: malaysia.jpg
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
          icon: laptop-medical
          icon_pack: fas
          description:  <span style="font-size:90%">메디컬AI 연게 전공을 하고 있고 관련 랩실에서 학부 연구생으로 있습니다.</span><br><br>
        - name: ALPS 부회장
          icon: laptop-code
          icon_pack: fas
          description:  <span style="font-size:90%">ALPS 부회장으로, Litmus Renewal Project에 참여했습니다.</span><br><br>
        - name: etc
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">교환학생, 동아리 부회장 등 여러 다양한 경험을 했습니다.</span><br><br>



  - block: collection
    content:
      id: section-1
      title: Projects
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - side
          - course
          - collaborate
      page_type: 
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: portfolio
    id: projects
    content:
      title: "Projects"
      subtitle: "Explore my work and collaborations"
      filters:
        folders:
          - project
        tags: []
        exclude_tags: []
        kinds:
          - page
      sort_by: 'tag'
      sort_ascending: false
      default_button_index: 0
      buttons:
        - name: "All"
          tag: '*'
        - name: "Liitmus Renewal Project"
          tag: collaborate
          link: 'https://litmus.jbnu.ac.kr/'
        - name: "인공지능 전공 특화 교육 개인 프로젝트 - 'DATA-AI'"
          tag: side
          link: 'https://github.com/seoharu/DATA-AI'
        - name: "3D 공간정보 모델링 프로젝트 참여"
          tag: collaborate
        - name: "[24-2 WSD] Github Pages 개인 소개 웹사이트"
          tag: course
          link: 'https://seoharu.github.io/'
        - name: "[24-2 캡스톤] 전공과제 - 인공지능 학습 데이터셋 구축"
          tag: course
        - name: "MRI 영상 기반 암 진단 자동화 연구"
          description: "MIL Mentoring 참여: medical image segmentation 모델 개발"
          tag: side
    design:
      columns: '3'
      view: showcase
      flip_alt_rows: true


  - block: portfolio
    id: activity
    content:
      title: Activities
      subtitle: 
      # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      filters:
        # Folders to display content from
        folders:
          - activity
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'tag'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: ALPS (ALgorithm & Programming Study group) 부회장
          tag: club
          link: 'https://sites.google.com/view/jbnu-alps'
        - name: HRC (우수학생 기숙형대학) 선발, 활동
          tag: club
        - name: 2차년도 MIT-Harvard Scientist Online Program & 2차년도 Harvard Medical School Bio-Science Online Program 참여
          tag: activity
        - name: 2022 동계 자기설계 도전활동 공모전 참여
          tag: activity
        - name: AUEA 교환학생 파견 @ Malaysia UM
          tag: activity
          description: 해외교환학습, 해외인턴십과정 (23-1학기)
        - name: 각종 교육, 특강, 캠프 참여
          description : 딥러닝 컴퓨터비전 교육, 파이썬 인공지능 코딩 특강, 
          tag: education
        - name: 2023년 동계 빅데이터 캠프 [딥러닝의 세계, 머신러닝의 미래] 참여, 수상
          description: AWS 실습 교육 및 딥레이서 경진대회 참여, 동상 수상
          tag: awards
        - name: 침해사고 대응훈련 - 스피어피싱 대응 기본, 심화 교육
          description: 2023 실전형 사이버훈련장 KISA
          tag: education
        - name: 2023 TBM 창업캠프 참여
          description: 
          tag: activity
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true

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
      css_style: "text-align: center;"

---