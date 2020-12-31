---
date: 2020-12-27
title: "Win10 + GitHub Pages + Hugoで無料ホームページを作る"
tags: ["Hugo", "css", "GitHub"]
categories: ["Hugo"]
---

何番煎じかわかりませんが、Windows10 + GitHub Pages + Hugoで簡単無料ホームページを作りましょう。

## GitHubアカウントの作成

GitHubアカウントを [公式ページ ](https://github.com/)より作成してください。トップページ右上のSign upをクリックし、必要な情報を入力してください。

![image-20201227215145803](./image-20201227215145803.png)

## GitHub Desktopのインストール

CUI によるレポジトリ管理でもいいですが、最近私は GUI の **GitHub Desktop** を使うことが多いです。コード差分がわかりやすく、なにより楽でいいですね。~~コマンドすぐ忘れる。~~

[GitHub Desktop](https://desktop.github.com/)よりインストールしてください。また、GitHubアカウントがない方はあらかじめ作成しておいてください。

## Hugoのインストール

Hugo をインストールしましょう。[公式ページ](https://gohugo.io/getting-started/installing/) によると、Windows の場合は chocolatey/scoopでインストールできるようです。私は chocolatey でインストールしました。

PowerShell を管理者権限で開き、以下のコマンドを入力してください。ここでは必ず ```hugo-extended``` を指定してください。

```bash
$ choco install hugo-extended
```

正しくインストールできたか確認しましょう。バージョン情報が表示されたらOKです。

```bash
$ hugo version
Hugo Static Site Generator v0.79.1/extended windows/amd64 BuildDate: unknown
```

## Hello! Hugo!







## GitHub にプッシュ

