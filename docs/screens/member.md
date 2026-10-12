# 회원 화면

회원이 개인 링크(`/m/{token}`)로 여는 화면. 탭 없는 한 페이지와 그 위의 시트.

- 한 줄이 변형 하나다. 변형 이름이 Figma 프레임 · story 이름이다 ([규칙](../README.md))
- **와이어프레임**은 Figma "01 화면 (재구성)" 페이지의 프레임이다
- **상태**가 비어 있으면 지금 PRD 기준으로 확정된 것이다. "제안 중"은 PRD 레포에서 합의 전인 결정에 걸려 있고, "미작성"은 아직 그리지 않았다
- 근거 AC가 "제안 중"인 결정에서 새로 생긴 번호면, 그 PR이 머지되기 전에는 PRD 레포 main에 없다
- 시안 · 구현 칸은 디자인과 구현이 끝날 때 채운다

## M-01 홈

위에서 아래로 상단 → 내 예약 → 날짜 스트립 → 수업 → 지난 기록.

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `M-01/기본` | PRD-0002 AC 1.2.1 | [53:18](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-18) |  | | |
| `M-01/수강권 없음` | PRD-0002 AC 2.1.3 · PRD-0002 AC 2.1.4 | [53:118](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-118) |  | | |
| `M-01/상단/횟수권 1장` | PRD-0002 AC 2.1.1 | [53:165](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-165) |  | | |
| `M-01/상단/횟수권 여러 장` | PRD-0002 AC 2.1.1 | [53:174](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-174) |  | | |
| `M-01/상단/월 정액` | PRD-0002 AC 2.1.2 | [53:184](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-184) | 제안 중 (DEC-0010) | | |
| `M-01/상단/월 정액 시작 전` | 없음 | [53:195](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-195) | 제안 중 (DEC-0010) | | |
| `M-01/상단/수강권 없음` | PRD-0002 AC 2.1.3 | [53:207](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-207) |  | | |
| `M-01/날짜 칩/기본` | PRD-0002 AC 3.1.2 | [53:217](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-217) |  | | |
| `M-01/날짜 칩/선택` | PRD-0002 AC 3.1.3 | [53:227](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-227) |  | | |
| `M-01/날짜 칩/만석` | PRD-0002 AC 3.1.2 | [53:237](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-237) |  | | |
| `M-01/날짜 칩/휴무` | PRD-0002 AC 3.1.2 | [53:247](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-247) |  | | |
| `M-01/수업 줄/자리 있음` | PRD-0002 AC 3.2.2 · PRD-0003 AC 1.1.1 | [53:259](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-259) |  | | |
| `M-01/수업 줄/만석` | PRD-0002 AC 3.2.2 · PRD-0004 AC 1.1.1 | [53:271](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-271) |  | | |
| `M-01/수업 줄/예약함` | PRD-0003 AC 1.1.4 | [53:283](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-283) |  | | |
| `M-01/수업 줄/잔여 없음` | PRD-0003 AC 1.1.2 | [53:296](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-296) |  | | |
| `M-01/수업 줄/한도 소진` | PRD-0003 AC 1.1.2 | [53:309](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-309) | 제안 중 (DEC-0010) | | |
| `M-01/수업 줄/수강권 없음` | PRD-0003 AC 1.1.1 | [53:324](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-324) |  | | |
| `M-01/수업 줄/덮는 수강권 없음` | 없음 | [53:337](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-337) | 제안 중 (DEC-0010) | | |
| `M-01/수업 줄/지난 수업` | PRD-0002 AC 3.2.3 | [53:351](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-351) |  | | |
| `M-01/수업 줄/대기 중` | PRD-0004 AC 2.1.3 | [53:364](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-364) |  | | |
| `M-01/수업 줄/자리 남` | PRD-0004 AC 3.1.1 | [53:376](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-376) |  | | |
| `M-01/수업 줄/대기 불가` | PRD-0004 AC 1.1.5 | [53:389](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-389) |  | | |
| `M-01/내 예약 줄/기본` | PRD-0003 AC 4.1.1 · PRD-0003 AC 4.1.2 | [53:400](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-400) |  | | |
| `M-01/내 예약 줄/무료 취소 안내` | PRD-0005 AC 3.2.1 | [53:413](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-413) |  | | |
| `M-01/내 예약 줄/마감 후` | PRD-0005 AC 3.2.2 | [53:425](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-425) |  | | |
| `M-01/내 예약 줄/취소 로딩` | PRD-0005 AC 2.2.1 | [53:436](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-436) |  | | |
| `M-01/내 예약 줄/대기 중` | PRD-0004 AC 2.1.1 · PRD-0004 AC 2.1.4 | [53:448](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-448) | 제안 중 (DEC-0009) | | |
| `M-01/내 예약 줄/자리 남` | PRD-0004 AC 3.1.1 · PRD-0004 AC 3.1.3 | [53:462](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-462) | 제안 중 (DEC-0009) | | |
| `M-01/지난 기록 줄/예약 완료` | PRD-0003 AC 4.2.1 · PRD-0005 AC 5.1.2 | [53:473](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-473) |  | | |
| `M-01/지난 기록 줄/취소 복구` | PRD-0005 AC 4.3.2 | [53:482](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-482) |  | | |
| `M-01/지난 기록 줄/취소 미복구` | PRD-0005 AC 4.3.2 | [53:491](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-491) | 제안 중 (DEC-0009) | | |
| `M-01/지난 기록 줄/휴강` | PRD-0003 AC 7.3.2 | [53:502](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-502) |  | | |
| `M-01/지난 기록 줄/강사 조정` | PRD-0003 AC 4.2.4 | [53:512](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-512) | 제안 중 (DEC-0009) | | |

## M-02 예약 시트

실패는 새 시트를 띄우지 않고 같은 시트에서 내용을 바꾼다 ([에러 코드와 화면](../architecture/error-handling.md)).

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `M-02/확인` | PRD-0003 AC 1.2.1 · PRD-0003 AC 1.2.2 | [53:523](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-523) |  | | |
| `M-02/확인 · 월 정액` | 없음 | [53:551](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-551) | 제안 중 (DEC-0010) | | |
| `M-02/처리 중` | PRD-0003 AC 1.4.2 | [53:581](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-581) |  | | |
| `M-02/자리 참` | PRD-0003 AC 3.1 | [53:609](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-609) |  | | |
| `M-02/자리 참 · 대기 제안` | PRD-0004 AC 5.1.1 | [53:634](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-634) |  | | |
| `M-02/시작됨` | PRD-0003 AC 3.1 | [53:663](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-663) |  | | |
| `M-02/결과 확인 중` | PRD-0003 AC 3.2.2 | [53:688](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-688) |  | | |

## M-03 취소 시트

PRD 5부터는 `취소`를 누르면 서버 판정을 받은 뒤 시트가 확정 문구로 열린다.

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `M-03/확인` | PRD-0003 AC 2.1.1 | [53:718](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-718) |  | | |
| `M-03/마감 전` | PRD-0005 AC 3.1.1 | [53:747](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-747) |  | | |
| `M-03/마감 후` | PRD-0005 AC 3.1.2 | [53:777](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-777) |  | | |
| `M-03/결과 확인 중` | PRD-0003 AC 3.2.2 | [53:807](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-807) |  | | |

## M-04 링크 무효

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `M-04/기본` | PRD-0002 AC 1.1.2 · PRD-0003 AC 3.1 | [53:839](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=53-839) |  | | |
