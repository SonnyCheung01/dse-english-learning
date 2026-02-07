# 三國英語學堂 🎮⚔️
## DSE English Grammar Learning Platform

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://pages.github.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

一個專為香港中學生設計的互動英文Grammar學習網站，結合三國誌主題、遊戲化學習、流行歌曲，讓DSE英文準備變得有趣！

🌐 **Live Demo:** [Your-GitHub-Pages-URL]

---

## 📚 項目簡介 | Project Overview

這個學習平台專為準備DSE英文考試的中四至中六學生而設，特別針對Grammar基礎較弱的學生。通過遊戲化、生活化的教學方式，讓學習英文不再沉悶。

### 🎯 核心目標
- 打好Grammar基礎（中四）
- 掌握DSE應試技巧（中五）
- 全面衝刺準備（中六）
- DSE目標：達到Level 3-4或以上

---

## ✨ 主要功能 | Key Features

### 🎮 遊戲化學習系統
- **武將闖關系統** - 每位三國武將代表一個Grammar主題
  - 劉備 - Present Tenses 時態大帝
  - 關羽 - Prepositions 介詞戰神
  - 張飛 - Articles 冠詞勇將
  - 趙雲 - Adverbs 副詞高手
  - 諸葛亮 - Sentence Structure 句式軍師
  - 周瑜 - Clauses 從句大師

- **經驗值 & 等級系統** - 完成練習賺取XP，提升等級
- **成就徽章** - 收集徽章，見證成長
- **連續天數追蹤** - 鼓勵每日學習習慣

### 🎵 英文歌學習
- 用流行歌曲學Grammar
- 歌詞重點highlight
- 點擊即學grammar point
- 包括：Adele、Ed Sheeran等熱門歌手

### 📊 進度追蹤
- 每週學習報告
- Grammar強弱分析
- 準確率統計
- 家長監察功能

### 📝 互動練習
- 即時批改
- 詳細解釋
- 錯題集
- AI個人化推薦

### 📅 每日任務系統
- 每日任務
- 每週挑戰
- 獎勵機制

---

## 🛠️ 技術棧 | Tech Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (Vanilla JS)
- **Styling:** Custom CSS with gradient designs, responsive layout
- **Deployment:** GitHub Pages
- **Version Control:** Git & GitHub

### 為何選擇純HTML/CSS/JS？
- ✅ 輕量級，載入快速
- ✅ 無需build process
- ✅ 容易維護和更新
- ✅ 適合初學者理解和修改
- ✅ GitHub Pages原生支援

---

## 🚀 快速開始 | Quick Start

### 方法1：直接訪問（最簡單）
直接打開部署好的網站：[Your-GitHub-Pages-URL]

### 方法2：本地運行
1. Clone這個repository
```bash
git clone https://github.com/your-username/dse-english-learning.git
```

2. 打開 `index.html`
```bash
cd dse-english-learning
open index.html  # Mac
start index.html # Windows
```

就這麼簡單！無需安裝任何dependencies。

---

## 📖 使用指南 | How to Use

### 學生使用
1. **選擇武將** - 點擊任何武將卡進入學習
2. **觀看短片** - 3-5分鐘YouTube風格教學
3. **做練習** - 互動quiz，即時回饋
4. **賺取XP** - 完成練習獲得經驗值
5. **查看進度** - 在進度報告查看學習情況

### 家長監察
- 進入「進度報告」頁面
- 查看每週學習時間
- 檢查Grammar強弱分析
- 了解需要加強的部分

---

## 📱 響應式設計 | Responsive Design

網站完全支援：
- 💻 Desktop (1920px+)
- 💻 Laptop (1366px - 1920px)
- 📱 Tablet (768px - 1366px)
- 📱 Mobile (320px - 768px)

在任何設備上都有最佳體驗！

---

## 🎨 設計理念 | Design Philosophy

### 視覺設計
- **三國主題配色** - 紅、金、黑為主色調
- **遊戲化UI** - 卡片式設計，動畫效果
- **清晰層次** - 重點突出，易於導航

### 教學理念
- **短時高頻** - 每日15-20分鐘
- **即時回饋** - 做錯立即解釋
- **生活化例子** - 用香港學生熟悉的場景
- **螺旋式複習** - 定期重溫舊知識

---

## 📂 文件結構 | File Structure

```
dse-english-learning/
│
├── index.html              # 主網站文件（包含所有HTML/CSS/JS）
├── README.md              # 本文件
└── (未來可能添加)
    ├── assets/            # 圖片、影片資源
    ├── data/              # 題目數據
    └── scripts/           # 拆分的JS文件
```

---

## 🔄 更新網站 | How to Update

### 修改內容
1. 編輯 `index.html`
2. 測試修改（在瀏覽器打開）
3. Commit changes
```bash
git add index.html
git commit -m "Update: 新增更多Grammar練習"
git push origin main
```

### 添加新武將（Grammar主題）
在 `getLessonData()` function中添加新的lesson對象：
```javascript
const lessons = {
    'your-new-topic': `
        <h2>新武將名稱</h2>
        // 你的課程內容HTML
    `
};
```

### 添加新歌曲
在Songs section添加新的 `.song-card` div。

---

## 🎯 未來計劃 | Roadmap

### Version 2.0 (計劃中)
- [ ] 真實YouTube教學短片整合
- [ ] 更多Grammar主題（完整50+單元）
- [ ] DSE Past Paper練習區
- [ ] AI批改寫作功能
- [ ] Speaking練習模組
- [ ] Listening訓練

### Version 3.0 (長遠目標)
- [ ] 用戶註冊系統
- [ ] 跨設備進度同步（Firebase/Supabase）
- [ ] 社群功能（學習小組）
- [ ] 教師管理後台
- [ ] 手機App版本（PWA）

---

## 🤝 貢獻 | Contributing

歡迎任何形式的貢獻！

### 如何貢獻
1. Fork這個repository
2. 創建你的feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit你的修改 (`git commit -m 'Add some AmazingFeature'`)
4. Push到branch (`git push origin feature/AmazingFeature`)
5. 開一個Pull Request

### 貢獻建議
- 📝 添加更多Grammar練習題
- 🎵 推薦適合學習的英文歌
- 🐛 報告bugs
- 💡 提出新功能建議
- 📖 改善文檔

---

## 📝 License | 授權

本項目採用 MIT License - 詳見 [LICENSE](LICENSE) 文件

---

## 👨‍💻 作者 | Author

**Sonny** - 銀行風險管理專業人士，為兒子DSE英文準備而開發

- 30年銀行經驗
- FRM & TMA資格
- 專長：Derivatives Valuation, Risk Management

---

## 🙏 致謝 | Acknowledgments

- 感謝所有測試網站的學生和家長
- 靈感來自：三國誌遊戲、Duolingo、Khan Academy
- 特別感謝：Claude AI 協助開發

---

## 📞 聯絡 | Contact

有任何問題或建議？歡迎聯絡！

- 📧 Email: [your-email@example.com]
- 💬 GitHub Issues: [提交Issue](https://github.com/your-username/dse-english-learning/issues)

---

## 📊 統計 | Stats

- 📚 Grammar主題：6個（持續增加中）
- 🎵 英文歌學習：3首（持續增加中）
- 📝 互動練習：50+ 題
- 🏆 成就徽章：6個
- 📱 支援設備：所有主流瀏覽器 & 手機

---

## 🌟 Star History

如果你覺得這個項目有用，請給個⭐️支持一下！

[![Star History Chart](https://api.star-history.com/svg?repos=your-username/dse-english-learning&type=Date)](https://star-history.com/#your-username/dse-english-learning&Date)

---

<div align="center">

**用遊戲化學習，征服DSE英文！🎮📚**

Made with ❤️ for Hong Kong students

[🌐 Visit Website](your-github-pages-url) | [📖 Documentation](link) | [🐛 Report Bug](issues-link) | [💡 Request Feature](issues-link)

</div>
