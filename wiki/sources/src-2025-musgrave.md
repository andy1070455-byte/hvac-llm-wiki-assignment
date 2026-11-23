# A Receding Horizon Reinforcement Learning Framework for Campus Chiller Energy Management - A case study from an Australian University
- 年份與來源：2025 | arXiv:2511.14160
- 核心問題：傳統冰水主機群定值規則控制（如上班冰水出水溫度約 6 °C、非上班約 11 °C）難以兼顧動態負載與約束。
- 方法與模型：Proximal Policy Optimization (PPO)、Receding Horizon 控制、TimeXer（24 小時冷負荷預測），調節冰水質量流率（mass flow rates）與啟停排程。
- 實驗與指標：四台冰水主機（four-chiller plant）案例；耗電量 66.49 MWh，較規則控制（92.35 MWh）節電 28%，較無滾動時域 RL（74.35 MWh）節電 8%；平均 PLR 由 0.81 升至 0.83，平均 COP 由 8.03 升至 8.81。
- 限制與缺口：實場部署需兼顧硬體安全保護與多設備耦合動態。
