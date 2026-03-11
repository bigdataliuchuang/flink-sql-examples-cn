# Launch Posts

这个文档提供一组可以直接复制后稍作修改就发布的首发文案，覆盖 GitHub、掘金、CSDN 和朋友圈/社群短文案。

如果你要发长文，直接参考 [first-article.md](./first-article.md)。

## GitHub About

### Description

`Chinese-first practical Flink SQL examples for streaming metrics, dedup, TopN, and interval join.`

### Topics

`flink`, `flink-sql`, `sql`, `streaming`, `big-data`, `chinese`, `kafka`, `realtime`

## GitHub 仓库首发短文案

可以发在仓库置顶 Issue、Discussion，或者同步发到 X / 即刻 / 社群。

```text
开了一个新的开源仓库：flink-sql-examples-cn

这是一个中文优先的 Flink SQL 实战案例库，不是单纯堆语法，而是尽量用最小可运行案例覆盖真实业务中高频场景。

当前已包含：
- 窗口 GMV
- 分钟级 UV
- 最新记录去重
- 下单转支付转化率
- 城市 GMV TopN
- 订单流与支付流 Interval Join

适合人群：
- 想从离线数仓转实时计算
- 想准备 Flink SQL / 实时数仓面试
- 想找一套能快速演示给团队看的最小案例

仓库地址：
https://github.com/bigdataliuchuang/flink-sql-examples-cn
```

## 掘金首发文案

### 标题建议

- `我开源了一个中文 Flink SQL 实战案例库，专门补“会语法但不会做业务”的空白`
- `开源一个 Flink SQL 中文案例仓库：窗口指标、去重、TopN、双流 Join`
- `做了一个 Flink SQL 实战仓库，适合实时数仓学习和面试准备`

### 正文模板

```markdown
# 我开源了一个中文 Flink SQL 实战案例库

最近把自己平时整理的一些 Flink SQL 案例收了一下，单独开了一个仓库：

项目地址：
https://github.com/bigdataliuchuang/flink-sql-examples-cn

这个仓库的定位不是“语法大全”，而是尽量用小而清晰的样例覆盖真实业务里高频出现的场景。

很多 Flink SQL 资料的问题是：

- 语法片段很多，但完整可跑的案例很少
- 只讲概念，不讲业务指标口径
- 英文资料不少，但中文实战案例不够集中

所以这个仓库现在重点做三件事：

1. 给出最小可运行案例
2. 覆盖高频业务场景
3. 保持中文优先、适合快速查阅

当前已经整理的内容包括：

- 基础建表：事件时间、水位线、文件源、Kafka Source
- 窗口指标：GMV、订单数、支付用户数、分钟级 UV
- 去重：保留每个用户最新一笔订单
- 业务指标：下单转支付转化率
- 维表关联：城市 GMV TopN
- 双流 Join：订单流与支付流的 Interval Join

这个仓库比较适合：

- 想从离线数仓转实时计算的同学
- 想准备 Flink SQL / 实时数仓面试的人
- 想给团队做内部分享，找一套最小案例的人

我后面会继续补这些方向：

- CDC 场景
- 维表 Join / Lookup Join
- TopN 与热门指标
- 迟到数据说明
- Doris / Paimon 下游落地模板

如果你也在学 Flink SQL，或者手里有比较典型的业务场景，欢迎提 Issue 或 PR。
也欢迎直接 star，后面我会持续更新。
```

## CSDN 首发文案

### 标题建议

- `开源一个 Flink SQL 中文实战案例仓库，含窗口指标、去重、TopN、双流 Join`
- `Flink SQL 学习资料不够落地？我整理了一个中文案例仓库`
- `适合实时数仓学习和面试：一个可直接运行的 Flink SQL 案例仓库`

### 正文模板

```markdown
最近把一些 Flink SQL 练习和业务型案例整理成了一个开源仓库：

仓库地址：
https://github.com/bigdataliuchuang/flink-sql-examples-cn

这个仓库主要想解决一个问题：
很多人会 Flink SQL 基础语法，但一到真实业务场景，比如窗口指标、去重、TopN、订单支付双流 Join，就不知道怎么写。

所以我没有把它做成语法笔记，而是做成了一个“中文优先的实战案例库”。

当前内容包括：

- 基础源表定义
- 事件时间和水位线
- Kafka / 文件源示例
- 分钟级 GMV 统计
- 分钟级 UV 统计
- 保留每个用户最新一笔订单
- 下单转支付转化率
- 城市 GMV TopN
- 订单流与支付流 Interval Join

这个仓库适合：

- 大数据开发工程师
- 实时数仓方向学习者
- 准备 Flink SQL 面试的同学
- 想做内部培训分享的团队

后续我会继续补充 CDC、维表 Join、迟到数据和 Doris/Paimon 下游落地案例。

如果你觉得这个方向有用，欢迎 star。
如果你有想看的典型场景，也欢迎提 Issue。
```

## 社群 / 朋友圈短文案

### 版本 1

```text
开了个新仓库：flink-sql-examples-cn
主要整理 Flink SQL 的中文实战案例，不是堆语法，重点放在窗口指标、去重、TopN、双流 Join 这些高频业务场景。
如果你也在学实时数仓或准备相关面试，可以看下：
https://github.com/bigdataliuchuang/flink-sql-examples-cn
```

### 版本 2

```text
最近整理了一个 Flink SQL 中文案例库，已经开源。
适合想从“会语法”走到“会写业务 SQL”的同学，里面先放了 GMV、UV、转化率、TopN、订单支付 Join 等案例。
仓库地址：
https://github.com/bigdataliuchuang/flink-sql-examples-cn
```
