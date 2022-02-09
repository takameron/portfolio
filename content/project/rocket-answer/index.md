---
title: 『Rocket Answer』のランキング機能
summary: 『Rocket Answer』というWebアプリのランキング機能を実装
tags:
- Ruby on Rails
- Web App
date: "2017-09-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: globe-asia
  icon_pack: fas
  name: Rocket Answer
  url: https://rocket-answer.com/
- icon: github
  icon_pack: fab
  name: GitHub
  url: https://github.com/KosenVenture/RocketAnswer
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

『Rocket Answer』というWebアプリケーションの、投稿者のランキング機能（[このページ](https://rocket-answer.com/ranking)）を実装しました。

Webアプリケーションについての知識は全くなかったため、Ruby on Railsの学習から始まりました。
既存のソースコードを解読して、やっとランキングが表示できるようになりましたが、レビューしていただくと、N+1クエリであることが判明したり、無駄に複雑なコードを書いていたことがわかりました。
ソースコードをリファクタリングしていただいて解説していただくと、いろいろとWebアプリに関する理解が深まりました。

開発環境をそろえるためにDockerを用いたので、Dockerについても触れる経験になりました。
また、データベースの扱い方、HTMLやCSS、セキュリティなど、Webアプリケーションに関するたくさんの知識を身につけられたので、貴重な経験になりました。


| 項目 |  値  |
| ---- | ---- |
| 言語 | Ruby |
| フレームワーク | Ruby on Rails |
