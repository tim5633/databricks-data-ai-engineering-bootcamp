# Day 18 — Spark execution and performance

**2026-11-12 · 2 hours · Week 3** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Company course → assigned section → lab → credential

- **Open:** [Databricks Performance Optimization](https://www.databricks.com/learn/training/home) via [Partner Academy](https://partner-academy.databricks.com/) (company account).
- **Section focus:** Spark shuffles, skew, Photon, query plans (assigned topic within the course; internal lesson title may vary).
- **Lab:** Benchmark and improve one slow join.
- **Certification:** **Data Engineer Professional** ([Exam Guides](https://www.databricks.com/learn/training/certification)).
- **Pass:** produce tested code, failed-case evidence and an ADR.

## Assigned official curriculum

**Databricks Partner Academy:** [Partner Academy](https://partner-academy.databricks.com/) — log in using an approved company account and locate **Data Management and Governance with UC**. The public [Databricks role-based training catalog](https://www.databricks.com/learn/training/home) lists relevant course titles.

**Today's official reading links:**
1. [Unity Catalog](https://docs.databricks.com/aws/en/data-governance/unity-catalog/)
2. [Declarative Automation Bundles](https://docs.databricks.com/aws/en/dev-tools/bundles/)
3. [Spark optimization](https://docs.databricks.com/aws/en/optimizations/)

## Learning outcomes

Analyze shuffles, skew, broadcast joins, partitioning and query profiles.

## Daily timetable

| Time | Action | Evidence |
|---|---|---|
| 00:00–00:40 | Study the named academy path and linked docs | Notes / runnable artifact |
| 00:40–01:45 | Benchmark and improve one slow join | Notes / runnable artifact |
| 01:45–02:00 | Verify results, explain one trade-off and commit | Notes / runnable artifact |

## Practical assignment and success criteria

**Build:** Benchmark and improve one slow join.

**Pass when:** the implementation or design can be reproduced, at least one failure/negative case has been tested, and a Git commit or learning log records results, a trade-off and remaining questions. Sunday is a recap/gap-analysis day rather than a new large build.

- [ ] Assigned reading and concept notes
- [ ] Lab / review delivered
- [ ] Validation evidence and failure case
- [ ] Git commit / ADR and short English explanation

---

<a id="traditional-chinese"></a>

# Day 18 — Spark 執行效能

**2026-11-12 · 2 小時 · 第 3 週** · [首頁](../README.md)

## 公司課程 → 指定 Section → 實作 → 認證

- **打開：** [Databricks Performance Optimization](https://www.databricks.com/learn/training/home) → 公司 [Partner Academy](https://partner-academy.databricks.com/)。
- **Section 主題：** Spark shuffles, skew, Photon, query plans（以公司登入後的 Lesson 名稱為準）。
- **實作 Lab：** Benchmark and improve one slow join.
- **對應認證：** Data Engineer Professional。
- **驗收：** 程式、失敗案例測試、架構取捨。

## 指定官方課程

**Databricks Partner Academy：** [Partner Academy](https://partner-academy.databricks.com/)（使用公司帳號登入），尋找 **Data Management and Governance with UC** 對應課程。課程名稱可在[官方 Learning Pathway 目錄](https://www.databricks.com/learn/training/home)確認。

**今日官方文件直達連結：**
1. [Unity Catalog](https://docs.databricks.com/aws/en/data-governance/unity-catalog/)
2. [Declarative Automation Bundles](https://docs.databricks.com/aws/en/dev-tools/bundles/)
3. [Spark optimization](https://docs.databricks.com/aws/en/optimizations/)

## 今日學習目標

**Spark 執行效能**：深入理解 Analyze shuffles, skew, broadcast joins, partitioning and query profiles，並能說明其技術取捨與企業使用情境。

## 每日學習時間線

| 時段 | 學習與實作 | 交付證據 |
|---|---|---|
| 00:00–00:40 | 學習指定 Academy 主題與官方文件 | 筆記、可重現實作 |
| 00:40–01:45 | 實作指定內容與測試 | 筆記、可重現實作 |
| 01:45–02:00 | 驗收、技術取捨與 Commit | 筆記、可重現實作 |

## 實戰驗收

**任務：** Benchmark and improve one slow join。

**通過標準：** 可重現實作或設計、至少測試一個失敗／邊界案例，並提交 Commit 或筆記，記錄測試、架構取捨與後續缺口。週日以複習為主，不增加大型新功能。

- [ ] 完成指定課程與筆記
- [ ] 完成當日實作或複習
- [ ] 保存測試與失敗案例證據
- [ ] Git Commit／ADR 與英文簡報

