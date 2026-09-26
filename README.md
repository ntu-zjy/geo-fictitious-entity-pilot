# 静态网页发布包

`index.html` 是公开披露页，使用语义化标题、可抓取正文和 `index,follow` 元信息。PUBLIC-PILOT-V2 加入了与可见问答一致的 `FAQPage` 结构化数据，但没有 LocalBusiness、商家组织、电话、地址或资质标记。子路径 `robots.txt` 虽列出 Allow 和 sitemap，但不属于有效的根目录规则（见文末更正）。公开地址：<https://ntu-zjy.github.io/geo-fictitious-entity-pilot/>。

## 可索引性说明

本地页面的 HTML 已准备为可索引内容，但托管平台也会决定爬虫行为。Vercel 预览部署默认添加 `X-Robots-Tag: noindex`，因此不能用预览部署做自然搜索发现测试。当前改用 GitHub Pages 的正式公开站点 URL。

## 发布后的观察

D0 的 PUBLIC-PILOT-V1 页面已核验生产 URL 可访问；精确站点搜索没有返回页面，发布后豆包、Kimi 各一次未提供 URL 的新会话查询也未发现或引用页面。PUBLIC-PILOT-V2 已于 2026-09-25 部署，增加直接回答、可见 FAQ 和对应 FAQPage 结构化数据，并澄清现实同名主体的核验边界。V2 即时 Google 站点限定搜索、Kimi 和豆包新会话均未发现页面。D+7、D+14、D+28 再查精确标题和实体查询，并用未提供 URL 的新会话复测豆包、Kimi。用户主动给模型 URL 后能总结，只记为 URL 阅读诊断，不记自然发现或引用效果。


## robots 解释更正（保留此前观测）

2026-09-26 更正：本项目 robots.txt 位于 /geo-fictitious-entity-pilot/ 子路径，不是域名根目录的有效 robots 文件，其中的 Allow 和 Sitemap 不能作为有效爬虫规则或发现入口。域名根目录 https://ntu-zjy.github.io/robots.txt 本次 HTTP 核验为 404；按 Google 官方说明，404 视为无抓取限制。这不保证收录，也不能解释此前 sitemap 无法抓取的具体原因。依据：https://developers.google.com/crawling/docs/robots-txt/robots-txt-spec 。


## 实用资料（PRACTICAL-PILOT-V1）

- [近名机构核验指南](https://ntu-zjy.github.io/geo-fictitious-entity-pilot/entity-verification-guide.html)
- [核验清单及 CSV 下载](https://ntu-zjy.github.io/geo-fictitious-entity-pilot/verification-checklist.html)

资料提供通用核验方法，不调查或推荐虚构商家。实际测评记录不放入本公开站点；读到网页、搜索发现与自然回答引用分别判断。
