---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "radikoのAPI仕様について"
subtitle: ""
summary: ""
authors: []
tags: []
categories: [memo]
date: 2020-04-12T12:58:36+09:00
lastmod: 2020-04-12T12:58:36+09:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# 番組表
radikoの番組表は、地域コードを指定すれば
http://radiko.jp/v3/program/today/JP13.xml
で取得できる。

現在放送している番組は、
http://radiko.jp/v3/program/now/JP13.xml
で、現在と一つあとの番組が取得できる。

## XMLデータ


# 完成したファイル
aacのまま保存、.m4aで保存していく。
番組表データや、番組ロゴなどをファイルに埋め込む予定。