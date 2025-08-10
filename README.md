
# Momento Experience (Temp)
Next.js 子站，用於嵌入 Framer 主站的「24 小時膠囊體驗」。

## 開發
```
npm install
npm run dev
```

## 必要環境變數
在 `.env.local` 加：
```
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_APP_ID=
SENDGRID_API_KEY=
```

## 部署（Vercel）
- 連 GitHub，Import 專案
- 設定上面環境變數
- Deploy 後把 URL 給 Framer 作為按鈕連結或 iframe src
