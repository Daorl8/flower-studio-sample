# CHANGELOG — flower-studio-sample

## 2026-06-18
- 레포 스캐폴딩 생성(.assetsignore, README, STRUCTURE, CHANGELOG).
- 샘플 방향 확정: 다양성 매트릭스의 "갤러리-퍼스트 · 좌측 숫자 내비 · 비대칭 에디토리얼 · 필름 내추럴" 셀 점유(네일/필라와 구조 차별).
- index.html 완성: 좌측 숫자 내비(01–06) + Hero(2CTA) + 01 Gallery(비대칭 6열, 라이트박스) + 02 About(오프셋 2단) + 03 Classes(원데이/정규/프라이빗) + 04 Order(신청·주문 폼) + 05 Reviews + 06 Contact + 모바일 하단 퀵바(div).
- 안전장치 선적용: 고정바 div, 100svh, blur 없음, rAF+passive 스크롤, 모바일 리빌 off, 푸터 ©2026.
- 이미지: Unsplash flower-bouquet 실로드 ID 8종(갤러리)+About+Order. 지도는 플레이스홀더(길찾기 버튼 연결).
- 미설정(납품 전): Formspree action ID, 실제 사진·연락처·주소·지도 좌표.
- **한국어 줄바꿈 교정:** body에 `word-break:keep-all`(+`overflow-wrap:break-word`) — 단어가 줄 중간에 쪼개지지 않고 어절 단위로만 줄바꿈.
- **배포 완료(2026-06-18):** GitHub `Daorl8/flower-studio-sample`(웹 업로드) → Cloudflare Workers `flower-studio-sample.lgt3232.workers.dev`. 검증: 히어로·갤러리 렌더 OK, `/.git/config` 404, Linktree 4번째 링크 등록. (실폰 모바일 점검은 미실시)
