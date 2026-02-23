# 🧪 GitHub Actions Playground

[![Lint Workflows](https://github.com/AariyJP/github-actions-playground/actions/workflows/lint-workflows.yml/badge.svg)](https://github.com/AariyJP/github-actions-playground/actions/workflows/lint-workflows.yml)
[![Matrix Python Test](https://github.com/AariyJP/github-actions-playground/actions/workflows/matrix-test.yml/badge.svg)](https://github.com/AariyJP/github-actions-playground/actions/workflows/matrix-test.yml)
[![PR Labeler](https://github.com/AariyJP/github-actions-playground/actions/workflows/labeler.yml/badge.svg)](https://github.com/AariyJP/github-actions-playground/actions/workflows/labeler.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **"Learn by doing, master by playing."**  
> GitHub Actionsの実践的なパターンを詰め込んだ、究極の学習・実験用リポジトリ。

---

## 🚀 収録されているワークフロー (Current Features)

現在、このリポジトリには以下の自動化・実践例が実装されています：

| カテゴリ        | ワークフロー名          | 概要                                                 |
| :-------------- | :---------------------- | :--------------------------------------------------- |
| **Maintenance** | 📝 `Lint Workflows`     | `actionlint` を使用し、全YAMLの構文を自動チェック    |
| **Testing**     | ♾️ `Matrix Python Test` | Python 3.9〜3.12での並列テスト実行の実演             |
| **Automation**  | 🏷️ `PR Labeler`         | ファイルパスに基づき自動でラベルを付与               |
| **Automation**  | 🏁 `Auto Merge Release` | `develop` -> `main` への特定ラベル付きPRを自動マージ |
| **Management**  | 📦 `Dependabot`         | 依存関係（Actions等）を自動で最新に維持              |
| **Community**   | 👋 `Greetings`          | 初めての参加者へ自動で挨拶を送信                     |

---

## 🛠️ このリポジトリで学べること (Learning Steps)

1.  **基本的なトリガー**: `push`, `pull_request`, `workflow_dispatch` の使い分け。
2.  **権限管理**: `permissions` ブロックによる安全なトークン制御。
3.  **マトリックス戦略**: 複数の環境での並列テスト手法。
4.  **サードパーティActionの活用**: `reviewdog`, `labeler` などの有名なActionの組み込み方。
5.  **セルフリンティング**: 自分が書いたCIコードが正しいかをCIで保証する手法。

---

## 📖 クイックスタート (How to Test)

1.  **ブランチを作成**: `git checkout -b chore/add-more-play`
2.  **ファイルを編集**: `.github/workflows/` 内に新しい実験を追加。
3.  **プッシュ**: プッシュすると `Lint Workflows` が走り、構文ミスがないか教えてくれます。
4.  **PR作成**: ラベルが自動付与される様子や、テストが並列で走る様子を確認できます。

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).  
Feel free to fork and build your own playground!

---

Developed with 💖 by **あぁりー (AariyJP)** using **Antigravity (AI Agent)**.
