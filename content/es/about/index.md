---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

# Display name
title: CHOI SEOYEON

# Full Name (for SEO)
first_name: SEOYEON
last_name: CHOI

# Username (this should match the folder name)
# authors:
#   - admin 

# Is this the primary user of the site?
superuser: true

# Role/position
role: student

# Organizations/Affiliations
organizations:
  - name: JEONBUK NATIONAL UNIVERSITY - Division of Computer Science and Engineering
    url: 'https://csai.jbnu.ac.kr/csai/index.do'
Affiliation:
  - name: JBNU-MACS (MacsLAB)
    url: 'https://jbnu.macs.or.kr'
Major:
  - name: Computer Science and Engineering
Joint Major:
  - name: Medical AI

# Short bio (displayed in user profile at end of posts)
bio: I am an undergraduate in computer science and studying medical AI as a joint major. I am working as an undergraduate research student in a related lab and conducting research and projects in the field of medical AI. I constantly try to fill my daily life with what I like and develop.

interests:
  - AI
  - Data Science
  - Development
  - Medical AI & Brain

education:
  courses:
    - course: M.S. in (Electronics and Information Engineering Department (Computer Engineering Major))
      institution: JEONBUK NATIONAL UNIVERSITY (integrated B.S & M.S)
      year: 2025.09 ~ 2027.02 (plan)
    - course: B.S. in (Division of Computer Science and Engineering)
      institution: JEONBUK NATIONAL UNIVERSITY
      year: 2022 ~ ing (Expected to graduate in 2025.09)

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

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
# user_groups:
#   - admin 


---

In the applications of medical artificial intelligence, i'm interested in the brain engineering cranial nerves, especially cranial neural modeling in the brain computer interface, and the study of interpreting the mechanisms of the brain in the field of deep neural networks.

sections:

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
        content: <span style="font-size:70%">joint major - Medical AI & undergraduate student researcher in MACS<span style="font-size:70%">
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Project</span>
        content: <span style="font-size:70%">Multiple projects and research in progress</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Participated in several developments, including the Litmus Renewal Project</span>
        align: center
        background:
          image:
            filename: 
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Activity</span>
        content: <span style="font-size:70%">Exchange student and more</span>
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