---
title: "about"
date: 2024-09-20
type: landing
description: "Página web de Seoyeon Choi, que estudia Inteligencia Artificial médica e informática."
keywords: ["CHOI SEOYEON", "Medical AI", "Computer Science", "JBNU"]
draft: false
# Full name (for SEO)
first_name: SEOYEON 최서연
last_name: CHOI

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
      
    design:
      background:
        color: #dfdfe6

  - block: markdown
    content:
      title: About me
      text: |- 
        <span class="justified-text">
        어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 전북대학교 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 그중에서도 의학과 공학을 융합해 의공학, 뇌공학 전반을 연구하며 뇌를 탐구하고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다. </span>
        

  - block: features
    content:
      title: "Interests"
      items:
        - name: "의학, 의공학"
          icon: notes-medical
          icon_pack: fas
        - name: "Medical AI & Brain"
          icon: brain
          icon_pack: fas
        - name: "인공지능 (AI)"
          icon: laptop
          icon_pack: fas
        - name: "Data Science"
          icon: chart-line
          icon_pack: fas
        - name: "개발 (Development)"
          icon: laptop-code
          icon_pack: fas
        - name: "Algorithm"
          icon: sitemap
          icon_pack: fas

    design:
      columns: '1'

  - block: skills
    content:
      title: Languages & Technologies
      text: ''
      username: admin
      css_style: |
        #section-skills > .col-12 {
          display: flex;
          flex-wrap: wrap;
          width: 100%;
          justify-content: flex-start;
        } 
        
        #section-skills .row {
          display: flex;
          flex-direction: column;
        }
        #section-skills .col-12 .col-md-6 {
          flex-direction: column;
          flex: 0 0 25%;
        }
        .skills-content {
          margin-left: 30px;
          margin-right: 30px;
        }
        .skills-wrapper {
          border: 1px solid #00E5E5;
        }
        .skills-percent {
          background-color: #00FFFF;

        }
          
    design:
        columns: '1'

  - block: skills
    content:
      title: Skills
      text: ''
      username: admin2
      css_style: |
        #section-skills > .col-12 {
          display: flex;
          flex-wrap: wrap;
          width: 100%;
          justify-content: flex-start;
        } 
        
        #section-skills .row {
          display: flex;
          flex-direction: column;
        }
        #section-skills .col-12 .col-md-6 {
          display: flex;
          flex: 0 0 50%;
        }
        .skills-content {
          margin-left: 30px;
          margin-right: 30px;
        }
        .skills-wrapper {
          border: 1px solid #00E5E5;
        }
        .skills-percent {
          background-color: #00FFFF;

        }

    design:
      columns: 1

  - block: collection
    content:
      id: section-1
      title: Various Activities
      subtitle:
      text:
      count: 60
      offset: 0
      order: desc
      filters:
        folders:
          - collaborate
          - researchproject
          - course
    design:
      view: card
      columns: '2'


  - block: features
    content:
      title: Favorites
      items:
        - name: Cat
          icon: cat
          icon_pack: fas
        - name: Book
          icon: book-bookmark
          icon_pack: fas
        - name: Music
          icon: guitar
          icon_pack: fas

        - name: Photography
          icon: camera-retro
          icon_pack: fas
        - name: Coffee & Tea
          icon: mug-saucer
          icon_pack: fas
        - name: Whiskey
          icon: whiskey-glass
          icon_pack: fas

    design:
      columns: 2

  
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

  - block: tag_cloud
    content:
      title: My tags
      subtitle: ''
      text: 어떤 태그들을 주로 사용했는지 확인할 수 있습니다.
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0

---


