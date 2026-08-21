# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## リポジトリ概要

SamplePages は GitHub Pages サイト用の最小限のサンプルリポジトリです。現在は Markdown コンテンツのみで構成されています:

- `README.md` — リポジトリ名のみ
- `index.md` — サイトのトップページ(現在は空)。GitHub Pages によってレンダリングされます

git の履歴を見ると、当初は `index.html` を使っていましたが、意図的に `index.md` へ置き換えられています(コミット「mdファイルに変更」)。特に指示がない限り、生の HTML を再導入せず、ページコンテンツは Markdown で作成してください。

## 開発

ビルドシステム、パッケージマネージャ、リンター、テストスイートはありません。ページはプレーンな Markdown で、push すると GitHub Pages(Jekyll)がレンダリングします。実行すべきコマンドはなく、変更は Markdown の内容を確認するだけで検証できます。

## 規約

- デフォルトの作業ブランチは `develop` です(`main`/`master` はありません)。
- コミットメッセージは従来日本語で書かれています(例:「index md追加」)。日本語・英語どちらでも、短いメッセージで問題ありません。
