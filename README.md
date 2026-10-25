# 🦊 ByakuyaTools V2 — Developer & Management Control Center

<p align="center">
  <img src="Developer.jpg" alt="Developer Icon" width="110" style="border-radius: 12px; border: 2px solid #00F58A; vertical-align: middle; margin-right: 14px;">
  <span style="font-size: 24px; font-weight: bold; vertical-align: middle;">Developer Byakuya</span>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Deno-v2.0-00F58A?style=for-the-badge&logo=deno&logoColor=black" alt="Deno">
  <img src="https://img.shields.io/badge/LINEJS-v3.4.2-00F0FF?style=for-the-badge&logo=line&logoColor=black" alt="LINEJS">
  <img src="https://img.shields.io/badge/Render-Deployed-78FFC0?style=for-the-badge&logo=render&logoColor=black" alt="Render">
  <img src="https://img.shields.io/badge/License-MIT-FFB800?style=for-the-badge" alt="License">
</p>

> **ByakuyaTools V2** は、LINE OpenChat および LINEJS 環境に特化した次世代カスタマイズ・ハッカー調開発者管理ポータル（Control Portal）です。

---

## 🌐 Production Live URL
- **Live Portal:** https://line-tools-qmzy.onrender.com/

- **Official LINE Account Tool🧰🔨** <img width="100" height="120" alt="image" src="https://github.com/user-attachments/assets/4e4f4a36-a113-43de-9589-c01633aa199f" />
https://line.me/R/ti/p/@605labgl

- **Local Dev Endpoint:** `http://127.0.0.1:8000`

---

## 🔥 Key Features

- ⚡ **Developer SPA Portal Dashboard**
  - ネオングリーン×ダークテーマのハッカー風コントロール UI（4色カラーテーマ切り替え対応）。
  - Welcome 画面からの滑らかなズームイン/ズームアウト遷移アニメーション & サイバータイピング演出。
- 🔑 **AuthToken Sync Manager**
  - LINE JS 認証トークンの安全な発行、暗号化保存、ワンクリックコピー & QR コード即時生成。
- 🤖 **LINEJS Auto-Reply Tester**
  - Webhook 連携ルールをその場で対話テストできるインタラクティブ・シミュレータモーダル。
- 📊 **Realtime Deno Resource Monitor**
  - Deno サーバーの稼働時間（Uptime）、ヒープメモリ使用量（Heap Memory）、総リクエスト数、Ping レイテンシをグラフィカル表示。
- 📜 **Live Terminal & Session Manager**
  - リアルタイムシステムログストリーミングおよびアクティブセッションの監視機能。
- 📱 **Full Mobile & PC Responsive UI**
  - スマホ・PC・タブレットの画面幅に合わせた自動最適化レイアウト。

---

## 🛠️ Tech Stack

- **Backend / Server:** Deno runtime, TypeScript
- **Frontend SPA:** HTML5, CSS3 (Modern Flexbox/Grid, Neon Effects), Vanilla JavaScript
- **API Engine:** LINEJS, LINE Messaging API (Webhook)
- **Deployment Platform:** Render Node Environment

---

## 🚀 Getting Started (Local Development)

```bash
# 1. Repository Clone
git clone [https://github.com/byakuya-121/ByakuyaTools.git](https://github.com/byakuya-121/ByakuyaTools.git)
cd ByakuyaTools

# 2. Run Integrated Deno Server
deno run --allow-net --allow-env --allow-read server.ts
