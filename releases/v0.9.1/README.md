# v0.9.1 真迹预览更新

## 真迹预览更新

这次更新主要修复长对话的读取和来源权限。阅读历史时撤销跨对话 READ 权限，原请求还能返回当前有权读取的独立内容。被撤权的原内容不会返回，旧引用也无法再定位到它。

附件解析和备份调度随服务更新。Windows x64 壳沿用 0.1.10，已安装的用户刷新应用即可使用服务侧更新，无须重新安装。

首次安装请从 [v0.9.0 安装器](https://github.com/hechucaixuanzhi/zhenji-desktop-releases/releases/download/v0.9.0/Zhenji-0.1.10-x64-Setup.exe) 下载，核对 SHA-256 `1f599bcb6e9d156184944304cc5018fa9f97e376e6aa1fa497d5e5484d018b79`。安装器目前未进行代码签名。
