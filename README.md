# Portfolio Website

Personal portfolio website.

## Features

- Responsive design
- LinkedIn and GitHub links
- Portfolio section with project cards
- Smooth scroll animations

## Usage

## 사용 방법

1. Open `index.html` in a web browser directly, or
2. Run a local server:
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