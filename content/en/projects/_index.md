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
        - name: "Individual project for education specializing in artificial intelligence major - 'DATA-AI'"
          tag: side
          link: 'https://github.com/seoharu/DATA-AI'
        - name: "3D GIS Modeling & Rendering Project"
          tag: collaborate
        - name: "[24-2 WSD] Github Pages Personal WebSite development"
          tag: course
          link: 'https://seoharu.github.io/'
        - name: "[24-2 Capstone] Major Tasks - Building AI Learning Dataset"
          tag: course
        - name: "An MRI Image-Based Automation of Cancer Diagnostics"
          description: "MIL Mentoring 참여: medical image segmentation model development"
          tag: side
    design:
      columns: '3'
      view: showcase
      flip_alt_rows: true

---
