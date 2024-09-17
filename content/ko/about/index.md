---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

---
# Display name
title: 최서연

# Full Name (for SEO)
first_name: SEOYEON
last_name: CHOI

<!-- # Username (this should match the folder name)
authors:
  - admin -->

# Is this the primary user of the site?
superuser: true

# Role/position
role: student

# Organizations/Affiliations
organizations:
  - name: 전북대학교 컴퓨터공학부
    url: 'https://csai.jbnu.ac.kr/csai/index.do'
Affiliation:
  - name: JBNU-MACS (의료인공지능 및 계산과학 연구실)
    url: 'https://jbnu.macs.or.kr'
Major:
  - name: 컴퓨터공학부
Joint Major:
  - name: 메디컬AI

# Short bio (displayed in user profile at end of posts)
bio: 컴퓨터공학부 학부생이자 메디컬AI 연계전공생입니다. 관련 연구실에서 학부연구생으로 있으면서, 메디컬AI 분야의 연구와 프로젝트를 진행하고 있습니다. 좋아하는 것들로 일상을 채우고 발전하려 끊임없이 노력합니다. 

interests:
  - 인공지능 (AI)
  - 데이터 분석 (Data Science)
  - 개발 (Development)
  - Medical AI & Brain
  - 책과 커피, 위스키
  - 여행

education:
  courses:
    - course: M.S. in (전자.정보공학부(컴퓨터공학전공))
      institution: 전북대학교 (학석사 연계 과정)
      year: 2025.09 ~ 2027.02 (예정)
    - course: B.S. in (컴퓨터공학부)
      institution: 전북대학교
      year: 2022 ~ 진행 중 (2025.09 졸업 예정)

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:yunseul@jbnu.ac.kr'

  - icon: cv
    icon_pack: ai
    <!-- link:  -->
  - icon: github
    icon_pack: github
    link: https://github.com/seoharu
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: 'yunseul@jbnu.ac.kr'

# Highlight the author in author lists? (true/false)
highlight_name: true
<!-- 
# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - admin -->


---

의료인공지능의 응용 영역에서도 뇌공학 뇌신경 쪽 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다.

sections:

  <!-- - block: features
    content:
      title: "<span style='font-size:70%, font-family: \"Dancing Script\", cursive;'>seoharu.github.io</span>"
      text: <br><span style="font-size:125%">최서연의 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./about/" cta_text="더 알아보기 →" %}} -->


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
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000