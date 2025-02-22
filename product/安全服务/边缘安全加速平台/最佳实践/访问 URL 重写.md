
## 功能简介

将客户端用户实际发起请求访问的 URL 重写到目标 URL，匹配节点缓存资源的 URL。

## 操作步骤

1. 登录 [边缘安全加速平台控制台](https://console.cloud.tencent.com/teo) ，在左侧菜单栏中，单击**规则引擎**。
2. 在规则引擎页面，选择所需站点，单击![](https://qcloudimg.tencent-cloud.cn/raw/fe4d4900f8ad69d506adc49bdb70fa32.png)可按需配置访问 URL 重写规则。
>!目前仅支持匹配条件为 URL path 或 Host And URL path 时配置 访问 URL 重写操作。
>
参数说明：
<table>
<thead>
<tr>
<th>配置项</th>
<th></th>
</tr>
</thead>
<tbody><tr>
<td>目标 URL</td>
<td>希望重写的目标 URL，例如：<code>www.example.com/images/foo.jpg</code> 或 <code>www.example.com/foo/bar</code></td>
</tr>
</tbody></table>
3. 根据实际需求，单击**保存并发布**或**仅保存**。
>?
>- 保存当前编辑的规则，并发布至现网生效。
>- 仅保存当前编辑的规则内容，不发布至现网。
