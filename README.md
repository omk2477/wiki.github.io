# Jekyll GitBook for SMC-Skills
[![Jekyll Themes](https://img.shields.io/badge/featured%20on-JekyllThemes-red.svg)](https://jekyll-themes.com/jekyll-gitbook/)

Wiki URL: [https://smc-skills.github.io/wiki.github.io/](https://smc-skills.github.io/wiki.github.io/)

## Demo

Live demo on Github Pages: [https://sighingnow.github.io/jekyll-gitbook](https://sighingnow.github.io/jekyll-gitbook)


### 로컬 설정

해당 테마는 루비와 젬파일들로 로컬에서 동작시킬 수 있습니다.

아래 설정 진행 후 [localhost:4000/wiki.github.io/index.html](localhost:4000/wiki.github.io/index.html) URL 로 접속이 가능합니다.

### Deploy Locally with Jekyll Serve

[Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) 

3줄 요약 
1. 루비 설치
2. bundle install
3. bundle exec jekyll serve

## Caution

root 디렉토리 index.md 에 가장 상위에는 아래 코드가 포함되어야 합니다.

해당 코드가 포함되지 않은 경우 404 에러가 발생합니다.

```
---
layout: home
---

```

## Full-text search

The search functionality in jekyll-gitbook theme is powered by the [gitbook-plugin-search-pro][5] plugin and is enabled by default.

[https://sighingnow.github.io/jekyll-gitbook/?q=generated](https://sighingnow.github.io/jekyll-gitbook/?q=generated)

## License

This work is open sourced under the Apache License, Version 2.0.

Copyright 2019 Tao He.

[1]: https://pages.github.com
[2]: https://pages.github.com/themes
[3]: https://github.com/sighingnow/jekyll-gitbook/fork
[4]: https://github.com/allejo/jekyll-toc
[5]: https://github.com/gitbook-plugins/gitbook-plugin-search-pro
[6]: https://github.com/rouge-ruby/rouge/tree/master/lib/rouge/themes
