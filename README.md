# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)


## Setup

リポジトリをクローン後に一度だけ行う。

``` shell
npm -v

npm init --yes 

npm install zenn-cli

npm install zenn-cli@latest

npx zenn init
```

## Usage

記事を作成する度に行う。

``` shell
# ファイル作成
npx zenn new:article --slug <ファイル名-yyyymmdd>
# プレビュー
npx zenn preview
```