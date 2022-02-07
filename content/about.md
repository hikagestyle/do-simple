+++
title = "あばうと"
date = 2022-01-01T00:00:00+09:00
template = "static.html"
+++

あばうとのページ。

![サンプル画像](../images/1920x1080.jpg)

固定ページと記事投稿は、相対リンクの階層が異なるので、記述に注意する。


## 環境

- x230(Lenovo ThinkPad)
- LinuxMint 20.2


## 補足

Zolaのクイックスタートをベースに、少しアレンジをした最低限のシンプルなテーマ。

3時間くらいで作ったので、かなりやっつけです。（2022-01-12）


### 2022-01-16（変更）

- 固定ページ追加
- css
- templates
- content内の.mdファイル


## 基本的な仕様

サクッと使う個人的な用途で小規模を想定。

blogフォルダへ投稿を詰め込んで、タグで仕分けるイメージ。

ドメイン直下、サブディレクトリでも、とりあえず使えるはず。（config.tomlのbase_urlによる）

- Zola v0.15.2
- pure.css
- config.toml
	- base_url（最後のスラッシュ無し）
- タグ（taxonomies）有効、カテゴリー無し
- 固定ページ
- ブログのページ送り:デフォルト10件ごと
- タグのページ送り:無し

基本的なファイル一式はGitHubに置いておきます。

<ul>
<li><a href="https://github.com/hikagestyle/zola-do-simple" target="_blank">zola-do-simple</a></li>
</ul>


## 公式サイト

<ul>
<li><a href="https://www.getzola.org/" target="_blank" rel="nofollow noopener noreferrer">Zola</a></li>
<li><a href="https://purecss.io/" target="_blank" rel="nofollow noopener noreferrer">Pure</a></li>
</ul>

