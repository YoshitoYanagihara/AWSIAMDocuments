# 実践検証

## 想定する前提

- フロントエンド・バックエンド分業体制での開発
  - プロダクトオーナーよりフロントエンド・バックエンドの開発をそれぞれ別企業に発注
- AWSのルートアカウントはプロダクトオーナーが所持
- プロダクトオーナーはAWSのadmin権限を付与したユーザをバックエンド側に委託
  - 各種管理はバックエンドに委ねる方針（但し[ベストプラクティス](https://docs.aws.amazon.com/ja_jp/IAM/latest/UserGuide/best-practices.html)には従うように指示）

## 関連資料

- [管理方針](https://github.com/YoshitoYanagihara/AWSIAMDocuments/blob/main/Practice/Policy.md)
- [ユーザリスト](https://github.com/YoshitoYanagihara/AWSIAMDocuments/blob/main/Practice/Users.md)
