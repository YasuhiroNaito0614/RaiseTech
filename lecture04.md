# 第四回課題

- VPCの構築、RDS、EC2の配置を実施。
- EC2に接続しMYSQLをインストール・ログインが可能であることを確認した。

- EC2にインストールしたmysqlにログインした結果
![MYSQLlog in画面](image/04_mysql_login_2.PNG)

- EC2設定画面
![EC2セッティング](image/04_EC2_settings_2.PNG)

- RDS設定画面
![RDSセッティング](image/04_RDS_settings.PNG)

- RDS設定画面(VPC状況)
![RDSセッティング２](image/04_RDS_settings_2_2.PNG)

- VPC設定画面
![VPCセッティング](image/04_VPC_settings.PNG)

- EC2用セキュリティグループ画面（インバウンド）
![EC2インバウンド](image/04_SG_forEC2_inbaund.PNG)

- EC2用セキュリティグループ画面（アウトバウンド）
![EC2アウトバウンド](image/04_SG_forEC2_outbaund.PNG)

- RDS用セキュリティグループ画面（インバウンド）
![EC2インバウンド](image/04_SG_forEC2_inbaund.PNG)

- RDS用セキュリティグループ画面（アウトバウンド）
![EC2アウトバウンド](image/04_SG_forEC2_outbaund.PNG)

- 今回の課題から学んだこと
- VPCを構築し、その上のパブリックサブネットにEC2、プライベートサブネットにRDSを設置し、
- 適切なルーティングを施すことで接続ができることが分かった。

- 失敗：EC2をデフォルトのVPCに配置してしまったことで、mysqlへのログインがはじかれてしまった。
- （そもそもpingすら飛ばない状況）