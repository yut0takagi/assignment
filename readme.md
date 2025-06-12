# 📚 Simple PDF Viewer with Tag Search (GitHub Pages Ready)

これは、GitHub Pages 上で動作するシンプルかつスタイリッシュな **PDFビューアー** テンプレートです。Tailwind CSS でスタイルされ、JSONファイルからPDF資料を読み込み、タグやキーワードで検索が可能です。

## 🎯 特徴

- 📄 PDFを`iframe`で右側に表示
- 🔍 タグ＆キーワード検索機能
- 🖼 Tailwind CSSによるシックなUI
- 📎 JSONファイルによる柔軟な資料管理
- 🗔 フルスクリーン表示対応（`viewer.html`）

## 💻 デモページ

👉 [GitHub Pagesでのデモはこちら](https://yut0takagi.github.io/assignment/)

## 🗂 ファイル構成

📁 assignment/
├── index.html               # メインビューアー
├── viewer.html              # フルスクリーンビューアー（オプション）
├── data.json                # 資料情報（JSON形式）
├── /pdf/                    # PDFファイル格納フォルダ
└── README.md

## 🛠 使い方

1. このリポジトリを `Use this template` または `Fork` します
2. `pdf/` フォルダに PDF ファイルを追加します
3. `data.json` にそのファイルの情報（タイトル・説明・タグなど）を記述します：

```json
[
  {
    "title": "AIと教育に関する発表資料",
    "path": "pdf/ai-education.pdf",
    "description": "ゼミ用スライド",
    "tags": ["AI", "教育", "スライド"]
  },
  {
    "title": "OpenPoseによるフォーム分析",
    "path": "pdf/form-analysis.pdf",
    "description": "実験レポート資料",
    "tags": ["スポーツ", "OpenPose", "実験"]
  }
]

4.GitHub Pages を有効にします（Settings → Pages → main branch → / (root)）

## 🖌 カスタマイズ例
- 背景をアニメーション付きにする → Vanta.js
- 検索バーにタグフィルターを追加
- FirebaseやGASでフォームと連携して登録可能に

---

