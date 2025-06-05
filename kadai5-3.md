## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
* エンドポイント:https://zipcloud.ibsnet.co.jp/api/search
* 機能:郵便番号をクエリとして送信して、結果をJSON形式で返す、その後,住所を表示。
* リクエストとレスポンスのフォーマット
* リクエストフォーマット：GET…https://zipcloud.ibsnet.co.jp/api/search?zipcode=郵便番号
* レスポンスフォーマット：JSON形式。
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
* API名：Open-Meteo API
* 参照URL：https://open-meteo.com/
* エンドポイントと機能
* エンドポイント：https://api.open-meteo.com/v1/forecast
* 機能：緯度・経度を指定して天気予報や現在の天気情報を取得できる。
* リクエストとレスポンスのフォーマット
* リクエスト：GET https://api.open-meteo.com/v1/forecast?latitude=35.68&longitude=139.76&current_weather=true
* レスポンスフォーマット：JSON形式。
### Q3-3. 感想
* 今回の課題で苦労したこと
* APIを探すことに苦労した。
* 演習を通して理解できたこと
* APIは、利用がしやすいものであると考えていたが規約などがしっかり読まなければならないと学んだ。
* Web APIの利便性や課題など
* APIを通すことで何かするときに作業が楽になると思うが、接続したりするまでが課題。
