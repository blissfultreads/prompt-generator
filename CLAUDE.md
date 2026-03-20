# Project Rules for Claude Code

## GitHub Pages 배포 규칙
- 배포 기준 파일은 반드시 `index.html` 하나만 사용한다
- 새로운 `.html` 파일을 별도로 생성하지 않는다
- 기능 추가/수정 시 항상 기존 `index.html`을 직접 수정한다
- 작업 완료 후 `prompt-generator.html` 등 중복 파일이 있다면 삭제한다

## 파일 구조 원칙
- 진입점: `index.html` (절대 변경 금지)
- 스타일/스크립트는 `index.html` 내부에 인라인으로 작성하거나
  별도 `style.css`, `script.js` 파일로 분리 가능
- 새로운 페이지 기능은 `index.html` 안에서 섹션/탭으로 구현할 것

## 커밋 메시지 규칙
- 한국어 또는 영어 모두 가능
- 변경 내용을 명확하게 기술할 것
