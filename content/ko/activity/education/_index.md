<!-- ---
title: Activity-Education
type: landing

sections:
  - block: slider
    content:
      slides: 
        - title: 23-1 AUEA 교환학생 파견 
          content: (at) Universiti Malaya(https://www.um.edu.my/student)
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
            #   filename: coders.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: 24-2 알고리즘 과목 TA 활동
          content: 
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
            #   filename: contact.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: 24-1 ALPS 멘토링 C 언어 멘토 
          content: 'Just opened last month!'
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
            #   filename: welcome.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
        #   link:
        #     icon: graduation-cap
        #     icon_pack: fas
        #     text: Join Us
        #     url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
--- -->


---
title: Activity-Education
type: landing

sections:
  - block: portfolio
    id: Education
    content:
      title: Activity - Education
      subtitle: 각종 교육 활동, 특강 참여 내역
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
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
        - name: 23-1 AUEA 교환학생 파견 
          tag: Global
        - name: 24-2 알고리즘 과목 TA 활동
          tag: TA
        - name: 24-1 ALPS 멘토링 C 언어 멘토
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
