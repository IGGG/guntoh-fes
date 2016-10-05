# 群桐祭 2016

IGGG は群馬大学理工学部の学園祭 "群桐祭" で催される "テクノドリームツアー" というイベントに出展する。
その時に用いたプログラムやサイトを管理する用のリポジトリ。

群桐祭については[公式サイト](http://guntohfes.com/)を参照してください。

## テクノドリームツアー

園児から中学生ぐらいが対象の科学系の体験型イベント。
基本的に研究室がその研究室のいろを出して出展する。

例えば：

- 情報の研究室なら子供向けのゲームブースを
- 化学の研究室ならスライム作りとか
- 機械の研究室ならペットボトルロケットとか

を出している。

## IGGG では

自分たちで作ったゲーム・アプリないしは、伝手のある研究室から借りたソフトウェアを展示して遊んでもらう。

![image](./fig/leaflet.png)

## ブランチについて

- master : 一応公開用でココを直接はいじらない
- develop : なんか追加したいときにはココからブランチ切ってください
- gh-page : IGGG の群桐祭に関する WEB サイト

## GitHub Pages

Jekyll を利用しています。

使いたかった良い感じテーマが Jekyll にあったからです。
カラースキームを IGGG カラーにして [Cleative Theme](https://github.com/volny/creative-theme-jekyll) を使わせてもらってます。
Thanks !!!

This software includes the work that is distributed in the Apache License 2.0

いじりたいときは `gh-pages` のブランチで

1. Ruby と Gem をインストールして Jekyll をインストール `gem install jekyll`
2. いろいろといじる
3. `jekyll serve` で確認

だけ、とても簡単！
出来たら push すれば反映されます。
(できればさらにブランチを切ってプルリクしてくれるとよいかも)
