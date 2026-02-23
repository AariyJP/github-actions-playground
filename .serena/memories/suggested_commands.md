# Suggested Commands For Windows (PowerShell)

## Git (Version Control)
- `git status`: ステータス確認
- `git checkout -b <branch-name>`: 新規ブランチ作成
- `git add .`: 変更のステージング
- `git commit -m "feat: <message>"`: コミット (Conventional Commits準拠推奨)
- `git push origin <branch-name>`: リモートへプッシュ

## GitHub CLI (gh)
- `gh pr create`: プルリクエスト作成
- `gh pr list`: プルリクエスト一覧
- `gh run list`: ワークフロー実行ログの確認
- `gh run view <run-id>`: 特定の実行詳細の確認

## Directory / File Management
- `ls`: ファイル一覧
- `cat <file>`: ファイル内容表示
- `grep -r "<pattern>" .`: パターン検索
