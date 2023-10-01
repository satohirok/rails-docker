## 手順1
自身のローカル環境にクローン:
```
git clone git@github.com:satohirok/rails-docker.git
```


## 手順2
ディレクトリの移動
```
cd rails-docker
```

## 手順3
コンテナの立ち上げ&起動:
```
docker-compose -d
```


## 手順4
dbを作成:
```
docker-compose run web rails db:create
docker-compose run web rails db:migrate
```

## 手順5
[ローカル環境](http://localhost:3000)

にアクセスし以下の画面が表示されれば成功

<img width="1040" alt="スクリーンショット 2023-10-01 20 53 31" src="https://github.com/satohirok/rails-docker/assets/93630297/82304d97-3993-45d7-9e75-bd22947e59b1">



