# flower-studio-sample

FLEUR DE SAISON · 계절의 꽃 — 연남동 플라워 스튜디오 샘플 (이피웹 포트폴리오).

- **목적:** 포트폴리오 다양화 샘플. `샘플_다양성_매트릭스.md`의 빈 셀 점유: **갤러리-퍼스트 · 신청폼+주문 · 비대칭 에디토리얼 · 좌측 세로 숫자 내비 · 라이트박스 · 필름 내추럴**. (네일/필라의 단일앵커·중앙클래식·상단내비와 의도적으로 다름)
- **스택:** 정적 HTML/CSS/JS (단일 `index.html`, 인라인). 빌드 없음.
- **호스팅:** Cloudflare Workers(정적 자산, 무료·상업 허용). 배포 후 `/.git/config` 404 확인.
- **배포 주소(예정):** `flower-studio-sample.lgt3232.workers.dev`

## 안전장치 (LESSONS §11·13·14 선적용)
고정바=`<div>`(nav 금지) / `100vh;100svh` 히어로 / `backdrop-filter:blur` 미사용 / 스크롤 `requestAnimationFrame`+`{passive}` / 모바일 스크롤 리빌 비활성화(데스크탑 전용) / Formspree `action` 실제 ID 교체 필요 / `.assetsignore`로 `.git` 노출 차단.

## 미설정(납품 전 교체)
- Formspree form ID (`YOUR_FORM_ID`) — 클래스 신청·주문 문의 폼.
- 실제 사진(현재 Unsplash 플레이스홀더, 톤 통일) / 작가 얼굴 / 지도 좌표·연락처·주소.
