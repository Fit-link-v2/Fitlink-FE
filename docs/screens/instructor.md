# 강사 화면

강사가 카카오 로그인 뒤에 쓰는 화면. 하단 탭 수업 · 회원, 설정은 헤더.

- 한 줄이 변형 하나다. 변형 이름이 Figma 프레임 · story 이름이다 ([규칙](../README.md))
- **와이어프레임**은 Figma "01 화면 (재구성)" 페이지의 프레임이다
- **상태**가 비어 있으면 지금 PRD 기준으로 확정된 것이다. "제안 중"은 PRD 레포에서 합의 전인 결정에 걸려 있고, "미작성"은 아직 그리지 않았다
- 근거 AC가 "제안 중"인 결정에서 새로 생긴 번호면, 그 PR이 머지되기 전에는 PRD 레포 main에 없다
- 시안 · 구현 칸은 디자인과 구현이 끝날 때 채운다

## I-01 로그인

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-01/기본` | PRD-0001 AC 1.1.8 · PRD-0001 AC 1.2.1 | [54:8](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-8) |  | | |
| `I-01/인증 실패` | PRD-0001 AC 1.1.5 | [54:28](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-28) |  | | |

## I-02 수업 탭

위는 반복 규칙, 아래는 다가오는 수업.

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-02/기본` | PRD-0001 AC 2.1.2 | [54:53](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-53) |  | | |
| `I-02/규칙 줄/활성` | PRD-0001 AC 2.1.5 | [54:117](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-117) |  | | |
| `I-02/규칙 줄/비활성` | PRD-0001 AC 2.1.4 | [54:129](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-129) |  | | |
| `I-02/수업 줄/기본` | PRD-0003 AC 5.1.1 | [54:139](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-139) |  | | |
| `I-02/수업 줄/대기 있음` | PRD-0004 AC 4.1.3 | [54:149](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-149) | 제안 중 (DEC-0009) | | |
| `I-02/수업 줄/자리 남 · 대기 있음` | PRD-0004 AC 4.1.3 | [54:163](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-163) | 제안 중 (DEC-0009) | | |

## I-03 반복 규칙 시트

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-03/기본` | PRD-0001 AC 2.1.5 · PRD-0001 AC 2.1.2 | [54:174](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-174) | 제안 중 (DEC-0009) | | |

## I-04 슬롯 상세

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-04/예약 없음` | PRD-0003 AC 5.1.1 | [54:234](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-234) |  | | |
| `I-04/예약 있음` | PRD-0003 AC 5.1.1 | [54:256](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-256) |  | | |
| `I-04/대기자 있음` | PRD-0004 AC 4.1.1 · PRD-0004 AC 4.1.2 | [54:286](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-286) |  | | |
| `I-04/대기자 줄/기본` | PRD-0004 AC 4.1.1 | [54:336](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-336) |  | | |
| `I-04/대기자 줄/1순위 자리 남` | PRD-0004 AC 4.1.2 · PRD-0004 AC 4.2.1 | [54:348](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-348) |  | | |

## I-05 시각 변경 시트

예약이 있는 슬롯은 시각을 바꿀 수 없다 (DEC-0006).

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-05/기본` | PRD-0001 AC 2.3.2 · PRD-0001 AC 2.3.3 | [54:359](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-359) |  | | |
| `I-05/예약 있어 불가` | PRD-0001 AC 2.3.2 | [54:382](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-382) | 미작성 | | |

## I-06 휴강 시트

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-06/확인 · 예약 없음` | PRD-0001 AC 2.3.4 · PRD-0003 AC 7.1.4 | [54:397](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-397) | 제안 중 (DEC-0009) | | |
| `I-06/확인 · 예약 있음` | PRD-0003 AC 7.1.3 | [54:417](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-417) | 제안 중 (DEC-0009) | | |
| `I-06/완료 · 안내 문구` | PRD-0003 AC 7.3.4 | [54:443](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-443) | 제안 중 (DEC-0009) | | |

## I-07 회원 목록

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-07/기본` | PRD-0001 AC 5.1.1 · PRD-0001 AC 5.1.5 | [54:472](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-472) | 제안 중 (DEC-0009) | | |
| `I-07/미개봉 없음` | PRD-0001 AC 5.1.4 | [54:524](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-524) |  | | |
| `I-07/회원 줄/미개봉` | PRD-0001 AC 5.1.5 | [54:580](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-580) | 제안 중 (DEC-0009) | | |
| `I-07/회원 줄/개봉` | PRD-0001 AC 5.1.5 | [54:593](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-593) | 제안 중 (DEC-0009) | | |
| `I-07/회원 줄/수강 종료` | PRD-0001 AC 3.3.1 | [54:605](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-605) |  | | |

## I-08 회원 추가 시트

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-08/기본` | PRD-0001 AC 3.1.1 · PRD-0001 AC 3.1.2 | [54:615](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-615) |  | | |

## I-09 링크 발급

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-09/기본` | PRD-0001 AC 3.1.3 · PRD-0001 AC 4.2.1 · PRD-0001 AC 4.2.2 | [54:651](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-651) |  | | |

## I-10 회원 상세

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-10/기본` | PRD-0001 AC 3.2.3 · PRD-0003 AC 5.2.1 · PRD-0001 AC 4.2.3 | [54:676](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-676) |  | | |
| `I-10/수강 종료됨` | PRD-0001 AC 3.3.1 · PRD-0001 AC 3.3.3 | [54:718](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-718) |  | | |
| `I-10/수강권 카드/횟수권` | PRD-0001 AC 3.2.1 · PRD-0001 AC 3.2.3 | [54:773](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-773) |  | | |
| `I-10/수강권 카드/만료` | PRD-0001 AC 3.2.4 | [54:782](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-782) |  | | |
| `I-10/수강권 카드/월 정액` | PRD-0001 AC 3.2.6 | [54:788](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-788) | 미작성 · 제안 중 (DEC-0010) | | |

## I-11 수강권 등록 시트

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-11/횟수권` | PRD-0001 AC 3.2.1 · PRD-0001 AC 3.2.5 | [54:803](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-803) |  | | |
| `I-11/월 정액` | PRD-0001 AC 3.2.5 · PRD-0001 AC 3.2.6 | [54:842](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-842) | 미작성 | | |
| `I-11/기간 겹침` | PRD-0001 AC 3.2.10 | [54:855](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-855) | 미작성 | | |

## I-12 재발급 확인 시트

회원이 이미 연 링크일 때만 띄운다.

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-12/확인` | PRD-0001 AC 4.3.1 | [54:870](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-870) |  | | |

## I-13 설정

| 변형 | 근거 AC | 와이어프레임 | 상태 | 시안 | 구현 |
|---|---|---|---|---|---|
| `I-13/기본` | PRD-0001 AC 2.4.1 · PRD-0005 AC 1.1.1 | [54:893](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-893) |  | | |
| `I-13/로그아웃` | PRD-0001 AC 1.1.7 | [54:925](https://www.figma.com/design/DKEXqSnsZu1S4pTIzHdz32/Fit-link-Wireframe?node-id=54-925) | 미작성 | | |
