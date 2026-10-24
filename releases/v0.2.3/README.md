# 真迹 v0.2.3 Windows Desktop Beta 更新说明

真迹预览版 v0.2.3：私信正文保存与发送体验改进。

- 新发送的私信保留输入中的首尾空白、缩进、换行，以及 emoji、组合字符等原文内容。
- 发送一条消息后继续输入下一条，前一条迟到的成功或失败回执不会清空新输入。
- 独立私信页与全局消息面板使用一致的安全纯文本显示；Markdown 符号、HTML 和链接保持字面内容，不启用 Markdown 模式或加载消息中的远端资源。
- 网络波动时先核对同一次发送，重试沿用原操作，避免产生重复私信；结果尚未确认时保留输入。

本次改进适用于新发送的私信。历史消息中已经丢失的空白或字符无法恢复。

先保存正在编辑的内容，再刷新页面或重新打开真迹。桌面壳继续使用 **0.1.9**，无需重装；本次没有重打、上传或改名安装器。

首次安装继续使用 [Windows x64 安装器 0.1.9](https://github.com/hechucaixuanzhi/zhenji-desktop-releases/releases/download/v0.1.9/Zhenji-0.1.9-x64-Setup.exe)，SHA256：

`92c44080863c42e724af9928adc1e04c61265e15eb15d7bcfee5d08bf16a3cde`

本次私信定向验证已完成，双 API 与 Web 已部署，部署后 301.3 秒、20 次观察通过。本次无数据库迁移，原 127 条迁移记录保留；验证与部署没有发起真实模型、Search 或 Fetch 请求，新增费用为 0。

源码：[ba6ac32b](https://github.com/hechucaixuanzhi/zhenji/commit/ba6ac32b6f1eb026ee8eda577dd917c4effdffb9)；源码树：`2a8dc4be5f94760ec18a6de02df1d3ae70590549`。

包号：TEXT-DM-01。
