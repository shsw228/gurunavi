# 簡易仕様書

作者     ：祖父江　亮

アプリ名 ：gurunavi

git      ：https://github.com/

対象OS  ：iOS

対象Ver  ：9.0~11.2

開発環境 ：Xcode 8.2

開発言語 ：Swift 3.0


## 機能一覧

|機能名|機能説明|
|:--:|:--:|
|レストラン検索|ぐるなびAPIを使用して、現在地周辺の飲食店を検索する。|
|レストラン情報取得|ぐるなびAPIを使用して、飲食店の詳細情報を取得する。|
|電話アプリ連携|飲食店の電話番号を電話アプリに連携する。|
|地図アプリ連携|飲食店の所在地を地図アプリに連携する。|

## 画面一覧

|画面名|画面概要|
|:--:|:--:|
|検索画面|条件を指定してレストランを検索する。|
|一覧画面|検索結果の飲食店を一覧表示する。|
|詳細画面|選択した飲食店の情報を表示する。|

## 使用しているAPI,SDKなど

- [ぐるなびAPI](http://api.gnavi.co.jp/api/manual/restsearch/)


## コンセプト

- 食べに行きたいお店がすぐ見つかる。
- すぐに電話予約ができる。


## こだわったポイント

- ユーザーが飲食店を探していて違和感をあまり感じないようにUI/UXを考慮した。
- 必要な情報がすぐ、探し回らなくても見つかるようにした。


## アドバイスして欲しいポイント

- ローディングの表示するタイミングをもっと適切にしたい。
- データの取り扱い方はどうすればベストかを教えて欲しい。
- パフォーマンスについてあまり考えたことがないので、この機会にぜひ教えていただけたらと思います。
(APIで受け取ったデータは別の構造体で保存しておくべき？そのままjsonで管理しておくべき？クラスを定義してそこに全データをまとめるべき？)
- LINEなどSNSで共有できるボタンなど、まだ詳細画面に表示させたいものは多数あるので、最適なレイアウトを見つけたい。

## その他、申し送り

- 提出遅れまして大変申し訳ありません。一通り無事完成しましたが、予想外の挙動や表示がまだされるかもしれません。バグ取りや例外処理もこういうところをチェックするといい、など知りたいことが様々ありますので、よろしくお願い致します。
- キーワード検索は実装はしましたが動作保証外とさせてください。
- 検索結果のページング(一番下に行くまでにテーブルセルを補充する)、スクロールビューでの実装はほぼ必須と考えています。
- お店のURLへ飛ぶ独自ブラウザも作りたいと考えています。

