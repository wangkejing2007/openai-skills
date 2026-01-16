不同 Agent 技能的集合。
是整理用來處理特定文件類型的技能庫，每個子目錄都包含定義該技能的 skill.md
主要結構如下：
1. docs/ (處理文件相關)
skill.md
: 技能定義檔。
render_docx.py
: 可能用於渲染或處理 docx 文件的 Python 腳本。
2. pdfs/ (處理 PDF 相關)
skill.md
: 技能定義檔。
3. spreadsheets/ (處理試算表相關)
skill.md
: 技能定義檔。
spreadsheet.md
: 可能包含關於試算表的詳細說明。
artifact_tool_spreadsheets_api.md
 & 
artifact_tool_spreadsheet_formulas.md
: 關於試算表 API 和公式的工具文檔。
examples/: 一個包含範例的資料夾 (內含約 21 個項目)。
