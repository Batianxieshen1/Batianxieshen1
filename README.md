# 蓝纸 · BLUE PAPER

> 一个人的造物与札记。**机器负责生成，人负责判断。**

🏠 **个人站**：[batianxieshen1.github.io/blog](https://batianxieshen1.github.io/blog/) —— 那里陈列作品，也收留它们背后的思考，按「一封公开的信」的方式排版。

## 造物

| 项目 | 一句话 | 链接 |
| --- | --- | --- |
| **OpenJob** | 本地优先的 AI 求职工作台：岗位采集 → AI 五维评分 → JD 定向简历 → 人工确认投递。是否投递永远由人按下放行键。 | [GitHub](https://github.com/Batianxieshen1/OpenJob) |
| **电商用户增长分析框架** | 配置驱动的通用分析引擎：换数据集不改一行代码，Olist 9.8 万笔订单验证，看板在线可玩。 | [GitHub](https://github.com/Batianxieshen1/ecommerce-growth-analysis) · [线上看板](https://batianxieshen1.github.io/ecommerce-growth-analysis/) |
| **Focus Room** | 沉浸式专注 Web 应用：番茄钟、自然场景视频背景、声音混音、学习热力图。 | [GitHub](https://github.com/Batianxieshen1/focus-room) · [线上体验](https://batianxieshen1.github.io/focus-room/) |
| **朝夕 · 订阅每日成本** | 把每一笔年费细算到每一天，到期逐日提醒。 | [GitHub](https://github.com/Batianxieshen1/zhaxi-sub) · [线上体验](https://batianxieshen1.github.io/zhaxi-sub/) |

## 开源

每个 PR 都先在本机复现、跑通测试、再提交——不交没验证过的改动。

| 项目 | 星标 | 已合并 | 做了什么 |
| --- | --- | --- | --- |
| **[deer-flow](https://github.com/bytedance/deer-flow)** · 字节跳动 | 84k★ | [1](https://github.com/bytedance/deer-flow/pull/7243) | 修复 main 分支 CI 红灯：cargo 冷编译超时预算不足 |
| **[etcd](https://github.com/etcd-io/etcd)** · CNCF | 52k★ | [4](https://github.com/etcd-io/etcd/pull/22629) | Go 工具链安全升级（CVE 修复），覆盖 main + release-3.7/3.6/3.5 四个分支 |
| **[FunASR](https://github.com/modelscope/FunASR)** · 阿里达摩院 | 21k★ | [2](https://github.com/modelscope/FunASR/pull/3784) | 修复 WER 指标的 NumPy int16 溢出（32768 token 时崩溃），含 12 个回归测试 |
| **[raft](https://github.com/etcd-io/raft)** · etcd-io | 3.5k★ | [3](https://github.com/etcd-io/raft/pull/537) | 同 issue 的 Go 版本升级，main + release-3.6/3.7 |
| **[auger](https://github.com/etcd-io/auger)** 等 4 个 etcd 子项目 | — | [4](https://github.com/etcd-io/auger/pull/538) | auger / etcd-operator / gofail / protodoc 的同类升级 |

另有 4 个 PR 在 bbolt 中等待合并（CI 全绿、已获双 APPROVED），2 个在 OpenViking 和 OpenCodeReview 中等待审查。

## 札记

把踩过的坑，写成后来人的路标 —— [蓝纸 · 札记](https://batianxieshen1.github.io/blog/posts/three-levels.html)：

- 大模型应用的三个层次：工具 → 工作流 → 决策
- OpenJob 复盘：把求职串成一条可审阅的流水线
- 配置驱动思维：换数据集不用改代码的数据分析框架

## 现在

- 在找 **AI 产品运营 / AI 应用产品**方向的实习
- 在写「蓝纸」；此刻的完整清单见 [now 页](https://batianxieshen1.github.io/blog/now/)
- 在给高星开源项目提 PR：etcd、deer-flow、FunASR、raft 等已合并 **13 个**，另有 6 个在审

---

*联系：邮箱 13676097998@163.com · 更多见个人站「信箱」区。*
