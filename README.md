# EtudeJPA
JavaSE環境で実行できるJPAの実装サンプルです。

## 主な実装済みのサンプルコード
- 動的クエリ用のBuilderクラス
- LocalDateTimeへのConverterクラス
- BooleanへのConverterクラス
- EnumへのConverterクラス
- EntityManager経由で挿入（persist）や更新（merge）する際にValidaterで検証する処理。

## その他留意事項
Lombokを使用しています。

DBに関してはこちらの記事の通りに作成しています。

[WindowsでApache Derbyを構築する手順書](http://qiita.com/nimzo6689/items/9b44f4bb2e446ca4938e)
