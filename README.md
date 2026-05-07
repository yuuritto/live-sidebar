# live-sidebar

Live Sidebar の公開ページ一式です。

## 現在の公開先

`ctun.net` のルートは個人ブログ `ctlog` です。このリポジトリの内容は
`https://ctun.net/live-sidebar/` 配下にだけ配置します。

- Homepage: `https://ctun.net/live-sidebar/`
- Help: `https://ctun.net/live-sidebar/help`
- Privacy Policy: `https://ctun.net/live-sidebar/privacy-policy`
- Terms of Service: `https://ctun.net/live-sidebar/terms`
- Commercial disclosure: `https://ctun.net/live-sidebar/tokushoho`

## デプロイ注意

このリポジトリを `ctun.net` のルートへ直接デプロイしないでください。
`/categories/` や `/tags/` など、個人ブログ側のページを壊します。

本番公開は `/workspace/ctun_blog/dist` をルートにし、このリポジトリの
HTMLを `live-sidebar/` 配下へコピーした一時ディレクトリを Cloudflare Pages
へデプロイします。
