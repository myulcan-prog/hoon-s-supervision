# 섹션 추가

랜딩 페이지에 새로운 섹션을 추가합니다.

## 수행 단계

1. 사용자에게 추가할 섹션 내용 확인
2. 기존 디자인 시스템(색상, 타이포, 간격) 분석
3. 기존 스타일과 일관된 HTML + CSS 작성
4. 적절한 위치에 섹션 삽입
5. 반응형(900px, 640px) 스타일 추가
6. scroll reveal 애니메이션 적용 (.reveal 클래스)
7. 네비게이션에 링크 추가 (필요 시)

## 디자인 가이드
- 섹션 패딩: `padding: 100px 0`
- 컨테이너: `max-width: 1200px, padding: 0 32px`
- 제목: `.section-label` + `.section-title` + `.section-desc`
- 카드: `border: 1px solid var(--border)`, `border-radius: var(--radius)`
- 호버: `translateY(-2px)` + `box-shadow`
