# markdown-dev

Markdownファイルを管理・執筆するためのリポジトリです。

## 管理対象

`content/` ディレクトリ配下でMarkdownファイルを管理します。記事、書籍・技術書の原稿、個人的なメモやドキュメントなど、複数種類の文書を横断的に扱います。

```
content/
├── articles/  # 記事・ブログ用原稿
├── books/     # 技術書・書籍の原稿
└── notes/     # 個人的なメモ・ドキュメント
```

## 前提条件

[mise](https://mise.jdx.dev/) がインストールされ、シェルに統合されていること。

macOS (Homebrew):

```bash
brew install mise
```

シェル統合 (zsh):

```bash
echo 'eval "$(mise activate zsh)"' >> ~/.zshrc
source ~/.zshrc
```

## セットアップ

```bash
mise trust && mise run setup
```

gitleaks / lefthook のインストールと Git フックの設定が一括で行われます。

