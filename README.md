# kinwsm

我在探索一种可追踪的项目协作方式：ChatGPT 读取共享资料并讨论方案，Codex 在本地执行与验证，双方通过 Git 交接结果。

## 项目

### [Git Project Handoff Skill](https://github.com/kinwsm/git-project-handoff-skill)

用项目仓库的 `HANDOFF.md` 把讨论确定的任务交给本地 Codex；请求带版本和唯一 ID，执行结果带回执和验证证据。

[看工作流程、使用示例与安装方式](https://github.com/kinwsm/git-project-handoff-skill#readme) · [查看 skill 指令](https://github.com/kinwsm/git-project-handoff-skill/blob/main/SKILL.md)

当前 [v2.0.1 可复现工作流](https://github.com/kinwsm/git-project-handoff-skill/releases/tag/v2.0.1)已按 MIT 开源，包含可安装的 skill、本地监听器、两端指令与配置模板，以及逐步验收说明。Windows/Linux 离线测试和 Windows 真实 Codex 执行验证已通过。使用者仍需连接自己的 GitHub 与 ChatGPT 账号，并为每个项目配置共享范围。原始说明版保留为 [V1](https://github.com/kinwsm/git-project-handoff-skill/releases/tag/v1)。
