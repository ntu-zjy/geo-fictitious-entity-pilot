# 静态网页发布包

`index.html` 是公开披露页，使用语义化标题、可抓取正文和 `index,follow` 元信息。PUBLIC-PILOT-V2 加入了与可见问答一致的 `FAQPage` 结构化数据，但没有 LocalBusiness、商家组织、电话、地址或资质标记。`robots.txt` 允许抓取并列出 sitemap。公开地址：<https://ntu-zjy.github.io/geo-fictitious-entity-pilot/>。

## 可索引性说明

本地页面的 HTML 已准备为可索引内容，但托管平台也会决定爬虫行为。Vercel 预览部署默认添加 `X-Robots-Tag: noindex`，因此不能用预览部署做自然搜索发现测试。当前改用 GitHub Pages 的正式公开站点 URL。

## 发布后的观察

D0 的 PUBLIC-PILOT-V1 页面已核验生产 URL 可访问；精确站点搜索没有返回页面，发布后豆包、Kimi 各一次未提供 URL 的新会话查询也未发现或引用页面。PUBLIC-PILOT-V2 旨在让实验身份、直接答案和实体边界更清楚，不保证索引或引用。D+7、D+14、D+28 再查精确标题和实体查询，并用未提供 URL 的新会话复测豆包、Kimi。用户主动给模型 URL 后能总结，只记为 URL 阅读诊断，不记自然发现或引用效果。
