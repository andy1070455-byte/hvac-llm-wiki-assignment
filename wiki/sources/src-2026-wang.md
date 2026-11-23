# ThermoForce: A Physics-Structured Interventional World Model for Building HVAC Control
- 年份與來源：2026 | arXiv:2607.03942
- 核心問題：被動預測準確度高不代表控制介入（control trajectory）推演準確，易出現方向或幅度失真。
- 方法與模型：ThermoForce，拆解為自由響應（free response，凍結 Time-Series Foundation Models, TSFM）與受迫響應（forced response，單調受迫響應算子），於 BOPTEST 搭配 MPC 評估。
- 實驗與指標：加熱氣候中觀測型 grey-box 被動 RMSE 為 0.761 K 但介入 RMSE 達 1.360 K，ThermoForce 介入 RMSE 為 0.751 K；冷卻氣候單調約束將介入 RMSE 從 0.331 K 降至 0.245 K；BOPTEST 不舒適度降 33–84% 並減耗。
- 限制與缺口：需控制激勵資料辨識介入響應，多機組 Chiller Bank 離散啟停耦合仍待驗證。
