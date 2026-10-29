# cinemo-clone

# 🎬 CINEMO (시네모)

> **당신의 다음 장면을 만나는 곳 — 영화 취향 기록 및 프로필 공유 플랫폼**

---

## 📌 1. 프로젝트 소개

- **서비스 명:** CINEMO (시네모)
- **기획 의도:** OTT 플랫폼의 홍수 속에서 사용자가 자신만의 영화 노트를 남기고, 함께 보는 이들의 취향과
  프로필을 가볍게 둘러보며 연결될 수 있는 취향 공유 웹 서비스입니다.
- **핵심 강점 (웹 표준 준수):**
  - **W3C HTML5 유효성 검사(Validator) Error 0개**를 달성한 무결점 마크업 기반의 프로젝트입니다.
  - `sr-only` 기법을 도입하여 시각 장애인을 위한 스크린 리더 표준 접근성을 준수했습니다.
  - SVG 그래픽 최적화를 통해 해상도에 깨짐 없는 고품질 UI를 제공합니다.

<br>

## 👥 2. 팀원 소개 및 담당 업무

| **🥇** | **장소현** <br> (팀장 / Frontend) | • `mypage.html` 마크업 및 스타일링(HTML/CSS) 구현<br>• `index.html`과 `mypage.html` 간의 상호 링크 연동<br> • 프로필 카드 레이아웃 수정 및 SVG 에셋 보정 작업<br>• **W3C 웹 표준 유효성 검사 실행 및 마크업 교정**<br>• 프로젝트 일정 관리 및 PPT 발표 자료 구성 작업 분배 |

| **🥈** | **이소영** <br> (팀원 / Frontend) | • `index.html` 메인 페이지의 전체 구조 마크업 및 레이아웃 구현<br>• 메인 상단 빈공간 보정 및 UI 완성도 향상<br>• 프로필 변경 탭 관련 전용 CSS 및 메인 `body` 오류 수정<br>• 전체 슬라이드 및 화면 구성을 위한 PPT 작업 데이터 수집 |

| **🥉** | **김은지** <br> (팀원 / Frontend) | • 프로젝트 공통 스타일 가이드(`:root` 변수 및 글로벌 초기화) 설정<br>• 메인 상단 인트로 및 핵심 콘텐츠 영역 레이아웃 구조화<br>• 헤더 내비게이션(Nav) 콘텐츠 계층 설계 및 호버(`:hover`) 애니메이션 효과 구현<br>• 웹 접근성을 고려한 언더라인(`underline`) 및 폰트 굵기(`font-weight`) 속성 적용 |

| **🏅** | **이건희** <br> (팀원 / Frontend) | • `index.html` 및 `mypage.html` 헤더(Header) 영역 HTML 구조 설계 및 빈 공간 보정<br>• 메인 레이아웃의 `body` 영역 스타일링 및 디자인 고도화<br>• 메인 페이지와 마이페이지 간의 전반적인 프로필 구조 수정을 통한 일관성 확보<br>• CSS 디버깅 및 전체 프로필 메인 컴포넌트 마크업 구조 최적화 |

| **🏅** | **지민우** <br> (팀원 / Frontend) | • `profile.html` 메인 본문 및 전체 영역 레이아웃 마크업 구조화<br>• 모바일 환경을 고려한 모바일 반응형 / 단독형 페이지 마크업 및 CSS 설계<br>• `profile.html`과 `mypage.html` 간의 원활한 이동을 위한 링크 경로 연결<br>• 페이지 전환 간 UI 흐름 및 컴포넌트 정렬 가이드 작성 |

<br>

## 📂 3. 디렉토리 구조 (Directory Structure)

```cinemo-clone
├── assets/             # 이미지 및 SVG 그래픽 에셋 폴더
├── styles/             # CSS 스타일시트 폴더
│   ├── reset.css       # 브라우저 기본 스타일 초기화
│   └── style.css       # 메인 레이아웃 및 컴포넌트 스타일
├── index-guest.html    # 설아 인트로 / 프로필 선택 페이지
├── index-jiho.html     # 준범 인트로 / 프로필 선택 페이지
├── index-min.html      # 혜란 인트로 / 프로필 선택 페이지
├── index.html          # 다미 인트로 / 프로필 선택 페이지
├── mypage.html         # 다미 프로필 상세 페이지
├── mypage-jiho.html    # 준범 프로필 상세 페이지
├── mypage-min.html     # 혜란 프로필 상세 페이지
├── mypage-guest.html   # 설아 프로필 상세 페이지
└── README.md           # 프로젝트 안내 문서
```

<br>

## 🚀 5. 실행 및 배포 정보

### 💻 로컬에서 실행하는 방법 (How to Run)

1. 저장소를 로컬 컴퓨터로 복제(Clone)합니다.
   ```bash
   git clone https://github.com/hohora98-art/cinemo-clone.git
   ```
2. 프로젝트 폴더로 이동합니다.
   ```bash
   cd cinemo-clone
   ```
3. `index.html` 파일을 더블 클릭하거나, VS Code의 `Live Server` 익스텐션을 활용해 로컬 서버 환경에서 실행합니다.

### 🌐 라이브 배포 정보 (Deployment)

본 프로젝트는 아래 배포 링크를 통해 설치 없이 웹 브라우저에서 즉시 확인하실 수 있습니다.

- **실행 링크 (GitHub Pages):** [👉 CINEMO 보러가기] -https://github.com/hohora98-art/cinemo-clone
- **디자인 가이드 (Figma):** [👉 피그마 프로젝트 링크] https://www.figma.com/design/EiKQEY9QBrCbw01FxBkeZ4/%EC%A0%9C%EB%AA%A9-%EC%97%86%EC%9D%8C--%EB%B3%B5%EC%82%AC-?node-id=0-1&t=sjxTEVf8URuvA2cv-1
