【公開安全版】
這個版本已移除兩個住處的精確門牌／巷弄資訊，適合放在公開 GitHub Pages。

今天吃什麼？ v22 手機 App 版（PWA）

這個資料夾可以免費放到 GitHub Pages / Cloudflare Pages。
必須把「整個資料夾內容」一起上傳，不能只上傳 index.html，否則主畫面安裝與離線功能不完整。

最簡單的 GitHub Pages 做法：
1. 建立一個新的 GitHub repository，例如 food-decider。
2. 把這個資料夾內所有檔案上傳到 repository 根目錄：
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
   apple-touch-icon.png
   favicon-32.png
   .nojekyll
3. 到 repository 的 Settings → Pages。
4. 將網站來源設成從 main branch 的根目錄部署。
5. 等待網站網址產生後，用手機開啟。
6. Android/Chrome：按「＋ 加到主畫面」或瀏覽器選單中的安裝。
7. iPhone/Safari：分享 → 加入主畫面。

舊版資料搬到手機：
1. 在電腦舊版按「匯出備份」。
2. 把 JSON 備份檔傳到手機。
3. 手機版進「資料維護」→「匯入備份」。
4. 之後評分、吃過紀錄、暫不推薦都會存在手機瀏覽器本機。

注意：
- 不使用 Google Places API、Supabase 或付費後端，所以仍然是 0 元方案。
- 使用者資料只存在各裝置瀏覽器本機，不會自動跨裝置同步。
- 第一次成功開啟網站後，PWA 會快取核心檔案；之後即使暫時沒網路，主要功能仍可使用。


v22 新增：咖啡廳獨立篩選／瀏覽分類，以及長榮二段、崇善、開山／孔廟與東區咖啡店漏網補強。


v22 重要修正：預設「智慧距離」不再縮小候選半徑；約 15 分鐘生活圈全部店家都可抽，距離改為排序權重。
