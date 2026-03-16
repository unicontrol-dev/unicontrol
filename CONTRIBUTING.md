# 贡献指南 / Contributing Guidelines
欢迎你参与 Unicontrol 项目的开发与维护！这份指南会告诉你如何高效地为项目做贡献。
Welcome to contribute to the Unicontrol project! This guide will help you make effective contributions.

## 行为准则 / Code of Conduct
- 尊重每一位贡献者，友好沟通，理性讨论技术问题；
- Respect all contributors, communicate friendly and discuss technical issues rationally;
- 聚焦项目核心目标（分布式治理的高可操控性），不提交无关功能；
- Focus on the project's core goal (high controllability of distributed governance), do not submit irrelevant features;
- 所有贡献需遵守 BSD 3-Clause 协议，提交代码即默认同意原作者保留署名权；
- All contributions must comply with the BSD 3-Clause License, and submitting code means agreeing that the original author retains the right of attribution.

## 贡献方式 / Ways to Contribute
### 1. 提交代码（PR） / 1. Submit Code (PR)
1. Fork 本仓库到你的 GitHub 账号； / Fork this repository to your GitHub account;
2. 基于 `main` 分支创建新分支，命名规范：`feature/功能名` 或 `fix/问题编号`； / Create a new branch based on the `main` branch, naming convention: `feature/feature-name` or `fix/issue-number`;
3. 编写代码，确保代码风格统一、注释清晰； / Write code with consistent style and clear comments;
4. 提交前自测，确保功能正常、无语法错误； / Self-test before submission to ensure functions work normally and no syntax errors;
5. 提交 PR 到本仓库的 `main` 分支，PR 描述需清晰说明： / Submit PR to the `main` branch of this repository, with clear PR description including:
   - 新增/修改了什么功能； / New/modified features;
   - 解决了什么问题（如有 Issue 请关联编号）； / Solved problems (link to Issue number if applicable);
   - 核心实现思路（可选）。 / Core implementation ideas (optional).

### 2. 反馈问题（Issue） / 2. Report Issues
1. 提交 Issue 前先搜索已有 Issue，避免重复； / Search existing Issues before submitting to avoid duplicates;
2. Issue 标题格式：`[类型] 问题描述`（类型可选：Bug、Feature、Docs、Question）； / Issue title format: `[Type] Issue Description` (Type: Bug, Feature, Docs, Question);
3. 详细描述问题： / Describe the issue in detail:
   - 复现步骤； / Reproduction steps;
   - 预期结果 vs 实际结果； / Expected result vs Actual result;
   - 环境信息（如 Redis 版本、JDK 版本）； / Environment information (e.g., Redis version, JDK version);
   - 报错日志/截图（如有）。 / Error logs/screenshots (if any).

### 3. 完善文档 / 3. Improve Documentation
- 补充/修正 README.md、使用文档中的错误； / Fix errors in README.md and usage documents;
- 新增使用示例、核心特性说明； / Add usage examples and core feature descriptions;
- 文档需保持中英双语对齐（如有能力）。 / Keep documents aligned in Chinese and English (if possible).

## 代码规范 / Code Standards
- 命名：变量/函数名使用驼峰式，常量全大写+下划线分隔； / Naming: Use camelCase for variables/functions, UPPER_CASE_WITH_UNDERSCORES for constants;
- 注释：核心逻辑必须加注释，对外接口需说明参数/返回值； / Comments: Core logic must have comments, external interfaces need to explain parameters/return values;
- 格式：遵循主流编程语言规范（如 Java 遵循 Alibaba 编码规范，Python 遵循 PEP8）； / Format: Follow mainstream programming language specifications (e.g., Alibaba Java Coding Guidelines for Java, PEP8 for Python).

## 注意事项 / Notes
1. 所有基于本项目核心思想的代码贡献，需在代码注释中保留 Unicontrol 项目溯源； / All code contributions based on the core ideas of this project must retain Unicontrol project traceability in code comments;
2. 禁止提交与本项目核心目标无关的代码（如无关的第三方工具、测试用例）； / Do not submit code unrelated to the project's core goals (e.g., irrelevant third-party tools, test cases);
3. PR 合并后，我们会在文档中注明核心贡献者信息。 / After PR is merged, we will note the core contributors in the documentation.

## 联系我们 / Contact Us
如有协作疑问，可通过 Issue 或项目主页留言沟通。 / For collaboration questions, communicate via Issue or comments on the project homepage.
