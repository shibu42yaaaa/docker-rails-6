## docker-rails-6
Docker環境の元リポジトリ
- Docker使用時にここからクローンする

## gemのインストール
```
$ docker-compose run --rm web bash
```

## DB作成（docker up状態で行う）
```
$ docker-compose exec web ./bin/rails db:creates
```
