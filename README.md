# program-language｜112-2 程式語言與資料分析學習紀錄

> **University Learning Journey · Year 2 / 2024**  
> 從「做網頁」進一步走向「取得、整理、分析並呈現資料」。

## About this repository

這個 repository 記錄我在國立臺灣師範大學「程式語言」課程中的 Python 學習與資料實作。

課程從 Python 基礎開始，逐步進入資料正規化、網路爬蟲、資料清整、視覺化與文字探勘。對我而言，這門課的重要轉折是：我開始理解程式不只是用來完成指定功能，也可以成為**觀察資料、提出問題與建立證據**的工具。

這種資料思維後來延伸到人員數據分析、LexiAI 專題驗證，以及目前對 AI 決策支援與研究方法的興趣。

## Course information

- **課程**：112-2 程式語言
- **學校**：國立臺灣師範大學
- **系所**：科技應用與人力資源發展學系
- **授課教師**：[蔡芸琤老師](https://github.com/pecu)
- **學生**：[董承翰](https://chenhan0301.github.io/Myweb/)

## Learning path

| 階段 | 主題 | 實作能力 |
|---|---|---|
| Week 2–4 | Python 基礎 | 資料型態、集合、流程控制與基本分析 |
| Week 5 | 資料正規化 | 將原始資料轉成可處理結構 |
| Week 6 | 網路爬蟲 | Requests / BeautifulSoup |
| Week 8 | 資料清整與視覺化 | Pandas、表格與圖表 |
| Week 9–10 | 文字探勘 | 文字資料處理與分析延伸 |

## Coursework & evidence

### HW1 · 世界排名集合分析
[View Notebook](https://github.com/chenhan0301/program-language/blob/main/HW1.ipynb)

以撞球世界排名資料為例，使用 Pandas 讀取 CSV，將 2023 與 2024 年排名轉為 Python Set，並以：

- Union 聯集
- Intersection 交集
- Difference 差集

比較不同年度選手組成。

**我在這裡學到：** 資料結構的選擇會直接影響問題可以如何被表達與計算。

### HW2 · 選手資料結構、篩選與視覺化
[View Notebook](https://github.com/chenhan0301/program-language/blob/main/HW2.ipynb)

整理撞球選手的：

- 總收入
- 國籍
- 世界排名

將多個資料欄位整合為 JSON，並進行條件篩選，例如國籍、排名與收入門檻。

相關成果：
- [視覺化圖表](https://github.com/chenhan0301/program-language/blob/main/HW2%20%E8%A6%96%E8%A6%BA%E7%95%AB%E5%9C%96%E8%A1%A8.png)
- [長條圖](https://github.com/chenhan0301/program-language/blob/main/%E9%95%B7%E6%A2%9D%E5%9C%96.png)

**我在這裡學到：** 從「存資料」走向「設計資料結構與閱讀資料」。

### HW3 · PTT Baseball 網路爬蟲
[View Notebook](https://github.com/chenhan0301/program-language/blob/main/HW3.ipynb) · [Demo Video](https://youtu.be/ccvip9SmF9k)

使用：
- `requests`
- `BeautifulSoup`
- `pandas`
- `json`

擷取 PTT Baseball 看板文章的標題、人氣與日期，並輸出為 JSON 與 CSV。

**流程：**

`Web Page → HTML Parsing → Structured Data → JSON / CSV`

**我在這裡學到：** 分析之前最重要的往往不是模型，而是如何可靠地取得與整理資料。

### HW4 · 資料分析與文字處理延伸
[View Notebook](https://github.com/chenhan0301/program-language/blob/main/HW4.ipynb)

在 Google Colab / GPU 環境中延伸資料分析、圖表生成與文字資料處理實作。

這個階段也讓我第一次接觸到較大型的 Python 套件與運算環境，成為後續理解 AI / NLP 工作流程的前置經驗。

## Skills developed

`Python` · `Pandas` · `Jupyter Notebook` · `Requests` · `BeautifulSoup` · `JSON` · `CSV` · `Data Visualization` · `Text Processing`

## Learning reflection

這個 repository 留下的是我從「程式語法」走向「資料思維」的過程。

後來做 LexiAI 時，我需要處理語言輸出、結構化 JSON、分析結果與報表；回頭看，這門課建立的資料處理觀念其實是其中很重要的基礎。

## Where this led next

**Web → Data → Database → AI System → Research**

- 前一階段：[Web](https://github.com/chenhan0301/Web)
- 下一階段：[Database-System](https://github.com/chenhan0301/Database-System)
- 大學整合專題：[Report-template / LexiAI](https://github.com/chenhan0301/Report-template)
- 完整四年歷程：[Personal Portfolio](https://chenhan0301.github.io/Myweb/)

---

**Chenhan Tung / 董承翰**  
Human Resources × Computer Science × Trustworthy AI
