# 第四回課題

- VPCの構築、RDS、EC2の配置を実施。
- EC2に接続しMYSQLをインストール・ログインが可能であることを確認した。

![MYSQLlog in画面](image/04_mysql_login.PNG)
![EC2セッティング](image/04_EC2_settings.PNG)
![RDSセッティング](image/04_RDS_settings.PNG)
![VPCセッティング](image/04_VPC_settings.PNG)

- 今回の課題から学んだこと
- VPCを構築し、その上のパブリックサブネットにEC2、プライベートサブネットにRDSを設置し、
- 適切なルーティングを施すことで接続ができることが分かった。

- 失敗：EC2をデフォルトのVPCに配置してしまったことで、mysqlへのログインがはじかれてしまった。
- （そもそもpingすら飛ばない状況）