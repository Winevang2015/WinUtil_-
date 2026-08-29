WinUtil 繁體中文版（WinUtil-TW）
非官方繁體中文修改版。基於 Chris Titus Tech 的 WinUtil 製作。

目前固定核心版本：26.08.19
繁中包裝版本：V15

專案說明
本專案的目的是在盡量不改變 WinUtil 原有功能與內部邏輯的前提下，提供較適合繁體中文使用者的操作介面。
為避免翻譯影響 WinUtil 內部路由、設定 ID、分類值與功能呼叫，本版本只針對經測試可安全修改的顯示文字進行繁體中文化。
下載與執行
下載以下兩個檔案，並放在同一個資料夾：
WinUtil_繁中_固定核心版_v15_26.08.19.ps1
啟動_WinUtil_繁中_固定核心版_v15_26.08.19.cmd
建議直接執行：
啟動_WinUtil_繁中_固定核心版_v15_26.08.19.cmd
Windows 出現 UAC 提示時，確認後以系統管理員權限執行。
也可以使用 PowerShell 手動啟動：
powershell.exe -NoProfile -ExecutionPolicy Bypass -File ".\WinUtil_繁中_固定核心版_v15_26.08.19.ps1"
V15 特點
固定內嵌 WinUtil 26.08.19 核心。
不會在啟動時自動替換成其他 WinUtil 核心版本。
保留 WinUtil 重要內部英文識別值，避免翻譯造成 Tweaks、Config、AppX 等頁面失效。
提供繁體中文介面翻譯。
保留 Standard / Minimal / Advanced 等原始功能。
可檢查官方版本號；偵測到新版時只提示，不自動覆蓋固定核心。
使用前注意
WinUtil 可以修改 Windows 系統設定、服務、登錄檔、更新設定與應用程式。執行 Tweaks 或其他系統修改前，建議先確認選取項目，重要電腦建議先建立系統還原點或備份。
本專案不是 Chris Titus Tech 官方繁體中文版。若繁中版本發生問題，可先使用官方 WinUtil 交叉測試，以判斷問題來自上游 WinUtil 或本專案的中文化處理。
上游專案
原始專案：ChrisTitusTech/winutil
官方 GitHub：
https://github.com/ChrisTitusTech/winutil
本專案保留原專案相關著作權與授權聲明。WinUtil 上游專案採 MIT License；詳細條款請參閱本專案 LICENSE 與上游專案。
版本
繁中版本：WinUtil 固定核心
狀態：V15 /26.08.19

測試中:V14.2/26.08.04

已驗證穩定版本
詳細變更請參閱 CHANGELOG.md。

問題回報
若遇到繁中介面造成的功能異常，回報時建議附上：
Windows 11 版本
WinUtil-TW 版本
發生問題的頁面或功能

錯誤訊息或畫面截圖

官方 WinUtil 是否有相同問題

這樣比較容易判斷是 WinUtil 上游問題，或繁體中文化造成的問題。
