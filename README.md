<div id="top"></div>

## 使用技術一覧

<!-- シールド一覧 -->
<!-- 該当するプロジェクトの中から任意のものを選ぶ-->
<p style="display: inline">
  <!-- フロントエンドのフレームワーク一覧 -->
  <img src="https://img.shields.io/badge/-Node.js-000000.svg?logo=node.js&style=for-the-badge">
  <img src="https://img.shields.io/badge/-Next.js-000000.svg?logo=next.js&style=for-the-badge">
  <img src="https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/-TypeScript-20232A?style=for-the-badge&logo=typescript">
  <img src="https://img.shields.io/badge/-Redux-20232A?style=for-the-badge&logo=redux">
</p>

## 目次

1. [プロジェクトについて](#プロジェクトについて)
2. [環境](#環境)
3. [ディレクトリ構成](#ディレクトリ構成)
4. [デザイン](#デザイン)
5. [TODO](#TODO)

<!-- プロジェクト名を記載 -->

## プロジェクト名

myProfileSite

<!-- プロジェクトについて -->

## プロジェクトについて

React/Next.js を利用したポートフォリオサイト。

- 自己紹介
- 各種 SNS リンク
- 投稿したブログ
- contact

<!-- プロジェクトの概要を記載 -->

## 環境

<!-- 言語、フレームワーク、ミドルウェア、インフラの一覧とバージョンを記載 -->

| 言語・フレームワーク | バージョン |
| -------------------- | ---------- |
| React                | 18.2.0     |
| Next.js              | 13.4.6     |
| Next.js              | 13.4.6     |
| Next.js              | 13.4.6     |
| Next.js              | 13.4.6     |
| Next.js              | 13.4.6     |
| Next.js              | 13.4.6     |

その他のパッケージのバージョンは pyproject.toml と package.json を参照してください

## ディレクトリ構成

<!-- Treeコマンドを使ってディレクトリ構成を記載 -->

❯ tree -a -I "node_modules|.next|.git"
.
├── .eslintrc.json
├── .git
│ ├── COMMIT_EDITMSG
│ ├── HEAD
│ ├── config
│ ├── description
│ ├── hooks
│ │ ├── applypatch-msg.sample
│ │ ├── commit-msg.sample
│ │ ├── fsmonitor-watchman.sample
│ │ ├── post-update.sample
│ │ ├── pre-applypatch.sample
│ │ ├── pre-commit.sample
│ │ ├── pre-merge-commit.sample
│ │ ├── pre-push.sample
│ │ ├── pre-rebase.sample
│ │ ├── pre-receive.sample
│ │ ├── prepare-commit-msg.sample
│ │ ├── push-to-checkout.sample
│ │ └── update.sample
│ ├── index
│ ├── info
│ │ └── exclude
│ ├── logs
│ │ ├── HEAD
│ │ └── refs
│ │ ├── heads
│ │ │ └── main
│ │ └── remotes
│ │ └── origin
│ │ └── main
│ ├── objects
│ │ ├── 00
│ │ │ └── 4145cddf3f9db91b57b9cb596683c8eb420862
│ │ ├── 12
│ │ │ └── 9fa870ebf51cc7e7487916d05075ceabf49eaf
│ │ ├── 1b
│ │ │ └── 62daacff96dad6584e71cd962051b82957c313
│ │ ├── 25
│ │ │ └── 966cf1f7daef67d8dd51ed0467fa9348c61f9d
│ │ ├── 26
│ │ │ └── 2211524f06783d6195a801431dfd6a7ac898d3
│ │ ├── 37
│ │ │ ├── 224185490e6db2d26a574d66d4d476336bf644
│ │ │ └── 30dbd69cba6ac339c4b58d1d6ee2f3f591c7ba
│ │ ├── 43
│ │ │ └── 365afe3f291e3e46a6b8a024d175488536310e
│ │ ├── 51
│ │ │ └── 74b28c565c285e3e312ec5178be64fbeca8398
│ │ ├── 56
│ │ │ └── 7f17b0d7c7fb662c16d4357dd74830caf2dccb
│ │ ├── 5d
│ │ │ └── e84702f08db97e77b4202f7b3999ea494ca8cf
│ │ ├── 6e
│ │ │ └── 182ee8c4fea4bcf0cecaac6af6c37827a77a9f
│ │ ├── 71
│ │ │ ├── 8d6fea4835ec2d246af9800eddb7ffb276240c
│ │ │ └── e1342cdb7135c0949e1db4c6e02e09d8b02b0d
│ │ ├── 77
│ │ │ └── 053960334e2e34dc584dea8019925c3b4ccca9
│ │ ├── 84
│ │ │ └── af2cb0e607ae0c0820d45757eb35fbfc048e2b
│ │ ├── b2
│ │ │ └── b2a44f6ebc70c450043c05a002e7a93ba5d651
│ │ ├── c1
│ │ │ └── 334095f876a408c10f2357faaced969ec090ab
│ │ ├── c8
│ │ │ └── 8f389de09f418da376598c42e8788d4fb6d172
│ │ ├── d3
│ │ │ └── 2cc78b89fc9af2b1caf304864e10f041df05e6
│ │ ├── da
│ │ │ └── 22aa556a85e9e6c31838885ab922b365d3d5f2
│ │ ├── dc
│ │ │ └── a06aee77143fbbf6668760a6b8ca3b50bbf84d
│ │ ├── e2
│ │ │ └── 15bc4ccf138bbc38ad58ad57e92135484b3c0f
│ │ ├── e3
│ │ │ └── 734be15e1f6fbb4b207761c8e424b77cf3a4eb
│ │ ├── e9
│ │ │ └── ffa3083ad279ecf95fd8eae59cb253e9a539c4
│ │ ├── ee
│ │ │ └── 9b8e6339404c1a331833c3db7cc55b4045aab2
│ │ ├── f2
│ │ │ └── ae185cbfd16946a534d819e9eb03924abbcc49
│ │ ├── fc
│ │ │ └── b741a341df889205f9868e01cdef51cc530ae9
│ │ ├── info
│ │ └── pack
│ └── refs
│ ├── heads
│ │ └── main
│ ├── remotes
│ │ └── origin
│ │ └── main
│ └── tags
├── .gitignore
├── README.md
├── next-env.d.ts
├── next.config.ts
├── package-lock.json
├── package.json
├── public
│ ├── file.svg
│ ├── globe.svg
│ ├── next.svg
│ ├── vercel.svg
│ └── window.svg
├── src
│ └── app
│ ├── favicon.ico
│ ├── fonts
│ │ ├── GeistMonoVF.woff
│ │ └── GeistVF.woff
│ ├── globals.css
│ ├── layout.tsx
│ ├── page.module.css
│ └── page.tsx
└── tsconfig.json

## デザイン

ここに Figma で作成したイメージ画像を載せる

## TODO
- これを参考に要件定義を先に実施しようか
https://qiita.com/mosyaneko/items/8a084443ea60d8da9d53

- ヘッダー・フッターに何を追加するかまとめる
- TOPページをコンポーネント分解せずに作成する
- コンポーネント追加する
- 全体レイアウトを作成する

UIコンポーネントはStorybookに追加する
UIコンポーネントはテストを書くことを必須とする


https://blog.microcms.io/microcms-next15-jamstack-blog/を利用してブログを取得できるようにする
