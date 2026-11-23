# 知識庫維護日誌 (Operation Log)

> 本檔案為唯讀追加（Append-only）的編年操作紀錄。每筆紀錄皆以 `## [YYYY-MM-DD] <操作類型> | <標題>` 開頭。

## [2026-11-23] init | 初始化 LoL 基礎科普與 T1 戰隊 LLM Wiki 知識庫
- 建立專案目錄結構（`raw/papers`、`raw/articles`、`wiki/` 各子目錄、`slides/`、`assets/`）。
- 確立 `AGENTS.md` 規範：繁體中文（台灣用語）搭配英文技術與遊戲專有名詞、玩法偏重零基礎科普、隔離 `assets/` 簡報圖片區。
- 初始化 `index.md` 與 `log.md`。

## [2026-11-23] ingest | 維基百科《英雄聯盟》與《T1 (電競隊伍)》條目
- 將 `英雄联盟.pdf` 與 `T1_(電競隊伍).pdf` 歸檔至 `raw/articles/`，建立來源摘要 `src-20261123-wiki-lol.md` 與 `src-20261123-wiki-t1.md`。
- 新建零基礎玩法科普頁面：`summoners-rift-basics.md`、`champions-and-roles.md`。
- 新建 T1 編年史與核心人物誌：`t1-chronicle.md`、`faker.md`。
- 同步更新 `index.md`。

## [2026-11-23] build | 生成 Wiki 互動式簡報投影片 (`slides/lol-t1-presentation.html`)
- 整合 `wiki/gameplay/`、`wiki/t1-eras/` 與 `wiki/entities/` 內容，搭配 `assets/` 圖片素材製作 8 頁式 T1 飛翼風格互動簡報（含召喚峽谷五路互動地圖按鈕與 T1 核心選手互動圖鑑）。
