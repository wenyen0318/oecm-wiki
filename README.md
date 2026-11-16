# 保育共生地知識站

用白話整理臺灣「保育共生地」（陸域 OECMs）的知識網站：概念、認證條件、申請流程、認證後的管理。一頁回答一個問題，每頁都附官方出處。

- 純 HTML / CSS / JavaScript，部署在 GitHub Pages
- AI 協作規則寫在 [`AGENTS.md`](./AGENTS.md)（Claude 會從 [`CLAUDE.md`](./CLAUDE.md) 被導向同一份規則）

## 新增一頁只要三步

1. 複製 `templates/page-template.html` 到 `pages/<slug>.html`，填入 `{{ }}` 欄位
2. 在 `data/pages.json` 登記一筆
3. 推上 GitHub，首頁卡片和上一頁／下一頁會自動更新

想讓 AI 幫忙？直接說：「請依照 AGENTS.md，新增一頁 `management-plan`，主題是經營計畫書要寫什麼。」

## 資料來源

主要依據農業部林業及自然保育署〈保育共生地認證方案〉與〈常見問答集〉，國際部分參考 CBD 第 14/8 號決議與 IUCN 指引。實際規定以主管機關公告為準。

---
國立臺灣大學「生成式 AI：文字與圖像生成的原理與實務」第九週作業。
