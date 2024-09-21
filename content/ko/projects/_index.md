---
title: My page
type: landing

sections:
  - block: portfolio
    id: projects
    content:
    title: Projects
    subtitle: 
    # text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    filters:
    # Folders to display content from
    folders:
        - project
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
        - name: Liitmus Renewal Project
          tag: collaborate
          link: 'https://litmus.jbnu.ac.kr/'
        - name: 인공지능 전공 특화 교육 개인 프로젝트 - 'DATA-AI'
          tag: side
          link: 'https://github.com/seoharu/DATA-AI'
        - name: 3D 공간정보 모델링 프로젝트 참여 
          tag: collaborate
        - name: [24-2 WSD] Github pages로 개인 소개 웹사이트 (포폴) 만들기
          tag: course
          link: 'https://seoharu.github.io/'
        - name: [24-2 캡스톤] 전공과제 - 인공지능 학습 데이터셋 구축을 위한 지능형 온라인 레이블 툴 제작
          tag: course
        - name: MRI 영상 기반 암 진단 자동화를 위한 segmentation 모델 연구개발
          description: |-
            MIL Mentoring 참여 - (1) 위 데이터셋을 사용한 medical image segmentation 기존연구(논문) 조사, (2) 최신 segmentation 모델 조사, (3)기존 모델 변경 및 성능 비교
          tag: side
    
---