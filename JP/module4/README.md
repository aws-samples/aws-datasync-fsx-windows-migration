# DataSyncを使ったFSx for Windows File Serverへのマイグレーション

© 2020 Amazon Web Services, Inc. and its affiliates. All rights reserved.
This sample code is made available under the MIT-0 license. See the LICENSE file.

Errors or corrections? Contact [jeffbart@amazon.com](mailto:jeffbart@amazon.com).

---

# モジュール 4
## リソースのクリーンアップ

このワークショップで使用した全てのリソースを削除するために、以下の手順にしたがって実行して下さい。 (次のステップに進むためにクラウドフォーメーションの完了を待つ必要はありません）

1. AWSマネジメントコンソールから**DataSync**サービスを選択。
2. **Tasks**を選択し、作成済みのタスクを削除してください。
3. **Locations**を選択し、作成済みのロケーションを削除してください。 
4. **Agents**を選択し、アクティベート済みのエージェントを削除してください。これによりDataSyncエージェントのEC2インスタンスは削除されない点に注意してください。インスタンスはクラウドフォーメーションスタックの削除と共に削除されます。
5. クラウドフォーメーションのページで**MigrationWorkshop**という名前のスタックを削除してください。

全てのクラウドフォーメーションテンプレートが正しく削除された事を確認するために、オンプレミスリージョンの全てのEC2インスタンスが**terminated**ステータスになっている事を確認して下さい。
