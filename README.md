# dorasenaapp.com

GitHub Pagesで `https://dorasenaapp.com` に公開するための静的サイトです。

## 必須URL

- Developer Website / Marketing URL: `https://dorasenaapp.com/`
- app-ads.txt: `https://dorasenaapp.com/app-ads.txt`
- はや家計簿 Privacy Policy: `https://dorasenaapp.com/hayakakeibo/privacy-policy/`
- はや家計簿 Support: `https://dorasenaapp.com/hayakakeibo/support/`

## DNS / GitHub Pages

GitHub PagesのCustom domainに `dorasenaapp.com` を設定します。

DNSのAレコード:

```text
@ 185.199.108.153
@ 185.199.109.153
@ 185.199.110.153
@ 185.199.111.153
```

`www` も使う場合:

```text
www CNAME <GitHubユーザー名>.github.io
```

GitHub Pages側でHTTPSが有効になったら `Enforce HTTPS` をオンにします。

## AdMob

`app-ads.txt` は本番AdMob App ID `ca-app-pub-1372524791906992~9800172852` から publisher ID を反映しています。

```text
google.com, pub-1372524791906992, DIRECT, f08c47fec0942fa0
```

AdMob管理画面の app-ads.txt スニペットと完全一致しているか、公開前に確認してください。
