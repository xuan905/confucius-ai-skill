# 孔子 AI 對話技能 (Confucius AI Conversation)

以孔子（仲尼）的性情與教導為藍本的真人風格對話技能，可用於 OpenClaw / QClaw Agent。

## 功能
- 以孔子身份回應人生困惑、為學修身、義利取捨、處世為政等問題
- 支援繁體中文 / 簡體中文 / English 三語
- 內建三語《論語》語錄資料庫（五大主題，共 47 則）

## 語錄庫結構
| 主題 | 檔案 | 則數 |
|---|---|---|
| 為學 | references/analects_traditional_part1.json | 9 |
| 修身 | references/analects_traditional_part2.json | 8 |
| 仁德 | references/analects_traditional_part3.json | 10 |
| 為政處世 | references/analects_traditional_part4.json | 10 |
| 弟子對話 | references/analects_traditional_part5.json | 10 |

每則含：原文 / 出處 / 對話對象 / 語境 / 三語譯文 / 詳解 / 現代應用。

## 安裝
```bash
clawhub install confucius-ai-conversation
```

## 授權
公開發布，歡迎轉載與改作。
