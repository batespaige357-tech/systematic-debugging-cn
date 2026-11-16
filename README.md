# Systematic Debugging CN

**先找根因，再改代码。**

基于 [obra/superpowers 的 systematic-debugging](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) 的小幅中文适配。独立社区版本，非官方。

## 保留上游核心

根因调查、模式对照、单一假设与最小验证、实施修复四阶段；保留错误信号、停止条件、根因追踪、防御性验证、条件等待与辅助文件。没有把原流程重写成另一套方法。

## 补充的内容

- 用中文区分现象、证据、假设与验证，原始报错与命令保持原文。
- 面对“没反应、偶尔失败”等模糊描述，先查已有证据，再询问缺少的复现信息。
- 没有安装配套 Superpowers 技能时，提供最小复现和实际验证的本地回退方式。
- 明确诊断日志脱敏、可执行辅助脚本的范围与前端编译边界。

## 安装与调用

```bash
npx skills add batespaige357-tech/systematic-debugging-cn --skill systematic-debugging-cn
```

对助手说“用 systematic-debugging-cn 排查这个问题”；Codex 可输入 `$systematic-debugging-cn`。也可把 `skills/systematic-debugging-cn` 整个目录复制到助手的技能目录。保留完整目录，支持材料与入口一起使用。

附带的 Bash/TypeScript 文件为上游技术辅助材料，不会因安装自动运行；使用需要相应环境和隔离工作区。项目不附效果截图或演示网页。

## 来源、许可与检查

MIT，保留 Jesse Vincent 的版权和完整许可。版本、具体改动及检查范围见 [CHANGES.md](CHANGES.md)。静态文件检查不证明真实排错效果；本版没有行为盲测，也不复用上游案例成绩为自身成绩。
