# vector-store

VECTOR MODS の販売案内ページ（静的 HTML）。GitHub Pages で公開: https://tomnexttech.github.io/vector-store/

## 中身
- `index.html` — 英語の頁（Gumroad が主）。
- `ja/index.html` — 日本語の頁（BOOTH が主）。hreflang で互いを指す。
- `assets/site.css` — 両方の頁が読む共通の CSS。意匠は白基調の製図（ライト）と氷のホログラム（ダーク）。色は白・水色・赤だけ。
- JS は二つだけで、どちらも頁に内蔵: 読み込み時のちらつきを防ぐ数行と、◐ 釦の明暗切替（選んだ側を localStorage に覚える）。外部フォント・外部スクリプトなし。
- `assets/` — 画像（JPEG）と `_license.txt`（出典・再配布可否）。
- `favicon.svg` / `favicon.ico` / `robots.txt` / `sitemap.xml`

## 直すとき
- 値段・リンクは各頁の本文と、先頭の JSON-LD の二か所にある。英語と日本語の二頁とも揃える。
- 値段: FUI Pack は $29 / ¥2,980、UI Kit は $39 / ¥3,980、ROOM と STREAM は各 ¥700、Field Notes は本 $29・本とキット $45。
- 値段が確かでない商品は JSON-LD の offers に入れない（DECK は発売前なので入れていない）。
- DL 数・星の数は載せない。JSON-LD は頁に見えている内容と一致させる。
- Minecraft に触れる所には、必ず「Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.」を添える。
- Claude Code に触れる所には、Anthropic とは無関係である旨を添える。
- 公開物に作者の個人名を入れない。名義は VECTOR（VECTOR MODS）。
