# rumath-prog2

[English](./README.md) | 日本語

龍谷大学先端理工学部数理・情報科学課程「プログラミング及び実習2」（C 言語）の講義ページ。

## 講義ページ

GitHub Pages で公開しています: **<https://sanoakr.github.io/rumath-prog2/>**

`docs/` を [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) でビルドし、
`main` への push ごとに `.github/workflows/pages.yml` がデプロイします。
各回のページは講義の進行に合わせて追加します。姉妹科目
（[rumath-network](https://github.com/sanoakr/rumath-network)）と共通の環境構築ガイドはこちらに置きます。

```fish
uv sync                 # mkdocs-material をインストール
uv run mkdocs serve     # http://127.0.0.1:8000/rumath-prog2/ でプレビュー
```
