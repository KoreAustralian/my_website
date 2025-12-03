# 포트폴리오 웹사이트

개인 포트폴리오 웹사이트입니다.

## 기능

- 반응형 디자인
- LinkedIn 및 GitHub 링크
- 포트폴리오 섹션 (추가 예정)
- 부드러운 스크롤 애니메이션

## 사용 방법

1. `index.html` 파일을 웹 브라우저에서 열기
2. 또는 로컬 서버를 통해 실행:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (http-server 설치 필요)
   npx http-server
   ```

## 커스터마이징

### LinkedIn 및 GitHub 링크 변경

`index.html` 파일의 연락처 섹션에서 링크를 수정하세요:

```html
<a href="https://linkedin.com/in/your-profile" ...>LinkedIn</a>
<a href="https://github.com/your-username" ...>GitHub</a>
```

### 포트폴리오 항목 추가

포트폴리오 섹션에 프로젝트 카드를 추가할 수 있습니다. `index.html`의 `portfolio-grid` 부분을 수정하세요.

## 기술 스택

- HTML5
- CSS3
- Vanilla JavaScript
- Font Awesome (아이콘)