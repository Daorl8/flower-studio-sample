# STRUCTURE — flower-studio-sample

단일 페이지(`index.html`), 좌측 세로 숫자 내비(01–06)로 섹션 이동. 비대칭 에디토리얼 레이아웃.

```
index.html
├─ <head> : 메타, 폰트(Cormorant Garamond + Pretendard), 인라인 CSS(디자인 토큰)
├─ 좌측 세로 내비 (.sidenav, position:fixed) — 00~06, 모바일선 상단 햄버거/숨김
├─ #hero      Hero : 풀블리드 꽃 + 미니멀 헤드라인 + CTA 2개(클래스 신청 / 주문 문의)
├─ #gallery   01 Gallery : 비대칭 작업물 그리드 + 라이트박스 (갤러리-퍼스트)
├─ #about     02 About : 작가 스토리(오프셋 2단)
├─ #classes   03 Classes : 원데이/정규/프라이빗 카드(일정·정원·준비물·가격) + 신청
├─ #order     04 Order : 주문 제작(부케·기념일·행사) 안내 + 문의 폼
├─ #reviews   05 Reviews : 후기
├─ #contact   06 Contact : 지도/네이버·카카오 길찾기·영업시간·주차·전화/카톡
├─ 모바일 하단 퀵바 (.mbar, <div>) : 전화 / 카톡 / 클래스 신청
└─ <script> : 좌측 내비 active 추적(rAF), 라이트박스, 폼 처리, 데스크탑 전용 리빌
```

## 디자인 토큰
- 컬러: `--ivory:#F7F2EA` `--sage:#6E7657` `--ink:#2A2A28` `--rose:#C9A8A0`(보조) `--line:#E3DBCE`
- 타입: 헤드라인 `Cormorant Garamond`, 본문 `Pretendard`. 한/영 병기.
- 모션: 데스크탑 스크롤 페이드(≥861px), 모바일 정적.
