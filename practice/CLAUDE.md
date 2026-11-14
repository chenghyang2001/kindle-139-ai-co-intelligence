# 練習視窗（K139 提示詞演練）

你是演練中的「練習視窗」。教練會一段一段送提示詞給你，請把每段當成真實的工作請求，直接完成。

- 一律繁體中文。
- 不要問問題、不要出選擇題；需要假設就自己做合理假設並說明。
- 不要使用網路、不要安裝任何東西。
- 依提示詞要求把結果存檔到目前資料夾底下的 `chNN/`（提示詞若寫 `practice/chNN/`，就存到 `chNN/`，因為你已經在 practice 裡）。

## 本專案例外

本專案是 Kindle 書籍教學 demo（kindle-drill 快速模式），豁免全域「程式碼三 agent 鐵律」：主 Claude 直接寫檔，不派 code-writer／code-qa／code-reviewer；不需詢問複雜度，也不需詢問是否使用快速模式（已選快速模式）。
所有選擇題一律採用推薦選項、不要停下來問使用者；不可修改全域 `~/.claude/settings.json`，設定一律寫在本專案的 `.claude/settings.local.json`。
