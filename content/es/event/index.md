---
title: Event
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Event page
          content: mostrar mis números recientes
          align: center
          background:
            image:
              caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: ''
              fit: cover
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Language
          content: |-
            Estoy aprendiendo español estos días. <br> I am also studying English. <br> Of course, Java.   
            <div style="text-align: left; margin-bottom: 5px;">
                Image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
            </div> 
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: 'lang.jpg'
              description: 'Image credit: [**Unsplash**](https://unsplash.com/)'
              filters:
                opacity: 0.8     # 이미지의 투명도를 조절
                brightness: 0.7
                
            position: right
            color: '#555'
            
        - title: Concert
          content: |-
            2023.02.05 : 2022 YOUNHA CONCERT C 2022YH <br>
            2024.02.07 : TAYLOR SWIFT THE ERAS TOUR (at) Tokyo Dome <br>
            2024.11.16 : LOVELYZ CONCERT <br>
            2024.11.17 : 2024 YOUNHA CONCERT GROWTH THEORY <br>
                <div style="text-align: left; margin-bottom: 5px;">
                    Image credit: <a href="https://unsplash.com/" target="_blank"><strong>Unsplash</strong></a>
                </div> 
          align: right
        
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: 'concert.png'
              caption: 'Image credit: blog'
              filters:
                brightness: 0.5
            position: center
            color: '#333'
            
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000



---
