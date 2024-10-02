---
title: "Projects"
type: landing

# Listing view
view: community/custom_card

sections:
  - block: portfolio
    id: Research
    content:
      title: "Research"
      subtitle: "Explore my Research Projects and Fields"
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
        - name: "Anesthesiology-data analysis"
          tag: Medical AI
          link: ''
        - name: "Parathyroid-Label tools"
          tag: Medical AI
          link: ''
        - name: "BCI"
          tag: bci

    design:
      columns: '3'
      view: showcase
      flip_alt_rows: true

---
