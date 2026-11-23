# 資優班街頭採訪隊

資優嘉年華：招生企劃（第1節）訪問小遊戲。

- 教師看板：`index.html`（Google 登入 peitt1940@gmail.com 才能使用）
  - 開新的一堂課 → 產生課堂代碼與四組 QR code
  - 即時看各組採訪進度、便利貼張數、分堆數、結論
  - 公布／收回各組歸納牆；清除這堂課
- 各組頁：`index.html?g=1&s=課堂代碼`～`?g=4`（家長／低年級學生／中高年級學生／社會人士），匿名登入、只寫自己那組
- 資料庫：Firebase Realtime Database（專案 gifted-interview-game），安全規則見 `database.rules.json`
- 沒有 `s` 參數時為單機模式（資料只存在平板，教師密碼清除）
- 版本：v4（2026-11-23）
