## ローカル環境構築

- リポジトリをクローン
```git
git clone git@github.com:tanikento/jekyll_on_docker.git
```

- ディレクトリ移動
```shell
cd jekyll_on_docker
```

- 新規jekyllプロジェクト作成
```docker
docker-compose run ghpages jekyll new . --force
```

- dockerイメージをビルド & up
```docker
docker-compose up -d --build
```

- localhostで確認
```
localhost:4000
```


## jekyllテーマ

- サイト
```s
http://jekyllthemes.org/
```

## GitHub Pages
- リポジトリを作成
```
リポジトリ名は [アカウント名].github.io にする
```

- GitHub Pagesを設定
```
settingsのGitHub Pagesで Source -> master branch
```

- 作ったものをmaster branch にプッシュ
```
git push origin master
```

- 確認
```
https://[アカウント名].github.io/
```


## Docker

- コンテナに入る
```shell
docker/shell
```

- コンテナ止める
```shell
docker/stop
```

- コンテナ再起動
```shell
docker/start
```
