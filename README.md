# 国能e招 · 招标监控看板

数据源：国能e招监控（江西 12 地名 × 20 类关键词，货物 tab）写入飞书两表，`build_dashboard_data.py` 定期生成快照，本页读取展示。

- `index.html`：看板（指标 / 监控动态 / 公告入库 / 候选人公示）
- `data.json`：数据快照（由生成器产出）

更新：在监控机运行 `python3 ~/Documents/chnenergy_monitor/build_dashboard_data.py` 后推送。
