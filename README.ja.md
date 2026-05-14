# wifisabae

福井県鯖江市の公衆WiFiスポットを表示するインタラクティブなマップです。このプロジェクトは、住民や訪問者が無料のインターネットアクセスを見つけるのに役立つよう、オープンデータを活用しています。

## デモ

**[ライブマップ: 鯖江WiFiマップ](https://code4fukui.github.io/wifisabae/)**

![OGPプレビュー](https://code4fukui.github.io/wifisabae/ogp.jpg)

## 機能

- 鯖江市内の公衆WiFiの場所をインタラクティブなマップ上で可視化します。
- 各スポットの推定電波到達範囲（半径30m）を半透明の円で表示します。
- クリックすると、SSID、パスワード、営業時間、電源の有無などの詳細情報が表示されます。
- 近くのWiFiスポットを見つけるための「現在地表示」ボタンを備えています。

## データと技術

このアプリケーションは、バニラHTML/CSSとJavaScript（ES Modules）で構築されています。

- **マッピング:** [egmapjs](https://code4fukui.github.io/egmapjs/egmap.mjs) を使用しています。
- **データソース:** [Open Data Platform (ODP)](https://odp.jig.jp/) からSPARQLクエリを使用してリアルタイムにデータを取得します。
- **データセット:** 鯖江市からCC BYライセンスで提供されている「[公衆無線LAN(福井県鯖江市)](https://ckan.odp.jig.jp/dataset/jp-fukui-sabae-173-odp)」。

## クレジット

APP:
