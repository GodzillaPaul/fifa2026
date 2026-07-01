# 2026 世足決鬥之路

GitHub Pages 入口檔案：`index.html`。頁面會直接向 ESPN 同步小組賽、32 強及後續淘汰賽資料。

## 上傳方式

1. 將這個資料夾內的 `index.html`、`README.md`、`.nojekyll` 上傳到 GitHub repository 根目錄。
2. 到 repository 的 **Settings > Pages**。
3. 選擇 **Deploy from a branch**，指定要發布的分支與根目錄。
4. 等待 GitHub Pages 完成發布，首頁會自動載入 `index.html`。

## 本版修正

- 完整補抓 16 場 32 強的 ESPN 已定案隊伍。
- 相容 ESPN summary 省略 `isActive` 欄位的真實隊伍資料。
- 重新載入頁面時，保留已同步的淘汰賽隊伍與比分。
