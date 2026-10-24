# 真迹 v0.2.2 Windows Desktop Beta 更新说明

真迹预览版 v0.2.2，包号 NET-MODEL-UI-01（A01-TOOL-01-NET-R1 / MODEL-01）。

- 模型目录新增13个准确型号，覆盖 DeepSeek V4.1 Flash、MiMo2.6、Qwen3.8、Kimi3.1、GLM5.3、MiniMax M3/M3.1 Flash、LongCat2.5 Preview、豆包2.1。实际可用性取决于现有渠道与账号资格；新增型号不自动扩大Project AUTO已验证范围；Preview明确标记，已下线型号保留历史并提供主动替代入口。不会静默改写已有选择、旧回答或排队任务。
- 开启联网偏好后，普通聊天和写作仍走普通回答。工具偏好与本次执行分开；不支持或暂不可用的明确搜索会保留输入并准确反馈。
- 新建会话首发、等待能力确认期间继续输入、账号/会话/模型切换及迟到回执均补齐保稿。
- 修复旧会话未显式选型时，能力接口与会话列表/实际生成的型号解析不一致；新会话继续继承账号保存的默认。

本次仍未开放真实联网搜索或网页读取。后端同厂Search与正式预算/外发合同已经完成合成联调，实际渠道、账号和收费调用仍待后续验证。本次执行者真实模型/Search调用及新增费用均为0。

本次更新界面和服务，桌面壳继续沿用0.1.9。先保存正在编辑的内容，再刷新或重新打开真迹，无需重装；没有重打、上传或改名安装器。

验证：14项真实Windows安装壳受影响检查、1条兼容reader回退代表，以及Windows/准确Linux镜像的双API默认解析回读。已过且未改的云端型号/联合链证据继续复用，原失败保留；未重跑旧全矩阵。两条新增原字节SQL和准确API/Web制品均绑定当前备份及本次GO，上线后至少300秒观察。人工物理IME仍NOT_RUN，50万字符输入迟滞和历史UNKNOWN保留。

[原包REPORT及证据](https://github.com/hechucaixuanzhi/zhenji/blob/codex/v1-local-controller-20261023/docs/engineering/v1/mainline-e/2026-10-23/A01-TOOL-01/REPORT.md)。

首次安装继续使用 [Windows x64 安装器0.1.9](https://github.com/hechucaixuanzhi/zhenji-desktop-releases/releases/download/v0.1.9/Zhenji-0.1.9-x64-Setup.exe)，SHA256 `92c44080863c42e724af9928adc1e04c61265e15eb15d7bcfee5d08bf16a3cde`。
