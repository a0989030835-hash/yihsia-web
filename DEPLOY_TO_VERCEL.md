# 如何將網站部署到 Vercel

由於我無法直接為您註冊帳號，但我已經準備好了所有網站檔案。請按照以下步驟操作，即可將您的網站發布到網路上：

## 第一步：準備帳號
1. 前往 [Vercel 官網](https://vercel.com/signup)。
2. 使用您的 **GitHub**、**GitLab** 或 **Email** 註冊一個免費帳號。

## 第二步：部署網站 (最簡單的方法)
1. 登入 Vercel Dashboard (儀表板)。
2. 點擊 **"Add New..."** 按鈕，選擇 **"Project"**。
3. 在 "Import Git Repository" 頁面的下方，您會看到一個 **Deploy manually** 的區塊。
4. 雖然手動上傳也是一種方式，但最推薦的方式是 **安裝 Vercel CLI** (如果您熟悉指令) 或者 **使用 GitHub**。

### 推薦方法：使用 GitHub (最穩定)
1. 將資料夾 `網頁測試` 上傳到您 GitHub 的一個新 Repository。
2. 在 Vercel 的 "Import Git Repository" 頁面，連接您的 GitHub 帳號。
3. 選擇您剛剛上傳的 Repository，點擊 **Import**。
4. 設定頁面保持預設即可，直接點擊 **Deploy**。

### 替代方法：使用 Vercel CLI (指令工具)
如果您電腦有安裝 Node.js，可以在這個資料夾開啟終端機 (Terminal / CMD)，然後輸入：

```bash
npx vercel
```

接著依照螢幕指示：
1. 按 `Enter` 確認要部署 (Deploy)。
2. 登入您的 Vercel 帳號 (瀏覽器會自動跳轉)。
3. 一路按 `Enter` 使用預設設定即可。

## 第三步：完成
部署成功後，Vercel 會給您一個網址 (例如 `your-project.vercel.app`)，這就是您的網站連結，可以分享給其他人了！
