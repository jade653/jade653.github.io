source "https://rubygems.org"

# GitHub Pages와 같은 버전의 Jekyll·테마·플러그인으로 로컬 미리보기
gem "github-pages", group: :jekyll_plugins

# Ruby 3.0+ 에는 웹서버가 기본 포함되지 않아 jekyll serve에 필요
gem "webrick"

# Windows용 시간대 데이터와 파일 변경 감지
platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end
