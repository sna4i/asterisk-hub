# asterisk-hub

Apex hub for **asterisk.dpdns.org** — a portfolio index of published apps, each on
its own subdomain.

| path | 役割 |
|------|------|
| `index.html` | アプリ一覧（ixis / EIDOS / 今後） |
| `privacy/`, `support/` | 旧 apex リンク救済：`ixis.asterisk.dpdns.org` の各ページへ 301 相当の redirect |
| `app-ads.txt` | AdMob 認証（apex を開発者サイトに設定している間は必要） |
| `CNAME` | `asterisk.dpdns.org` |

## アプリ追加
1. `<app>-site` repo を作り `<app>.asterisk.dpdns.org` で配信（DNS: `<app>` CNAME → `sna4i.github.io`、grey）。
2. この `index.html` の `.grid` にカードを1枚足す。

---
© 2026 sna. All rights reserved. Proprietary — see `LICENSE`.
