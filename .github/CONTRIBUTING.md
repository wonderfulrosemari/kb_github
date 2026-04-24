# Commit Message 규칙

## 커밋 타입
- feat: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서 수정
- style: 포맷, 세미콜론 등 비즈니스 로직에 변경 없는 수정
- refactor: 코드 리팩토링
- test: 테스트 코드 추가
- chore: 빌드 업무 수정, 패키지 매니저 수정

## 커밋 메시지 형식
```text
<타입>: <변경사항 요약>
```

## 예시
```text
feat: Add member intro page
fix: Correct typo in main page
docs: Add pull request guide
```

## 브랜치 규칙
작업은 `main` 브랜치에서 직접 진행하지 않고, 아래 형식의 브랜치를 만들어 진행합니다.

```text
feature/issue-{번호}
feature/{변경제목}
```
