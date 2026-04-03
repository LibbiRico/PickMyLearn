### 檔案架構不定時更新

```
# clone下來的時候 應該會是 PickMyLearn (留意大寫) 路徑下還會有 pickymylearn(前端) + server(後端) 這兩個資料夾
# git push 的時候記得在 PickMyLearn 路徑底下 commit，因為當時 .git是在 PickMyLearn 路徑底下，所以不要在小寫的 pickMyLearn 裡面 commit

├── pickymylearn/          # 前端主要入口，只需要在此進行維護
│   ├── .next/
│   ├── app/               # Next.js App Router 目錄
│   │   ├── ZZZ/          
│   │   ├── xxx/
│   │
│   ├── node_modules/      # Node 套件依賴
│   └── public/            # 靜態公開資源
│   ├── .gitignore         # Git 忽略檔案
│   ├── AGENTS.md          # Agents 文件
│   ├── CLAUDE.md          # Claude 相關筆記
│   ├── .eslintrc.js       # ESLint 設定檔
│   ├── next-env.d.ts      # Next.js TypeScript 環境宣告
│   ├── tsconfig.json      # TypeScript 設定檔
│   ├── package-lock.json  # NPM 鎖定檔
│   ├── package.json       # 專案依賴與腳本
│   ├── postcss.config.js  # PostCSS 設定檔
│   └── tsconfig.json      # 重複 TS 設定檔？（或應用程式專用）
│   
│   
├── server/                # 端人員切勿在這個路徑底下做任何修改
│   ├── 001/         #
│   ├── 002/         #

```
