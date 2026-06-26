# CHANGELOG

## v0.7.1

- Heroの「FC POUPELLE」と「FOOTBALL, FRIENDS, GOOD ENERGY.」が途中で改行されないように調整
- CSSキャッシュ対策として `style.css` の読み込みバージョンを `v=0.7.1` に更新

## v0.7.0

- `index.html` のEventセクションを `NEXT EVENT` / `UPCOMING` の2段構成に更新
- NEXT EVENTを大きいカード、UPCOMINGを3件の小さいカードで表示
- 各イベントにイベント名、日時、場所、参加費、対象、ステータスを追加
- NEXT EVENTに「LINEで参加申込」と「支払い方法を見る」ボタンを配置
- Eventセクションの未確定要素を赤字表示にし、補足文でも明示
- スマホ表示でEventカードが縦に読みやすく並ぶようCSSを追加
- `index.html` を本番HTMLとして最新化し、`fc-poupelle_HPsite.html` は編集しない方針を維持

## v0.6.8

- READMEにユーザー担当、Codex担当、Codex非担当の役割分担を追加
- `index.html` を本番HTMLとして扱う方針を明確化
- `fc-poupelle_HPsite.html` は今後使用しない旧版・重複ファイルとして明記
- Git操作はユーザーがGitHub Desktopで行い、Codexは実行しない方針を明記
- GitHub Desktopでの作業フロー、キャッシュ対策、更新前チェックリストを整理
- `index.html` と `fc-poupelle_HPsite.html` は完全一致しており、旧HTMLから本番HTMLへ反映すべき差分がないことを確認

## v0.6.7

- ロゴ外周の白い円が残っていたため、CSSの円形クリップ範囲をさらに内側へ調整
- CSSキャッシュ対策のバージョンを `v=0.6.7` に更新

## v0.6.6

- ロゴ画像ファイルは変更せず、CSS側で表示サイズを調整
- `assets/logo.png` の外周の白い縁が見えにくいよう、各ロゴ表示を円形にクリップ
- Hero / Brand内の大きなロゴを少し小さく調整
- CSSキャッシュ対策としてHTML側の `style.css` 読み込みにバージョンを付与

## v0.6.5

- GitHub Pages入口ファイル名を `Index.html` から `index.html` に修正
- 公開時に大文字小文字で入口ファイルがずれないよう整理

## v0.6.4

- GitHub Pages公開前のファイル構成を整理
- 古い内容だった `index.html` を入口用ファイルに変更
- `index.html` から `fc-poupelle_HPsite.html` へ移動する構成に変更
- `style.css` と `assets/logo.png` の参照パスを確認
- READMEにGitHub Pages公開手順の概要を追記

## v0.6.3

- LINE公式アカウントURLを正式リンクとして反映
- Eventの申込ボタンをLINE公式アカウントへの外部リンクに変更
- ContactのLINE問い合わせボタンをLINE公式アカウントへの外部リンクに変更
- LINE関連ボタンの仮表示スタイルを解除

## v0.6.2

- Instagramリンクを正式URLに差し替え
- Hero、Instagramセクション、Contact内のInstagramボタンを外部リンク化
- Instagramセクションの仮表示スタイルを解除

## v0.6.1

- 仮情報や未設定リンクを赤字・赤枠で表示
- Eventの仮日時、場所、料金、対象、申込ボタンを仮表示として明示
- 支払いダミー情報、QRプレースホルダー、Instagram / LINE未設定リンクを仮表示として明示
- READMEに仮情報表示の確認方法を追記

## v0.6.0

- Hero右側からNEXT EVENT、COMING SOON、イベント説明文を削除
- Heroをメインメッセージ、サブコピー、CTA、ブランドビジュアル中心に整理
- Hero直下に `#brand` セクションを追加し、ロゴと短いブランド説明を分離
- `#event` セクションにNEXT EVENT情報を集約
- Eventカードにイベント名、日時、場所、料金、対象、申込ボタン、支払い方法を見るボタンを配置
- PC / スマホ表示でHeroが縦に長くなりすぎないよう余白とカードサイズを調整
- 文字化けしていた主要テキストを読みやすい日本語に修正
- READMEを現在のファイル構成と確認方法に合わせて更新

## v0.5.0

- Heroのロゴ表示を改善
- 白いチェッカーボード背景が目立つ問題を緩和
- ロゴをメインカード内で小さめに配置
- Hero右側をブランドカード風に変更

## v0.4.0

- CSSとロゴをHTMLへ組み込んだ単体確認用を作成

## v0.3.0

- FC POUPELLEロゴを組み込み
- Header / Hero / Profileにロゴを配置

## v0.2.0

- 黒とくすみゴールドの見た目を強めに調整
