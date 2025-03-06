# ディレクトリ構成

このプロジェクトは以下のディレクトリ構造で構成されています。

```
.
├── .cursor/                   # Cursor IDE の設定ファイル
├── .git/                      # Gitリポジトリ情報
├── client/                    # フロントエンドのソースコード
│   ├── assets/                # 静的アセット
│   │   └── openai-logomark.svg # OpenAIのロゴ
│   ├── components/            # Reactコンポーネント
│   │   ├── App.jsx            # メインアプリケーションコンポーネント
│   │   ├── Button.jsx         # ボタンコンポーネント
│   │   ├── EventLog.jsx       # イベントログ表示コンポーネント
│   │   ├── SessionControls.jsx # セッション制御コンポーネント
│   │   └── ToolPanel.jsx      # ツールパネルコンポーネント
│   ├── pages/                 # ページコンポーネント
│   │   └── index.jsx          # メインページ
│   ├── base.css               # 基本スタイル定義
│   ├── entry-client.jsx       # クライアントエントリーポイント
│   ├── entry-server.jsx       # サーバーサイドレンダリングエントリーポイント
│   ├── index.html             # HTMLテンプレート
│   └── index.js               # メインJavaScriptファイル
├── coverage/                  # テストカバレッジレポート
├── docs/                      # プロジェクトドキュメント
│   ├── technology-stack.md    # 技術スタック情報
│   └── directory.md           # ディレクトリ構造情報
├── node_modules/              # Node.js 依存パッケージ
├── .env                       # 環境変数（非公開）
├── .env.example               # 環境変数のサンプル
├── .gitignore                 # Gitの無視ファイル設定
├── .prettierrc                # Prettier設定
├── LICENSE                    # ライセンス情報（MIT）
├── README.md                  # プロジェクト概要説明
├── package-lock.json          # パッケージのバージョン固定ファイル
├── package.json               # プロジェクト設定とスクリプト
├── postcss.config.cjs         # PostCSS設定
├── server.js                  # Express サーバー
├── tailwind.config.js         # Tailwind CSS 設定
└── vite.config.js             # Vite ビルド設定
```

## 主要コンポーネント

### バックエンド
- `server.js`: Express サーバーの設定と実行コード。OpenAI Realtime API とのインテグレーションを処理。

### フロントエンド
- `client/components/App.jsx`: メインアプリケーションの実装。WebRTC接続と状態管理。
- `client/components/EventLog.jsx`: 送受信されたイベントをログ表示するコンポーネント。
- `client/components/SessionControls.jsx`: セッション開始/停止などのコントロール。
- `client/components/ToolPanel.jsx`: 利用可能なツールを提供するパネル。

### ビルド設定
- `vite.config.js`: Vite ビルドツールの設定。
- `postcss.config.cjs`: PostCSS の処理設定。
- `tailwind.config.js`: Tailwind CSS のカスタマイズ設定。 
