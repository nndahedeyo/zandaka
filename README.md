# 残高帳 Zandaka

[日本語](#日本語) · [English](#english)

## 日本語

保有している暗号資産の銘柄と枚数を入れると、いまの評価額を表示するアプリです。iPhoneのホーム画面に置いて、普通のアプリのように使えます。日本語と英語に対応しています（端末の言語で自動的に切り替わり、設定から変更もできます）。

- 送金・署名の機能はありません。秘密鍵、復元フレーズ、ウォレットのアドレスは一切扱いません
- 端末の外に出るのは、価格を問い合わせる銘柄名だけです。枚数と評価額はその端末にだけ保存されます
- 価格は [CoinGecko](https://www.coingecko.com/) の公開APIから取得します

### できること

- 銘柄の検索と追加（時価総額の順位つき）
- 評価額の合計、24時間の増減、銘柄ごとの割合
- 目標の配分とのずれ（5ポイント以上ずれると赤）
- 自動更新、金額を隠す表示、バックアップの書き出しと読み込み
- 電波がないときは前回の価格で表示

### 公開のしかた（GitHub Pages・無料）

1. GitHubで公開リポジトリを作る（例：`zandaka`）
2. このフォルダのファイルをすべてアップロードする（「Add file」→「Upload files」）
3. 「Settings」→「Pages」で、Branchを `main`、フォルダを `/ (root)` にして保存
4. 数分後に `https://<ユーザー名>.github.io/zandaka/` で開ける

### iPhoneでアプリとして使う

1. Safariで上のアドレスを開く
2. 共有ボタン →「ホーム画面に追加」
3. ホーム画面の「残高帳」から開く

### 注意

表示される評価額は参考値です。投資の判断や税金の計算には、取引所や公式の記録を使ってください。

## English

Zandaka shows what your crypto is worth right now. Enter the coins you hold and how many, and it adds them up. Add it to your iPhone home screen and it works like a regular app. It runs in Japanese and English (it follows your device language, and you can switch in Settings).

- It can't send or sign anything, and never handles private keys, recovery phrases or wallet addresses
- Only the names of the coins you look up leave your device. Amounts and values stay on your device
- Prices come from the public [CoinGecko](https://www.coingecko.com/) API

### Features

- Search and add coins (with market-cap rank)
- Total value, 24h change, share by coin
- Distance from your target allocation (red at 5 points or more)
- Auto refresh, hide amounts, backup export and restore
- Shows the last prices when you're offline

### Publish it (GitHub Pages, free)

1. Create a public repository on GitHub (e.g. `zandaka`)
2. Upload every file in this folder ("Add file" → "Upload files")
3. In "Settings" → "Pages", set Branch to `main` and folder to `/ (root)`, then save
4. After a few minutes it opens at `https://<your-username>.github.io/zandaka/`

### Use it on iPhone

1. Open the address above in Safari
2. Tap Share → "Add to Home Screen"
3. Open "残高帳" from your home screen

### Note

Values are for reference only. Use your exchange's or other official records for investment decisions and taxes.

## Files

| File | Role |
| --- | --- |
| index.html | The app |
| manifest.webmanifest | App name and icons |
| sw.js | Lets the app open offline |
| icon-192.png / icon-512.png / apple-touch-icon.png | Icons |
