# DataSyncを使ったFSx for Windows File Serverへのマイグレーション

© 2020 Amazon Web Services, Inc. and its affiliates. All rights reserved.
This sample code is made available under the MIT-0 license. See the LICENSE file.

Errors or corrections? Contact [jeffbart@amazon.com](mailto:jeffbart@amazon.com).

---
DataSyncを使ったFSx for Windows File Serverへのマイグレーション
## このワークショップのシナリオ

あなたのデータセンターには更新時期を迎えるWindowsサーバーが有ります。このサーバーはあなたの組織内のグループに対し、ファイル共有とホームディレクトリを提供しています。
データセンターのフットプリントを削減し、リソースを解放するため、あなたはWindowsサーバーのデータをクラウドへ移行させたいと考えています。

色々と調べたところ、あなたはオンプレミスのWindowsサーバーから[Amazon FSx for Windows File Server](https://aws.amazon.com/fsx/windows/)へのデータマイグレーションに[AWS DataSync](https://aws.amazon.com/datasync/)が使える事を知りました。

このワークショップでは、クラウドフォーメーションテンプレートを使用してリソースをデプロイし、デプロイしたリソースをAWSマネージメントコンソールから操作しながら、このシナリオの流れを学習します。

## このワークショップでカバーされる内容

- クラウドフォーメーションを使ったリソースのデプロイ
- FSx for Windowsファイルサーバー共有の作成と管理
- DataSyncを使った、WindowsファイルサーバーからFSxへのデータコピー

## 前提条件

#### AWSアカウント

このワークショップを完了させるには、ワークショップ内で登場するリージョンで、EC2インスタンス、FSxファイルシステム、DataSyncエージェント、CloudFormationスタックを作成する権限を持ったAWS IAMロールを持ったAWSアカウントが必要です。

#### ソフトウェア

- **インターネットブラウザ**  – このワークショップには最新バージョンのChrome又はFirefoxを推奨します

## コスト

このワークショップを完了させるにはおよそ**10.00 USD**のコストがかかります。ワークショップ完了後は全てのデプロイしたリソースを削除し、無駄なコストを生じさせないように、モジュール最後に有るクリーンアップのガイダンスに従う事を推奨します。

## 関連するワークショップ

- [NFS server migration using AWS DataSync and Storage Gateway](https://github.com/aws-samples/aws-datasync-migration-workshop/blob/master/workshops/nfs-migration)
- [Migrate millions of files using AWS DataSync](https://github.com/aws-samples/aws-datasync-migration-workshop/blob/master/workshops/nfs-million-files)
- [Get hands-on with online data migration options to simplify & accelerate your journey to AWS](https://github.com/aws-samples/aws-online-data-migration-workshop)

## ワークショップモジュール

このワークショップは以下のモジュールで構成されます

- [モジュール 1](module1) - クラウドフォーメーションを使用したリソースのデプロイ
- [モジュール 2](module2) - WindowsファイルサーバーとFSxでのファイル共有の構成
- [モジュール 3](module3) - DataSyncを使ったWindowsファイルサーバーからFSxへのデータコピー
- [モジュール 4](module4) - リソースのクリーンアップ

始めるには [モジュール 1](module1)へ
