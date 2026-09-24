# FB工具箱发布

本仓库保存 Windows 发布包、签名更新清单和使用说明，不包含源码、用户浏览器资料或发布密钥。

## 当前版本：2.2.0.213

| 产品 | 下载入口 | 完整包大小 |
| --- | --- | --- |
| 数据获取版（原 FB投放版，含搭建广告、BM报表） | [下载 2.2.0.213](https://github.com/GaoLiJ/facebook-onboarding-releases/releases/tag/ads-reports-v2.2.0.213) | 约 111 MB |
| 开户版（含开户、营业执照识别） | [下载 2.2.0.213](https://github.com/GaoLiJ/facebook-onboarding-releases/releases/tag/onboarding-v2.2.0.213) | 约 175 MB |

两版应用版本相同，按用途裁剪依赖。首次安装请选择对应 Release 中的完整 `win-x64.zip`，解压后运行 `FB工具箱.exe`。

## 自动更新

- 版本号旁是常驻更新入口；发现新版显示绿色提示点，关闭通知后仍可点击查看。
- 后台下载后，任务结束时由用户点击重启工具箱生效，浏览器保持打开。
- 数据获取版 2.2.0.212 升级到 213 的增量下载约 2.14 MB；`.delta.zip` 由更新器使用，手动安装请选择完整 ZIP。
- 更新按新版完整文件清单重建，新增、修改、删除均适用。工具箱旧目录保留用于回滚。
- 两版采用各自的应用更新频道，不会相互覆盖。更早的开户版首次需要安装此完整包，以后使用内置更新。

## 浏览器连接器

当前沿用 **0.0.52**，并建立[独立连接器发布通道](https://github.com/GaoLiJ/facebook-onboarding-releases/releases/tag/browser-connector-v0.0.52)。

从工具箱 2.2.0.213 起，连接器可独立下载新版，任务空闲后自动替换并后台重载；应用版本不必变化。扩展自身版本必须递增，不在同一个完整版本号下覆盖不同内容。当前通道基线 0.0.52 不会要求已就绪的 0.0.52 再升级一次。

## 历史版本

[查看全部发布版本](https://github.com/GaoLiJ/facebook-onboarding-releases/releases)

历史发布包不会因新版本而覆盖。[数据获取版前身 2.2.0.212](https://github.com/GaoLiJ/facebook-onboarding-releases/releases/tag/ads-reports-v2.2.0.212) 和原 [Facebook 开户自动化 v2.0.4](https://github.com/GaoLiJ/facebook-onboarding-releases/releases/tag/v2.0.4) 仍可下载。
