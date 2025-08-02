# つんどくアプリ Webページ

このフォルダには、GitHub Pagesで公開するWebページのファイルが含まれています。

## ファイル構成

- `index.html` - メインページ（アプリ紹介）
- `privacy-policy.html` - プライバシーポリシー
- `terms-of-service.html` - 利用規約
- `README.md` - このファイル

## GitHub Pages設定手順

### 1. GitHubリポジトリ作成
1. GitHub.comにログイン
2. 新しいリポジトリを作成
   - Repository name: `tsundoku-privacy`
   - Public に設定
   - Initialize with README をチェック

### 2. ファイルアップロード
1. 作成したリポジトリに移動
2. `Add file` → `Upload files`
3. このフォルダの3つのHTMLファイルをアップロード
4. `Commit changes`

### 3. GitHub Pages有効化
1. リポジトリの `Settings` タブ
2. 左サイドバーの `Pages`
3. Source: `Deploy from a branch`
4. Branch: `main` / `/ (root)`
5. `Save`

### 4. URL確認
約5分後に以下のURLでアクセス可能：
- メインページ: `https://[username].github.io/tsundoku-privacy/`
- プライバシーポリシー: `https://[username].github.io/tsundoku-privacy/privacy-policy.html`
- 利用規約: `https://[username].github.io/tsundoku-privacy/terms-of-service.html`

## ストア申請での使用

### App Store Connect
- App Information → Privacy Policy URL
- プライバシーポリシーのURL: `https://[username].github.io/tsundoku-privacy/privacy-policy.html`

### Google Play Console
- Store listing → Privacy Policy
- プライバシーポリシーのURL: `https://[username].github.io/tsundoku-privacy/privacy-policy.html`

## 注意事項

- HTMLファイルは日本語で作成されています
- モバイルフレンドリーなレスポンシブデザイン
- アプリのブランドカラー（#6B4A9A）を使用
- SEO対応済み（title, meta tags）

## 更新方法

1. HTMLファイルを編集
2. GitHubリポジトリにコミット
3. 自動的にGitHub Pagesに反映（数分後）