---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

sections:

  - block: features
    content:
      title: "<span style='font-size:70%, font-family: \"Dancing Script\", cursive;'>seoharu.github.io</span>"
      text: |
        <br><span class="justified-text">
          I am an undergraduate student in the Computer Science and Engineering, and I am studying Medical AI as an joint major. As an undergraduate researcher in the Medical AI lab, I am conducting research and projects in the field of Medical AI. I try to fill my life with things I love to do and constantly push myself to do what I want to do. I want to become an expert in the field of medical artificial intelligence, especially in the field of neural networks.
        </span> <br><br>
        {{% cta cta_link="./about/" cta_text="more about →" 
        class="justified-cta" %}}

  - block: slider
    content:
      slides:
      - title: <span style="font-size:90%;">Home</span>
        content: |- 
          <span style="font-size:70%"> 최서연의 홈페이지 [seoharu.github.io]에 오신 것을 환영합니다!
          <br> image credit: photo by me </span>
        align: center
        background:
          image:
            filename: me.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: house-user
          icon_pack: fas
          text: <span style="font-size:60%">Preview</span>
          text-color: '#000'
          url: 'https://seoharu.github.io/'
      - title: <span style="font-size:90%;">About</span>
        content: |-
          <span style="font-size:70%">A summary of the homepage menu, submenus. 
          <br> image credit: photo by me </span>
        align: center
        background:
          image:
            filename: me.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: address-card
          icon_pack: fas
          text: <span style="font-size:60%">About</span>
          text-color: '#000'
          url: about

      - title: <span style="font-size:90%">Research</span>
        content: |- 
          <span style="font-size:70%">This is about my work and research interests as an undergraduate research student in the Medical AI Lab. <br>
            image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
          </span>
        align: center
        background:
          image:
            filename: medical.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: book-open
          icon_pack: fas
          text: <span style="font-size:60%">Research</span>
          text-color: '#000'
          url: research
        

      - title: <span style="font-size:90%">Medical AI</span>
        content: |- 
          <span style="font-size:70%">Undergraduate Research Student in the Medical AI Lab
          <br>
            image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
          </span>
        align: center
        background:
          image:
            caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
            filename: lab.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: tags
          icon_pack: fas
          text: <span style="font-size:60%">MacsLAB</span>
          text-color: '#000'
          url: https://jbnu.macs.or.kr/

      - title: <span style="font-size:90%">Projects</span>
        content: |- 
          <span style="font-size:70%">Here are some of my personal [Side], course [Course], and collaborative [Collaboration] projects. There are many projects related to development, data science, and medical AI. <br>
            image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
            </span>
        align: center
        background:
          image:
            filename: project.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: laptop
          icon_pack: fas
          text: <span style="font-size:60%">Projects</span>
          text-color: '#000'
          url: projects

      - title: <span style="font-size:90%">Activity</span>
        content: |- 
          <span style="font-size:70%">It's about my extracurricular activities, awards and certifications, and various experiences. <br> Highlights include the AUEA Placement - Malaysia exchange student experience.  <br>
            image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
          </span>
        align: center
        background:
          image:
            filename: malaysia.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: list-check
          icon_pack: fas
          text: <span style="font-size:60%">Activity</span>
          text-color: '#000'
          url: activity

      - title: <span style="font-size:90%;">Personal</span>
        content: |- 
          <span style="font-size:70%">In [Events], I've put current events, and in [ETC], I've put a list of my favorite things. <br> In [Blog], I've pulled some of my blog posts. <br> image credit: photo by me 
          </span>
        align: center
        background:
          image:
            filename: me.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: blog
          icon_pack: fas
          text: <span style="font-size:60%">Personal</span>
          text-color: '#000'
          url: personal
      - title: <span style="font-size:90%;">Contact</span>
        content: |-  
          <span style="font-size:70%">Interested in SEOYEON?
          <br> image credit: photo by me  </span>
        align: center
        background:
          image:
            filename: me.png
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: envelope
          icon_pack: fas
          text: <span style="font-size:60%">Contact!</span>
          text-color: '#000'
          url: Contact
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">My Interests</span>
      text: I'm the kind of person who fills my life with things I love, and I want to grow.<br><br><br><br>
      items:
        - name: Brain, Medical Science
          icon: brain
          icon_pack: fas
          description: <span style="font-size:90%;"> <span class="justified-text"> I'm interested in medical science, biomedical engineering, and the brain in general. </span></span><br><br>
        - name: 인공지능(AI)
          icon: microchip
          icon_pack: fas
          description: <span style="font-size:90%;"> <span class="justified-text"> I think about how we can apply the intuition that happens in the human brain to AI models. </spn></span><br><br>
        - name: Medical AI
          icon: laptop-medical
          icon_pack: fas
          description:  <span style="font-size:90%;"> <span class="justified-text"> In AI, I am interested in Medical AI, especially in the field of neuroscience, where I would like to apply AI technology to uncover the secrets of the brain. I am majoring in Medical AI and working as an undergraduate research student in a related lab. </span></span><br><br>
        - name: Data Science
          icon: chart-line
          icon_pack: fas
          description: <span style="font-size:90%;"><span class="justified-text"> I'm interested in analyzing and modeling data from multiple disciplines. </spn></span><br><br>
        - name: 개발 
          icon: laptop-code
          icon_pack: fas
          description: <span style="font-size:90%;"> <span class="justified-text"> I'm currently working on the Litmus Renewal Project maintenance and development of the Reader test webpage.</span></span><br><br>
        - name: Algorithm
          icon: sitemap
          icon_pack: fas
          description: <span style="font-size:90%;"> <span class="justified-text"> I've been working on the algorithm. </spn></span><br><br>
        - name: Experience
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%;"> <span class="justified-text"> I value experience. I'm interested in many things, so I've had many different experiences, including being an exchange student and vice president of a club.</span> </span><br><br>
        - name: Book
          icon: book
          icon_pack: fas
          description:  <span style="font-size:90%;"> <span class="justified-text"> I love the physicality of books. Reading is more of a routine than a hobby for me.</span> </span><br><br>
        - name: Travel
          icon: passport
          icon_pack: fas
          description:  <span style="font-size:90%;"> <span class="justified-text"> I love to travel. I'd like to visit the Bermuda Triangle, the Serengeti, and other mysterious places, as well as milky way.</span> </span><br><br>

  - block: collection
    content:
      id: section-1
      title: Research Projects
      subtitle:
      text:
      count: 30
      offset: 0
      order: desc
      filters:
        folders:
          - researchproject
          - 
    design:
      view: compact
      columns: '2'

  - block: collection
    content:
      id: section-2
      title: Projects
      subtitle:
      text:
      count: 30
      offset: 0
      order: desc
      filters:
        folders:
          - collaborate
          - side
          - course
    design:
      view: card
      columns: '2'
  

  - block: collection
    content:
      id: section-3
      title: Experiences
      subtitle:
      text:
      count: 30
      offset: 0
      order: desc
      filters:
        folders:
          - activity
    design:
      view: showcase
      columns: '4'
      css_style: "display: math"
        
        
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./about/" cta_text="MORE →" 
        class="justified-cta" %}}
    design:
      columns: '1'
      css_style: "text-align: center;"

---
  