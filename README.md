# AI Agent Difference

这个仓库用于整理和比较主流 AI 编程工具之间的差别，包括 OpenAI Codex、GitHub Copilot、Cursor、Claude Code、Devin 等。

核心问题不是简单判断“哪个工具最好”，而是分析它们在不同软件工程任务中的定位、优势、限制和适用场景。

## 快速导航

- [AI 工具差别分析](./关于AI工具之间的差别.md)
- [学习日志](./学习日志.md)

## 核心结论

AI 编程工具的差异主要不在于“会不会写代码”，而在于它们是否能理解上下文、执行多步任务、调用工具、验证结果，并融入真实的软件工程流程。

目前比较稳妥的判断是：

- **Copilot** 更像嵌入 IDE 和 GitHub 的实时编程助手。
- **Codex** 更像可以被委派任务的执行型 coding agent。
- **Cursor** 更适合高频交互式开发和局部修复。
- **Claude Code** 更擅长代码库理解、方案讨论和多文件修改。
- **Devin** 更接近自主软件工程师，适合边界清晰、可验收的后台任务。

## 工具定位对比

| 工具 | 定位 | 典型强项 | 更适合的场景 |
| --- | --- | --- | --- |
| OpenAI Codex | 通用型 coding agent | 读写代码、运行命令、处理明确任务 | 修 bug、补测试、中等规模代码修改 |
| GitHub Copilot | IDE/GitHub 内的编程助手 | 补全、解释、局部修改、GitHub 工作流集成 | 日常开发、快速问答、低摩擦辅助 |
| Cursor | AI-first 编辑器 | 代码库交互、局部重构、快速 fix | 边写边改、高频调试、编辑器内开发 |
| Claude Code | 终端/IDE 中的 agentic coding 工具 | 代码库理解、文档、feature 任务 | 先讨论方案再执行多文件修改 |
| Devin | 自主软件工程师型产品 | 端到端任务、后台执行、PR 产出 | 明确 issue、长期任务、可独立验收的工作 |

## 分析框架

比较 AI coding tools 时，可以从以下几个维度看：

1. **任务类型**：修 bug、写 feature、补文档、重构、测试、代码审查。
2. **上下文能力**：能否理解整个代码库，而不是只看当前文件。
3. **执行能力**：能否读写文件、运行命令、跑测试、生成 PR。
4. **验证能力**：能否发现失败、修复失败，并给出可检查的结果。
5. **工作流集成**：是否适合 GitHub、IDE、终端或团队 review 流程。

## 阅读建议

如果你只想快速了解差别，可以先看本 README 的对比表。

如果你想看更完整的论文依据、场景分析和选择建议，可以阅读：

- [关于AI工具之间的差别.md](./关于AI工具之间的差别.md)

如果你想看学习过程中的碎片笔记和后续延伸，可以阅读：

- [学习日志.md](./学习日志.md)

## 参考来源

- [Comparing AI Coding Agents: A Task-Stratified Analysis of Pull Request Acceptance](https://arxiv.org/abs/2602.08915)
- [The Rise of AI Teammates in Software Engineering (SE) 3.0](https://arxiv.org/abs/2507.15003)
- [Code Review Agent Benchmark](https://arxiv.org/abs/2603.23448)
- [SWE Atlas: Benchmarking Coding Agents Beyond Issue Resolution](https://arxiv.org/abs/2605.08366)
- [SWE Context Bench: A Benchmark for Context Learning in Coding](https://arxiv.org/abs/2602.08316)
- [SWE-bench Leaderboards](https://www.swebench.com/)

## License

This project is licensed under the [MIT License](./LICENSE).
