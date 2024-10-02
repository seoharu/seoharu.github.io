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
        I have been interested in medicine, especially the brain and cranial nerves, since I was a child. I enrolled in the Department of Computer Science at Chonbuk National University with the idea of learning computer science and artificial intelligence in order to study the brain, and I have been taking classes in the Department of Computer Science and Biomedical Engineering to learn about medicine, medical engineering, and computer science in general. I enjoy connecting and fusing multiple fields to create something complex, and I would like to explore the brain by studying medical engineering and brain engineering by fusing medicine and engineering. In the field of medical artificial intelligence, I am also interested in brain engineering and brain neurology, especially brain neural modeling in the field of brain computer interface and deep neural network to interpret the mechanism of the brain. </span>
        

  - block: features
    content:
      title: "Interests"
      items:
        - name: "Medical, Medical Science & Engineering"
          icon: notes-medical
          icon_pack: fas
        - name: "Medical AI & Brain"
          icon: brain
          icon_pack: fas
        - name: "AI"
          icon: laptop
          icon_pack: fas
        - name: "Data Science"
          icon: chart-line
          icon_pack: fas
        - name: "Development"
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
        - title: Integrated B.S. - M.S. in Division of Electronics and Information Engineering (Computer Science Major)
          description: JBNU (Integrated B.S. - M.S.)
          date_start: '2025-09-02'
          date_end: '2027-02-28'
        - title: B.S. in (Division of Computer Science and Engineering)
          description: JBNU - Division of Computer Science and Engineering
          date_start: '2022-03-02'
          date_end: '2025-08-31'

  - block: tag_cloud
    content:
      title: My tags
      subtitle: ''
      text: You can see which tags were used most often.
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0

---


