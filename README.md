# 咖啡101 網站（coffeestory101.github.io）

> 📘 中文說明書（2026-11-28 整理）｜狀態：🟢 使用中
> 全部 29 個 repo 的總表與封存建議：[repo 地圖](https://github.com/jay0916746661/jimframe-site/blob/main/docs/repo地圖與封存建議.md)

## 這是什麼
咖啡101 的網站：咖啡時間軸、世界產地、咖啡圖鑑、台北老店、故事頁（`t01.html`～）。網址 https://coffeestory101.github.io。

## 怎麼用／怎麼改
原本 README 寫「由 `coffee101/engine/build_mag.py` 產生，不要手改」，但 **11/28 查過，這支產生器不在任何一個 repo 裡**（大概只留在某次 Claude 的暫存工作區）。所以現在只能直接改 HTML：改之前先下載備份，一次改一頁，改完用手機看一次。之後如果要大改版，請 Antigravity 先寫一支新的產生器放進這個 repo。

## 要注意
字型、灰字顏色在 `mag.css`。圖片在 `img/`，分享縮圖是 `og.jpg`。

### 怎麼修（不用 Claude 也做得到）
1. 小改字：在 GitHub 網頁打開檔案 → 右上角鉛筆 ✏️ → 改完按 Commit changes。
2. 大改：用 Antigravity（Gemini）開這個 repo，第一句貼：「先讀 README.md，照裡面的說明改，改完給我分支名＋PR 連結，不要直接改 main。」
3. 改壞了：GitHub 網頁 → Commits → 找到改壞前那一版 → 點 `<>` 看舊檔，複製回來。**不要刪 repo、不要 force push。**

## 封存建議（只是建議，沒有動任何東西）
不建議。

---

## 原本的 README（保留原文）

# 咖啡101 網站

https://coffeestory101.github.io

由 `coffee101/engine/build_mag.py` 產生，不要手改 HTML。
