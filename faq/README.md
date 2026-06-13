# FAQ 在线问答

App 从此目录按语言拉取 JSON：`https://raw.githubusercontent.com/lamymay/input/main/faq/{locale}.json`

## 文件命名

与 App 语言代码一致：`en.json`、`zh-Hans.json`、`zh-Hant.json`、`ja.json`、`ko.json`、`fr.json`

## JSON 格式

```json
{
  "items": [
    {
      "id": "unique_id",
      "question": "问题文本",
      "answer": "回答文本"
    }
  ]
}
```

`id` 可选，用于列表展开状态；省略时用 `question` 作为标识。
