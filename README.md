# Hotel Operation Analysis Project

基于真实酒店预订数据，独立完成从数据清洗、指标建模到业务洞察的全流程分析。
分析过程全部在 **Excel** 中完成（函数公式、条件计算、图表），
并同步输出 **Power BI 报表** 和 **AI 辅助生成的 H5 交互看板**。

## 仓库结构

```
├── Hotel dataset.xlsx                    # 【核心】原始数据 + Excel 分析（函数建模/图表）
├── Hotel Report.pbix                     # Power BI 经营分析仪表盘（手动搭建）
└── hotel_2018_annual_review.html         # AI 辅助生成的 H5 交互看板（ECharts）
```
## 分析内容

所有分析均在 Excel 中完成，包括：

- **数据清洗**：缺失值处理、异常值剔除、字段标准化（渠道 / 房型 / 餐食 / 取消标记）
- **指标建模**：使用 Excel 函数（SUMIFS、AVERAGEIFS、COUNTIFS、IF 嵌套等）计算月度营收、入住率、ADR、RevPAR 等核心经营指标
- **维度拆解**：按渠道、房型、月份交叉分析，识别营收驱动因素
- **风险洞察**：线上渠道取消率 42% vs 企业客户 7%，提出差异化风控 + 渠道投放建议

## 技术栈

- **分析工具**：Excel（函数公式 / 条件计算 / 图表）
- **可视化**：Power BI（.pbix）、HTML + ECharts（H5）
- **AI 辅助**：WorkBuddy（仅用于 H5 页面代码生成）

## 快速查看

- **Excel 分析**：直接下载 `Hotel dataset.xlsx`，查看各工作表（原始数据、函数计算表、分析图表）
- **Power BI**：下载 `Hotel Report.pbix`，用 Power BI Desktop 打开
- **H5 看板**：[点击预览](部署后的 GitHub Pages 链接)

## 可迁移场景

本项目的分析框架（Excel 函数建模 → 多维拆解 → 风险洞察 → 多工具可视化输出）
可复用至零售、资产运营、财务经营分析等业务场景。

---
© 2026 Lizhen-zhi
