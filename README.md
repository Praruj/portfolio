<div align="center">

**Language / 言語:**  
[🇬🇧 English](#english) · [🇯🇵 日本語](#japanese)

</div>

---

<a name="english"></a>

# Praruj Thapa — Portfolio Website

> Personal portfolio for **Praruj Thapa**, Machine Learning & Computer Vision Engineer based in Osaka, Japan.

🔗 **Live site:** [PRaruj.github.io/praruj-portfolio](https://PRaruj.github.io/praruj-portfolio)

---

## Features

- **Bilingual (EN / 日本語)** — full language toggle, every section translates including nav, descriptions, dates, and labels. Built for Japanese recruiters.
- **Dark terminal aesthetic** — hacker-style design with scanline overlay, green-on-black palette, and monospace typography.
- **Active nav on scroll** — nav link for the current section highlights automatically as you scroll.
- **Responsive + mobile menu** — hamburger menu on small screens, single-column layout on mobile.
- **CV download button** — links to `cv.pdf` in the repo root.
- **Open Graph meta tags** — clean link previews when shared on LinkedIn, Discord, or Twitter.
- **Zero dependencies** — pure HTML, CSS, and vanilla JS. No frameworks, no build step.

---

## Sections

| # | Section |
|---|---------|
| 01 | About |
| 02 | Work Experience |
| 03 | Projects |
| 04 | Skills |
| 05 | Education |
| 06 | Contact |

---

## Project Highlights

**Automated Cap Opening & Closing Mechanism** — Capstone project with Shimadzu Corporation. Automated screw-type lab container caps using SolidWorks CAD, Arduino, servo motors, IR sensors, and electromagnets. 🏆 *Capstone Exhibition Award 2025*

**Smart Showcase Management System** — Industry project with フクシマガリレイ株式会社. Real-time shelf monitoring using Raspberry Pi + computer vision. Reduced manual stock checks for retail stores. 🏆 *Pre-Capstone Exhibition Award*

**ML & CV Learning Projects** — Personal GitHub repository documenting machine learning experiments and computer vision implementations from fundamentals to advanced models.

---

## Tech Stack

```
HTML5  ·  CSS3 (custom properties, grid, flexbox)  ·  Vanilla JS
Fonts: Share Tech Mono · Rajdhani · Noto Sans JP (Google Fonts)
Hosted: GitHub Pages
```

---

## Getting Started

No build tools needed — just open `index.html` in a browser.

```bash
git clone https://github.com/PRaruj/praruj-portfolio.git
cd praruj-portfolio
open index.html        # macOS
# or just drag into your browser
```

### Adding your CV

Place your CV as `cv.pdf` in the repo root. The **Download CV** button in the hero will automatically link to it.

```
praruj-portfolio/
├── index.html
├── cv.pdf          ← add this
├── preview.png     ← add this for Open Graph link previews (1200×630px)
└── README.md
```

### Updating Content

All content is in `index.html`. Each translated element uses `data-en` and `data-ja` attributes:

```html
<h2 data-en="About Me" data-ja="自己紹介">About Me</h2>
```

The JS reads these on toggle — just update both attributes and you're done.

---

## Deployment

This site is deployed via **GitHub Pages**.

1. Push changes to the `main` branch
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://PRaruj.github.io/praruj-portfolio`

---

## Contact

- 📧 thapa.praruj@gmail.com
- 💼 [linkedin.com/in/praruj-thapa](https://www.linkedin.com/in/praruj-thapa/)
- 🐙 [github.com/PRaruj](https://github.com/PRaruj)

---

<div align="right"><a href="#japanese">🇯🇵 日本語版を見る ↓</a></div>

---
---

<a name="japanese"></a>

# Praruj Thapa — ポートフォリオサイト

> 大阪在住の機械学習・コンピュータビジョンエンジニア **Praruj Thapa** の個人ポートフォリオです。

🔗 **公開サイト:** [PRaruj.github.io/praruj-portfolio](https://PRaruj.github.io/praruj-portfolio)

---

## 特徴

- **日英バイリンガル対応（EN / 日本語）** — ナビ・説明文・日付・ラベルを含む全セクションが切り替わります。日本語の採用担当者向けに対応。
- **ダークターミナルデザイン** — スキャンラインオーバーレイ、黒地に緑のカラーパレット、等幅フォントによるハッカー風デザイン。
- **スクロール連動ナビ** — 現在表示中のセクションに対応するナビリンクが自動でハイライト。
- **レスポンシブ + モバイルメニュー** — スマートフォン画面ではハンバーガーメニューに切り替わり、1カラムレイアウトで表示。
- **履歴書ダウンロードボタン** — リポジトリルートの `cv.pdf` にリンク。
- **Open Graphメタタグ** — LinkedIn・Discord・Twitterでリンク共有時にきれいなプレビューを表示。
- **ゼロ依存** — 純粋なHTML・CSS・バニラJSのみ。フレームワーク不要、ビルドステップなし。

---

## セクション構成

| # | セクション |
|---|-----------|
| 01 | 自己紹介 |
| 02 | 職務経歴 |
| 03 | プロジェクト |
| 04 | スキル |
| 05 | 学歴 |
| 06 | 連絡先 |

---

## 主なプロジェクト

**検体容器キャップ自動開閉機構** — 島津製作所との産学連携卒業研究。SolidWorks CAD・Arduino・サーボモーター・IRセンサー・電磁石を使用し、実験用ネジキャップの自動開閉を実現。🏆 *キャップストーン展示会賞 2025*

**スマート陳列棚管理システム** — フクシマガリレイ株式会社との産業プロジェクト。Raspberry Pi＋コンピュータビジョンによるリアルタイム棚管理。手動在庫確認の削減を実現。🏆 *プレキャップストーン展示会賞*

**機械学習・CVプロジェクト集** — 機械学習の実験とコンピュータビジョンの実装を記録した個人GitHubリポジトリ。基礎から応用まで学習の過程を網羅。

---

## 使用技術

```
HTML5  ·  CSS3（カスタムプロパティ・グリッド・フレックスボックス）  ·  バニラJS
フォント: Share Tech Mono · Rajdhani · Noto Sans JP（Google Fonts）
ホスティング: GitHub Pages
```

---

## 使い方

ビルドツール不要 — `index.html` をブラウザで開くだけで動作します。

```bash
git clone https://github.com/PRaruj/praruj-portfolio.git
cd praruj-portfolio
open index.html        # macOS
# またはブラウザにドラッグ＆ドロップ
```

### 履歴書の追加

`cv.pdf` をリポジトリのルートに配置すると、ヒーローセクションの「履歴書をDL」ボタンが自動的にリンクされます。

```
praruj-portfolio/
├── index.html
├── cv.pdf          ← 追加してください
├── preview.png     ← OGプレビュー用（1200×630px推奨）
└── README.md
```

### コンテンツの更新

すべてのコンテンツは `index.html` 内にあります。翻訳対象の要素は `data-en` と `data-ja` 属性を使用しています。

```html
<h2 data-en="About Me" data-ja="自己紹介">About Me</h2>
```

両方の属性を更新するだけで完了です。

---

## デプロイ方法

**GitHub Pages** を使用してデプロイしています。

1. `main` ブランチに変更をプッシュ
2. **Settings → Pages** を開く
3. ソースを `main` ブランチの `/ (root)` に設定
4. `https://PRaruj.github.io/praruj-portfolio` でサイトが公開されます

---

## 連絡先

- 📧 thapa.praruj@gmail.com
- 💼 [linkedin.com/in/praruj-thapa](https://www.linkedin.com/in/praruj-thapa/)
- 🐙 [github.com/PRaruj](https://github.com/PRaruj)

---

<div align="right"><a href="#english">🇬🇧 Back to English ↑</a></div>
