<p align="center">
  <strong>中文</strong> · <a href="README.en.md">English</a>
</p>

<p align="center">
  <img src="assets/profile-banner.png" width="100%" alt="Lior1969 — Build. Learn. Refine.">
</p>

<p align="center">
  <strong>AI Agents · 安全研究 · 自动化</strong>
</p>

把想法做成能用的工具，把研究沉淀为可复用的代码与文档。

我关注 AI Agent 的工程实践、安全分析与工作流自动化，围绕工具构建、运行验证和研究整理持续迭代。

公开数据入口：**[开源安全策略索引](https://8eeth0ven.github.io/security-md-collect/)** · **[Android APK 与赏金项目目录](https://8eeth0ven.github.io/security-md-collect/赏金APK/赏金APK看板.html)**。支持明亮 / 深色、中英文检索，便于查找项目来源与应用入口。

## 代表项目

| 项目 | 解决什么问题 |
| --- | --- |
| **[security-md-collect](https://github.com/8eeth0ven/security-md-collect)** | 收集公开 SECURITY.md 安全策略与四平台 Android 目标，提供可搜索的[策略看板](https://8eeth0ven.github.io/security-md-collect/)和 [APK 目录](https://8eeth0ven.github.io/security-md-collect/赏金APK/赏金APK看板.html)，区分赏金状态与未验证镜像候选。 |
| **[bfs-clicker](https://github.com/8eeth0ven/bfs-clicker)** | 使用 Playwright 探索 Web 界面，提取 Android / iOS 接口证据，并通过 MCP 接入 AI 客户端。 |
| **[agentskills-bridge](https://github.com/8eeth0ven/agentskills-bridge)** | 将 Agent 技能迁移为目标框架的可执行实现，结合行为验收、原生运行时验证与错误修复。 |
| **[re-skill](https://github.com/8eeth0ven/re-skill)** | 整合逆向工程知识、分析工具与执行流程，为授权研究保留可追溯的证据。 |
| **[Bilingual Paper Studio](https://github.com/8eeth0ven/bilingual-paper-studio)** | 本地双语论文阅读工作台，支持中英逐段对齐、选区 AI 讨论，以及连接 LaTeX 原稿后的编辑与编译。 |
| **[AI for Security Papers](https://github.com/8eeth0ven/AI-for-Security-Paper)** | 整理 AI 安全代码审计相关论文，提供中英文评述、主题索引与基于证据的比较。 |

## 开源贡献

**[AgentProvenance](https://github.com/ByteYellow/AgentProvenance) — 安全修复与加固**  
[PR #34 · 已合并](https://github.com/ByteYellow/AgentProvenance/pull/34)

- **鉴权与请求校验**：默认启用 daemon 鉴权，补充 CSRF 与 Host / Origin 校验。
- **路径与证据处理**：约束文件访问与导出路径，完善敏感信息脱敏及导入验证。
- **兼容性与验证**：补充回归测试、端到端检查与行为变更迁移说明。

## 工作方式

从具体问题出发，用运行结果检验实现；在代码与文档中说明证据、支持范围和已知限制。

欢迎通过项目的 Issues / Pull Requests 交流使用反馈、实现思路与改进建议。
