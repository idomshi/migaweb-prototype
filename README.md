# みが市ウェブサイトプロトタイプ

## このリポジトリについて

Discordサーバーみが市のPRをするウェブサイトのプロトタイプ（試作版）です。
これをたたき台にして、カッコいいサイト（本番用）を作りましょう。

## 開発方法など

このサイトはNuxt3を使って作られています。Nuxt3の動作にはNode.js（最新のLTS版）が必要です。

NuxtはVue3を使って作ります。[Vue3の公式ドキュメント](https://v3.ja.vuejs.org/guide/introduction.html)を読むとだいたい使い方が分かります。日本語になっているし読みやすいよ。

Nuxt3の基本的な開発用のコマンドは次の通りです。
設定ファイルの書き方やディレクトリの役割などは[公式のドキュメント](https://v3.nuxtjs.org)を参照してください（そのうち日本語化されると思うよ！）。

### 最初の作業

リポジトリをローカルにクローンしたら、次のコマンドで環境をインストールしてください。

```bash
yarn install
```

### 開発用サーバーの起動

開発用のサーバーを起動するには次のコマンドを叩いて、http://localhost:3000 にアクセスしてください。

```bash
yarn dev
```

### 本番用ビルド

本番用にビルドします。

```bash
yarn build
```
