# 物理实验报告 Skill

从实验讲义、实测数据或已有草稿，生成和检查符合课程要求的中文物理实验报告。

## 功能

- 摘要概括目的、方法、核心结果和结论。
- 简化正文计算，保留可复算的数据与处理方法。
- 三线表、居中公式、右对齐编号及正确上下标。
- 坐标轴物理量与单位、图下编号图注、正文两端对齐及分页检查。
- 核对测量模型、单位、不确定度与数值一致性。
- 在工具支持时制作并渲染检查正式 PDF。

缺少实测数据时明确标注待补，不编造测量或实验结论。

## 安装

将本仓库的 `physics-lab-report` 文件夹复制到 `~/.codex/skills/`，确保其中直接包含 `SKILL.md`。Windows 默认位置为 `%USERPROFILE%\.codex\skills\physics-lab-report`。新会话会发现该技能。

也可让支持 GitHub 安装的技能安装器从本仓库安装子目录 `physics-lab-report`。

## 使用

```text
使用 $physics-lab-report，根据我的实验讲义和真实数据撰写实验报告。缺失信息标记待补，最后生成 PDF。
```

```text
使用 $physics-lab-report，检查这份报告的摘要、计算、三线表、公式、图注与分页，并直接修改。
```

## 文件

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](physics-lab-report/SKILL.md) | 主技能与触发条件 |
| [课程要求](physics-lab-report/references/course-requirements.md) | PPT 页码和要求映射 |
| [质量清单](physics-lab-report/references/quality-checklist.md) | 交付检查 |
| [内容模板](physics-lab-report/assets/report-template.md) | 文字草稿结构 |
| [LaTeX 模板](physics-lab-report/assets/report-template.tex) | XeLaTeX 基础版式与三线表 |
| [界面信息](physics-lab-report/agents/openai.yaml) | Codex 名称与示例提示词 |

## 来源与范围

仅发布重新整理的技能、要求映射和自建模板，不包含原始 PPT、截图、教师联系方式、学生报告或个人实验数据。模板字号、页边距和章节是可修改的默认值，应以当前讲义和用户要求为准。

模板包含待补项，不是完成的实验报告。使用本技能不自动授权公开报告或数据。
