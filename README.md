# 🌬️ Still UI Base

Laravel Jetstream（Inertia） + Vuetify + GraphQL 構成の拡張テンプレート。
「風が通る」ように、UI/UXの余白と構造を最初から整備した実務向けベースプロジェクトです。

---

## ✅ 特徴

* Laravel Jetstream（Inertia版）をベースに構築
* Vuetify + TypeScript による柔軟なUI設計
* GraphQL（Lighthouse）標準搭載
* GoogleログインなどのSNS認証に対応（Socialite）
* 状態管理（Pinia）・多言語対応（vue-i18n）
* CSV・PDF出力、DataTable編集、RichEditorなど導入想定済
* Tailwind完全除去済 → Vuetifyに最適化

---

## 🔧 初期構築手順（ローカル）

```bash
git clone https://github.com/your-name/still-ui-base.git
cd still-ui-base

cp .env.example .env
composer install
php artisan key:generate

npm install
npm run dev

php artisan migrate
```

---

## 📡 GraphQL エンドポイント

```
POST /graphql
```

初期スキーマは `graphql/schema.graphql` にて管理。

---

## 🧪 テスト

```bash
# Laravel側（Pest）
php artisan test

# Vue側（Vitest）
npx vitest
```

---

## 🔖 ライセンス

MIT（ただし、一部含まれる外部ライブラリは各ライセンスに準拠）

---

## 🌀 制作者メモ

このテンプレートは、Still文化に基づく「風を通す」構造を体現する基盤です。
使い捨てでない実務にも、教育にも、どちらにも通用する柔軟性を備えています。
