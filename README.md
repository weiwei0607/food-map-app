# 🍽️ Food Map — 我的美食地圖

> 個人美食收藏 + 隨機推薦 + Google Maps 整合

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript" />
  <img src="https://img.shields.io/badge/Google%20Maps-API-4285F4?logo=googlemaps" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## ✨ 功能

- **📍 餐廳管理** — 新增、編輯、刪除收藏的餐廳資訊
- **🎲 隨機推薦** — 選擇困難症的救星，依據評分權重隨機挑選
- **🔍 Google Maps 搜尋** — 整合 Places API，搜尋附近餐廳並一鍵收藏
- **⭐ 評分系統** — 為每間餐廳打分、寫心得
- **🏷️ 標籤篩選** — 依類型、價位、辣度等條件篩選
- **💾 本地儲存** — 所有資料儲存在瀏覽器 localStorage，不流失

---

## 🚀 使用方式

這是純靜態 HTML 應用，無需建置：

```bash
# 直接開啟
cd food-map-app
open index.html

# 或用本地伺服器
npx serve .
```

### 設定 Google Maps API Key

在 `index.html` 中將 `YOUR_API_KEY` 替換為你的 [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)：

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places" async defer></script>
```

---

## 📁 專案結構

```
food-map-app/
└── index.html          # 單一檔案完整應用
```

---

## 📝 License

MIT License © 2026
