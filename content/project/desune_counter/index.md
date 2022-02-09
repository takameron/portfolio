---
title: desune_counter
summary: 指定した語が発声された時に反応する、遊びプログラム
tags:
- Demo
- NaturalLanguageProcessing
date: "2019-07-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub
  url: https://github.com/takameron/desune_counter
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

サクッと作る遊びプログラムとして、特定の語が話された場合に反応するプログラムを作成しました。

初めて「Julius」という音声認識エンジンを使用してみましたが、活用法によっては便利なプログラムを作れそうな感触を得ました。
音声認識は、まだ活躍できる余地があるような気がします。

また、今まではProcessingで文字の入力欄などの見た目を頑張って自作していました。しかし、SwingというGUIライブラリの存在を知って、簡単にそれなりの見た目にできる手軽さに喜びを覚えました。

反応時のエフェクトを面白くすれば、パーティーグッズのように使えるのではないかと期待しています。

| 項目 |  値  |
| ---- | ---- |
| 言語 | Processing |
| ライブラリ | Swing(GUIライブラリ)<br>Julius(汎用大語彙連続音声認識エンジン) (https://julius.osdn.jp/) |
