# AIエージェント × GitHub 研修用 練習リポジトリ

「AIエージェント × GitHub 引き継ぎガイド」の **デモ（スライド20）** と **ミニ体験（スライド21）** で使う練習用リポジトリです。
中身は架空サイトの1ページだけです。本番案件ではないので、安心して失敗してください。

| 項目 | 内容 |
|---|---|
| リポジトリ | https://github.com/protimes-webconsul/ai-agent-github-practice |
| 公開先（GitHub Pages） | https://protimes-webconsul.github.io/ai-agent-github-practice/ |
| 反映のしくみ | `main` にマージされると GitHub Pages が自動で再公開（1〜2分） |

## 進め方

| 使う場面 | 手順書 | 対象 |
|---|---|---|
| スライド20：ライブデモ | [docs/demo-script.md](docs/demo-script.md) | 講師 |
| スライド21：ミニ体験 | [docs/workshop.md](docs/workshop.md) | 受講者 |

## ファイル構成

```
index.html                       練習ページ本体（変更対象はここだけ）
style.css                        見た目（今回は変更しない）
.github/pull_request_template.md PR本文テンプレート（スライド15）
docs/demo-script.md              講師用デモ台本
docs/workshop.md                 受講者用ミニ体験シート
```

## 変更してよい箇所

| 場面 | 場所 | Before | After |
|---|---|---|---|
| デモ | `index.html` の `id="contact-button"` | お問い合わせ | 無料相談はこちら |
| ミニ体験 | `index.html` の `id="main-heading"` | 住まいのお悩み、まとめて解決します | 点検から修繕まで、ひとつの窓口で |

それ以外（色・配置・リンク先・`style.css`）は変更しません。

## ルール（スライド22）

1. 作業前に `main` をプル
2. `main` へ直プッシュ禁止（ブランチ保護で禁止済み）
3. 1ブランチ＝1目的
4. AIの変更は人が差分・表示で確認
5. PRに「何を・なぜ・どう確認したか」を残す
6. 困ったら止まって講師に相談（強制プッシュ禁止）
