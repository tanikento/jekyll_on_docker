## ローカル環境構築

- リポジトリをクローン
```git
git clone
```

- 新規jekyllプロジェクト作成
```docker
docker-compose run web jekyll new . --force
```

- dockerイメージをビルド & up
```docker
docker-compose up -d --build
```

- localhostで確認
```http
localhost:4000
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
