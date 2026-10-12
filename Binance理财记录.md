# Binance 理财记录

_最近更新：2026-10-12 15:23:18 CST_

## 每日汇总

| 日期 | 金额 | 利率 | 实际利率 | 预期收益 | 实际收益 | To RMB | 利息 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-12 | 300.254224162473 | 1.05% | 0.00% | 0.05801872424336298 | 0 | 2011.7945791727145 | 0 |

## 当前持仓

| 采集时间 | 账户类型 | 币种 | 产品ID | 持仓数量 | 实时年化利率 | 预估每日利息 | 阶梯年化利率（分档） | 阶梯预估每日利息 | 合计预估每日利息 | 昨日奖励(接口值) | 累计奖励(接口值) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-12 15:23:18 CST | 活期 | U | U001 | 300.16417491 | 1.05% | 0.00865926769662008 | 0-8000U: 6.00% | 0.04934205614958904 | 0.05800132384620912 | 0 | 0.56653943 |

## 每日持仓历史

| 日期 | 采集时间 | 账户类型 | 币种 | 产品ID | 持仓数量 | 实时年化利率 | 预估每日利息 | 阶梯年化利率（分档） | 阶梯预估每日利息 | 合计预估每日利息 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-12 | 2026-10-12 15:23:18 CST | 活期 | U | U001 | 300.16417491 | 1.05% | 0.00865926769662008 | 0-8000U: 6.00% | 0.04934205614958904 | 0.05800132384620912 |

## 实际利息记录

| 奖励时间 | 记录采集时间 | 账户类型 | 币种 | 产品ID | 奖励类型 | 实际奖励数量 | 记录状态 | 去重键 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-10-10 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDT | USDT001 | REALTIME | 0.00000001 |  | 7b911d4aaad3eb8d0709f371d8ef5e8c474cdb9ccdb59dfd8e2f11df3b1d1a3a |
| 2026-10-08 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDC | USDC001 | REALTIME | 0.00001957 |  | 9cc5e61b7a08661c2458ef0ec8705b9977abce8ac02a74e4d7ea131c1e1b5c4d |
| 2026-10-08 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDT | USDT001 | REALTIME | 0.00209893 |  | aacf6d525e0dd93f9152a521a9c9daf55afe43ac13ce4b6b2eebb8d321a0960c |
| 2026-10-07 11:39:04 | 2026-10-12 15:17:25 CST | 活期 | USDT | USDT001 | BONUS | 0.01372374 |  | 7d0bd0bca374f52f62abf2e05f4831e1bf9be435111263d700d9f4b66b310326 |
| 2026-10-07 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDT | USDT001 | REALTIME | 0.00966997 |  | 04eb2eb8b4199d50ce407f2b22d7861a432181bef0b3ed4cc3d40d3b8992d82c |
| 2026-10-06 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | ONG | ONG001 | REALTIME | 0.00000734 |  | ccd4328316871ce6f6173fd7b0b25ef20a6d4260a6762d8fee275dffb6db500d |
| 2026-10-06 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDC | USDC001 | REALTIME | 0.00162274 |  | ac9404a8e4ded8c8c709d07c0814dd2e8eaf29123a162df0a868613d5327a4f0 |
| 2026-10-06 07:59:59 | 2026-10-12 15:17:25 CST | 活期 | USDT | USDT001 | REALTIME | 0.00768764 |  | 9fd2fec6223735084db33d6c1c803cf4d9cbab76992c8ccfb3055cd9d593d198 |

## 运行日志

| 时间 | 级别 | 内容 |
| --- | --- | --- |
| 2026-10-12 15:11:49 CST | ERROR | 同步失败：网络请求失败：HTTPSConnectionPool(host='api.binance.com', port=443): Max retries exceeded with url: /sapi/v1/simple-earn/flexible/position?current=1&size=100&recvWindow=10000&timestamp=1791789109890&signature=6909aa8c0fa18391668d23c09db3595256866b2789b364fc06aa44a8035c4ae8 (Caused by NewConnectionError("HTTPSConnection(host='api.binance.com', port=443): Failed to establish a new connection: [Errno 101] Network is unreachable")) |
| 2026-10-12 15:16:17 CST | ERROR | 同步失败：网络请求失败：HTTPSConnectionPool(host='api.binance.com', port=443): Max retries exceeded with url: /sapi/v1/simple-earn/flexible/position?current=1&size=100&recvWindow=10000&timestamp=1791789377626&signature=65c72856bab5d81111623b1f9a5cb556b536dc78c43ad5cc7eacbdff011dc9f5 (Caused by NewConnectionError("HTTPSConnection(host='api.binance.com', port=443): Failed to establish a new connection: [Errno 101] Network is unreachable")) |
| 2026-10-12 15:17:25 CST | INFO | 同步成功：当前持仓 1 条；新增活期奖励 8 条；新增定期奖励 0 条。奖励接口回查最近 7 天并按去重键去重。每日汇总金额=300.25418807 USDT，昨日实际奖励=0.00000000 USDT；USDT/CNY=6.700304（API 实时获取，数据更新时间：Mon, 12 Oct 2026 00:02:32 +0000）。 |
| 2026-10-12 15:21:10 CST | INFO | 同步成功：当前持仓 1 条；新增活期奖励 0 条；新增定期奖励 0 条。奖励接口回查最近 7 天并按去重键去重。每日汇总金额=300.25420612 USDT，昨日实际奖励=0.00000000 USDT；USDT/CNY=6.700304（API 实时获取，数据更新时间：Mon, 12 Oct 2026 00:02:32 +0000）。 |
| 2026-10-12 15:23:18 CST | INFO | 同步成功：当前持仓 1 条；新增活期奖励 0 条；新增定期奖励 0 条。奖励接口回查最近 7 天并按去重键去重。每日汇总金额=300.25422416 USDT，昨日实际奖励=0.00000000 USDT；USDT/CNY=6.700304（API 实时获取，数据更新时间：Mon, 12 Oct 2026 00:02:32 +0000）。 |
