# shoichirotanaka.com

[TANAAKK サイト規則](https://www.tanaakk.com/2026/03/11/grains-of-sand/) に準拠した、ライトカラーパターン・レスポンシブな静的サイトです。

## 構成

- `index.html` — メインHTML（スキップリンク、ヘッダー、ヒーロー、セクション、フッター）
- `styles.css` — ライトカラーテーマとレスポンシブ用CSS
- `script.js` — モバイル用ナビゲーション開閉

## ローカルで確認

```bash
# Python 3
python3 -m http.server 8000

# または npx
npx serve .
```

ブラウザで `http://localhost:8000` を開いてください。

## デプロイ

静的ファイル（`index.html`, `styles.css`, `script.js`）を任意のホスティング（Firebase Hosting, Netlify, Vercel 等）にアップロードしてください。