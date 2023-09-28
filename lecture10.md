# 第10回課題

- cloudformationを用いてVPC、EC2、RDS、ALB、S3を構築する。

- cloudformation実行結果
![cloudformation実行結果](image/10_cloudformation_success.PNG)

- 構築されたVPC
![VPC情報](image/10_vpc_info.PNG)

- パブリックサブネットおよびプライベートサブネット
![パブリックサブネットA](image/10_publicsubneta_info.PNG)
![パブリックサブネットC](image/10_publicsubnetc_info.PNG)
![プライベートサブネットA](image/10_privatesubneta_info.PNG)
![プライベートサブネットC](image/10_privatesubnetc_info.PNG)

- ルートテーブル
![パブリックルートA](image/10_publicroutea.PNG)
![パブリックルートC](image/10_publicroutec.PNG)
![プライベートルートA](image/10_privateroutea.PNG)
![プライベートルートC](image/10_privateroutec.PNG)

- インターネットゲートウェイ
![IGW](image/10_igw.PNG)

- 構築されたEC2
![EC2](image/10_ec2_info.PNG)

- EC2のインバウンド・アウトバウンド
![EC2セキュリティグループ](image/10_ec2_sg.PNG)

- 構築されたRDS
![RDS](image/10_rds_info.PNG)

- RDSのインバウンド・アウトバウンド
![RDSインバウンド](image/10_rds_sg_inbound.PNG)
![RDSアウトバウンド](image/10_rds_sg_outbound.PNG)

- 構築されたALB
![ALB](image/10_alb_info.PNG)

- ALBのインバウンド・アウトバウンド
![ALBインバウンド](image/10_alb_sg_inbound.PNG)
![ALBアウトバウンド](image/10_alb_sg_outbound.PNG)

- ALBのリスナールール
![ALBリスナールール](image/10_alb_listener.PNG)

- ALBのネットワーキング
![ALBネットワーキング](image/10_alb_network.PNG)

- ターゲットグループ
![ターゲットグループ](image/10_targetgroup.PNG)

- 構築されたS3
![S3](image/10_s3_info.PNG)

- 実コードは以下参照
[lecture10.yml] (template/lecture10.yml)

- 今回の課題から学んだこと
- RDSの構築に結構時間かかる。
- 一つのテンプレートで作成するとかなり見づらくなる。
- cloudformationの実行ログは内容が分かりにくいようで実のところしっかり読めば分かりやすい。