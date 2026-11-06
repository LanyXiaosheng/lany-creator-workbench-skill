# 总入口使用说明

> 发布状态：本地提供全部十二项专项；其中价值定位、AI工作流、行动复盘、社群设计四个远程仓库暂因GitHub内容创建限流待建立。其余链接可用。

不知道该用哪个专项技能时从这里开始；已明确要脚本、卡片等产物时可直接调用对应技能。

## 需要提供

当前目标、已有材料、卡点和时间等限制。不必先填长问卷。缺少资料的结论只能作为假设；信息够用时直接工作。

## 示例（虚构）

```text
$lany-creator-workbench-skill
我有30条AI工具使用笔记，想做面向独立设计师的内容。
目前没有客户数据，每周可用3小时。
请确定本周该产出什么，并完成第一份产物。
```

合理起点可能是整理一个可验证的用户问题，或从已经提供的笔记建立洞见卡。不能据此断言设计师一定愿意购买服务。

## 会得到什么

定位草案、洞见卡、口播稿、下轮实验、AI 工作流或社群机制等当前任务的具体产物，以及简短的选路理由。需要多个环节时保留输入输出，不机械地运行全部十二个专项技能。

## 扩展的工作流

新增 AI 工作流、行动复盘、社群设计三条入口，并为原九项技能补充本地方法笔记。总入口可独立选路；只有用到的专项才会被读取。

```text
$lany-creator-workbench-skill
每周整理客户资料要重复四小时，步骤经常漏。我已有一份手工完成的样例。
请帮我设计一个可验收的 AI 协作流程，先做方案，不安装软件或修改账户。
```

此例应选择 AI 工作流，读取样例并交付人机分工、完成标准及验证办法；不转去做内容定位或要求建立知识库。

## 明确任务时直接调用

```text
$lany-short-video-script-skill 把下面真实经历改成60秒口播，保留事实，不增加成绩或收入数字。
```

完整选择表见[SKILL.md](SKILL.md)。本入口不替代平台实时规则查询，不自动发布、联系他人，也不承诺涨粉收益。[方法笔记](references/methods.md)解释选路与串联边界。

## 独立仓库与安装

仓库：[lany-creator-workbench-skill](https://github.com/LanyXiaosheng/lany-creator-workbench-skill)。本仓库根目录即技能目录，包含 `SKILL.md`、本说明及 `references/`。

确认目标目录不存在后，可在未设置 `CODEX_HOME` 的默认环境下安装：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/LanyXiaosheng/lany-creator-workbench-skill.git ~/.codex/skills/lany-creator-workbench-skill
```

已设置 `CODEX_HOME` 时，将目标改为该目录下的 `skills/lany-creator-workbench-skill`。已有同名技能时先比较或备份，不覆盖。客户端发现技能后，使用 `$lany-creator-workbench-skill` 调用。

总入口需要读取专项技能后才能完整执行。可单独安装需要的专项技能，并与本目录保持同级；专项技能列表及公开仓库链接见 [SKILL.md](SKILL.md)。它不会因安装本入口而自动安装其他技能。

当前版本附自包含方法笔记，无需访问外部原文；现有仓库提交历史保留。

## 专项技能依赖

本仓库只含总入口，不自动安装其余十二项。按需安装所用专项；全部安装时保持下列目录与总入口同级。

| 独立仓库 | 本地入口 |
|---|---|
| lany-action-review-skill（远程待创建；本地 `../lany-action-review-skill/SKILL.md`） | `../lany-action-review-skill/SKILL.md` |
| lany-ai-workflow-skill（远程待创建；本地 `../lany-ai-workflow-skill/SKILL.md`） | `../lany-ai-workflow-skill/SKILL.md` |
| lany-community-design-skill（远程待创建；本地 `../lany-community-design-skill/SKILL.md`） | `../lany-community-design-skill/SKILL.md` |
| [lany-content-experiment-skill](https://github.com/LanyXiaosheng/lany-content-experiment-skill) | `../lany-content-experiment-skill/SKILL.md` |
| [lany-content-remix-skill](https://github.com/LanyXiaosheng/lany-content-remix-skill) | `../lany-content-remix-skill/SKILL.md` |
| [lany-insight-card-skill](https://github.com/LanyXiaosheng/lany-insight-card-skill) | `../lany-insight-card-skill/SKILL.md` |
| [lany-knowledge-workflow-skill](https://github.com/LanyXiaosheng/lany-knowledge-workflow-skill) | `../lany-knowledge-workflow-skill/SKILL.md` |
| [lany-project-learning-skill](https://github.com/LanyXiaosheng/lany-project-learning-skill) | `../lany-project-learning-skill/SKILL.md` |
| [lany-short-video-script-skill](https://github.com/LanyXiaosheng/lany-short-video-script-skill) | `../lany-short-video-script-skill/SKILL.md` |
| [lany-small-bet-business-skill](https://github.com/LanyXiaosheng/lany-small-bet-business-skill) | `../lany-small-bet-business-skill/SKILL.md` |
| [lany-trust-relationship-skill](https://github.com/LanyXiaosheng/lany-trust-relationship-skill) | `../lany-trust-relationship-skill/SKILL.md` |
| lany-value-positioning-skill（远程待创建；本地 `../lany-value-positioning-skill/SKILL.md`） | `../lany-value-positioning-skill/SKILL.md` |

## 操作手册

[本地操作手册](references/workbook.md)包含可填写模板、完整虚构案例、反例与验收步骤，可与方法笔记配合使用，无需访问原文网站。
