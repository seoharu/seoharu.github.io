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
        - name: "Liitmus Renewal Project"
          tag: development
          link: 'https://litmus.jbnu.ac.kr/'
        - name: "3D 공간정보 모델링 프로젝트 참여"
          tag: modeling
        
    design:
      columns: '3'
      view: showcase
      flip_alt_rows: true

---