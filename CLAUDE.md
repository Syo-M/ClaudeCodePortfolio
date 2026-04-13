# portfolio

制作したアプリをまとめるポートフォリオページ（Astro 静的サイト）。

## 技術スタック

- Astro v6（静的サイト）
- CSS Modules + デザイントークン（Mocha Mousse）

## 掲載アプリ

| アプリ名 | URL | 概要 |
|---|---|---|
| clerk-auth-demo | https://cleak-auth-demo.vercel.app/ | Clerk v7 認証デモ |
| FlontEnd Library | https://flont-end-library.vercel.app/dashboard | Notion 学習DBビジュアライザー |
| Notion Blog | https://notion-blog-khaki-sigma.vercel.app/ | Notion ブログ |
| Engineer Dashboard | https://eo-dashboard-iota.vercel.app/ | エンジニア向け作業ダッシュボード |
| Ensō Visualizer | https://enso-visualizer.vercel.app/ | 水墨画風音楽ビジュアライザー |

## 非掲載アプリ（ポートフォリオ対象外）

| アプリ名 | 理由 |
|---|---|
| MkDataList | ポートフォリオ掲載対象外（個人利用）|
| ZITPromptMaker | ポートフォリオ掲載対象外（個人利用）|

## デプロイ先

https://claude-code-portfolio-six.vercel.app/

## 開発コマンド

```bash
npm run dev     # http://localhost:4322
npm run build
```

## 注意

- noindex 設定済み（robots.txt + meta robots）
- アプリを追加する場合は `src/pages/index.astro` の `projects` 配列を編集
- コンポーネントライブラリの情報は `library` オブジェクトを編集（components配列でコンポーネント名を管理）
