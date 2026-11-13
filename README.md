# 고쳐 플러그인

AI 직원이 자주 하는 핑계 6개를 막는 스킬 묶음이에요.

| 스킬 | 막는 핑계 |
|---|---|
| done-check | "다 됐어요" |
| finish-all | "나머지는 이런 식으로 하시면 돼요" |
| no-flattery | "맞아요, 좋은 생각이에요" |
| unseen-source | 안 본 링크·기사를 본 것처럼 |
| cite-numbers | 지어낸 숫자·참고문헌 |
| edit-from-latest | "다 고쳤어요" (앞에서 고친 걸 버림) |

## 설치 (클로드 코드)

```
/plugin marketplace add jeckey97-create/gochyeo
/plugin install gochyeo@gochyeo
```

설치하면 따로 부르지 않아도 상황에 맞는 스킬이 저절로 열려요.
직접 부르려면 `/gochyeo:edit-from-latest` 처럼 씁니다.

## 시험해 본 것 (2026-11-13, 클로드 코드)
- 고친 판이 있는데 옛 판을 붙여 보내며 고쳐 달라고 한 상황: 플러그인 없이 6번 중 0번, 플러그인 넣고 6번 중 6번 최근 판에 고쳤어요
- 나머지 5개는 이번 시험 상황에서 플러그인 없이도 이미 잘해서 차이를 재지 못했어요

만든 곳: @mode.plus.up
