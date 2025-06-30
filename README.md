# Git-Rensyu（git の練習）

以下、すべて嘘です。
モダンな技術スタック（Next.js + TypeScript + Tailwind CSS）を使ったフルスタック Web アプリケーションです。  
コンポーネント設計、状態管理、API 連携、スタイリング、テストまでのベースが整っています。

---

## 🚀 主な機能・使用技術

- ✅ **Next.js** による SSR 対応 & ルーティング
- 🟦 **TypeScript** による型安全な開発
- 🎨 **Tailwind CSS** によるユーティリティファーストなスタイリング
- 🧩 **shadcn/ui** を利用したアクセシブルな UI コンポーネント
- ⚙️ API 通信（REST / fetch / axios など）
- 🧪 単体テスト & コンポーネントテスト（Jest + React Testing Library）
- 🔐 環境変数で設定可能な API キー管理

---

## 🛠 開発環境（Development Environment）

### 必要なもの（Prerequisites）

- Node.js（18.x 以上推奨）
- パッケージマネージャ（pnpm / yarn / npm）

### セットアップ手順

```bash
git clone https://github.com/your-username/mywebapp.git
cd mywebapp
pnpm install
開発用サーバー起動
bash
コピーする
編集する
pnpm dev
ブラウザで http://localhost:3000 を開いてください。

本番ビルド
bash
コピーする
編集する
pnpm build
pnpm start
📁 ディレクトリ構成
csharp
コピーする
編集する
mywebapp/
├── components/      # UIコンポーネント
├── pages/           # ページルーティング（Next.js）
├── lib/             # ヘルパー・ユーティリティ関数
├── hooks/           # カスタムフック
├── styles/          # スタイルファイル
├── public/          # 静的ファイル（画像・faviconなど）
└── tests/           # テストコード
```
