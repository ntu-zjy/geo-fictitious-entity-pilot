# 静态网页发布包

`index.html` 是公开披露页，使用语义化标题、可抓取正文和 `index,follow` 元信息；没有 LocalBusiness、电话、地址、资质或其他会把样本误标成真实公司的结构化数据。`robots.txt` 允许抓取并列出 sitemap。预定公开地址：<https://ntu-zjy.github.io/geo-fictitious-entity-pilot/>。

## 可索引性说明

本地页面的 HTML 已准备为可索引内容，但托管平台也会决定爬虫行为。Vercel 预览部署默认添加 `X-Robots-Tag: noindex`，因此不能用预览部署做自然搜索发现测试。当前改用 GitHub Pages 的正式公开站点 URL。

## 发布后的观察

登记生产 URL、发布时间和页面访问状态；马上做一次 URL 可访问检查和精确标题检索作为 D0 诊断。D+7、D+14、D+28 再查一次精确标题和实体查询，并用未提供 URL 的新会话复测豆包、Kimi。用户主动给模型 URL 后能总结，只记为 URL 阅读诊断，不记自然发现或引用效果。
