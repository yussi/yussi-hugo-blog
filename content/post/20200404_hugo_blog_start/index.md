---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Hugoでブログを作成してみた"
subtitle: ""
summary: ""
authors: []
tags: []
categories: [diary]
date: 2020-04-04T23:19:36+09:00
lastmod: 2020-04-04T23:19:36+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "本文とは全く関係ありませんが、去年とった桜の写真。京急三浦海岸〜三崎口駅にて"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# はじめに
ときどきブログを書きたい気分になって、時々Wordpressやはてなブログを使っていました。で、途中で飽きてしまうのですが、以前のブログを削除すると今まで書いていた文書が全部消えてしまいます。なにかのきっかけで読み直したいことがあるので、なんとか上手に管理できないかと思っていました。

最近はHugo, Hexoなどの静的サイトジェネレータを用いたサイト作成が流行しているようなので、流行に乗っかって使ってみます。Wordpressのようにセキュリティ対策のバージョンアップやスパムに悩まされることも減りそうです。

# Hugoのインストール
Wordpressインストール職人として、無駄に場数を踏んできましたが、Hugoでブログ作るのは非常に簡単でした。HugoとAcademicテーマをGithubにデプロイして、Netlifyと連携するだけで公開できちゃいます。

記事はすべてMarkdownで記述して、Githubのレポジトリで管理できるため、VSCodeやEmacsなどのエディタでどのマシンからも編集できます。画像の取り扱いは、Wordpressなどと比べるとリッチなエディタが無いため若干面倒ですが、慣れれば何とかなりそう。

# 今後の予定
趣味のカメラやラジオの話とか、技術関係で勉強したことをアウトプットできればと思います。