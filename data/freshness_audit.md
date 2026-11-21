# 数据新鲜度审计

- 时间: 2026-11-22 06:04 CST
- 扫描: 42 个文件 | STALE 14 | 无时间戳 1 | 解析失败 0

| 文件 | 档位 | 时间戳 | 年龄(h) | 阈值(h) | 状态 |
|---|---|---|---|---|---|
| ai_pick_v4.json | daily | 2026-10-14T17:59:10 | 924.1 | 30 | **STALE** |
| ban_pick.json | daily | 2026-10-14T18:00:27 | 924.1 | 30 | **STALE** |
| ban_prob.json | daily | 2026-10-14T18:00:15 | 924.1 | 30 | **STALE** |
| decision.json | daily | 2026-10-14T18:00:15 | 924.1 | 30 | **STALE** |
| engine_v5.json | daily | 2026-10-14T17:59:03 | 924.1 | 30 | **STALE** |
| kline_sim.json | weekly | 2026-10-14T18:00:34 | 924.1 | 192 | **STALE** |
| market_phase.json | daily | 2026-10-14T17:58:29 | 924.1 | 30 | **STALE** |
| multidim.json | daily | 2026-10-14T18:00:15 | 924.1 | 30 | **STALE** |
| edge_report.json | weekly | 2026-10-14T18:03:04 | 924.0 | 192 | **STALE** |
| scenario.json | daily | 2026-10-14T18:03:04 | 924.0 | 30 | **STALE** |
| self_reflect.json | daily | 2026-10-14T18:03:04 | 924.0 | 30 | **STALE** |
| news_digest.json | daily | 2026-10-28T21:31:56 | 584.5 | 30 | **STALE** |
| ai_picks.json | daily | 2026-10-29T05:44:37 | 576.3 | 30 | **STALE** |
| all_sources.json | daily | 2026-10-29T05:44:05 | 576.3 | 30 | **STALE** |
| risk_plan.json | daily | None | - | - | **NO_TS** |
| flow_divergence.json | unknown | 2026-10-14T18:00:34 | 924.1 | None | **UNKNOWN_TIER** |
| anomaly_report.json | unknown | 2026-10-14T18:03:08 | 924.0 | None | **UNKNOWN_TIER** |
| ban_prob_balanced.json | unknown | 2026-10-14T18:03:03 | 924.0 | None | **UNKNOWN_TIER** |
| signal_audit.json | unknown | 2026-10-14T18:03:04 | 924.0 | None | **UNKNOWN_TIER** |
| validation_report.json | unknown | 2026-10-14T18:03:08 | 924.0 | None | **UNKNOWN_TIER** |
| bulk_kline_1.json | unknown | 2026-10-25T06:05:52 | 672.0 | None | **UNKNOWN_TIER** |
| global_fx.json | unknown | 2026-10-28T21:31:56 | 584.5 | None | **UNKNOWN_TIER** |
| analysis_manifest.json | unknown | 2026-11-22T00:11:22 | 5.9 | None | **UNKNOWN_TIER** |
| global_kline.json | unknown | 2026-11-22T00:09:40 | 5.9 | None | **UNKNOWN_TIER** |
| klineshare_hq.json | unknown | 2026-11-22T00:09:41 | 5.9 | None | **UNKNOWN_TIER** |
| concept_map.json | unknown | 2026-11-22T06:04:08 | 0.0 | None | **UNKNOWN_TIER** |
| industry_stocks.json | unknown | 2026-11-22T06:04:08 | 0.0 | None | **UNKNOWN_TIER** |
| news_impact.json | unknown | 2026-11-22T06:04:08 | 0.0 | None | **UNKNOWN_TIER** |
| recent_mainlines.json | unknown | 2026-11-22T06:04:09 | 0.0 | None | **UNKNOWN_TIER** |
| realtime_minute.json | realtime | 2026-10-28T21:29:35 | 584.6 | 0.5 | **EXPECTED_CLOSED** |
| enrich.json | intraday | 2026-10-29T05:43:48 | 576.3 | 3 | **EXPECTED_CLOSED** |
| hot_impact.json | realtime | 2026-10-29T05:43:23 | 576.3 | 0.5 | **EXPECTED_CLOSED** |
| market_now.json | realtime | 2026-10-29T05:43:33 | 576.3 | 0.5 | **EXPECTED_CLOSED** |
| global_markets.json | realtime | 2026-11-22T00:09:16 | 5.9 | 0.5 | **EXPECTED_CLOSED** |
| hot_news.json | daily | 2026-11-22T06:04:06 | 0.0 | 30 | **OK** |
| hot_themes.json | daily | 2026-11-22T06:04:09 | 0.0 | 30 | **OK** |
| mainline.json | daily | 2026-11-22T06:04:09 | 0.0 | 30 | **OK** |
| news_extra.json | daily | 2026-11-22T06:03:56 | 0.0 | 30 | **OK** |
| news_transmission.json | daily | 2026-11-22T06:04:09 | 0.0 | 30 | **OK** |
| shard_b.json | intraday | 2026-11-22T06:03:44 | 0.0 | 3 | **OK** |
| sources_registry.json | static | 2026-10-28T21:30:41 | - | - | **STATIC** |
| stock_names.json | static | None | - | - | **STATIC** |

## 说明

- STALE = 超过该档位阈值。非交易时段采集类变旧是预期, 需结合
  是否交易时段判断; 真正的故障是「交易日盘中仍不更新」。
- EXPECTED_CLOSED = 周末或非交易时段，当前文件不应被当作实时故障。
- 本报告由 `scripts/audit_freshness.py` 生成, 可加 `--fail-on-stale`
  作为 CI 门禁。
