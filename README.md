# social-assets

有的沒的小舖（魯魯）社群貼文用的圖片，供 Buffer 等排程工具抓取。

**規則：只放「本來就要公開發布」的圖。** 未公開素材、內部資料、任何個資不要放這裡。

路徑：`年/月/YYYY-MM-DD_主題.jpg`
直接連結格式：`https://raw.githubusercontent.com/lululin221010/social-assets/main/<路徑>`

## posts.json（已發布貼文索引，給 SS「魯魯相簿」用）

2026-10-02 從 Buffer 匯出所有已發布貼文，合併各平台重複貼文後整理。每筆有：日期、文字、各平台連結、素材（已備份到 `archive/`）、`ss`（include／exclude／review）、`category`。

- `ss: exclude`：商品／課程推廣、含第三方推薦碼——SS「純免費、不推銷」規則不放。
- `ss: review`：需妹決定（無文字圖、含真人照片）。
- 素材 `lost: true`：原檔在 Vercel 暫存區已被清掉，需從本機或原平台補回。
