# リリース通知くん -お気に入りアーティストの新曲お知らせBot-



## サービス概要
「学生時代に推しだったアーティストのアルバム最近全然追えてないなぁ・・・」　  
ーーこんな悩みをお持ちのあなた！  
日々、忙しく過ごしているとアーティストの活動を追いかけるのって大変ですよね  
本サービスでは、LINE通知を利用し、事前に登録したお気に入りアーティストの新曲リリース情報をいち早くお知らせいたします！  

## 想定しているサービスの流れ
1. SpotifyAPIを利用して、ユーザーにお気に入りのアーティストを登録してもらいます
1. User情報に登録アーティストを紐づけて保存しておきます
1. 定期実行の処理で、登録したアーティストの最新曲のリリース日付を取得
1. 現在日付と一致しているか確認
1. 一致していた場合は新曲リリースありと判断し、LINEBOTにて通知をユーザーに送信


## 使用予定の技術
### バックエンド
- Ruby on Rails
### フロントエンド
（検討中）
- react
- svelte
- TypeScript
=> TS・Reactでやってみる
### 外部API
- SpotifyAPI
- LINEログイン API
- LINE Messaging API
### インフラ・その他
- 要検討
