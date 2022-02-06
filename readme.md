# まえがき

Zola（静的サイトジェネレーター）のテーマ。

個人的なファイル一式。

修正や加工ほか、ご利用は自己責任で。


## 環境

- x230(Lenovo ThinkPad)
- LinuxMint 20.2


## 使い方

1. config.tomlの編集（base_url,title,description）
2. templatesを必要に応じて編集（_analytics.html,_sidebar.html）
3. 記事の作成（mdファイル,content/blog）
4. ローカルチェック（zola serve or zola serve --drafts）
5. ビルド（zola build or zola build --drafts）


## 補足

Zolaのクイックスタートをベースに、少しアレンジをした最低限のシンプルなテーマ。

3時間くらいで作ったので、かなりやっつけです。（2022-01-12）


### 2022-01-22（修正）

- static/css/style.css


### 2022-01-19（修正）

- content/about.md


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
- カテゴリー無し
- タグ（taxonomies）有効
- 固定ページ
- ブログのページ送り:デフォルト10件ごと
- タグのページ送り:無し


## 完成イメージ

デモサイト

https://zola-do-simple.netlify.app/


## 公式サイト

- [Zola](https://www.getzola.org/)
- [Pure](https://purecss.io/)

