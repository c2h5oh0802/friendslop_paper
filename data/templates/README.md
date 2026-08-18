# 資料表模板

正式收資料前，複製模板到 `data/processed/` 或對應案例資料夾，再加版本號。不要直接把實際資料填進模板檔。

## 模板

- `lfcg_case_matrix.csv`：四款遊戲的 LFCG 判定與證據。
- `session_manifest.csv`：每次實驗／先導場次的條件與有效性。
- `event_log.csv`：影片中的玩家互賴事件。
- `trial_results.csv`：每隊每條件的任務與互賴摘要。
- `video_manifest.csv`：原始影片、剪輯與雜湊值索引。
- `questionnaire_items.csv`：條件後短問卷工作版。

## 填寫原則

- 空白表示尚未填；`NA` 表示確定不適用；`UNKNOWN` 表示目前無法判定。
- 時間一律使用 `HH:MM:SS.mmm`。
- 日期使用 `YYYY-MM-DD`。
- 布林值使用 `TRUE`／`FALSE`。
- 不在自由文字中放姓名、帳號或聯絡方式。
- 修改欄位時建立新模板版本，並在 commit 說明原因。
