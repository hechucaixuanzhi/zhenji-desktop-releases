# 真迹 v0.2.6 Windows Desktop Beta 更新说明

真迹预览版 v0.2.6：评论原文与回复输入修复。

- 本人作品页和公开作品页的评论、回复保留本次提交的多行原文、缩进、空白与字符，Markdown/HTML标记按文字显示。
- 发送评论或回复后继续输入新内容，迟到的成功回执会保留后写输入；切换回复对象后，旧回执不会关闭新的回复输入框。
- 刷新后可重新读回已保存的评论与回复原文。

本轮界面更新限以上评论切片。材料格式的后台接口不代表相关新界面已开放；其余尚未签收的界面继续按现有状态使用。**Task新发起和真实联网继续关闭。** 既有任务、来源和执行/费用待核记录保留，不因刷新自动重发。

请先保存正在编辑的内容，再刷新页面或正常重开现有 **0.1.9** 真迹客户端；无需重新安装。本次仅更新Web/API，没有重建、改名或上传安装器。

首次安装继续使用 [Windows x64安装器0.1.9](https://github.com/hechucaixuanzhi/zhenji-desktop-releases/releases/download/v0.1.9/Zhenji-0.1.9-x64-Setup.exe)，SHA256：

92c44080863c42e724af9928adc1e04c61265e15eb15d7bcfee5d08bf16a3cde

双 API 与 Web 已按本次准确源码部署，部署后 301.3 秒、20 次只读观察通过。本次没有 SQL 迁移，原 129 条迁移账据保持不变；C06 保持原开放，Task 新发起、真实联网及 Task 新入口仍关闭。

评论切片已完成真实已安装0.1.9客户端的10项自动化检查与6次Comment HTTP/PG核验；本轮物理中文输入法和系统剪贴板均为NOT_RUN。真实模型/Search/Fetch调用与本次新增费用为0；历史FAIL、UNKNOWN及未确认费用事实保留。

源码：[19de72fd](https://github.com/hechucaixuanzhi/zhenji/commit/19de72fd351436b6ecc10360bcc52e83dc2e7b20)；源码树：ac48f7e80f6740aaddac2ffc0f03fd5a9c9c3c82。

包号：INTEGRATION-04。材料格式后台接口及物理发送前的期限守卫随准确候选交付；未将未签收界面、Task或真实联网记为开放。
