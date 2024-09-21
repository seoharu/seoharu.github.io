---
title: ""
date: 2024-09-20
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
      
    design:
      background:
        color: blue

  - block: markdown
    content:
      title: About me
      text: |-
        어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 의학과 공학의 결합으로 의공학, 뇌공학 전반을 연구하는 삶을 살고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다.
        

  - block: features
    content:
      title: "Interests"
      items:
        - name: "인공지능 (AI)"
          icon: code-branch
          icon_pack: fas
        - name: "Data Science"
          icon: database
          icon_pack: fas
        - name: "개발 (Development)"
          icon: laptop
          icon_pack: fas
        - name: "의학, 의공학"
          icon: brain
          icon_pack: fas
        - name: "Medical AI & Brain"
          icon: laptop-medical
          icon_pack: fas
        - name: "Algorithm"
          icon: folder-tree
          icon_pack: fas

    design:
      columns: '1'

  - block: skills
    content:
      title: Languages & Technologies
      text: ''
      username: admin
      css_style: |
        #section-skills > .col-md-6 {
        display: block !important;
        width: 100% !important;  
        margin-bottom: 20px !important; 
        }
          
    design:
        columns: '1'

  - block: skills
    content:
      title: Language
      text: ''
      username: admin2

    design:
      columns: 1

  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     subtitle: 
  #     # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  #     filters:
  #       # Folders to display content from
  #       folders:
  #         - project
  #       # Only show content with these tags
  #       tags: []
  #       # Exclude content with these tags
  #       exclude_tags: []
  #       # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
  #       kinds:
  #         - page
  #     # Field to sort by, such as Date or Title
  #     sort_by: 'tag'
  #     sort_ascending: false
  #     # Default portfolio filter button
  #     # 0 corresponds to the first button below and so on
  #     # For example, 0 will default to showing all content as the first button below shows content with *any* tag
  #     default_button_index: 0
  #     # Filter button toolbar (optional).
  #     # Add or remove as many buttons as you like.
  #     # To show all content, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the button toolbar, delete the entire `buttons` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Liitmus Renewal Project
  #         tag: collaborate
  #         link: 'https://litmus.jbnu.ac.kr/'
  #       - name: 인공지능 전공 특화 교육 개인 프로젝트 - 'DATA-AI'
  #         tag: side
  #         link: 'https://github.com/seoharu/DATA-AI'
  #       - name: 3D 공간정보 모델링 프로젝트 참여 
  #         tag: collaborate
  #       - name: [24-2 WSD] Github pages로 개인 소개 웹사이트 (포폴) 만들기
  #         tag: course
  #         link: 'https://seoharu.github.io/'
  #       - name: [24-2 캡스톤] 전공과제 - 인공지능 학습 데이터셋 구축을 위한 지능형 온라인 레이블 툴 제작
  #         tag: course
  #       - name: MRI 영상 기반 암 진단 자동화를 위한 segmentation 모델 연구개발
  #         description: |- 
  #           MIL Mentoring 참여 - (1) 위 데이터셋을 사용한 medical image segmentation 기존연구(논문) 조사, (2) 최신 segmentation 모델 조사, (3)기존 모델 변경 및 성능 비교
  #         tag: side
  #   content:
  #     title: Activities
  #     subtitle: 
  #     # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
  #     filters:
  #       # Folders to display content from
  #       folders:
  #         - project
  #       # Only show content with these tags
  #       tags: []
  #       # Exclude content with these tags
  #       exclude_tags: []
  #       # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
  #       kinds:
  #         - page
  #     # Field to sort by, such as Date or Title
  #     sort_by: 'tag'
  #     sort_ascending: false
  #     # Default portfolio filter button
  #     # 0 corresponds to the first button below and so on
  #     # For example, 0 will default to showing all content as the first button below shows content with *any* tag
  #     default_button_index: 0
  #     # Filter button toolbar (optional).
  #     # Add or remove as many buttons as you like.
  #     # To show all content, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the button toolbar, delete the entire `buttons` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: ALPS (ALgorithm & Programming Study group) 부회장
  #         tag: club
  #         link: 'https://sites.google.com/view/jbnu-alps'
  #       - name: HRC (우수학생 기숙형대학) 선발, 활동
  #         tag: club
  #       - name: 2차년도 MIT-Harvard Scientist Online Program & 2차년도 Harvard Medical School Bio-Science Online Program 참여
  #         tag: activity
  #       - name: 2022 동계 자기설계 도전활동 공모전 참여
  #         tag: activity
  #       - name: AUEA 교환학생 파견 @ Malaysia UM
  #         tag: activity
  #         description: 해외교환학습, 해외인턴십과정 (23-1학기)
  #       - name: 각종 교육, 특강, 캠프 참여
  #         description : 딥러닝 컴퓨터비전 교육, 파이썬 인공지능 코딩 특강, 
  #         tag: education
  #       - name: 2023년 동계 빅데이터 캠프 [딥러닝의 세계, 머신러닝의 미래] 참여, 수상
  #         description: AWS 실습 교육 및 딥레이서 경진대회 참여, 동상 수상
  #         tag: awards
  #       - name: 침해사고 대응훈련 - 스피어피싱 대응 기본, 심화 교육
  #         description: 2023 실전형 사이버훈련장 KISA
  #         tag: education
  #       - name: 2023 TBM 창업캠프 참여
  #         description: 
  #         tag: activity


  #   design:
  #     # See Page Builder docs for all section customization options.
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     # Choose a listing view
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: true

  - block: features
    content:
      title: Hobbies
      items:
        - name: 독서
        - name: 악기 연주
          description: 피아노, 바이올린, 드럼
        - name: 전시회 및 공연 관람
        - name: 사진 촬영
          description: 바다, 하늘 등 풍경 사진 찍기
    design:
      columns: 2
  - block: features
    content:
      title: Favorites
      items:
        - name: Cat
  
  - block: experience
    content:
      title: Education
      items:
        - title: M.S. in 전자.정보공학부(컴퓨터공학전공)
          description: 전북대학교 (학석사 연계 과정)
          date_start: '2025-09-02'
          date_end: '2027-02-28'
        - title: B.S. in (컴퓨터공학부)
          description: 전북대학교 (JBNU) 컴퓨터공학부
          date_start: '2022-03-02'
          date_end: '2025-08-31'



---

<!-- 
---
# 홈페이지 제목을 사이트 제목으로 사용하려면 비워두세요
title: ""

date: 2024-09-20
type: landing

design:
  # 기본 섹션 간격
  spacing: "6rem"


---
# Display name
title: seoharu.github.io

# Name pronunciation (optional)
name_pronunciation: 최서연

# Full name (for SEO)
first_name: SEOYEON
last_name: CHOI

# Status emoji
status:
  icon: 💻

authors:
  - admin
  
# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Student
position: Undergraduate research student

# Organizations/Affiliations to show in About widget
organizations:
  - name: JBNU - Division of Computer Science and Engineering
    url: https://csai.jbnu.ac.kr/csai/index.do
affiliations:
  - name: MACS
    url: https://jbnu.macs.or.kr/
major: 컴퓨터공학
joint_major: 메디컬AI

# Short bio (displayed in user profile at end of posts)
bio: 컴퓨터공학부 학부생이자 메디컬AI 연계전공생입니다. 관련 연구실에서 학부연구생으로 있으면서, 메디컬AI 분야의 연구와 프로젝트를 진행하고 있습니다. 좋아하는 것들로 일상을 채우고 발전하려 끊임없이 노력합니다. 

interests:
  - 인공지능 (AI)
  - 데이터 분석 (Data Science)
  - 개발 (Development)
  - 의학, 의공학
  - Medical AI & Brain
  - Global

education:
  courses:
    - course: M.S. in (전자.정보공학부(컴퓨터공학전공))
      institution: 전북대학교 (학석사 연계 과정)
      year: 2025.09 ~ 2027.02 (예정)
    - course: B.S. in (컴퓨터공학부)
      institution: 전북대학교
      year: 2022 ~ 진행 중 (2025.09 졸업 예정)

skills:
  items:
    - name: 데이터 분석 및 모델링
      description: ''
      percent: 50
      icon: chart-bar
    - name: Front-end
      description: ''
      percent: 40
    - name: Back-end
      description: ''
      percent: 10
    - name: AI
      description: ''
      percent: 30
languages:
  - name: programming
    items: 
      - name: Basic Language
        description: C, C++, Python
      - name: Web-oriented Language
        description: Javascript, TypeScript
  - name: frameworks
    items:
      - name: Deep learning frameworks
        desctription: Python (Tensorflow, pytorch), C++ (CUDA)
      - name: Web frameworks
        description: Vue.js
  - name: DBMS
    items: 
      - name: SQL
        description: MySQL, MongoDB
  - name: AWS
    
  - name: lingual
    items:
      - name: Korean
        description: Native
      - name: English
        description: Academic (studying one semester as exchange students in Malaysia)
      - name: Espanol
        description: daily conversation 

hobbys:
  items:
    - name: 독서
      description: ''
    - name: 악기
      description: 피아노, 바이올린 and 드럼
    - name: 전시회, 공연 감상
    - name: 사진

favorites:
  items:
    - name: Cat
    - name: 


# Social Networking
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:yunseul@jbnu.ac.kr'
    label: E-mail Me
  - icon: github
    url: https://github.com/seoharu
    label: github
  # Link to a PDF of your resume/CV - upload it to `static/uploads/resume.pdf`
  # - icon: academicons/cv
  #   url: uploads/resume.pdf
  #   label: Download my resume
  # - icon: rss
  #   url: ./post/index.xml
  #   label: Subscribe to my blog via RSS feed

# Highlight the author in author lists? (true/false)
highlight_name: true

user_groups:
  - admin

# Author's website URL
website: "https://seoharu.github.io/"
---

어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 의학과 공학의 결합으로 의공학, 뇌공학 전반을 연구하는 삶을 살고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다.


sections:
  - block: features
    content:
      title: Profile
      # 표시할 사용자 프로필 선택 (`content/authors/` 내 폴더명)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: white

        image:
          # `assets/media/`에 배경 이미지를 추가하세요.
          # filename: a.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  
        

    design:
      # 레이아웃 보기 선택
      view: date-title-summary
      # 간격 줄이기
      spacing:
        padding: [0, 0, 0, 0]

  - block: collection
    content:
      id: section-1
      title: hobbies
      filters:
        folders:
          - name: 독서
            description: ""
          - name: 악기
            description: 피아노, 바이올린, 그리고 드럼
          - name: 전시회, 공연 감상
            descriptipn: ""
          - name: 사진
            description: 바다, 하늘 등 풍경 사진 찍기 
  - block: collection
    content:
      id: section-2
      title: hobbies
      filters:
        folders:
          - name: "Cat"
            description: ""

  # - block: cta-card
  #   demo: true # Hugo Blox Builder 데모 사이트에서만 이 섹션을 표시
  #   content:
  #     title: "👉 이와 같은 학술 웹사이트를 만들어 보세요"
  #     text: |-
  #       이 사이트는 250,000명 이상의 학자들이 신뢰하는 무료 Hugo 기반 오픈소스 웹사이트 빌더인 Hugo Blox Builder로 생성되었습니다.

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="GitHub에서 HugoBlox/hugo-blox-builder에 Star를 주기">Star</a>

  #       블록으로 쉽게 구축하세요 - 코딩 필요 없음!

  #       랜딩 페이지, 세컨드 브레인, 코스에서 학술 이력서, 컨퍼런스, 기술 블로그까지 모두 구축 가능합니다.
  #     button:
  #       text: "시작하기"
  #       url: "https://hugoblox.com/templates/"
    design:
      card:
        # 카드 배경 색상 (CSS 클래스)
        css_class: "bg-primary-700"
        css_style: ""
--- -->