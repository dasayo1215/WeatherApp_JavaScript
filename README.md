# WeatherApp_JavaScript

OpenWeather API を利用し、指定した都市の現在天気と3時間ごとの予報を取得・表示するアプリです。<br>
async/await による非同期通信とクラス設計で、データ処理とUI表示を分離しています。

## 🔗 動作デモ＆ソースコード（StackBlitzで開く）
[https://stackblitz.com/edit/vitejs-vite-9r4ridqs](https://stackblitz.com/edit/vitejs-vite-9r4ridqs)

## 📘 学習ポイント
- 外部APIの利用と非同期通信（fetch / async-await もしくは axios）
- クラス設計による責務分離（WeatherData / ForecastItem）
- localStorage管理と定期更新処理（setInterval）

## ⚙️ 実装機能
- 都市検索と天気表示（現在・予報）
- お気に入り都市リスト（localStorage保存）
- 1分ごとの自動更新
- 通信エラー時の通知表示・最終更新時刻の表示
