# Jekyll GitBook for SMC-Skills
[![Jekyll Themes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com/jekyll-gitbook/)

Wiki URL: [https://smc-skills.github.io/wiki.github.io/][1]

## 개요
SMC-Skills 위키에 오신것을 환영합니다.  
이 위키는 세명컴퓨터고등학교 기능반 학생들이 운영하며,  
근처 맛집 및 학교에 대한 정보를 표시합니다.  
  
특정 인물에 대한 비난과 같은 내용은 기재가 금지되며  
발견 시 삭제될 수 있음에 유의 바랍니다.

## 브랜치 전략

따로 기능적 추가가 필요없을것으로 판단되어 해당 저장소에서는 다음 규칙을 참고하시기 바랍니다.

메인 브랜치 : main 브랜치로 구성합니다.

보조 브랜치 : feature, bugfix 브랜치로 구성합니다.

feature : 내용 추가를 위한 브랜치입니다.

bugfix : feature 브랜치에서 발생한 버그를 수정하는 브랜치입니다.


### 로컬 설정

해당 테마는 루비와 젬파일들로 로컬에서 동작시킬 수 있습니다.

아래 설정 진행 후 [localhost:4000/wiki.github.io/index.html][2] URL 로 접속이 가능합니다.

[지킬 서버를 로컬에서 동작 하는 법][3]

__3줄 요약__ 
- 루비 설치
- 프로젝트 폴더에서 bundle install
- 프로젝트 폴더에서 bundle exec jekyll serve

## Caution

root 디렉토리 index.md 에 가장 상위에는 아래 코드가 포함되어야 합니다.

해당 코드가 포함되지 않은 경우 404 에러가 발생합니다.

```
---
layout: home
---

```

## Full-text search

The search functionality in jekyll-gitbook theme is powered by the [gitbook-plugin-search-pro][4] plugin and is enabled by default.

[https://smc-skills.github.io/wiki.github.io/?q=generated][5]

## License

This work is open sourced under the Apache License, Version 2.0.

Copyright 2019 Tao He.

[1]: https://smc-skills.github.io/wiki.github.io/
[2]: localhost:4000/wiki.github.io/index.html
[3]: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll
[4]: https://github.com/gitbook-plugins/gitbook-plugin-search-pro
[5]: https://smc-skills.github.io/wiki.github.io/?q=generated