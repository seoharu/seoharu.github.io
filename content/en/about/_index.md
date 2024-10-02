---
title: "about"
date: 2024-09-20
type: landing
description: "CHOI SEOYEON's homepage to study medical AI and computer engineering"
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
        Since I was young, I have been interested in medicine, especially the brain and cranial nerves. I entered the computer engineering department of Jeonbuk National University with the idea that I should first learn computer engineering and artificial intelligence to study the brain, and I am learning the whole of medicine, medicine, and computer engineering while taking classes in the departments of computer engineering and biomedical engineering. I enjoy creating complex things by connecting and converging across fields. I want to explore the brain by researching medicine and engineering in general, medicine engineering, and brain engineering by converging medical and engineering. I am also interested in researching brain nerve modeling in the field of medical artificial intelligence, especially in the field of brain computer interface, and in the field of deep neural networks. </span>
        

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


