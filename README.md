# ChizUP! Flash Store Data

此 repo 用於管理 ChizUP! 官網商品頁的百貨快閃據點資訊。
每月更新 `flash-stores.json` 即可讓所有商品頁自動同步。

## 更新方式

1. 點開 `flash-stores.json`
2. 點右上角鉛筆圖示（Edit）
3. 修改 `stores` 陣列內容與 `updated` 月份
4. 按 **Commit changes**
5. 完成，所有商品頁約 1 分鐘內自動更新

## JSON 欄位說明

| 欄位 | 說明 | 範例 |
|------|------|------|
| `name` | 百貨名稱 | `"台北美麗華"` |
| `floor` | 樓層 | `"B1"` |
| `start` | 開始日期（MM/DD） | `"04/01"` |
| `end` | 結束日期（MM/DD） | `"04/30"` |

## Widget 公開網址

```
https://raw.githubusercontent.com/chizupAI-sys/chizup-flash-data/main/flash-stores.json
```
