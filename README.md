# forcodextesting
nothing to say, just testing how can I code

## Mr. Dottyと、旅の計画を。

ChatGPT Sitesで作成した日本語の旅行計画体験記です。HTMLとCSSのみで構成され、ビルドや依存パッケージは不要です。

### ファイル

- `dist/index.html`: 記事本文とCSS。ブラウザーで直接開いて表示できます。
- `.openai/hosting.json`: 既存のChatGPT SitesのサイトIDと静的ファイルの公開先設定。

### ローカルで表示

`dist/index.html`をブラウザーで開くか、リポジトリのルートで次を実行します。

```sh
python3 -m http.server 8000 --directory dist
```

その後、`http://localhost:8000`を開きます。

### 公開とアクセス設定

このGitHubリポジトリへのコミットだけでは、Sitesは自動更新されません。Sitesでの公開操作が別途必要です。閲覧範囲はSites側で管理され、このコードには認証情報を含めていません。

Notionは記事作成時の参照元であり、実行時のNotion連携はありません。個別の渡航日・予約情報・Notion内部リンクは掲載していません。
