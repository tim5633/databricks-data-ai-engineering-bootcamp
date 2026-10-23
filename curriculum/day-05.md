# Day 05 — Databricks SQL and query plans

**2026-10-30 · 2 hours · Week 1** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Open this course → study this section → do this lab → exam mapping

1. **Open company course:** [Data Analysis with Databricks — SQL Analytics on Databricks](https://partner-academy.databricks.com/learn/courses/830/data-analysis-with-databricks-sql-ilt) via [Databricks Partner Academy](https://partner-academy.databricks.com/) using your corporate email. Where the URL is a catalog/docs page rather than the exact course, use the **named course title** to locate the lesson after login.
2. **Assigned section / topic:** **SQL Execution and Query Analysis sections; Photon / Query Insights**. This is a *recommended section focus*, **not** a claim that the Partner Academy uses this exact internal lesson title.
3. **Hands-on lab:** Optimize three analytical queries on synthetic data.
4. **Certification coverage:** **Data Engineer Associate; Data Analyst Associate (optional)**. Cross-check current [official certification guide](https://www.databricks.com/learn/training/certification).
5. **Completion evidence:** course notes, an executable lab or design, one failing/negative test, a commit, and a 3-minute independent explanation.

## Assigned official curriculum

**Databricks Partner Academy:** [Partner Academy](https://partner-academy.databricks.com/) — log in using an approved company account and locate **Get Started with Data Engineering; Databricks Fundamentals**. The public [Databricks role-based training catalog](https://www.databricks.com/learn/training/home) lists relevant course titles.

**Today's official reading links:**
1. [Get started with Databricks](https://docs.databricks.com/aws/en/getting-started/)
2. [Delta Lake](https://docs.databricks.com/aws/en/delta/)
3. [PySpark API](https://spark.apache.org/docs/latest/api/python/)

## Learning outcomes

Review SQL joins, aggregations, EXPLAIN, partition/pruning.

## Daily timetable

| Time | Action | Evidence |
|---|---|---|
| 00:00–00:40 | Study the named academy path and linked docs | Notes / runnable artifact |
| 00:40–01:45 | Optimize three analytical queries on synthetic data | Notes / runnable artifact |
| 01:45–02:00 | Verify results, explain one trade-off and commit | Notes / runnable artifact |

## Practical assignment and success criteria

**Build:** Optimize three analytical queries on synthetic data.

**Pass when:** the implementation or design can be reproduced, at least one failure/negative case has been tested, and a Git commit or learning log records results, a trade-off and remaining questions. Sunday is a recap/gap-analysis day rather than a new large build.

- [ ] Assigned reading and concept notes
- [ ] Lab / review delivered
- [ ] Validation evidence and failure case
- [ ] Git commit / ADR and short English explanation

---

<a id="traditional-chinese"></a>

# Day 05 — Databricks SQL 與查詢計畫

**2026-10-30 · 2 小時 · 第 1 週** · [首頁](../README.md)

## 今天要開哪門課 → 哪個 Section → 做什麼 Lab → 對應證照

1. **公司指定課程：** [Data Analysis with Databricks — SQL Analytics on Databricks](https://partner-academy.databricks.com/learn/courses/830/data-analysis-with-databricks-sql-ilt)，以公司信箱登入 [Databricks Partner Academy](https://partner-academy.databricks.com/)；若連結為目錄或技術文件，請依**課程全名**在登入後搜尋。
2. **指定學習 Section／主題：** **SQL Execution and Query Analysis sections; Photon / Query Insights**。這是我指定的學習範圍，**不表示 Partner Academy 內部 Lesson 原名一定相同**。
3. **實作 Lab：** Optimize three analytical queries on synthetic data。
4. **對應證書：** **Data Engineer Associate; Data Analyst Associate (optional)**，正式範圍以[官方考綱](https://www.databricks.com/learn/training/certification)為準。
5. **完成證據：** 官方課程筆記、程式／架構成果、至少一個失敗或權限測試、Git Commit 和三分鐘技術解說。

## 指定官方課程

**Databricks Partner Academy：** [Partner Academy](https://partner-academy.databricks.com/)（使用公司帳號登入），尋找 **Get Started with Data Engineering; Databricks Fundamentals** 對應課程。課程名稱可在[官方 Learning Pathway 目錄](https://www.databricks.com/learn/training/home)確認。

**今日官方文件直達連結：**
1. [Get started with Databricks](https://docs.databricks.com/aws/en/getting-started/)
2. [Delta Lake](https://docs.databricks.com/aws/en/delta/)
3. [PySpark API](https://spark.apache.org/docs/latest/api/python/)

## 今日學習目標

**Databricks SQL 與查詢計畫**：深入理解 Review SQL joins, aggregations, EXPLAIN, partition/pruning，並能說明其技術取捨與企業使用情境。

## 每日學習時間線

| 時段 | 學習與實作 | 交付證據 |
|---|---|---|
| 00:00–00:40 | 學習指定 Academy 主題與官方文件 | 筆記、可重現實作 |
| 00:40–01:45 | 實作指定內容與測試 | 筆記、可重現實作 |
| 01:45–02:00 | 驗收、技術取捨與 Commit | 筆記、可重現實作 |

## 實戰驗收

**任務：** Optimize three analytical queries on synthetic data。

**通過標準：** 可重現實作或設計、至少測試一個失敗／邊界案例，並提交 Commit 或筆記，記錄測試、架構取捨與後續缺口。週日以複習為主，不增加大型新功能。

- [ ] 完成指定課程與筆記
- [ ] 完成當日實作或複習
- [ ] 保存測試與失敗案例證據
- [ ] Git Commit／ADR 與英文簡報

