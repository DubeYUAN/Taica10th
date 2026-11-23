# LoL 基礎科普 & T1 戰隊編年史 LLM Wiki 專案

本專案採用 Andrej Karpathy 的 **LLM Wiki** 知識庫架構，結合《英雄聯盟》（League of Legends）零基礎遊戲玩法教學與 **T1** 戰隊編年史，並內附基於 Wiki 內容生成的可互動式 HTML 簡報投影片。

## 目錄結構

```text
lol-t1-llm-wiki/
├── AGENTS.md                       # LLM 知識庫維護最高指導原則（Schema）
├── index.md                        # 全站知識目錄（Content-oriented）
├── log.md                          # 編年操作日誌（Append-only）
├── README.md                       # 專案說明與使用指南
├── assets/                         # 簡報專用圖片資源（T1 隊標、召喚峽谷地圖、選手照）
├── slides/                         # 基於 Wiki 內容生成的簡報投影片
│   └── lol-t1-presentation.html    # 8 頁式 T1 飛翼風格互動式簡報
├── raw/                            # 不可變原始資料層（Source of Truth）
│   ├── articles/                   # 原始維基百科 PDF 歸檔
│   ├── papers/                     # 學術論文 PDF 歸檔區
│   └── raw_assets/                 # 原始文章附圖區
└── wiki/                           # LLM 全權維護之知識庫本體
    ├── overview.md                 # 全站總覽
    ├── gameplay/                   # 零基礎遊戲機制科普
    ├── t1-eras/                    # T1 戰隊編年史
    ├── entities/                   # 核心選手人物誌
    ├── matches/                    # 經典戰役復盤
    └── sources/                    # 原始資料摘要頁
```

## 快速預覽簡報
解壓縮本專案後，直接以瀏覽器開啟 `slides/lol-t1-presentation.html` 即可瀏覽：
- **第 1–5 頁**：《英雄聯盟》零基礎玩法教學（基本攻城規則、三大中立物件、六大英雄定位與選角 BP、**第 5 頁召喚峽谷五路互動地圖按鈕**）。
- **第 6–8 頁**：T1 戰隊六冠與三連霸歷史、ZOFGK 至 2026 陣容傳承，以及**第 8 頁 T1 核心選手互動圖鑑**。
