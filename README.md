# jade653.github.io

Jekyll 블로그 + HTML 포트폴리오

- 블로그 글: `_posts/YYYY-MM-DD-제목.md`
- 순수 HTML 페이지: 폴더에 front matter 없는 `index.html` (예: `portfolio/index.html`)

## 로컬 미리보기

GitHub에 배포할 때는 GitHub가 Jekyll을 실행하므로 아래 설치는 로컬 미리보기에만 필요합니다.

1. Ruby + DevKit 설치 (PowerShell, 설치 후 새 터미널 열기)

   ```bash
   winget install RubyInstallerTeam.RubyWithDevKit.3.3
   ```

2. 의존성 설치 (프로젝트 폴더에서)

   ```bash
   bundle install
   ```

3. 실행 후 http://localhost:4000 접속

   ```bash
   bundle exec jekyll serve
   ```
