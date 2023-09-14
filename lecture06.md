# 第6回課題

- ①CloudTrailのイベントを3つ確認する

- イベント１：StopInstances ⇒ 課題5実施時のインスタンス停止作業
![インスタンス停止](image/06_event1_stopinstance.PNG)

- イベント２：ConsoleLogin ⇒ AWSコンソールへのログイン
![コンソールlog in](image/06_event2_consolelogin.PNG)

- イベント３：DeleteBucketPolicy ⇒ S3バケットのポリシーの削除
![バケットポリシー削除](image/06_event3_deletepolicy.PNG)


- ②CloudWatchアラーム実装＆メール通知

- アラート設定画面
![アラート設定画面](image/06_alarts_info.PNG)

- アラートアクション画面
![アラートアクション画面](image/06_alarts_action.PNG)

- アラート履歴画面
![アラート履歴画面](image/06_alarts_logs.PNG)

- 実際のアラート通知
![アラート通知](image/06_alarts_mail.PNG)


- ③AWS利用料見積作成

- 見積画像
![見積１](image/06_AWS_calculator_1.PNG)
![見積２](image/06_AWS_calculator_2.PNG)
![見積３](image/06_AWS_calculator_3.PNG)

- 共有パス
[AWS calculator path](https://calculator.aws/#/estimate?id=897620030675032cd874dda65e2610fccb30a865)


- 今回の課題から学んだこと
- AWS意外とお金かかる。特にRDS。
- アラート通知は実態とある程度の時差が発生する。