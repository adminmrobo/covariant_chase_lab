# 이미지 제작 명세서 — 01 주판봇의 초파리 추적 대작전 ① 공변미분

> 그림체: 16비트 RPG풍 픽셀아트 (모든 그림 공통) · 배경: 낮의 연구실(흰 바탕) · 그림 안 글자 금지

## 1. 그림 전체 목록

| 키 | 판 | 상태 | 자리 | 내용 |
|---|---|---|---|---|
| cover_01 | L 16:9 | **새로 그림** | `#cover` | 표지 — `COVER_01_covariant_chase.md` |
| og_01 | 1200×630 | 표지에서 자름 | `<meta og:image>` | 표지 가운데 자르기 |
| thumb_01 | 3:2 | 표지에서 자름 | 목차 썸네일 | 표지 가운데 자르기 |
| 캐릭터 표정 36장 | 96px | **캐릭터 팩 재사용** | 말풍선·등장인물·대결·캔버스 | fruitfly-lab-expressions @ 86d04ac (아래 3장) |
| sc_01 ~ sc_07 | 3:2 | **새로 그림** | 실험 ①~⑤ 앞, 대결 결과 안, 2편 예고 | 장면 그림 7장 — `GENSPARK_요청서.md` |

> 게임 캔버스 5개의 지구본·레이더·드론은 코드로 그리므로 그림이 필요 없습니다(도장: 설명용 모형).

## 2. 만드는 순서
1. `cover_01` (표지, 코믹: 악에 받친 주판봇을 넷이 말리고 초파리는 따돌리고 X1~X3 응원) → 그림체 확인
2. 대화 B·C에서 `sc_01`~`sc_07` — 표지를 참고 그림으로 함께 올림 (`GENSPARK_요청서.md`)
3. 받은 표지에서 `og_01`, `thumb_01` 자르기

## 3. 캐릭터 팩에서 쓴 표정 키
doc: front · board · think · magic · judge / asst: smile · report · firm · spark · shock · proud / fly: clip · point · arms · magnify · coffee / robo: smile · coin · calc · happy · sigh · wow · e22(뿔남) / sia: smile · signal · think · doze / moa: cheer · cry · sparkle · tea / x1·x2·x3: hint

- 아웃트로 표정은 대결 결과(F, 초파리 편 승)와 맞춤: 초파리 arms, 주판봇 sigh, 하루 proud, 박사 magic.
- 박사·조수·시아·모아는 좌우 반전하지 않음. 대결 머리의 주판봇만 CSS 반전(허용).

## 4. 장면 프롬프트
`GENSPARK_요청서.md`에 모았습니다. 실전 연습장(`practice/index.html`)의 그래프·구조 그림은 코드로 그리므로 그림이 필요 없습니다.
