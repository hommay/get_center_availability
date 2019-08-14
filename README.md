# 公民館空き状況照会

## ログイン情報
- プライベートな情報なので隠した(本番運用では環境変数に入れる)
- main.pyの7行目、8行目で変数に入れる

## デプロイコマンド
- gcloud functions deploy get_nishinomiya_center_availability --runtime python37 --trigger-http --region asia-northeast1 --memory 512MB

## TODO
- リクエストパラメータで日時絞る
- JSONでreturnさせる
- windows環境でもデプロイできるようにする(現状はMacOSのみ)
- 環境変数にログイン情報入れる
