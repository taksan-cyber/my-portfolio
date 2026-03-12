# ToolBox | 究極のオンライン便利ツール集

[![Powered by Antigravity](https://img.shields.io/badge/Powered%20by-Antigravity-blueviolet)](https://antigravity.google)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

ToolBoxは、日常生活や開発作業で頻繁に必要となるツールを一つにまとめた、高速・軽量・高機能なWebアプリケーションです。

## ✨ 特徴

- **13種類以上のツール**: テキスト変換、パスワード生成、計算機、QRコード、JSON整形、単位換算、Markdownプレビューなど。
- **プライバシー重視**: すべての処理はクライアントサイド（ブラウザ上）で行われ、サーバーにデータが送信されることはありません。
- **高速な動作**: バニラJSと高度に最適化されたCSS（グラスモフィズム設計）により、瞬時の読み込みと動作を実現。
- **PWA対応**: オフライン環境でも使用可能。
- **モダンなUI**: ダークモード標準対応。お気に入り機能や利用履歴も搭載。

## 🛠️ 搭載ツール一覧

- **Phase 1**: テキスト変換, パスワード生成, 計算機, タイマー, QRコード生成
- **Phase 2**: 単位換算, カラーコード変換, JSON整形, 統計情報
- **Phase 3**: Base64変換, URLエンコード, Markdownプレビュー, クイックメモ
- **Phase 4**: お気に入り機能, 利用履歴, PWA対応

## 🚀 技術スタック

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Logic**: 
  - `marked.js` (Markdown 変換)
  - `qrcode.js` (QRコード生成)
- **Framework**: Antigravity Python (Development)
- **Persistence**: LocalStorage (Settings & History)

## 📦 セットアップ

```bash
# 1. リポジトリをクローン
git clone https://github.com/your-username/toolbox.git

# 2. ディレクトリへ移動
cd toolbox

# 3. ブラウザで開く
open tool-site.html
```

## 📄 ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。
