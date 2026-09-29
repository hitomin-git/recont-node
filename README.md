# Recont Node

深海の原石から4つのブランドの輝きへつながる、Recont Nodeのコーポレートサイトです。

公開サイト: https://ricont-deep-sea-0925.hitomin-toke.chatgpt.site/

## ローカルで見る

ビルド不要の静的サイトです。Pythonがある場合、プロジェクトのルートで以下を実行して http://localhost:4173/ を開いてください。

```sh
python -m http.server 4173 --directory dist
```

## 構成

- `dist/index.html`: ブランド紹介・ページ本文
- `dist/style.css`: レイアウト・スマートフォン対応
- `dist/scene.js`: Three.jsによる海中・原石の描画
- `dist/opening.js`: オープニングの進行
- `dist/philosophy.js`, `dist/brands.js`: スクロール演出
- `.openai/hosting.json`: Sites公開先の設定（認証情報は含みません）

## 掲載情報の出典

2026年9月29日に公式サイトの内容を確認しました。営業時間・予約条件などの最新情報は各店舗の公式サイトをご確認ください。

- matchpomp: https://matchpomp.com/
- ゑむず: https://www.instagram.com/emuzu_akasaka/
- Mayro Pilates Studio: https://mayro-pilates.com/
- 中村鍼灸整体院: https://nakamuraseitai.jp/

## 公開・素材について

ホスティングはSitesを使用しています。GitHubへのpushだけでは本番サイトは更新されません。
ロゴ・店舗名・画像等の素材の権利は各権利者に帰属します。リポジトリの公開は素材の自由利用を許諾するものではありません。
