# Learning Board

繁體中文 React 學習看板，使用 Vite 建置。可分類與搜尋課程、更新課程進度、勾選學習任務及新增自訂任務。課程與任務資料保存在瀏覽器 localStorage。

本機執行：`pnpm install`、`pnpm dev`。建置：`pnpm build`。

Vercel 部署：匯入 GitHub Repository，Framework Preset 選擇 Vite，Build Command 使用 `pnpm build`，Output Directory 使用 `dist`。