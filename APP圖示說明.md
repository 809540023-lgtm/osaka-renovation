# 林博御裝修系統 - App 圖示

## 📱 圖示尺寸需求

要讓 App 正常顯示，您需要準備以下圖示：

| 尺寸 | 用途 |
|------|------|
| 192x192 | 小圖示 (手機桌面) |
| 512x512 | 大圖示 (App Store/Play Store) |

---

## 🎨 建議設計

- 背景：深藍色 (#1a1a2e)
- 圖案：🏠 房子圖案
- 文字：林博御裝修

---

## 📍 放置位置

將圖示檔案放在根目錄：
```
osaka-renovation/
├── icon-192.png  ← 192x192 圖示
├── icon-512.png  ← 512x512 圖示
└── ...
```

---

## 🔧 生成圖示的方法

### 方法1：線上工具
1. 到 https://realfavicongenerator.net/
2. 上傳一張圖片
3. 下載所有尺寸的圖示
4. 把檔案放到根目錄

### 方法2：自己繪製
- 用 Canva 或 Photoshop 繪製
- 匯出成 PNG 格式

---

## 📦 目前的檔案結構

```
osaka-renovation/
├── index.html          🌐 主網頁
├── manifest.json       📋 PWA 資訊清單
├── sw.js               ⚙️ Service Worker
├── login.html          🔐 登入
├── register.html       📝 註冊
├── agent-system.html   🤖 AI 助手
├── client/             👀 客戶後台
├── worker/             👷 工班後台
├── agent/              🤝 中介後台
└── admin/              ⚙️ 管理員後台
```
