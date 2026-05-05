# ARIA v7.0 — The All-Weather Auditor (Work in Progress)

**ARIA v7.0（全天候稽核員）** 透過整合 **SAR 雷達資料（Sentinel-1）** 的穿雲能力與 **光學影像（Sentinel-2）** 的水體指標，建立具備多重確信度分級的淹水地圖。

**本次案例分析**：2025 年 11 月鳳凰颱風登陸後，花蓮馬太鞍溪流域的淹水與堰塞湖災情評估。

## 四項任務 (Current Progress)

- **Task 1: SAR 全天候淹水偵測** (STAC 串流、斑點雜訊濾波、二元水體遮罩萃取)
- **Task 2: 感測器融合 — 多源確信度地圖** (光學 NDWI 計算、雲遮罩建立、4 級確信度融合地圖)
- **Task 3: 地形分析 — DEM 與坡度評估** (Copernicus DEM 載入、坡度過濾地形假水體、DEM 適用性討論)
- **Task 4: AI 戰略簡報 + 演進報告** (Groq API 自動生成戰略簡報、W9 vs W10 比較分析)
