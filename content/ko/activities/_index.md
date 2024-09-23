---
title: "Activities"
type: landing


sections:
  - block: portfolio
    id: projects
    content:
      title: Activities
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

---