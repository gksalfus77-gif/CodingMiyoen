
## 🌐 mellow-Ond 웹쇼핑몰 개발

<!-- ![IMG](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/Mellow%20Ond-%20frontend/IMG/%EC%A0%84%EC%B2%B4%EC%A0%81%EC%9D%B8%20%EB%B8%8C%EB%9E%9C%EB%93%9C%20%EC%84%A4%EB%AA%85.png?raw=true) -->
### 🔖프론트 기술스텍
| 기술 | 설명 |
|------|------|
| ![HTML](https://img.shields.io/badge/HTML-RED) | 전체적인 사이트 화면을 HTML로 기본틀을 잡음 |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white) |웹사이트 전반에 인터랙티브한 동작과 애니메이션 효과를 구현. |
| ![GITHUB](https://img.shields.io/badge/GITHUB-%23ff69b4) | 협업을 위해 공유하고 수정함|
| ![CSS](https://img.shields.io/badge/CSS-%23000000) |기본적인 디자인을 HTML과 CSS로 구성|


### 🔖담당부분 주요특징
| 기술 | 설명 |
|------|------|
| ![frontmain](https://img.shields.io/badge/frontend-main-%236B7280) | 전체적인 사이트 UI/UX를 설계하고, 메인 화면을 HTML, CSS, React 기반으로 구현. |
| ![Topmenu](https://img.shields.io/badge/frontend-Top%20Menu-FF69B4) | 로고, 카테고리, 검색창, 마이페이지, 장바구니 아이콘 배치.|
| ![Product](https://img.shields.io/badge/frontend-%20Product%20Image-1E90FF) | 쇼핑몰 전반적인 상품이미지 구간을 모두 프론트함.|
| ![login-membership](https://img.shields.io/badge/frontend-%20login%2Fmembers-00FF00) |로그인 페이지와 회원가입(Membership) 페이지의 UI 디자인 및 프론트엔드 개발을 담당했습니다.|


## 💻 주요(내파트) 화면 및 기능 상세

<details>
<summary>✨ MAIN 화면</summary>

![IMG](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/MELLOW-OND%20-frontend/IMG/Dji%20%EB%93%9C%EB%A1%A0%20%ED%99%88%ED%8E%98%EC%9D%B4%EC%A7%80%20(Community)%20(2).png?raw=true)

### 📑[메인 상세 페이지 프론트엔드 개발 & UI/UX 디자인]

- 🥣브랜드 감성을 살린 메인 비주얼 디자인: 화이트·뉴트럴 톤의 브랜드 아이덴티티를 극대화한 상단 히어로 배너 및 내비게이션 레이아웃 구현.

- 🖼️인스타그램 스타일 3x3 브랜드 갤러리 구축: CSS 그리드(Grid) 레이아웃과 object-fit: cover 속성을 활용하여 원본 이미지의 왜곡 없이 깔끔한 정사각형 격자 화면 구현.

- 🛒데이터 매핑 기반 베스트 상품 UI 개발: 백엔드 상품 배열 데이터를 동적으로 반복 렌더링하는 컴포넌트를 설계하고, 4열 반응형 그리드 시스템 및 텍스트 말줄임표 방어 코드 적용.

</details>

<details>
<summary>✨ 로그인/회원가입 </summary>

![LOG IMG](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/MELLOW-OND%20-frontend/IMG/%EB%A1%9C%EA%B7%B8%EC%9D%B8%20%ED%8E%98%EC%9D%B4%EC%A7%80%20.png?raw=true)

### 📑[로그인 화면]
- 🎫비회원 주문 접근성을 고려한 멀티 로그인 시스템: 일반 회원 로그인 기능 외에도 쇼핑몰 특성에 맞춘 '비회원 로그인' 및 비밀번호 찾기, 회원가입 링크 전환 처리 컴포넌트 구축.
</details>

<details>
<summary>✨ Product page </summary>

![공지사항 img](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/IMG/%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD01.png?raw=true)

### 📑[Sevice Center 공지사항 page]

- 전체적인 공지사항 페이지를 만들고 헤드를 투명으로 만듬.

![공지사항 img](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/IMG/%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%20%EA%B2%8C%EC%8B%9C%ED%8C%90.png?raw=true)

### 📑[커뮤니티(Community) 화면]
- 소통 활성화를 위한 참여형 구조: 고객이 직접 글을 작성하고 댓글로 소통할 수 있는 기능을 전면에 배치하여 서비스센터 내 활발한 유저 커뮤니티 형성.

- 탭 기반의 카테고리 내비게이션: [전체], [자유게시판], [이용후기], [충전 팁], [공지사항]으로 분류하여 사용자가 원하는 주제의 게시글을 빠르게 필터링하도록 구현.

- 직관적인 검색 및 글쓰기 UI: 게시글 검색 창과 메인 컬러(퍼플)가 적용된 '글쓰기' 버튼을 상단에 배치하여 유저의 행동 유도 및 접근성 극대화.

- 대시보드형 통계 위젯 제공: 우측 하단에 '전체 게시글'과 '공지사항'의 개수를 실시간으로 시각화하는 커뮤니티 통계 컴포넌트 탑재.

![자주묻는 질문](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/IMG/%EC%9E%90%EC%A3%BC%EB%AC%BB%EB%8A%94%20%EC%A7%88%EB%AC%B8.png?raw=true)

- 효율적인 CS 응대를 위한 FAQ 구축: 사용자가 자주 묻는 질문들을 한눈에 확인하고 해결할 수 있도록 설계하여 고객센터의 운영 효율성 증대.

- 통일감 있는 브랜드 디자인: 배너 상단의 '고객지원' 태그와 타이틀 텍스트에 메인 컬러(퍼플)를 적용하여 전체 웹사이트와의 시각적 일관성 확보.


### 📑[고객센터 화면]

![고객센터](https://github.com/gksalfus77-gif/CodingMiyoen/blob/main/IMG/%EA%B3%A0%EA%B0%9D%EC%84%BC%ED%84%B0.png?raw=true)

- 다채널 고객 지원 내비게이션: 상단에 [1:1 고객문의], [커뮤니케이션], [자주 묻는 질문] 카드를 배치하여 원하는 지원 채널로의 즉각적인 이동 지원.

- 직관적인 유선 상담 연동: 일반 전화상담(1588)과 24시간 긴급 출동(080) 번호를 이원화하고, 클릭 시 바로 연결 가능한 '전화 연결하기' 및 '긴급 호출하기' 액션 버튼 배치.

</details>