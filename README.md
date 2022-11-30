
# Project Build

## Theme

- Theme 적용

## Uploade

- Webrick 오류 해결

## Uploade : MongoDB
- Config 수정
- MongoDB 업로드

## Remove Posts and Update Config

- post.md 파일을 지울려했지만 다른 더미 파일을 지움
- bundle exec jekyll serve 명령어가 작동하지 않아서 오류 해결 시도

## Theme Remove (try:2)

- 기존에 있던 post.md 파일들 지움

## Update Config

- 커밋이 제대로 되지 않아서 커밋 후 푸시 테스트

## Modify config

- 블로그에 MongoDB 포스트가 보이지 않는 오류 해결 시도 1회 // url의 value값 변경


## Modify Config

- 블로그에 MongoDB 포스트가 보이지 않는 오류 해결 시도 2회 // 문법에 맞지 않는 내용 수정

## Modify config

 블로그에 MongoDB 포스트가 보이지 않는 오류 해결 시도 3회
- 커밋 후 푸시 작업이 제대로 이루어지지않은 줄 알고 한번 더 다시 커밋 후 푸시

## Modify Config and MonogoDB.md

 블로그에 MongoDB 포스트가 보이지 않는 오류 해결 시도 4회
- _config.yml에 futrue: true 추가
- _posts/2022-11-29-MonogoDB.md에 published: true 추가

## Modify Config and Monogo.db

 블로그에 MongoDB 포스트가 보이지 않는 오류 해결 시도 5회
- _config.yml에 timezone: Asia/Seoul 추가
- _posts/2022-11-29-MonogoDB.md에 date:	2022-11-29 14:26:02 +0900 값 변경
- 파일의 인코딩의 문제인걸 발견해서 _posts/2022-11-29-MonogoDB.md의 인코딩을 UTF-8로 인코딩 변경

## Upload Markdown.md

- Upload _posts/2022-11-28-MarkDown.md
- Gemfile에 gem "tzinfo", "~> 2.0" ,gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw] 추가
- README.md 내용 삭제

## Update Disqus

 -_config.yml에 

```html
# Custom vars
version : 1.1.0
google_analytics_id: #UA-XXXX-Y
comment:
    provider:       "disqus"
    disqus:
        shortname:  "kmu-hyunsik"
```
- _layouts/post.html 내용 변경
- _posts/2022-11-28-MarkDown.md에 comments: true 추가
- _posts/2022-11-29-MonogoDB.md comments: true 추가

## Modify Config and post.html

- _config.yml에         comments: true 추가
- _layouts/post.html 내용 변경

## Modify Config and post.html

- _config.yml 문법 올바르게 수정
