# 株式会社ガウラ 公開Webサイト（静的サイト）

Amazon SP-API パブリック開発者登録の「ウェブサイト」欄用の会社／サービス紹介サイトです。
HTML/CSSのみで構成され、JavaScript・外部CDN・Cookie・アクセス解析は使用していません。
既存の gaura_review_saas（Lambda / DynamoDB / CloudFormation 等）とは完全に独立しています。

## ファイル構成
- index.html          … トップページ（会社情報／サービス／概要／セキュリティ／プライバシー要約／お問い合わせ）
- privacy.html        … プライバシーポリシー全文
- assets/style.css    … 共通スタイル（スマホ対応）
- README.md           … このファイル

## ローカル確認
    cd gaura-site
    python3 -m http.server 8000
ブラウザで http://localhost:8000/ を開く。
（index.html をダブルクリックして直接開いても表示できます）
