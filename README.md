# 九曜天賦探索所 ✦
**THE NINE STARS ACADEMY**

公開網站：<https://mikibear418.github.io/jiuyao-talent-academy/>

## 網站內容
- 72 題三幕探索旅程：九個面向各 6 題任務挑戰、2 題興趣覺察
- 9 個智能探索角色、雙指標雷達圖與進度條
- 在手機上直接作答，進度會儲存在目前瀏覽器
- 可下載探索結果 CSV 和角色紀念卡 PNG
- 純靜態單頁網站：全部內容在 `index.html`，不需額外安裝服務

## 首次啟用 GitHub Pages
1. 登入 GitHub 並前往本儲存庫的 [Pages 設定](https://github.com/mikibear418/jiuyao-talent-academy/settings/pages)。
2. 在 **Build and deployment → Source** 選 **GitHub Actions**（而不是 Deploy from a branch）。
3. 若 GitHub 未自動開始發布，可前往 [Actions](https://github.com/mikibear418/jiuyao-talent-academy/actions)，選擇 **Publish 九曜天賦探索所 to GitHub Pages**，點 **Run workflow**，分支選 **main**。
4. 成功後，從 <https://mikibear418.github.io/jiuyao-talent-academy/> 開始作答。

## 未來更新
只要更新 `main` 分支，`.github/workflows/pages.yml` 就會重新部署網站。網站採用相對路徑，不須另裝框架。

## 教學使用提醒
本網站的任務題僅衡量這一組文字情境題的答題表現，興趣題為主觀感受；並非標準化多元智能、性向、心理或能力診斷。結果適合用於自我探索與班級討論，不宜作為升學分流或能力判斷。答案不會上傳伺服器，僅儲存在本機瀏覽器。
