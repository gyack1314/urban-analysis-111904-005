# 城市更新资料契约

全部楼宇、机构、居民群体、设备、交易及事件均为本地合成，不对应新闻所涉真实主体，不声称新闻中发生这些业务问题。seed.json及各同名Parquet保留完全相同的原始值；actions.json是尚未应用的后续资料。inventory.json仅记录物理大小、摘要及行数，不是业务结论。原始量纲、空值和时区按下文解释。

observations.LAeq_db为duration_seconds积分等效声级，censor=below_limit仅知低于limit_db，missing为未知。observed_peak_db只覆盖该次观察。时间为UTC+08半开区间，重叠须保留。calibrations给dB修正及有效期；receptors含坐标/户数；source_logs为实际设备开关位置，planned_trials是计划，trial_receipts才说明执行/取消。traffic/weather为同期背景，targets为研究目标非法律标准。measures给衰减范围、位移或工序延长与成本，分贝非线性；split隔离日/接收点，actions是独立停机原始观测，不给贡献真值。
