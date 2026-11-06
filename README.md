# Academic Writing Expert · 科研英文论文写作专家

A Codex skill for writing and revising scientific manuscripts and journal submission letters. It works from the evidence and author details you provide.

**[查看全部功能、子模块与调用示例](FEATURES.zh-CN.md)**

从研究笔记、图表或已有稿件开始，可以起草英文论文、深度修订、精简、润色和中译英。投稿阶段可以起草给编辑的英文投稿信，按目标期刊核对声明，准备返修说明与逐点回复。每项任务按需读取相关模块。

## 安装

下载最新发布页中的 `academic-writing-expert-v1.1.0.zip`，解压后将包含 `SKILL.md` 的 `academic-writing-expert` 文件夹放入个人技能目录，例如 `~/.agents/skills/`。若环境配置了另一个技能目录，使用该目录。打开新的 Codex 会话即可调用。[下载发布包](https://github.com/shuozhang-shz/academic-writing-expert/releases/latest)

You can also clone the repository into your configured skills directory under the name `academic-writing-expert`. The entry point, reference guides and optional manuscript dossier use Markdown.

## 使用

> $academic-writing-expert 请根据附件稿件和期刊简介起草首次投稿信，说明核心发现对本刊读者的价值，并在信后列出尚待作者确认的声明。

> $academic-writing-expert 请按 CARS 检查英文引言，再对照方法与结果判断引言提出的问题是否都得到了回答。

> Use $academic-writing-expert to shorten the supplied abstract to 180 words. Preserve the comparator, units, conditions and strength of each claim.

## 资料与版本

- 中文功能说明按任务列出输入、输出和对应文件，并提供可直接使用的请求。[功能说明](FEATURES.zh-CN.md)
- 来源映射记录教程页码、既有覆盖和新增的写作判断，便于核对教材与技能之间的对应关系。[来源映射](references/source-map.md)
- 版本记录列出此次公开更新的范围。此次检查涵盖技能格式、内部链接和三项虚构材料的写作试用。[更新记录](CHANGELOG.md)
- 原创技能说明、示例和仓库文档采用 MIT 许可证。第三方教学材料的权利归其权利人所有。[许可证](LICENSE) · [来源说明](NOTICE.md)
