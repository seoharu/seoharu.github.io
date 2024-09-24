---
title: My activities
type: landing

sections:
  - block: portfolio
    id: activity
    content:
      title: My acitivites
      subtitle: 여러 활동들 중 교육과 관련된 내용입니다. 
      text: ''
      filters:
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
        - name: AUEA 교환학생 파견
          tag: Global
        - name: 알고리즘 과목 TA 활동
          tag: TA
        - name: ALPS 스터디 C 언어 멘토
          tag: Mentoring
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
---
