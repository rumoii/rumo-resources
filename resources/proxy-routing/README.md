# 代理分流规则

供 Android v2rayNG 和 Windows v2rayN 使用的分流规则及配套分类库。**不包含代理节点**，请先导入自己的节点并确认普通连接可用。

## 下载

[发布说明与全部附件](https://github.com/rumoii/rumo-resources/releases/tag/proxy-routing-2026-11-18)

| 平台 | 适用版本 | 文件 |
| --- | --- | --- |
| Android | v2rayNG 1.10.32 | [android-v2rayng-1.10.32.zip](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-11-18/android-v2rayng-1.10.32.zip) |
| Windows | v2rayN 7.25.4、Xray 26.9.9、sing-box 1.14.0 | [windows-v2rayn-7.25.4.zip](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-11-18/windows-v2rayn-7.25.4.zip) |

[SHA256 校验文件](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-11-18/SHA256SUMS.txt) · [旧版 2026-10-16](https://github.com/rumoii/rumo-resources/releases/tag/proxy-routing-2026-10-16)

## 使用

下载并解压对应压缩包，按包内 `README.md` 操作。先导出原规则并记录 DNS、TUN 设置，再导入本包规则。Android 包内有可在浏览器打开的 `import.html`，供复制路由规则。

Android 包包含 13 条规则、两份分类库和操作说明；Windows 包包含 14 条规则、分类库和操作说明。Windows 的第一条进程例外默认停用，需要时填写自己的进程路径再启用。

2026-11-18 快照在 AI 代理规则中补充 Persona 两个域名后缀和 Google Maps 精确域名。沿用 2026-10-16 版分类库的 Android 用户可只更新路由。启用了完整 Xray 配置模板的 Windows 用户按包内说明同步模板中的路由和 DNS。分类库来源及许可证见包内说明。

已有验证覆盖压缩包完整性、规则解析及隔离路由选择，不代表在你的设备上完成联网验收。导入后检查出口、DNS、WebRTC 和国内访问；需要恢复时按包内说明还原原规则与设置。
