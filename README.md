# textlint-rule-preset-stlato

技術記事をよりスマートに。

Zennへの技術的な投稿やテクニカルライティングに最適なtextlintルールプリセットを提供します。

このtextlintのルール設定のプリセットを使うと、日本語のミスや技術的用語の間違いを自動で検知することができます。

## インストール

```bash
yarn add textlint-rule-preset-stlato
```

## 基本設定

```json
// .textlintrc
{
  "rules": {
    "preset-stlato": true
  }
}
```

## 使い方

### Via CLI

```bash
textlint --rule preset-stlato README.md
```

### Via npm command

```json
// your package.json
"scripts": {
  "textlint": "textlint ./**/*.md"
},
```

```bash
yarn textlint
```

## 参考

[記事を書くときの自分ルール](https://zenn.dev/suzuki_hoge/articles/2022-12-output-my-rule-37db5df201ba16)
[私の技術記事の書き方](https://azukiazusa.hatenablog.com/entry/2023/01/02/162336)
[フロントエンド開発にtextlintを導入して運用している話](https://speakerdeck.com/diescake/hurontoentokai-fa-nitextlintwodao-ru-siteyun-yong-siteiruhua)
# textlint-rule-preset-stlato
