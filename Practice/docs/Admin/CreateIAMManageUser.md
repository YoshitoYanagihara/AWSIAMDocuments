# IAM管理ユーザの作成

このドキュメントでは、以下の権限を持ったIAM管理用ユーザを作成する手順を記述する
- 「child_」と言うプレフィクスの付いたユーザ、グループを作成及び削除できるようにする

※「iam_manage」と言うユーザを、IAM管理用ユーザとして作成するものとする

1. ユーザ「iam_manage」を作成
2. iam_manageにアタッチする為のポリシーを作成（ポリシー名はiam_manage_policyとする）
3. iam_manage_policyに対してIAMの全てのIAMアクション権限を付与し、リソースのgroupとuserの「ARNの追加」→「Group(User) name with path」に「child_*」と指定する
4. iam_manage_policyをiam_manageにアタッチ

上記手順にて、「child_」のプレフィクスを持つユーザ・グループのみを管理できるようになる
