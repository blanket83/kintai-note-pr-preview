# 勤怠ノート PR プレビュー

このフォルダーは、ドラフトPR #1（コミット `25a44e9`）の画面確認用コピーです。

- `index.html` はPR版を元にしています。
- Supabase JavaScript CDNの読み込みと `cloud-sync.js` は含めていません。Supabaseへの通信・保存・取得はありません。
- ブラウザー内保存キーをプレビュー専用に分離しています。
- 個人情報や既存勤怠データは含みません。合成データだけを入力してください。実在のCSVは読み込まないでください。
- このコピーはステージング専用です。元の `blanket83/kintai-note`、`main`、本番Pages設定には変更を加えません。

## GitHub Pagesに置く手順

`kintai-note-pr-preview` という別リポジトリのルートに `index.html` を配置し、そのリポジトリだけで **Settings → Pages → Build and deployment** を設定します。元リポジトリのPages設定は変更しません。公開範囲とPages利用条件はGitHubの画面で確認してください。
