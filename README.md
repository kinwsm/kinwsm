# kinwsm

我在探索一种可追踪的项目协作方式：ChatGPT 读取共享资料并讨论方案，Codex 在本地执行与验证，双方通过 Git 交接结果。

## 项目

### [Git Project Handoff Skill](https://github.com/kinwsm/git-project-handoff-skill)

用项目仓库的 `HANDOFF.md` 把讨论确定的任务交给本地 Codex；请求带版本和唯一 ID，执行结果带回执和验证证据。

[看工作流程、使用示例与安装方式](https://github.com/kinwsm/git-project-handoff-skill#readme) · [查看 skill 指令](https://github.com/kinwsm/git-project-handoff-skill/blob/main/SKILL.md)

当前 [v2.1.0 可复现工作流](https://github.com/kinwsm/git-project-handoff-skill/releases/tag/v2.1.0)按 MIT 开源，包含可安装的 skill、本地监听器、两端指令与配置模板。新增聊天端能力验收、按项目选择模型、消耗回执与故障恢复说明。25 项离线测试在 Windows/Linux 四组环境中通过，Windows 隔离编程验收完成了真实代码修改和六项独立测试。使用者仍需连接自己的 GitHub 与 ChatGPT 账号，并完成各自的远端往返验收。原始说明版保留为 [V1](https://github.com/kinwsm/git-project-handoff-skill/releases/tag/v1)。
