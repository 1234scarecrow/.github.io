#### 1. note list
+ 接口 URL
`{{url}}/note?curPage=1&pageSize=3`
+ 请求方式
`GET`
+ 请求 Query 参数
|参数|示例值|必填|参数描述|
|---|---|---|---|
|curPage|1|必填|当前页码|
|pageSize|3|必填|每页显示数量|

+ 成功响应示例
```json
{
  "code":200,
  "msg":"get notes success",
  "data":[
    {
      "noteId":1,
      "content":"Lorem1...",
      "pubTime":"2020-2-22"
    },
    {
      "noteId":2,
      "content":"Lorem2...",
      "pubTime":"2020-2-22"
    },
    {
      "noteId":3,
      "content":"Lorem3...",
      "pubTime":"2020-2-22"
    },
  ],
  "pageNum":"1",
  "pageSize":3,
}