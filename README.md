# folder-caretaker

**folder-caretaker 是一个给 Agent 用的文件夹治理 skill**：在文件夹根目录生成 `00_使用规则.md` 作为放置协议做持续治理，或把乱文件夹按不超过两层分类整理完。适用于 AI 产出物文件夹、代码库、知识库、素材库、会话导出等任何文件夹形态。

## 怎么装

```
git clone https://github.com/TEXXXXTURE/folder-caretaker.git
```

把本仓 `SKILL.md` 与 `templates/` 一起放进你的 agent skills 目录（skill 运行时要读 `templates/folder-rules-template.md`）。

## 协议全文

三功能（持续治理 / 一次性梳理 / 上云同步）的触发语义、整理方法论、8 条验收标准、类型适配与禁区默认值，全部以 [SKILL.md](SKILL.md) 为唯一事实源，见该文件。

## 许可证

MIT