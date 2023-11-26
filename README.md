# nextjs-dashboard
個人勉強用リポジトリ。

教材出典：[Next.js公式 - Learn Next.js](https://nextjs.org/learn)  
※Next.js 14系とともに公開された新しいチュートリアル。

## 環境
- TypeScript：5.2.2
- Node.js：20.9.0
- Next.js：14.0.2
- Tailwind CSS：3.3.3

## 環境構築
ライブラリインストール
```bash
npm install
```

環境変数の準備（自分の vercel/postgres のデータベース情報を入れる）
```bash
cp .env.example .env
```

初期データ投入
```bash
npm run seed
```

開発サーバ立ち上げ
```bash
npm run dev
```
