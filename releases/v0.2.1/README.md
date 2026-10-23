# 真迹 v0.2.1 Windows Desktop Beta 更新说明

真迹预览版 v0.2.1，本次包号 A01-A03-UI-R1。

- 同一次生成只保留一处通用生成提示，普通完成不再额外追加“已完成”；异常、停止及 UNKNOWN 反馈保留。
- 等待队列恢复到输入框上方，支持展开/收起和重排；编辑排队消息使用原输入框，取消后恢复原来尚未发送的草稿。
- 联网工具偏好移回“设置 → AI → 工具”，输入框下方不再展示内部接线说明。偏好保留，真实联网尚未开放；模型目录更新不在本次范围。

先保存正在编辑的内容，再刷新或重新打开真迹。桌面壳继续使用 0.1.9，无需重新安装；本次没有上传、改名或重打安装器。

本次仅替换 Web，API、数据库、队列配置和既有作品保持原状。准确源码 1a143bbdd09aba24a43be9682243ca2bb3ae4558，Web BUILD_ID DDu5YTXHoRcAuZt3ryBXl。

验证：云端 12 项定向检查及 4 项最终补验，另有本机 8 项真实 Windows 安装壳差额验收；仅复验此次受影响路径。发布后至少 300 秒服务、HTTP、准确静态资源与双 API 只读回读观察。真实模型调用及新增费用均为 0。人工物理输入法验收仍为 NOT_RUN，50 万字符输入迟滞与历史 FAIL/UNKNOWN 保留。

[包内报告和证据](https://github.com/hechucaixuanzhi/zhenji/blob/codex/v1-local-controller-20261023/docs/engineering/v1/mainline-e/2026-10-23/A03-QUEUE-01/REPORT.md)。
