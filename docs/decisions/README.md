# 설계 결정 (ADR)

FE 내부 설계 결정. BE와 같이 따르는 결정은 [PRD 레포 `decisions/`](https://github.com/Fit-link-v2/Fit-link-PRD/tree/main/decisions)에 둔다.

- 파일 이름: `{4자리}-{영문-슬러그}.md`. ID는 `FE-ADR-{4자리}`
- 형식: [`templates/decision.md`](../templates/decision.md)
- 한 번 `accepted`가 된 결정은 고치지 않는다. 바뀌면 새 번호를 만들고 이전 결정의 상태를 `superseded by FE-ADR-XXXX`로 바꾼다

| ID | 제목 | 상태 |
|---|---|---|
| [FE-ADR-0001](0001-logic-outside-components.md) | 판정 로직은 컴포넌트 밖에 두고, 컴포넌트는 결과만 그린다 | proposed |
