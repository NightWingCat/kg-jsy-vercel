# 코코비 월드 투어 v8

키글 1주차 에이전틱 과제 랜딩페이지입니다. 코코와 러비가 키글 자동차를 타고 테마 세계를 지나 전 세계와 우주 끝까지 달려가는 3D 스크롤 여행입니다.

- `index.html` 한 파일로 된 정적 사이트입니다 (이미지 · 스타일 · 스크립트 포함, Three.js · Lenis · 글꼴은 CDN).
- Vercel 에서 별도 빌드 설정 없이 루트의 `index.html` 을 그대로 배포합니다.

## v8 · Kigle Design System 적용

Figma `kg-design-system` 의 웹 디자인 시스템(01 Kigle Web)을 UI 전체에 적용했습니다.

- 로고에서 뽑은 플레이 팔레트: Red #FF4A4A · Yellow #FFC34A · Green #30A12F · Sky #4AACFF · Ground Brown #9C5843
- 텍스트는 브라운 잉크 #2E211C, 그림자는 브라운 틴트, 노랑·하늘색 위 글자는 잉크색
- 글꼴 Nunito(영문·숫자) + Noto Sans KR(한글) — Fredoka · Jua 대체
- 카드 20px · 버튼/탭 pill, 누를 수 있는 요소에 그라운드 섀도, 포커스 링 추가
- 소스: `kg-jsy-web01/kigle-v8/src` → `python3 kigle-v8/scripts/build.py`
