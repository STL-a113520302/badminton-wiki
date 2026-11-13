# 羽球運動傷害與修復 Wiki

這個專案整理羽球運動傷害、伸展與熱身、競賽心理相關文獻，並以 HTML 閱讀簡報呈現主題內容。主要讀者為一般民眾與課程助教。

## 從哪裡開始

- **網站入口：**開啟專案根目錄的 [`index.html`](index.html)。部署至 GitHub Pages 後，入口頁會連到簡報選單。
- **簡報選單：**[`presentations/index.html`](presentations/index.html)。可進入三份主題簡報。
- **Wiki 導覽：**[`wiki/index.md`](wiki/index.md)。在 GitHub 專案頁面中開啟，可閱讀已整理的主題與文獻筆記。

## 專案內容

- `wiki/papers/`：逐篇文獻筆記，包含研究方法、結果、實務解讀、限制與引用。
- `wiki/topics/`：跨文獻主題整理，連結至支持各項說法的文獻頁。
- `wiki/index.md`：Wiki 導覽索引。
- `sources/raw/`：原始論文 PDF，供回查文獻頁碼。
- `presentations/`：HTML 閱讀簡報與整合入口頁。
- `workflows/`：Wiki 維護及簡報製作流程規格。
- `AGENTS.md`：本專案的整理、引用與寫作規則。

## HTML 簡報

簡報使用繁體中文，面向一般讀者；每份簡報有 10–15 頁內容，封面與參考資料另計。從 [`presentations/index.html`](presentations/index.html) 進入以下主題：

1. [打羽球會造成哪些傷害？](presentations/badminton-injuries/index.html)
2. [羽球運動傷後處置](presentations/badminton-injury-aftercare/index.html)
3. [羽球伸展動作與競賽心理](presentations/badminton-stretch-psychology/index.html)

## 發布到 GitHub Pages

1. 將整個專案資料夾建立為 GitHub 儲存庫並推送至 `main` 分支。
2. 在 GitHub 儲存庫開啟 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**，分支選 `main`、資料夾選 `/(root)`，再按 **Save**。
4. 發布完成後，網站入口網址格式為 `https://<帳號>.github.io/<儲存庫名稱>/`；簡報選單亦可由網址後加 `presentations/` 開啟。

GitHub Pages 網站會公開在網路上。公開前請確認原始 PDF 的分享權限，以及專案內容是否適合公開。若只需讓助教查看檔案，可改用 Private 儲存庫並邀請助教；GitHub Pages 發布的網站仍是公開可瀏覽的。

## 閱讀提醒

本 Wiki 是文獻閱讀工具，不提供個人診斷、治療或復健處方。各研究的對象、年代與方法不同，請連同文獻頁所列 PDF 頁碼及研究限制閱讀結果。舊文中的建議會標示為作者當時的觀點，不代表最新醫療標準。
