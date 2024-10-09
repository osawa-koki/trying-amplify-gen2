# trying-amplify-gen2

🗞🗞🗞 Amplify Gen2を試してみる！  

<https://docs.amplify.aws/nextjs/start/quickstart/nextjs-app-router-client-components/>を参考に進めています。  

## 本番環境へのデプロイ

最初に、このリポジトリをクローンします。  

```shell
git clone https://github.com/osawa-koki/trying-amplify-gen2.git
```

次に、<https://console.aws.amazon.com/amplify/create/repo-branch>からAWSへのデプロイを設定します。  
その後は、mainブランチへのpushをトリガーとしてデプロイが自動で行われます。  

## ローカル環境での起動

最初にnpmモジュールをインストールします。  

```shell
npm install
```

サンドボックス環境をローカルで起動します。  

```shell
npx ampx sandbox
```

上記コマンドに並行して、Next.jsのローカルサーバーを起動します。  

```shell
npm run dev
```
