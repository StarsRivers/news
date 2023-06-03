# 每日早报

[![news](https://socialify.git.ci/zkeq/news/image?description=1&descriptionEditable=%E5%89%8D%E5%90%8E%E7%AB%AF%E5%9D%87%E5%9F%BA%E4%BA%8E%20vercel%20%E7%9A%84%E8%BD%BB%E9%87%8F%E7%BA%A7%E6%AF%8F%E6%97%A5%E6%97%A9%E6%8A%A5%E9%A1%B9%E7%9B%AE%EF%BC%8C%E6%94%AF%E6%8C%81%E4%B8%80%E9%94%AE%E9%83%A8%E7%BD%B2%EF%BC%8C%E6%94%AF%E6%8C%81%E9%83%A8%E7%BD%B2%E8%87%B3%E6%9C%8D%E5%8A%A1%E5%99%A8%E3%80%82%E5%90%8E%E7%AB%AF%E7%94%B1%20FastAPI%20%2B%20BeautifulSoup%20%E5%AE%9E%E7%8E%B0%E3%80%82&font=Raleway&forks=1&logo=https%3A%2F%2Fnews.icodeq.com%2Ffavicon.svg&name=1&owner=1&pattern=Plus&stargazers=1&theme=Dark)](https://news.icodeq.com)

#### 项目起因

- 经常在各种地方看到 `每日60s读懂世界`

- 感觉很不错，就想着能不能自己做一个

- 详细经过见博文：[归档 | 前后端都基于 vercel 的每日早报项目](https://icodeq.com/2022/5fe2010403bb/)



#### [源项目](https://github.com/zkeq/news/blob/main/)


#### API 说明

GET：`/api`

##### 请求参数

| 参数名           | 位置  | 类型   | 必填 | 示例值 |说明  |
| :--------------- | :---- | :----- | :--: | :--------------------- | :--------------------- |
| `_vercel_no_cache` | `query` |        |  否  | `1` |说明：`vercel` 强制不缓存                            |
| `cache`          | `query` |        |  否  | 任意值  |说明：清除缓存用                              |
| `index`          | `query` | `number` |  否  | `0` | 说明：`0-99` 用来控制天数，`0` 为今天，`1` 为昨天，依次类推 |
| `origin`         | `query` | `string` |  否  | `zhihu` |说明："`zhihu`" 或 "`163`" 切换源                  |

详细信息见：[每日早报 (apifox.cn)](https://www.apifox.cn/apidoc/shared-4c5d28ed-633e-45e0-a6d5-3c0a8933f132/api-28569354)
