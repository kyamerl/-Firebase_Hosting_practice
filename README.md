> vue.jsを構築後から記述
> あらかじめ，firabase にプロジェクトを作成

## プロジェクトディレクトリで，firabese toolsをインストール

```
npm install -g firebase-tools
```

## firabase にログインする
```
firebase login
```

## firabeseの設定ファイルを作成
```
firebase init
```

> その後，hosting を[space key]で選択し，[enter key]で決定
> 既存のfirabase プロジェクトを選択する

<!--
```
npm run serve
```
-->

## 下記コマンドを実行して，firabaseに反映できたことを確認
```
npm run build
```

```
firebase deploy
```

```
npm run build
```

