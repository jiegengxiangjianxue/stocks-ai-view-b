# 数据新鲜度审计

- 时间: 2026-11-11 23:38 CST
- 扫描: 42 个文件 | STALE 18 | 无时间戳 1 | 解析失败 0

| 文件 | 档位 | 时间戳 | 年龄(h) | 阈值(h) | 状态 |
|---|---|---|---|---|---|
| ai_pick_v4.json | daily | 2026-10-14T17:59:10 | 677.7 | 30 | **STALE** |
| engine_v5.json | daily | 2026-10-14T17:59:03 | 677.7 | 30 | **STALE** |
| market_phase.json | daily | 2026-10-14T17:58:29 | 677.7 | 30 | **STALE** |
| ban_pick.json | daily | 2026-10-14T18:00:27 | 677.6 | 30 | **STALE** |
| ban_prob.json | daily | 2026-10-14T18:00:15 | 677.6 | 30 | **STALE** |
| decision.json | daily | 2026-10-14T18:00:15 | 677.6 | 30 | **STALE** |
| edge_report.json | weekly | 2026-10-14T18:03:04 | 677.6 | 192 | **STALE** |
| kline_sim.json | weekly | 2026-10-14T18:00:34 | 677.6 | 192 | **STALE** |
| multidim.json | daily | 2026-10-14T18:00:15 | 677.6 | 30 | **STALE** |
| scenario.json | daily | 2026-10-14T18:03:04 | 677.6 | 30 | **STALE** |
| self_reflect.json | daily | 2026-10-14T18:03:04 | 677.6 | 30 | **STALE** |
| news_digest.json | daily | 2026-10-28T21:31:56 | 338.1 | 30 | **STALE** |
| realtime_minute.json | realtime | 2026-10-28T21:29:35 | 338.1 | 0.5 | **STALE** |
| ai_picks.json | daily | 2026-10-29T05:44:37 | 329.9 | 30 | **STALE** |
| all_sources.json | daily | 2026-10-29T05:44:05 | 329.9 | 30 | **STALE** |
| enrich.json | intraday | 2026-10-29T05:43:48 | 329.9 | 3 | **STALE** |
| hot_impact.json | realtime | 2026-10-29T05:43:23 | 329.9 | 0.5 | **STALE** |
| market_now.json | realtime | 2026-10-29T05:43:33 | 329.9 | 0.5 | **STALE** |
| risk_plan.json | daily | None | - | - | **NO_TS** |
| anomaly_report.json | unknown | 2026-10-14T18:03:08 | 677.6 | None | **UNKNOWN_TIER** |
| ban_prob_balanced.json | unknown | 2026-10-14T18:03:03 | 677.6 | None | **UNKNOWN_TIER** |
| flow_divergence.json | unknown | 2026-10-14T18:00:34 | 677.6 | None | **UNKNOWN_TIER** |
| signal_audit.json | unknown | 2026-10-14T18:03:04 | 677.6 | None | **UNKNOWN_TIER** |
| validation_report.json | unknown | 2026-10-14T18:03:08 | 677.6 | None | **UNKNOWN_TIER** |
| bulk_kline_1.json | unknown | 2026-10-25T06:05:52 | 425.5 | None | **UNKNOWN_TIER** |
| global_fx.json | unknown | 2026-10-28T21:31:56 | 338.1 | None | **UNKNOWN_TIER** |
| analysis_manifest.json | unknown | 2026-11-11T15:42:54 | 7.9 | None | **UNKNOWN_TIER** |
| global_kline.json | unknown | 2026-11-11T15:41:26 | 7.9 | None | **UNKNOWN_TIER** |
| klineshare_hq.json | unknown | 2026-11-11T15:41:26 | 7.9 | None | **UNKNOWN_TIER** |
| concept_map.json | unknown | 2026-11-11T23:38:13 | 0.0 | None | **UNKNOWN_TIER** |
| industry_stocks.json | unknown | 2026-11-11T23:38:13 | 0.0 | None | **UNKNOWN_TIER** |
| news_impact.json | unknown | 2026-11-11T23:38:13 | 0.0 | None | **UNKNOWN_TIER** |
| recent_mainlines.json | unknown | 2026-11-11T23:38:14 | 0.0 | None | **UNKNOWN_TIER** |
| global_markets.json | realtime | 2026-11-11T15:40:55 | 8.0 | 0.5 | **OK** |
| hot_news.json | daily | 2026-11-11T23:38:11 | 0.0 | 30 | **OK** |
| hot_themes.json | daily | 2026-11-11T23:38:14 | 0.0 | 30 | **OK** |
| mainline.json | daily | 2026-11-11T23:38:14 | 0.0 | 30 | **OK** |
| news_extra.json | daily | 2026-11-11T23:37:59 | 0.0 | 30 | **OK** |
| news_transmission.json | daily | 2026-11-11T23:38:14 | 0.0 | 30 | **OK** |
| shard_b.json | intraday | 2026-11-11T23:37:47 | 0.0 | 3 | **OK** |
| sources_registry.json | static | 2026-10-28T21:30:41 | - | - | **STATIC** |
| stock_names.json | static | None | - | - | **STATIC** |

## 说明

- STALE = 超过该档位阈值。非交易时段采集类变旧是预期, 需结合
  是否交易时段判断; 真正的故障是「交易日盘中仍不更新」。
- EXPECTED_CLOSED = 周末或非交易时段，当前文件不应被当作实时故障。
- 本报告由 `scripts/audit_freshness.py` 生成, 可加 `--fail-on-stale`
  作为 CI 门禁。
