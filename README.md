# OurPins Legal

共同マップアプリ **OurPins** のプライバシーポリシーと利用規約を公開する静的サイトです。GitHub Pages でホスティングします。

## ページ

| ファイル | 内容 |
| --- | --- |
| [`index.html`](index.html) | トップページ（各ポリシーへのリンク） |
| [`privacy-policy.html`](privacy-policy.html) | プライバシーポリシー |
| [`terms-of-service.html`](terms-of-service.html) | 利用規約 |
| [`styles.css`](styles.css) | 共通スタイル |

## ローカルで確認する

ビルド不要の静的サイトです。ブラウザでファイルを直接開くか、簡易サーバーで確認できます。

```bash
# 例: Python の簡易サーバー
python -m http.server 8000
# http://localhost:8000 を開く
```

## GitHub Pages での公開手順

1. GitHub でリポジトリ（例: `OurPins-legal`）を作成する。
2. このディレクトリを push する。
3. リポジトリの **Settings → Pages** を開く。
4. **Build and deployment → Source** を「Deploy from a branch」にする。
5. Branch を `main`（フォルダは `/root`）に設定して保存する。
6. 数分後、`https://<ユーザー名>.github.io/OurPins-legal/` で公開されます。

> `.nojekyll` ファイルを置いているため、Jekyll の処理をスキップしてファイルをそのまま配信します。

## 更新時の注意

- 内容を変更した場合は、各ページの「最終更新日」を更新してください。
- 連絡先メールアドレスは各 HTML の問い合わせ窓口に記載しています。変更時は両ページを更新してください。
