# cfw-test1

Cloudflare Workers の練習。
[Get started - CLI · Cloudflare Workers docs](https://developers.cloudflare.com/workers/get-started/guide/)
のコードに、

- API を 1 個追加(UUID を生成)
- index.html を追加

したやつ。

```sh
# 準備
pnpm audit
pnpm ci

# ローカルで開発
pnpm run dev
pnpm run test

# ビルドサイズ確認
pnpm size
# Cloudflare へログイン

pnpm run login
## または
pnpm run login-no-browser

# デプロイ
pnpm run deploy

# 楽しんだら消す
pnpm run delete
```
