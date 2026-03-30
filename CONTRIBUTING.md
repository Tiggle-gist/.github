# Contributing Guide

## 브랜치 전략

```
main        ← 안정된 버전만
dev         ← 통합 테스트
feat/xxx    ← 기능 개발
fix/xxx     ← 버그 수정
```

- `main`에 직접 push 금지
- 모든 변경은 PR → 최소 1명 리뷰 → merge

## 커밋 메시지

```
feat: 새로운 기능
fix:  버그 수정
docs: 문서 수정
refactor: 리팩토링
chore: 기타
```

예시: `feat: NLP 명령 파싱 기본 구현`


## PR 규칙

- 제목: `[feat] 서버 명령 파싱 추가`
- 작은 단위로 자주 올리기
- 머지 전 최소 1명 리뷰 승인
