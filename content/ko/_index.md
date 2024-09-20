---
# 홈페이지 제목을 사이트 제목으로 사용하려면 비워두세요
title: ""

date: 2024-09-20
type: landing

design:
  # 기본 섹션 간격
  spacing: "6rem"

sections:
  - block: about
    content:
      # 표시할 사용자 프로필 선택 (`content/authors/` 내 폴더명)
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: white

        image:
          # `assets/media/`에 배경 이미지를 추가하세요.
          # filename: a.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "📚 About Me"
      subtitle: ""
      text: |-
        어릴 때부터 의학, 특히 뇌와 뇌신경에 관심이 많았습니다. 뇌를 연구하기 위해 우선 컴퓨터공학과 인공지능을 배워야겠다는 생각 하에 컴퓨터공학부에 입학했고, 컴퓨터공학부와 바이오메디컬공학부의 수업을 들으며 의학과 의공학, 컴퓨터공학의 전반을 배우고 있습니다. 여러 분야를 넘나들며 연결짓고 융합해 복합적인 무언가를 만들어내는 것을 즐깁니다. 의학과 공학의 결합으로 의공학, 뇌공학 전반을 연구하는 삶을 살고 싶습니다. 의료인공지능의 응용 영역에서도 뇌공학과 뇌신경 쪽, 특히 뇌 컴퓨터 인터페이스 분야의 뇌신경 모델링과 심층신경망 분야에서 뇌의 메커니즘을 해석하는 연구에 관심 있습니다.

    design:
      # 레이아웃 보기 선택
      view: date-title-summary
      # 간격 줄이기
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-card
    demo: true # Hugo Blox Builder 데모 사이트에서만 이 섹션을 표시
    content:
      title: "👉 이와 같은 학술 웹사이트를 만들어 보세요"
      text: |-
        이 사이트는 250,000명 이상의 학자들이 신뢰하는 무료 Hugo 기반 오픈소스 웹사이트 빌더인 Hugo Blox Builder로 생성되었습니다.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="GitHub에서 HugoBlox/hugo-blox-builder에 Star를 주기">Star</a>

        블록으로 쉽게 구축하세요 - 코딩 필요 없음!

        랜딩 페이지, 세컨드 브레인, 코스에서 학술 이력서, 컨퍼런스, 기술 블로그까지 모두 구축 가능합니다.
      button:
        text: "시작하기"
        url: "https://hugoblox.com/templates/"
    design:
      card:
        # 카드 배경 색상 (CSS 클래스)
        css_class: "bg-primary-700"
        css_style: ""
---
