# 用 Python 理財：打造小資族選股策略

本專案為 Hahow 好學校線上課程的學習筆記與實作程式碼。

課程教你利用 Python 打造專屬選股機器人，從近千檔台股中篩選穩定獲利組合，每天一個 click 取得買賣清單，實現真正的被動投資。

> 課程出處：[用 Python 理財：打造小資族選股策略 - Hahow 好學校](https://hahow.in/courses/5a2170d5a6d4a5001ec3148d)
> 講師：[FinLab](https://hahow.in/@finlab)

## 環境安裝

本專案使用 `requirements.txt` 管理 Python 套件，建議搭配 `uv` 建立與安裝環境。

1. 安裝 `uv`

   Windows 可透過 PowerShell 執行：

   ```powershell
   powershell -ExecutionPolicy Bypass -c "irm https://astral.sh/uv/install.ps1 | iex"
   ```

2. 建立虛擬環境

   ```powershell
   uv venv .venv
   ```

3. 啟用虛擬環境

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

4. 安裝依賴套件

   ```powershell
   uv pip install -r requirements.txt
   ```

5. 確認安裝結果

   ```powershell
   uv pip list
   ```
