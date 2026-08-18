# Friendslop 研討會論文研究紀錄

這個 Repository 保存 Friendslop 研究的決策、老師會談、文獻筆記、遊戲分析、互賴實驗、證據索引、前三章規劃與口試影片材料。

目前方向：以 LFCG 比較 Hurezeanu 等（2026）提到的四款 Friendslop 案例——`Lethal Company`、`Content Warning`、`R.E.P.O.`、`PEAK`——整理合作設計上的共通點、差異與例外。研究目前不替 Friendslop 下完整定義，也不直接回答玩家為什麼使用這個名稱。

## 目前狀態

- 階段：研究設計、四案例分析準備、前三章準備
- 投稿目標：下一屆臺北數位圖像國際學術研討會；正式簡章尚待公告
- 老師會談：2026-08-18 已討論研究方法，老師未指出重大方向問題
- 老師要求補強：如何具體測試設計變化是否真的改變玩家互賴
- 口試前實驗：能完成很好；來不及也不是目前硬性條件
- 口試方向：以影片和實際做出的內容為主，第一章簡短，重點放第二、第三章
- 前三章：老師希望早點收到；研究者目前以 2026 年 10 月為工作目標

詳細狀態見 [`project/research_state.md`](project/research_state.md)。

## 先從這四份看

1. [`meetings/2026-08-18_advisor_meeting.md`](meetings/2026-08-18_advisor_meeting.md)：今天老師說了什麼、哪些只是會後解讀。
2. [`project/decision_log.md`](project/decision_log.md)：已確認、暫定與未決事項。
3. [`research_design/player_interdependence_experiment.md`](research_design/player_interdependence_experiment.md)：基準／變化版、互賴指標與先導流程。
4. [`data/README.md`](data/README.md)：原始影片、個資、證據 ID、雜湊值與處理資料規則。

## 目前主要待辦

- [Issue #1：核對 LFCG 原文、分類與頁碼](https://github.com/c2h5oh0802/friendslop_paper/issues/1)
- [Issue #2：完成 PEAK 第一份完整 LFCG 試編碼](https://github.com/c2h5oh0802/friendslop_paper/issues/2)
- [Issue #3：建立 V-CARRY-01 基準版／變化版並做先導](https://github.com/c2h5oh0802/friendslop_paper/issues/3)
- [Issue #4：2026 年 10 月前三章工作稿](https://github.com/c2h5oh0802/friendslop_paper/issues/4)
- [Issue #5：確認口試規格與受試者研究倫理要求](https://github.com/c2h5oh0802/friendslop_paper/issues/5)

## Repository 導覽

### `project/`

- `research_state.md`：目前研究定位、老師回饋、主張界線與未知事項
- `decision_log.md`：每個重要決策的來源、狀態與影響
- `roadmap.md`：到十月前三章與口試前的工作順序
- `terminology.md`：Friendslop、LFCG、互賴、假設等詞的固定用法

### `meetings/`

保存老師會談。明確分開老師意見、研究者解讀與工作安排。

### `literature/`

- `sources.csv`：來源 ID、閱讀狀態與驗證狀態
- `notes/`：逐篇筆記、能支撐與不能支撐的主張

未讀全文或未補頁碼的來源，不得假裝已確認。

### `research_design/`

- `overview.md`：四案例分析與互賴實驗的兩層研究設計
- `case_selection.md`：四案例選擇理由與正例限制
- `lfcg_coding_guide.md`：四面向分析、證據等級與反例搜尋
- `player_interdependence_experiment.md`：具體 A/B 測試工作稿
- `interdependence_event_codebook.md`：影片事件判定方式
- `variation_selection_matrix.csv`：各候選變化的可行性與混淆比較
- `data_management_and_ethics.md`：參與者同意、公開影片與待查官方要求

### `data/`

- `evidence_index.csv`：來源、會談、影片與主張的總索引
- `templates/`：LFCG、場次、事件、結果、問卷與影片清單模板
- `cases/`：四款遊戲各自的版本與分析入口
- `raw/`、`private/`：只放規則說明，真正檔案不得提交
- `processed/`：可提交的去識別資料

### `writing/`

- `chapter_plan.md`：前三章內容、十月交付條件與寫作順序
- `claim_evidence_map.csv`：每個主張能說多強、由什麼證據支持

### `presentation/`

- `oral_exam_plan.md`：影片為主的口試配置
- `video_clip_manifest.csv`：每段影片的來源、時間碼、主張與公開同意

## 研究記錄原則

1. 重要主張都要能回查文獻、官方資料、遊戲版本、測試情境、錄影或會談紀錄。
2. 觀察事實、推論、假設與老師已確認事項分開寫。
3. 原始影片、參與者姓名、同意書與任何可識別個資不得放進公開 Repository。
4. 原始資料不覆寫；處理後資料保留上游 ID、版本與修改原因。
5. 沒有實際完成的測試，不得寫成已驗證結果。
6. 「互賴增加」「任務變難」與「更好玩」是不同問題，不能互相代替。
7. 不利於原假設的反例與無效場次也要留下。

## 現在最先做

先完成 Issue #1 與 Issue #2。LFCG 定義和第一份完整案例表穩定後，再依原型條件決定 Issue #3 是否採 V-CARRY-01，或改用 `V-INFO-01`。這會比先把四款遊戲各寫成一篇介紹，更快產生能放進第二、第三章的證據。
