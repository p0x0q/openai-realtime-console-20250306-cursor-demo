# 技術スタック

このプロジェクトは OpenAI の Realtime API を WebRTC を使用してデモンストレーションするアプリケーションです。

## フロントエンド
- **React**: ^18.2.0
- **React DOM**: ^18.2.0
- **React Router DOM**: ^6.20.0
- **React Feather**: ^2.0.10（アイコンライブラリ）
- **History**: ^5.3.0（履歴管理）

## バックエンド
- **Node.js**
- **Express**: ^4.21.2（Webサーバーフレームワーク）
- **dotenv**: ^16.4.7（環境変数管理）

## ビルドツール
- **Vite**: ^5.0.2（フロントエンドビルドツール）
- **@vitejs/plugin-react**: ^4.3.4（Vite用Reactプラグイン）

## スタイリング
- **TailwindCSS**: ^3.4.1（ユーティリティファーストCSSフレームワーク）
- **PostCSS**: ^8.4.31（CSSプロセッサー）
- **PostCSS Nesting**: ^12.0.2（CSSネスト機能）
- **PostCSS Preset Env**: ^7.7.1（モダンなCSS機能のサポート）

## API
- **OpenAI Realtime API**（WebRTC経由）

## 開発環境
- **ESLint**（コード品質管理）
- **Prettier**: .prettierrc設定ファイルによる整形ルール

## デプロイメント
- 開発モード: `npm run dev`
- 本番モード: `npm start`
- ビルド: `npm run build`（クライアントとサーバーの両方をビルド） 
