# ikeido-style-novel

一个 Codex 技能，指导 AI 写作池井户润式产业/金融群像小说——小主体对抗大制度、硬知识、数字化赌注、章章对峙、规则内翻盘。

## 这是什么

基于《半泽直树》四册与《下町火箭》的 EPUB 全文定量蒸馏 + 机制拆解，提炼出可直接执行的写作规则。不是泛化的"写好对话"，而是具体到对话翻转节奏、章末钩子四型、冲突升级公式、角色九宫格和双模板引擎。

## 安装

```bash
# 克隆到 Codex skills 目录
git clone https://github.com/YOUR_USERNAME/ikeido-style-novel.git "$CODEX_HOME/skills/ikeido-style-novel"
```

## 使用

在 Codex 中触发：

```
用 ikeido-style-novel 帮我写一章银行对峙戏
```

或直接描述任务，Codex 会自动匹配。

## 可选：放入原文全文

skill 的蒸馏规则可以直接使用，不需要原文。但如果你拥有合法的 EPUB 副本，可以自行提取为纯文本放入 `references/source-texts/`，然后按 SKILL.md 中"查原文的方法"一节按需搜索对照。

**注意：** 本仓库不包含任何受版权保护的作品全文。`references/source-texts/` 已加入 `.gitignore`，你放入的原文不会被推送到 GitHub。

## 版权说明

- `SKILL.md` 和 `references/` 下的蒸馏报告均为原创分析，可自由使用和修改
- 不包含池井户润作品的任何原文片段（蒸馏报告中的短引仅作研究证据，每处不超过 20 字）
- 提取原作全文仅供个人学习，禁止分发或商业使用

## License

MIT（仅限本仓库原创内容）
