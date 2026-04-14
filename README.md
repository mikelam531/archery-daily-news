# 每日香港射箭新聞 Daily Archery News

此倉庫由自動化腳本每日更新，儲存來自中國香港射箭總會的最新消息。

## 資料格式

`data/news.json` — 最新 3 篇新聞報導（JSON 格式）

### 讀取 URL

```
https://raw.githubusercontent.com/mikelam531/archery-daily-news/main/data/news.json
```

### JSON 結構

```json
{
  "generated_at": "2026-04-14 08:00:00",
  "date": "2026-04-14",
  "articles": [
    {
      "id": "2026-04-14-XXXXXX",
      "date": "2026-04-14",
      "category": "本地動態",
      "title": "文章標題",
      "summary": "50字以內摘要",
      "content": "完整報導內容",
      "source_url": "https://www.archery.org.hk/...",
      "generated_at": "2026-04-14 08:00:00",
      "status": "published"
    }
  ]
}
```

## 來源

資料來源：[中國香港射箭總會](https://www.archery.org.hk)
