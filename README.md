# vector-store

VECTOR MODS の販売案内ページ（静的・HTML 一枚）。GitHub Pages 用。公開先の想定 URL: https://tomnexttech.github.io/vector-store/

## 中身
- `index.html` — 本体。CSS は内蔵、JS なし、外部フォント・外部スクリプトなし。英語が主（Gumroad）、日本語の節（BOOTH）つき。明暗は OS の設定に従う。
- `assets/` — 画像（JPEG、合計 約 0.65 MB）と `_license.txt`（出典・再配布可否）。
- `favicon.svg` / `favicon.ico` / `robots.txt` / `sitemap.xml`

## 公開の手順（これは実行していない）
1. このフォルダの中身を、リポジトリ `vector-store` の既定ブランチ直下へ置く。
2. GitHub の Settings → Pages で、そのブランチの root を公開元にする。
3. 公開後、`https://tomnexttech.github.io/vector-store/` が開くこと、og:image（`/assets/og.jpg`）が取れることを確かめる。

## 直すとき
- 値段・リンクは `index.html` の本文と、先頭の JSON-LD の二か所にある。両方を揃える。
- 値段が確かでない商品は JSON-LD の offers に入れない（DECK は発売前なので入れていない）。
- Minecraft に触れる所には、必ず「Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.」を添える。
