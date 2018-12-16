# README
- GraphQL練習用プロジェクト
- [Apollo Client](https://www.apollographql.com/docs/react/)を使用している
- GitHubの公開リポジトリを検索できる
- リポジトリに対して、StarをOn/Offできる

## 実行手順
ライブラリのインストール
```
yarn install
```

GitHub tokenの設定  
public_repo (Access public repositories)を付与したtokenを用意する  
環境変数を設定する
```
REACT_APP_GITHUB_TOKEN=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

起動
```
yarn start
```