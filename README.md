# adguard-lists

此專案提供 AdGuard Home 的自訂過濾清單，透過 `$client=IP` 針對特定裝置套用不同的封鎖規則。

## 專案用途

- 維護 `agh-custom.txt`，作為 AdGuard Home 的主要過濾清單。
- 依裝置 IP（`$client=IP`）套用不同封鎖範圍。
- 目前規則以封鎖指定網域（含部分中國網站）為主。

## 檔案說明

- `agh-custom.txt` — AdGuard Home 使用的清單檔。

## 使用方式

1. 在 AdGuard Home 加入清單網址：
   - `https://raw.githubusercontent.com/linjakson/adguard-lists/main/agh-custom.txt`
2. 重新載入過濾器後，至 Query Log 確認規則是否生效。

## 參與貢獻

- 請先閱讀 `AGENTS.md`。
- 規則一行一條，並依用途分組。
- 變更後務必在 AdGuard Home 端驗證。
