# 事前設定
## GitHub Secrets
以下のシークレットをGitHubリポジトリに設定してください

### AWS関連
- `AWS_ACCESS_KEY_ID`: AWSアクセスキーID
- `AWS_SECRET_ACCESS_KEY`: AWSシークレットアクセスキー  
- `AWS_APP_ID`: AmplifyアプリケーションのアプリケーションID

### Vercel関連
- `VERCEL_TOKEN`: Vercelのアクセストークン
- `VERCEL_ORG_ID`: VercelのOrganization ID（オプション）
- `VERCEL_PROJECT_ID`: VercelのProject ID（オプション）

## アプリケーション関連
- `AGENT_CORE_ENDPOINT`: Bedrock AgentCoreのエンドポイント

## GitHub Variables
以下の変数をGitHubリポジトリに設定してください

### リージョン設定
- `AWS_REGION`: AWSリージョン（デフォルト: us-east-1）
- `VERCEL_REGION`: Vercelデプロイリージョン（デフォルト: iad1）ko