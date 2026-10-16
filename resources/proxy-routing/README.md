# 代理分流规则

供 Android v2rayNG 和 Windows v2rayN 使用的分流规则及配套分类库。**不包含代理节点**，请先导入自己的节点并确认普通连接可用。

## 下载

[发布说明与全部附件](https://github.com/rumoii/rumo-resources/releases/tag/proxy-routing-2026-10-16)

| 平台 | 适用版本 | 文件 |
| --- | --- | --- |
| Android | v2rayNG 1.10.32 | [android-v2rayng-1.10.32.zip](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-10-16/android-v2rayng-1.10.32.zip) |
| Windows | v2rayN 7.25.4、Xray 26.9.9、sing-box 1.14.0 | [windows-v2rayn-7.25.4.zip](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-10-16/windows-v2rayn-7.25.4.zip) |

[SHA256 校验文件](https://github.com/rumoii/rumo-resources/releases/download/proxy-routing-2026-10-16/SHA256SUMS.txt)

## 使用

下载并解压对应压缩包，按包内 `README.md` 操作。先导出原规则并记录 DNS、TUN 设置，再导入本包规则。Android 包内有可在浏览器打开的 `import.html`，供复制路由规则。

Android 包包含 13 条规则、两份分类库和操作说明；Windows 包包含 14 条规则、分类库和操作说明。Windows 的第一条进程例外默认停用，需要时填写自己的进程路径再启用。

规则快照日期为 2026-10-04，首次资源发布日期为 2026-10-16。包内保留第三方分类库的来源与许可证，详见各自说明。

已有验证覆盖压缩包完整性、规则解析及隔离路由选择，不代表在你的设备上完成联网验收。导入后检查出口、DNS、WebRTC 和国内访问；需要恢复时按包内说明还原原规则与设置。
