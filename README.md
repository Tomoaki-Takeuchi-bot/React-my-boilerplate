# TypeScript - React - TSX 練習用のレポジトリです。

## レポジトリ環境構築手順について

下記サイトを参考に環境構築を実施しております。
[Type Script Deep Dive 日本語版](https://typescript-jp.gitbook.io/deep-dive/browser#2-create-react-appwosuru)

```
npm i -g create-react-app
npx create-react-app my-app --template typescript
cd my-app
npm start # または、yarn start
```

## 環境構築後は下記コマンドが使用可能です。

### `yarn start`

アプリをブラウザでリアルタイム稼働させ確認できます。<br />
クロームでアクセスしてください。 [http://localhost:3000](http://localhost:3000)
編集される度に更新されます。
またコンソールにエラー出力されます。

### `yarn test`

**注意事項:このレポジトリには`src/App.test.tsx`を含みません。Jest テスト想定される場合はご注意ください。**
インタラクティブウォッチモードでテストを稼働させます。
下記サイトを参照して下さい。
[running tests](https://facebook.github.io/create-react-app/docs/running-tests)

### `yarn build`

本番用のアプリを `build` フォルダに作成します。最適化によりデプロイの準備を行うものです。
下記サイトを参照して下さい。
[deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn eject`

**注意事項: このコマンド`eject`は一度行うと取り消しできません。**
このコマンドによりビルドされたツールや選択された設定を削除します。
CRA の管轄から離れる事を意味します。
Webpack の設定をカスタマイズする場合等に有効です。

## CRA , React, TSX についての参考サイト

Create React App について</br> [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).</br>

React について</br> [React documentation](https://reactjs.org/).</br>

TSX コマンド入力、トラブルシュートについて</br> [React TypeScript Cheetsheet](https://react-typescript-cheatsheet.netlify.app/)
