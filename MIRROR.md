# Mirror node B

stocks-ai-view 的采集镜像节点 (多账号分片, 分散出口 IP)。

- 代码唯一事实源: https://github.com/qwerzxcva/stocks-ai-view
- 本仓分片: b (b)
- 本仓 cron 分钟位: 4,9,14,19,24,29,34,39,44,49,54,59 (mod 5)
- 只跑分片采集; AI/复盘/归档/回溯已禁用 (避免重复烧额度与 commit 冲突)
- 不要在本地手改代码, 会被下次部署覆盖
