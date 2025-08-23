# News Vault 📰

週刊ニュース自動収集システム for Obsidian - Powered by Grok & n8n

このリポジトリは、n8nワークフローを使用してAIとテクノロジーニュースを自動収集し、Obsidianで管理するためのVaultです。

## 📁 フォルダ構造

```
news-vault/
├── AI-News/          # AI関連ニュース
├── Tech-News/        # テクノロジーニュース
├── Templates/        # Obsidianテンプレート
├── Attachments/      # 添付ファイル（画像など）
└── README.md
```

## 🛠 セットアップ

### 1. リポジトリのクローン
```bash
git clone https://github.com/x24ken/news-vault.git
```

### 2. Obsidianでの開き方
1. Obsidianを起動
2. 「Open folder as vault」を選択
3. クローンした `news-vault` フォルダを選択

### 3. n8n連携の設定
n8nワークフロー「grok-news-obsidian」が以下の処理を自動化します：
- Grok APIを使用したニュースの収集・要約
- 自動的なマークダウンファイル生成
- GitHubへの自動プッシュ

## 📝 使用方法

### ニュースファイルの管理
- **AI-News/**: AI、機械学習、データサイエンス関連のニュース
- **Tech-News/**: 一般的なテクノロジーニュース

### テンプレートの活用
`Templates/` フォルダにObsidian用のテンプレートを配置し、一貫したフォーマットでニュース記事を管理できます。

### 添付ファイルの管理
画像やその他のメディアファイルは `Attachments/` フォルダに保存されます。

## 🔄 ワークフロー

1. n8nワークフローが定期的に実行
2. 最新ニュースを収集・要約
3. 適切なフォルダにマークダウンファイルを生成
4. GitHubに自動コミット・プッシュ
5. Obsidianで同期して閲覧

## 🚀 特徴

- **自動収集**: n8nによる完全自動化
- **AI要約**: Grokを使用した高品質な要約
- **Obsidian最適化**: リンクとタグを活用した知識管理
- **GitHub連携**: バージョン管理とバックアップ

## 📧 お問い合わせ

このリポジトリに関するご質問やフィードバックがございましたら、Issuesにてお知らせください。
