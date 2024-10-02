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
          Soy un estudiante de pregrado en Ciencias de la Computación e Ingeniería, y estoy estudiando Medical AI como una especialización conjunta. Como investigador universitario en el laboratorio de IA médica, llevo a cabo investigaciones y proyectos en el campo de la IA médica. Intento llenar mi vida de cosas que me gustan y me esfuerzo constantemente por hacer lo que quiero. Quiero convertirme en un experto en el campo de la inteligencia artificial médica, especialmente en el campo de las redes neuronales.
        </span> <br><br>
        {{% cta cta_link="./about/" cta_text="Más información →" 
        class="justified-cta" %}}

  - block: slider
    content:
      slides:
      - title: <span style="font-size:90%;">Home</span>
        content: |- 
          <span style="font-size:70%"> Bienvenido a la página de SEOYEON [seoharu.github.io]!
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
          <span style="font-size:70%">Un resumen del menú de la página de inicio, submenús. <br> image credit: photo by me </span>
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
          <span style="font-size:70%">Acerca de mi trabajo como estudiante de investigación en el laboratorio de Inteligencia Artificial Médica y mis intereses de investigación. <br>
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
          <span style="font-size:70%">Investigadores universitarios en el Laboratorio de Inteligencia Artificial Médica <br> image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a> </span>
        align: center
        background:
          image:
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
          <span style="font-size:70%">Aquí encontrarás un vistazo a mis proyectos personales, docentes y de colaboración centrados en el desarrollo, la ciencia de datos y la IA médica. <br>
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
          <span style="font-size:70%">Puedes echar un vistazo a mis actividades y experiencias, incluida la de estudiante de intercambio.  <br> image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a> </span>
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
          <span style="font-size:70%">En [Event], he enumerado los acontecimientos actuales, y en [ETC], he enumerado algunas de mis cosas favoritas. <br> En [Blog], he sacado algunas de las entradas de mi blog. <br> image credit: photo by me  </span>
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
          <span style="font-size:70%">Interested in SEOYEON? <br> image credit: photo by me </span>
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


  - block: collection
    content:
      title: Project
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - side
          - course
          - collaborate
      offset: 0
      order: desc
      page_type: 
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: collection
    content:
      id: section-2
      title: Personal
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - event
          - etc
          - Blog
    design:
      view: community/custom_card
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="MAS →" %}}
      position: center
    design:
      columns: '1'
---