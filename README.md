# PLAYZONE 互動遊樂大廳 (jun-wg-261023)

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/jun851125-dotcom/jun-wg-261023)

精選互動網頁遊戲大廳與旗下原創遊戲專案，純前端單檔架構，支援免安裝即開即玩、零外部資源依賴與 Web Audio API 原生合成音效。

---

## 🎮 收錄遊戲

1. **成語填填看 (`game1/`)**
   - **類型**：國學益智 ‧ 語文測驗 ‧ 成語探秘
   - **特色**：隨機 10 題經典四字成語，隨機挖空一字，四選一作答。搭載雙血條計時制、即時釋義解析與連擊火焰回饋。
   - **導航**：頂部選單、開始畫面與結算畫面均配備「返回大廳」雙向按鈕。

2. **太空英打防衛戰 (`game2/`)**
   - **類型**：鍵盤英打 ‧ 星際射擊 ‧ 極速反應
   - **特色**：天降 26 個星際英文字母，敲擊鍵盤發射雷射粒子光束進行殲滅。獨家防呆漏打重降機制、即時打字速率 (CPM) 分析與虛擬觸控螢幕鍵盤。
   - **導航**：頂部戰況 HUD、任務簡報與通關結算畫面均配備「返回大廳」雙向按鈕。

3. **遊戲大廳首頁 (`index.html`)**
   - 街機賽博黑曜石主題風格，搭載背景懸浮星芒 Canvas 與實機動態模擬畫面預覽。
   - 具備分類過濾、隨機選遊戲輪盤 (Roulette) 與原生合成音效切換功能。

---

## 🚀 一鍵部署到 Netlify (Continuous Deployment)

點擊下方按鈕，即可直接將本儲存庫一鍵導入 Netlify 並建立自動持續發佈（每當 GitHub 有新 commit 時自動同步部署）：

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/jun851125-dotcom/jun-wg-261023)

---

## 🛠️ 本地執行

本專案無需任何建置步驟 (Zero-build)，直接以任何瀏覽器開啟 `index.html` 即可暢玩：

```bash
# 使用 Python 快速啟動本地伺服器
python -m http.server 8000
# 瀏覽器開啟 http://localhost:8000
```
