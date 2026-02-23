# Style and Conventions
- **YAML**: 標準的なYAMLフォーマット。
- **Branching Strategy**: 
  - `main`: プロダクション用（リリース先）。
  - `develop`: 開発用ブランチ。
- **GitHub Actions**:
  - `GH_TOKEN` には `${{ secrets.GITHUB_TOKEN }}` を使用。
  - 権限（`permissions`）は最小限に設定（`pull-requests: write`, `contents: write` など）。
  - ワークフローは特定の条件（ブランチ名、ラベルなど）に基づいて実行される。
