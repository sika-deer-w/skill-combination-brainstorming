# skill-combination-brainstorming

在动手做计划或实现之前，把两个或多个已有 skill 重新组合成新方案。它不替代具体 skill，只帮你看见更多组合、边界和最小可行路径。

用户确认下一步之前，只输出概念层结果：不写文件、不跑实现、不调用会改外部系统的 skill。

## 什么时候用

- 想把几个 skill 接成一条流程，但还没定该怎么接
- 要从全部已安装 skill 里找组合，而不是只看当前对话里提到的几个
- 需要先发散几个方向，再选一个进入 plan

已经明确要执行某一个 skill 的标准流程时，不要用这个 skill。

## 两种范围

点名具体 skill 时，必须先读对应的 `SKILL.md`，再谈组合。读不到就标明不确定，不把猜测写进推荐。

要求「从全部 skill 里找」时，先扫常见目录里的 `SKILL.md`，按能力聚类，再做跨类组合。最终 Top 10 里的每个方案至少包含 2 个已读过的 skill。

## 产物

普通模式给 3 到 5 个方向，并推荐 1 个。全局探索先产生不少于 20 个原始方向，再筛成 Top 10。每个方向按价值、可行性、组合度、风险打 1 到 5 分。

输出后停下来，等用户选择：进入 plan、继续发散、补充输入、调用具体 skill，或停止。

## 目录

| 路径 | 内容 |
|---|---|
| `SKILL.md` | 发散、收敛、评分和确认节点 |

## 安装

```bash
git clone https://github.com/sika-deer-w/skill-combination-brainstorming.git \
  ~/.cursor/skills/skill-combination-brainstorming
```
