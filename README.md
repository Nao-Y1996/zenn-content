# Zenn CLI

* [📘 How to use](https://zenn.dev/zenn/articles/zenn-cli-guide)

## メモ

記事を新規作成する

```bash
npx zenn new:article --slug {任意のスラグ}
```

プレビューを表示する

```bash
npx zenn preview
```

## リポジトリ管理ルール

### ブランチ

`main` ブランチのみを使用する。

### コミットメッセージ

- 記事の下書き: `draft:{slug}`
- 記事の公開: `publish:{slug}`
- 記事の修正: `update:{slug}:{修正内容}`
- リポジトリの整理: `refactor:{整理内容}`
