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

6. 更新 requirements.txt（如需新增或更新套件後）

   ```powershell
   uv pip freeze > requirements.txt
   ```

7. 安裝資料庫管理工具

   本專案使用 SQLite 資料庫，建議安裝 **DB Browser for SQLite** 進行資料庫檢查和管理：

   [DB Browser for SQLite](https://sqlitebrowser.org/)

   **安裝方式：**
   - 前往官方網站下載適合您作業系統的版本
   - 或使用套件管理工具安裝：
     - Windows (Chocolatey): `choco install sqlitebrowser`

## 參考資料

- [MOPS公開資訊觀測站](https://mops.twse.com.tw/mops/#/web/home)

## 備註

有些網址已更新，只參考投資策略
