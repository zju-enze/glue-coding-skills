# glue-coding-skills

胶水开发技能集，灵感来源：https://github.com/tukuaiai/vibe-coding-cn.git

用于codex/claude的胶水编程skills，ai不自研新组件，而是优先复用社区已有成熟项目并做粘合拼接

## 包含技能

### glue-development-constraints
胶水开发约束 - 核心原则是把依赖库视为权威、完整、不可修改的黑箱实现，当前项目只承担业务流程编排、模块组合调度、参数配置等胶水职责。

### glue-prototype-replacement
基于原型重构检索采用成熟函数、组件、模块、方法实现 - 审查原型代码，识别可由成熟社区能力替代的部分，形成明确、可执行、可审计、可退役的迁移方案。

## 使用方式

在 Claude Code 中使用 Skill 工具调用：
- `glue-development-constraints` - 胶水开发约束检查
- `glue-prototype-replacement` - 原型重构检索
