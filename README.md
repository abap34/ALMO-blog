# ALMO-blog

ALMOを使ったブログ作成のテンプレートレポジトリ。

## 使い方

1. `config/config.json` を設定します。

```json
{
  // ページのルートパス。　GitHub Pagesの場合は https://{username}.github.io/{repository_name} になる
  "root_url": "https://abap34.github.io/ALMO-blog",
  // ブログのタイトル. 投稿一覧などのページに使われます。
  "blog_name": "abap34's blog",
  // 著者
  "author": "abap34",
  // メールアドレス
  "mail": "abap0002@gmail.com",
  // Twitter ID
  "twitter_id": "abap34",
  // GitHub ID
  "github_id": "abap34",
  // テーマ。themesフォルダにあるテーマを指定する
  "themes": "modern-light"
}
```

2. `generate.py` で記事のテンプレートを作成する。


