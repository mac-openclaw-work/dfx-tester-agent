# Session: 2026-04-30 09:02:51 GMT+8

- **Session Key**: agent:dfx-tester:main
- **Session ID**: 01d709a5-d43f-46ab-bfef-d9a7327b68ec
- **Source**: webchat

## Conversation Summary

user: [Thu 2026-04-30 08:02 GMT+8] 未经我确认，严禁重启网关，写到你的安全手册里面
assistant: 已创建 `SAFETY.md`，把这条铁律写进去了：

**🚫 严禁未经用户明确同意重启网关**

同时把另外几条高风险操作（透露密钥、安装 Skill、执行破坏性命令）也一起写进去了，分类明确，判断原则清晰。

这个文件优先级高于 AGENTS.md 中的同名规则——也就是说，即使 AGENTS.md 里写了什么，只要和 SAFETY.md 冲突，以 SAFETY.md 为准。
user: [Thu 2026-04-30 08:18 GMT+8] 列出你的skill
assistant: 我的 Skills（按状态分类）：

---

### ✅ 可用（已就绪）

| Skill | 用途 |
|---|---|
| **self-improving** | 自我反思 + 自我批评 + 持续学习 |
| **minimax-token-plan** | 查询 MiniMax Token Plan 订阅余额 |
| **skill-finder-cn** | 搜索和安装 ClawHub Skills |
| **skill-vetter** | 安装 Skill 前的安全审查 |
| **summarize / summarize-pro** | 总结文章、文档、视频、URL、PDF 等 |
| **multi-search-engine** | 多引擎搜索（8 个中文 + 9 个国际） |
| **agent-reach** | 互联网浏览 + 17 个平台操作（社交媒体等） |
| **github / gh-issues** | GitHub 操作 |
| **clawhub** | ClawHub 技能市场 |
| **browser-automation** | 浏览器自动化 |
| **feishu-doc/drive/wiki/perm** | 飞书文档、云盘、知识库、权限 |
| **mcporter** | MCP 服务器/工具管理 |
| **healthcheck** | 主机安全审计 |
| **taskflow / taskflow-inbox-triage** | 多步骤任务编排 |
| **tavily** | Tavily 网页搜索 |
| **weather** | 天气查询 |
| **video-frames** | 视频帧提取 |
| **session-logs** | 历史会话日志搜索 |
| **skill-creator** | 创建新 Skill 指南 |

### ⏸ 已停用
iMessage、Apple Notes、Bear、Obsidian、Gemini、Gmail、Slack、Spotify 等。

### △ 需配置
imap-smtp-email、QQBot 系列、Sherpa TTS、Hue 灯光、Things 3 等。

---

其中 **workspace 专属**的 5 个是：
`self-improving` · `minimax-token-plan` · `skill-finder-cn` · `skill-vetter` · `skill-creator`
