# minndmap-pages

Markdown-mindmap ファイルをマインドマップとして可視化し、GitHub Pages で公開するリポジトリです。

## 概要

`maps/` ディレクトリ以下に Markdown ファイルを置くと、[markmap](https://markmap.js.org/) を使って自動的に HTML のマインドマップに変換され、GitHub Pages で閲覧できます。

## ディレクトリ構成

```
maps/
└── personal/          # カテゴリごとにサブディレクトリで管理
    └── my-work-values.md
```

## GitHub Pages

公開URL: https://shoji0423.github.io/mindmap-pages/

`main` ブランチの `maps/**` に変更を push すると、GitHub Actions が自動でビルド・デプロイします。

## 使い方

1. `maps/` 以下に Markdown ファイルを追加する
2. `main` ブランチに push する
3. GitHub Actions が自動でマインドマップに変換して公開される
