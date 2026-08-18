# Repository 工作規則

這個 Repository 用來保存可回查的研究資料。人工撰寫、ChatGPT、Codex 或其他工具都要遵守本檔。

## 修改前先讀

1. `project/research_state.md`
2. `project/decision_log.md`
3. 最新的 `meetings/` 會談紀錄
4. `research_design/overview.md`
5. `research_design/player_interdependence_experiment.md`
6. `literature/sources.csv`

較新的老師明確意見、研究者決定與正式規範，優先於舊草稿和模型建議。

## 不得編造

不得編造作者、年份、篇名、DOI、頁碼、引文、遊戲版本、測試結果、錄影時間碼、玩家反應、老師意見或研究結論。未讀全文的文獻要保留 `not_read`、`partially_read` 或 `pending_page_check`，不能寫成已確認。

## 資訊狀態

- `Advisor-confirmed`：老師有明確表示。
- `User-confirmed`：研究者已明確決定。
- `Working decision`：目前採用，但可依證據修改。
- `Observed`：可由影片、遊戲紀錄或原始資料直接確認。
- `Supported inference`：由證據支持的解釋，但不是畫面直接顯示。
- `Hypothesis`：待測試。
- `Unknown`：目前資料不足。

「老師覺得沒啥問題」只能寫成沒有指出重大方向問題，不能擴張成逐項核准。

## 固定 ID

- 文獻：`LIT-###`
- 決策：`DEC-###`
- 證據：`EVD-###`
- 實機／實驗場次：`SES-###`
- 影片：`VID-###`
- 遊戲觀察：`OBS-###`
- 互賴事件：`EVT-###`
- 論文主張：`CLM-###`

ID 建立後不得重複使用或重新編號。

## 證據鏈

正式文字的重要主張要能沿下列路徑回查：

`CLM-* → 分析／EVT-* → OBS-* → SES-*／VID-*／LIT-* → 時間碼、頁碼、網址或 SHA-256`

沒有直接證據時，只能標成推論、假設或未知。

## 資料與隱私

- 原始錄影、語音、同意書、姓名、帳號和參與者對照表不得提交到公開 Repository。
- 公開 Repository 只放代碼化資料、索引、欄位說明與雜湊值。
- 大型檔案保存在私有研究空間；位置記在索引，不能只留在單一電腦。
- 原始資料不覆寫。修正以新增紀錄或處理後版本完成，並保留原因。
- 開始招募、錄音或錄影前，先確認知情同意和校內研究倫理要求。

## 修改與驗證

不要刪除、重寫或重新格式化與當前工作無關的內容。新增方法、分類或結果前，先檢查現有決策和證據。完成後至少檢查：連結是否存在、CSV 欄位是否一致、ID 是否重複、主張是否有來源、私密資料是否誤入 Git。
