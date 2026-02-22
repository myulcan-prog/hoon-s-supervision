# 커밋 & 푸시

변경 사항을 커밋하고 GitHub에 푸시합니다.

## 수행 단계

1. `git status`로 변경 사항 확인
2. `git diff`로 변경 내용 확인
3. `git log --oneline -5`로 최근 커밋 스타일 확인
4. 변경 내용에 맞는 커밋 메시지 작성
5. `git add`로 관련 파일만 스테이징
6. `git commit`으로 커밋
7. `git push origin main`으로 푸시

## 커밋 메시지 규칙
- 한국어 또는 영어 (일관되게)
- 형식: `{type}: {description}`
- type: feat, fix, content, style, refactor, docs
