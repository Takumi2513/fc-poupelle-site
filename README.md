# FC POUPELLE Static Website

FC POUPELLEの静的ホームページです。GitHub Pagesで公開できる、HTML/CSSのみの構成です。

## メインHTML

現在使用しているメインHTMLファイルは以下です。

```text
fc-poupelle_HPsite.html
```

ファイル名は変更しません。GitHub PagesのルートURLで開けるように、`index.html` は入口用ファイルとして `fc-poupelle_HPsite.html` へ移動する役割にしています。

## ファイル構成

```text
WebSite_HP_FC POUPELLE/
├─ index.html
├─ fc-poupelle_HPsite.html
├─ style.css
├─ README.md
├─ CHANGELOG.md
└─ assets/
   ├─ logo.png
   └─ logo-clean.png
```

## 公開に必要な参照パス

- CSS: `style.css`
- ロゴ: `assets/logo.png`

どちらもルートからの相対パスで参照しています。GitHub Pagesでリポジトリ直下を公開する場合、この構成のままで読み込めます。

## セクションID

LINEリッチメニューなどから直接遷移する可能性があるため、以下のIDは維持します。

- `#about`
- `#event`
- `#payment`
- `#profile`
- `#instagram`
- `#contact`

ロゴ専用のブランド表示として `#brand` も追加しています。

## GitHub Pages公開手順の概要

1. このフォルダ内のファイル一式をGitHubリポジトリへアップロードする
2. GitHubのリポジトリ画面で `Settings` を開く
3. `Pages` を開く
4. `Build and deployment` の `Source` を `Deploy from a branch` にする
5. 公開ブランチを選ぶ
6. 公開フォルダをリポジトリ直下にする場合は `/root` を選ぶ
7. 保存後、表示されるGitHub Pages URLへアクセスする

GitHub Pagesは通常、公開フォルダ直下の `index.html` を入口として表示します。そのため、このサイトでは `index.html` を入口用に置き、実ページの `fc-poupelle_HPsite.html` へ誘導しています。

## 確認方法

1. `fc-poupelle_HPsite.html` をブラウザで開く
2. `index.html` を開いたときに `fc-poupelle_HPsite.html` へ移動することを確認する
3. Heroに次回予定が表示されていないことを確認する
4. Hero直下のBrand / Logoセクションで `assets/logo.png` が表示されることを確認する
5. EventセクションにNEXT EVENT、イベント名、日時、場所、料金、申込ボタン、支払い方法を見るボタンがまとまっていることを確認する
6. PC幅とスマホ幅で、文字やボタンが重ならないことを確認する
7. 仮情報や未設定情報が赤字・赤枠で表示されていることを確認する

## 仮情報の表示

作成段階で仮に入れている文言、金額、場所、QRなどは赤字・赤枠で表示しています。本番公開前に正式情報へ差し替えた箇所は、HTML上の `placeholder-*` クラスを外してください。

## 画像

ロゴは `assets/logo.png` を使用しています。画像パスは変更しないでください。
