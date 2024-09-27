---
title: "Projects"
type: landing

# Listing view
view: community/custom_card

sections:
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
        - name: "Litmus Renewal Project"
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

---
