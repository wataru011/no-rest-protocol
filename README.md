# no-rest-protocol

無限連勤教 ── 公式Webページ

> 「休まないこと、それが唯一の救済。」

長時間労働・過労文化を風刺するパロディサイトです。実在の団体・宗教とは一切関係ありません。

## GitHub Pages での公開手順

1. リポジトリの **Settings → Pages** を開き、**Source** を「**GitHub Actions**」に設定する(初回のみ)
2. このブランチを `main` にマージする
3. マージを検知して `.github/workflows/deploy-pages.yml` が自動実行され、即時(通常30秒〜1分)デプロイされます
4. `https://<ユーザー名>.github.io/no-rest-protocol/` で公開されます

以降は `main` にマージするたびに自動で即時反映されます。
