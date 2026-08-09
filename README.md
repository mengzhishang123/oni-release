# 缺氧综合数据库（安装包发布）

这个仓库用于发布《缺氧综合数据库》的桌面版安装包。

## 下载方式

请前往 Releases 页面下载最新版本：

- [Releases](https://github.com/mengzhishang123/oni-release/releases)
- [Latest Release](https://github.com/mengzhishang123/oni-release/releases/latest)

## 说明

- 这里主要提供安装包下载
- 这里不作为源码开发仓库使用
- 如需查看每个版本的主要更新内容，请阅读对应 Release 说明

## 当前版本

当前建议下载 0.1.7 版本对应平台的安装包：

Windows：

- `oni-database-v0.1.7-x64-zh-CN.msi`

Linux：

- `oni-database-v0.1.7-linux-x86_64.AppImage`
- `oni-database-v0.1.7-linux-amd64.deb`
- `oni-database-v0.1.7-linux-x86_64.rpm`

校验文件：

- `oni-database-v0.1.7-sha256.txt`
- `oni-database-v0.1.7-linux-sha256.txt`

## 安装提示

- Windows 安装完成后可从开始菜单或桌面快捷方式启动
- Windows 安装器不会自动下载 WebView2 运行时；如果目标电脑缺少 WebView2，程序可能无法正常启动
- Linux 用户可优先尝试 AppImage；Debian / Ubuntu 系可使用 `.deb`，Fedora / RHEL 系可使用 `.rpm`
- macOS 版本目前仅在 CI 中构建，尚未在真实 macOS 设备上完成验证，因此暂不提供正式下载

## 校验信息

Release 附件中的 `oni-database-v0.1.7-sha256.txt` 与 `oni-database-v0.1.7-linux-sha256.txt` 可用于校验对应平台安装包的完整性。
