# dev.folio — 개발 포트폴리오

Art Circles 스타일의 인터랙티브 원형 UI를 적용한 풀스택 개발자 포트폴리오 사이트입니다.

## Features

- **Art Circles Hero** — 좌우 원형 궤도에 16개 아이템(프로젝트 + 데코 이미지) 배치, hover 시 가운데 상세 카드 + 양옆 사이드 이미지가 동기화 변경
- **프로젝트 모달** — 프로젝트 카드 클릭 시 모달 팝업 (상세 설명 + GitHub 링크)
- **원페이지 스크롤** — Hero → About → Values → Skills → Projects → Experience → Contact
- **다크 섹션** — 가치관(Values) 섹션에 소프트 다크 네이비 배경으로 시각적 리듬감
- **반응형 디자인** — 데스크톱, 태블릿, 모바일 대응
- **스크롤 애니메이션** — Intersection Observer 기반 fade-up 효과
- **자동 순환** — Hero 섹션 프로젝트가 4초 간격 자동 전환 (hover 시 정지)
- **카드 호버 오버레이** — 프로젝트 카드 hover 시 "Click to view" 오버레이 표시

## Tech Stack

`HTML` `CSS` `Vanilla JavaScript`

## Sections

| 섹션 | 설명 |
|------|------|
| Hero | 좌우 원형 궤도(16개) + 중앙 프로젝트 카드 + 양옆 사이드 이미지 |
| About | 자기소개 + 경력 통계 (Years / Projects / Clients) |
| Values | 개발자 가치관 6개 카드 (다크 배경) |
| Skills | 기술 스택 컬러 아이콘 원형 배치 (17개) |
| Projects | Main 3개 + Toy 6개 (3열 그리드, 모달 팝업) |
| Experience | 타임라인 형식 경력 & 학력 |
| Contact | Email, GitHub, Blog |

## Projects

| 구분 | 프로젝트 | 기술 |
|------|----------|------|
| Main | Reeflo — 반려동물 플랫폼 | Spring Boot, Java, Bootstrap, MVC |
| Main | E-Commerce Platform | React, Node.js, MongoDB |
| Main | Data Dashboard | Next.js, Python, D3.js |
| Toy | Task Manager | React, Django, PostgreSQL |
| Toy | Weather App | Vue.js, API, CSS |
| Toy | Blog Engine | Next.js, MDX, Tailwind |
| Toy | Music Player | React, Web Audio, Node.js |
| Toy | Photo Gallery | Vue.js, Python, AWS S3 |
| Toy | Chat App | Vue.js, Socket.io, Express |
