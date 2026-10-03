# Academic Writing Expert · 科研英文论文写作专家

A reusable Codex skill for drafting, revising, translating, and polishing scientific manuscripts in English.

面向科研英文论文写作的可复用技能：从研究笔记、数据和图表梳理论证，起草各章节，进行深度修改、中文到英文改写、语言润色和一致性检查。

## What it does / 能力

- Develop a manuscript argument from supplied evidence and keep claims traceable.
- Draft or revise titles, abstracts, introductions, Methods, Results, Discussion, conclusions, and captions.
- Preserve numbers, units, uncertainty, sample identities, citations, and claim strength while polishing.
- Diagnose clause boundaries, punctuation, fragments, dangling modifiers, and variable mappings with scientific examples.
- Distinguish faithful language editing from substantive changes to scientific conclusions.
- Support Chinese-to-English academic rewriting and explain important changes in Chinese when appropriate.

它不会补造实验、统计结果、参考文献、机理证据或作者声明。没有结果时，可以协助构思或起草明确标注的概念稿。

## Install / 安装

Download the `academic-writing-expert-v1.0.0.zip` asset from this repository's Releases page and extract it. Place the resulting `academic-writing-expert` folder in your personal skills directory, for example:

```text
~/.agents/skills/academic-writing-expert/
```

The folder must contain `SKILL.md` directly, alongside `references`, `agents`, and `assets`. Avoid an extra nested folder or duplicate copies in multiple scanned locations. If your Codex environment uses another skill directory, use that configured directory instead. Open a new session if the updated skill is not discovered immediately.

也可以下载仓库内容，将包含 `SKILL.md` 的仓库根目录作为 `academic-writing-expert` 文件夹放入技能目录。技能运行不需要原始 PDF、PPT、Python、付费 API 或其他科研技能。

## Use / 使用

Invoke the skill explicitly with `$academic-writing-expert` and provide the relevant passage, manuscript, notes, or figures.

**保守润色**

> 请使用 $academic-writing-expert 润色以下段落，保持结构、数据和科学含义。若发现证据或逻辑问题，请单独说明，不要悄悄改变结论。

**论文起草**

> 请使用 $academic-writing-expert，根据这些笔记和图表起草英文 Results 和 Discussion。区分观察结果、解释和推测，标出需要作者补充的信息。

**语法检查与讲解**

> 请使用 $academic-writing-expert 检查独立分句、连接词、标点、句子残缺和悬垂修饰，给出修订稿并用中文解释重要修改。

**English example**

> Use $academic-writing-expert to revise this abstract for clarity and concision. Preserve every numerical value, qualifier, comparison, and citation. Explain substantive concerns separately.

## Contents / 文件结构

| File | Purpose |
|---|---|
| [SKILL.md](SKILL.md) | Entry point, task scope, and scientific invariants |
| [Workflow](references/workflow.md) | Drafting, revision levels, translation, and continuing long manuscripts |
| [Argument and evidence](references/argument-and-evidence.md) | Claims, quantitative meaning, and source verification |
| [Manuscript sections](references/manuscript-sections.md) | Section-specific reader questions |
| [Language and style](references/language-and-style.md) | Context-sensitive scientific style |
| [Grammar and punctuation](references/grammar-and-punctuation.md) | Detailed decisions and scientific teaching examples |
| [Review and delivery](references/review-and-delivery.md) | Manuscript checks and deliverable boundaries |
| [Worked examples](references/worked-examples.md) | Fictional examples of editorial decisions |
| [Source map](references/source-map.md) | Tutorial provenance, slide coverage, and adaptations |
| [Manuscript dossier](assets/manuscript-dossier.md) | Optional working record for substantial projects |

References load as needed; routine sentence polishing does not require running a full manuscript audit.

## Sources and design / 来源与设计

The skill combines an original synthesis of William Strunk Jr.'s supplied 2011 revision of *The Elements of Style*, two essays on writing and thinking, and a 46-slide academic-writing presentation. Detailed provenance and distinctions between source advice and added scientific safeguards are recorded in the [source map](references/source-map.md).

Historical prescriptions are interpreted in context. The grammar module distinguishes coordinating `so` from conjunctive adverbs and treats manual word division as a typesetting concern. Source documents and slide images are not distributed in this repository.

“GPT-6-compatible” describes concise instructions, conditional reference loading, and proportional workflows. It does not mean model training, a model switch, access to hidden architecture, or a guarantee of expert judgment. Other capable models may also use the skill.

## Validation and limits / 验证与边界

Before this release, the 11 skill files passed the official skill-format validator and internal-link checks. Nine fictional usage cases were exercised by a separate agent and reviewed for preservation of meaning, including punctuation, modifier attachment, uncertain sample scope, variable mappings, and typesetting advice. These are limited usage checks, not a cross-model benchmark or proof of scientific correctness.

Researchers remain responsible for the underlying evidence, analysis, references, and final manuscript. Fluent prose does not establish a scientific claim or guarantee acceptance. Journal-specific requirements must be checked when relevant.

## License and contributions / 许可与贡献

Original skill instructions, examples, and repository documentation are available under the [MIT License](LICENSE). Third-party source materials are not included or relicensed; see [NOTICE.md](NOTICE.md).

Issues and pull requests are welcome. Describe the writing task, expected behavior, and an anonymized example. Do not submit confidential manuscripts, unpublished data, or credentials.
