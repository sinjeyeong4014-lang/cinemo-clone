# 🎬 CINEMO — OTT 웹사이트

Figma 디자인 시안을 바탕으로 제작한 가상의 OTT 서비스 웹사이트입니다. HTML5와 CSS3를 활용하여 메인 페이지, 프로필 선택 페이지, 마이페이지를 구현하고, PC·태블릿·모바일 환경에 대응하는 반응형 웹사이트를 제작했습니다.

팀원 간 역할 분담과 GitHub 협업을 통해 프로젝트를 진행했으며, 최종 결과물을 GitHub Pages로 배포했습니다.

## 📌 프로젝트 소개

- **프로젝트명:** CINEMO-Clone
- **프로젝트 유형:** 팀 프로젝트
- **프로젝트 주제:** OTT 서비스 웹사이트 UI 구현
- **개발 인원:** 5명
- **개발 기간:** 2026.10.23 ~ 2026.10.29
- **디자인 도구:** Figma
- **개발 환경:** Visual Studio Code
- **형상 관리:** Git, GitHub
- **배포 환경:** GitHub Pages

## 🎯 프로젝트 목표

- Figma 디자인 시안을 기반으로 실제 웹 페이지 구현
- HTML5 시맨틱 마크업과 CSS3 스타일링 활용
- Flexbox, CSS Grid, Media Query를 활용한 반응형 웹 개발
- 공통 스타일과 페이지별 구조를 구분하여 코드 재사용성 향상
- GitHub 브랜치와 Pull Request를 활용한 팀 협업 경험
- GitHub Pages를 통한 웹사이트 배포

## ✨ 주요 기능

### 1. 메인 페이지 (Main)

- **공통 헤더 및 내비게이션:** 로고와 메뉴를 배치하고 주요 페이지로 이동할 수 있는 UI 구현
- **히어로 배너:** 대표 콘텐츠의 배경 이미지와 콘텐츠 정보 영역 구성
- **콘텐츠 정보 및 버튼 UI:** 콘텐츠 소개와 관련 버튼 요소 구현
- **카테고리별 콘텐츠 목록:** 콘텐츠를 카드 형태로 배치하여 탐색하기 편리한 화면 구성
- **모바일 가로 스크롤:** 모바일 화면에서 콘텐츠 카드를 가로로 탐색할 수 있도록 구현
- **공통 푸터:** 페이지 하단에 공통 정보 영역 구성

### 2. 프로필 선택 페이지 (Profile Selection)

- **프로필 카드 UI:** 사용자 프로필 4개를 카드 형태로 구성
- **프로필 관리 UI:** 프로필 관리 버튼 및 관련 화면 요소 구현
- **반응형 프로필 배치:** PC에서는 가로 배치, 모바일에서는 2열 그리드로 표시
- **프로필 선택 화면:** OTT 서비스의 사용자 프로필 선택 화면 구현

### 3. 마이페이지 (My Page)

- **찜한 콘텐츠 목록:** 찜한 콘텐츠를 확인할 수 있는 카드 목록 UI 구현
- **계정 설정 영역:** 계정 정보를 표시하고 변경 버튼 UI 구성
- **반응형 콘텐츠 배치:** 화면 크기에 따라 콘텐츠와 설정 영역의 배치 변경

### 4. 공통 UI 및 페이지 이동

- 공통 헤더, 내비게이션, 푸터 등 반복되는 UI 구성
- 주요 내비게이션과 페이지 간 링크 연결
- CSS Hover 및 Focus 상태 스타일 적용
- 시맨틱 HTML과 이미지 대체 텍스트 등 웹 접근성을 고려한 마크업 작성

### 5. 반응형 웹

- PC·태블릿·모바일 화면에 대응하는 레이아웃 구현
- Flexbox와 CSS Grid를 활용한 콘텐츠 배치
- Media Query를 통한 화면 크기별 스타일 적용
- 모바일 콘텐츠 가로 스크롤 및 프로필 카드 2열 배치
- 화면 크기 변화에 따른 요소 잘림과 불필요한 가로 스크롤 방지

### 6. 협업 및 배포

- GitHub Repository를 통한 소스 코드 관리
- 팀원별 작업 브랜치 분리
- Pull Request를 통한 코드 검토 및 병합
- GitHub Pages를 활용한 웹사이트 배포

## 🛠️ 기술 스택

| 구분 | 기술 |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Layout | Flexbox, CSS Grid |
| Responsive | Media Query |
| UI Interaction | CSS Hover, Focus 및 시각적 UI 구현 |
| Design | Figma |
| Development | Visual Studio Code |
| Version Control | Git, GitHub |
| Deployment | GitHub Pages |

## 📱 반응형 웹 구현

화면 크기에 따라 콘텐츠 배치와 레이아웃이 자연스럽게 변경되도록 반응형 웹을 구현했습니다.

- **PC:** 넓은 화면에 적합한 콘텐츠 배치 및 카드 레이아웃 구성
- **Tablet:** 화면 너비에 맞춰 콘텐츠 간격과 배치 조정
- **Mobile:** 프로필 카드 2열 배치 및 콘텐츠 가로 스크롤 적용
- **레이아웃 최적화:** Flexbox, CSS Grid, Media Query를 활용하여 요소의 잘림과 불필요한 가로 스크롤 방지
- **스타일:** 버튼 및 링크의 Hover, Focus 스타일 적용

## 📂 프로젝트 폴더 구조

공통 CSS를 중심으로 반복되는 스타일을 관리하고, 페이지별 HTML 파일을 분리하여 구성했습니다.

아래는 폴더 구조 예시입니다. 실제 프로젝트 파일명에 맞게 수정해 주세요.

```text
CINEMO/
├── index.html
├── profile.html
├── mypage.html
├── css/
│   └── style.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

- `index.html`: 메인 페이지
- `profile.html`: 프로필 선택 페이지
- `mypage.html`: 마이페이지
- `css/style.css`: 공통 스타일 및 반응형 스타일
- `assets/images/`: 배경 이미지 및 콘텐츠 이미지
- `assets/icons/`: 아이콘 리소스

## 👥 팀원 및 담당 업무

본 프로젝트는 5명의 팀원이 참여하여 페이지 구현과 공통 UI 작업을 분담하고, GitHub를 활용하여 코드를 통합하는 방식으로 진행했습니다.

| 팀원 | 담당 업무 |
| 팀장 신제영 | 메인페이지, 마이페이지 (카테고리별 콘텐츠 카드 목록,
내가 찜한 콘텐츠 목록)/ Git |
| 팀원 정고은 | 메인 페이지 콘텐츠 히어로 배너 |
| 팀원 박인애 | 마이페이지 프로필, 계정 설정  |
| 팀원 이재웅 | 프로필 선택 페이지 |
| 팀원 권해성 | 공통 헤더, 푸터와 내비게이션 |

## 🤝 협업 방식

- GitHub Repository를 활용한 소스 코드 관리
- 팀원별 작업 브랜치 분리를 통한 독립적인 개발
- Pull Request를 통한 코드 공유 및 검토
- 공통 CSS와 페이지별 HTML을 중심으로 한 파일 관리
- 클래스 네이밍 규칙과 코드 작성 기준 통일
- 코드 통합 후 페이지 연결 및 반응형 레이아웃 검수

## 🚀 실행 방법

### 1. Repository Clone

```bash
git clone [https://github.com/sinjeyeong4014-lang/cinemo-clone.git]
```

### 2. 프로젝트 폴더 이동

```bash
cd CINEMO
```

### 3. 웹사이트 실행

프로젝트 폴더의 `index.html` 파일을 브라우저에서 열거나, Visual Studio Code의 Live Server 확장 프로그램을 사용하여 실행할 수 있습니다.

별도의 패키지 설치나 빌드 과정 없이 HTML 파일을 통해 확인할 수 있습니다.

## 🌐 배포 주소

- **Website:** [https://sinjeyeong4014-lang.github.io/cinemo-clone/]
- **Repository:** [https://github.com/sinjeyeong4014-lang/cinemo-clone.git]

GitHub Pages를 통해 배포된 웹사이트에서 최종 구현 결과를 확인할 수 있습니다.

## ⚠️ 구현 범위 및 제한 사항

- 본 프로젝트는 학습 목적으로 제작한 가상의 OTT 서비스 웹사이트입니다.
- HTML과 CSS를 중심으로 화면 구성 및 반응형 UI를 구현했습니다.
- 실제 로그인, 회원 관리, 서버 연동 및 데이터 저장 기능은 구현 범위에 포함되지 않습니다.
- 찜하기 및 작품 살펴보기 버튼은 실제 기능이 아닌 UI 표현을 목적으로 구현했습니다.
- 실제 콘텐츠 스트리밍 기능은 포함하지 않습니다.

---

**CINEMO**  
Responsive OTT Website Project  
Built with HTML5 and CSS3.
