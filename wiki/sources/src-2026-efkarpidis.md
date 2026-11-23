# Comparative review of hybrid forecasting models for short-term prediction of building thermal load
- 年份與來源：2026 | arXiv:2610.06881
- 核心問題：短期熱負荷（short-term thermal load forecasting）高度非線性，單一模型難應對所有情境，突發尖峰（spikes / swells）預測仍具挑戰。
- 方法與模型：比較白箱、資料驅動與 13 種混合模型（hybrid models），涵蓋 EMD-LSTM-Markov、LSTM、GRU、XGB、RF、ARX、NARX、1R1C、metaheuristics。
- 實驗與指標：於歷史熱需求與天氣預報資料集評估；EMD-LSTM-Markov 對日前（day-ahead）加熱與生活熱水需求整體準確度最高，但對劇烈尖峰（high power swells and spikes）仍可能低估。
- 限制與缺口：各文獻基準不一，極端尖峰預測仍需改進。
