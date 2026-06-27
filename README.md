# 株式会社 豊 (YUTAKA, INC.) コーポレートサイト

日本の農業を通じて「食卓を豊かに」することを目指す、株式会社 豊 のコーポレートサイトです。
静的な HTML / CSS / JavaScript で構成されており、ビルド工程は不要です。

## 配色・タイポグラフィ

| 役割 | 値 |
|------|----|
| 深緑 (メイン) | `#1F3A3D` |
| 和紙クリーム (背景) | `#F4EFE4` |
| 稲穂金 (アクセント) | `#C9A227` |
| 明朝 (見出し) | Shippori Mincho |
| ゴシック (本文) | Noto Sans JP |
| 欧文 | Cormorant Garamond |

## ページ構成

| ファイル | 内容 |
|----------|------|
| `index.html` | トップページ（インラインCSS・自己完結。`style.css` は読み込みません） |
| `about.html` | ABOUT — 私たちが考える「豊さ」とは |
| `story.html` | STORY |
| `service-megumi.html` | SERVICE 01 — 恵 (MEGUMI) |
| `service-global.html` | SERVICE 02 — GLOBAL |
| `company.html` | 会社情報（会社概要表 + Googleマップ アクセス） |
| `contact.html` | お問い合わせ |
| `style.css` | 子ページ共通スタイル（`index.html` 以外が読み込み） |
| `main.js` | スクロール演出などの共通スクリプト |
| `images/` | 各ページで使用する画像 |

## ローカルでの確認方法

任意の静的サーバーで配信できます。例：

```bash
# このフォルダ直下で
python3 -m http.server 8000
# → http://localhost:8000/index.html
```

## 確認・反映待ちの項目

公開前に下記の差し替えをお願いします（現在はプレースホルダー `#` のまま）。

- フッターの SNS リンク（YouTube / X / Instagram）
- `service-megumi.html` の「VIEW MORE →」が指す 恵 (MEGUMI) プラットフォームの URL
