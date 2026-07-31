# Live Event Deal Decision System / 演出机会商业决策系统

A self-contained decision-support product for evaluating live-event opportunities, modelling multi-city tour P&L, comparing artist OFFER structures, and producing approval or negotiation materials.

面向演出主办方的单文件商业决策系统：将艺人及城市评估、上座率假设、票房、巡演成本与演出 OFFER 放入同一套可解释模型，辅助机会判断、预算制定和报价决策。

> **Current demo:** v3.8.278  
> **Status:** Actively iterating. The public build uses fictional, non-confidential sample data.
>
> **当前Demo：** v3.8.278  
> **状态：** 持续迭代中；公开版本仅使用虚构及脱敏示例数据。

## Try it live / 在线体验

[Open the latest web demo / 打开最新在线Demo](https://blanca-vibing.github.io/quick-pnl-simulator/)

The product is delivered as one self-contained `index.html` file. It requires no installation or server, and all calculations run locally in the browser.

系统为独立的 `index.html` 文件，无需安装或服务器；计算在浏览器本地完成。

## The decision it supports / 支持的核心决策

> Is this artist opportunity worth advancing, and what budget and OFFER structure should the promoter use?
>
> 这个艺人机会是否值得推进，以及主办方应该采用怎样的预算和演出 OFFER？

## Core workflow / 核心流程

1. Define the tour, artist, party, ticket tiers, and routing.
2. Evaluate artist-level and city-level ticket potential.
3. Convert assessment inputs into explainable occupancy assumptions.
4. Model gross/net box office, operating costs, taxes, and travel.
5. Compare guarantee, guarantee-plus-backend, and related OFFER scenarios.
6. Review profit, margin, ROI, sensitivity, and break-even results.
7. Produce internal approval and external Deal Memo materials.

中文流程：

1. 填写巡演、艺人、团队、票档与路线；
2. 完成艺人层及城市层票房潜力评估；
3. 将评分转化为可解释的上座率假设；
4. 测算总票房、净票房、运营成本、税费与差旅；
5. 比较纯保底、保底加分成等演出 OFFER；
6. 查看利润、利润率、ROI、敏感性和盈亏平衡；
7. 生成内部审批与对外 Deal Memo 材料。

## Product principles / 产品原则

- **Explainable over black-box:** recommendations show their inputs and logic.
- **Human judgment remains in control:** users can override assumptions with reasons.
- **One source of truth:** the same project data drives P&L, OFFER, summaries, and Memo.
- **Scenario comparison:** uncertainty is expressed through ranges and sensitivity, not false precision.
- **Local-first demo:** projects can be saved and loaded as JSON without a backend.

产品强调可解释计算、人工最终判断、跨模块单一数据源、情景比较和本地保存。

## Languages and currencies / 语言与币种

- 中文 / English / Español
- CNY / USD / EUR display switching

## Repository contents / 仓库内容

- `index.html` — latest public product demo / 最新公开Demo
- `portfolio.html` — earlier portfolio page; a new decision-product case narrative is being prepared
- `CHANGELOG.md` — selected iteration history / 主要版本记录
- `LICENSE.md` — repository license

## Scope and roadmap / 当前边界与路线

The current release focuses on the **assessment → budget → OFFER decision** chain for Livehouse-scale touring. Opportunity intake, reusable artist assessment records, explicit Go / No-Go decision logs, real multi-user collaboration, and post-show calibration are roadmap items rather than completed platform capabilities.

当前版本聚焦Livehouse巡演的“评估—预算—OFFER决策”链路。机会档案、可复用艺人评估、明确的Go / No-Go决策记录、真实多人协作与演出后校准仍属于路线图，不将其包装为已经完成的平台能力。

---

Built by Blanca (刘雪莹) · Product Manager
