# test

# AWS Amplifyで作るIoTバックエンド

本リポジトリは技術書典13で頒布した技術書「AWs Amplifyで作るIoTバックエンド」のサンプルWebアプリケーション＆サポートページです。

![カバー](https://user-images.githubusercontent.com/8074640/187302938-1d19dd6a-10fc-4d8f-b2be-99630e4ce75b.png)
![ダッシュボード](https://user-images.githubusercontent.com/8074640/187302960-030ef24f-2df7-419b-8aac-c7a44828e7a4.png)
![構成図](https://user-images.githubusercontent.com/8074640/187302984-fc290b6f-e0e6-4732-827e-fc09d8d5f594.png)

## 利用方法

ブランチを `base` に切り替えて、本書に沿って作業を進めてください。
起動確認する際は以下コマンドで起動ください。

```sh
$ yarn install
$ yarn dev
```

コマンドを実行したあと、ブラウザで [http://localhost:3000](http://localhost:3000) を開くとサンプルWebアプリケーションが表示されます。

## 利用パッケージ

サンプルWebアプリケーションは以下のようなパッケージ、フレームワークを利用して実装しています。

- [AWS Amplify](https://docs.amplify.aws/)
- [TypeScript](https://www.typescriptlang.org/)
- [Next.js](https://nextjs.org/)
- [Windster - Tailwind CSS Dashboard](https://github.com/themesberg/tailwind-dashboard-windster)
- [React Query](https://tanstack.com/query/v4/?from=reactQueryV3&original=https://react-query-v3.tanstack.com/)
- [React Hook Form](https://react-hook-form.com/jp/)
- [react-chartjs-2](https://react-chartjs-2.js.org/)
- [React-Toastify](https://github.com/fkhadra/react-toastify)
- [Day.js](https://day.js.org/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- 等...

## 正誤表

書籍の誤植が見つかった場合、こちらに追記予定です。

## 指摘・質問がある場合

[本リポジトリのIssues](https://github.com/yuuu/iot_dashboard_aws_amplify_book_site/issues)に書き込みをお願いいたします。
