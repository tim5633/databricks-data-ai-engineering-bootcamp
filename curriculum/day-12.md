# Day 12 — Schema evolution and quarantine

**2026-11-06 · 2 hours · Week 2** · [Home](../README.md) · [繁體中文 ↓](#traditional-chinese)

## Daily course → section → lab → certification

- **Open:** [Databricks Partner Academy](https://partner-academy.databricks.com/) → **Build Data Pipelines with Spark Declarative Pipelines** ([public official learning catalog](https://www.databricks.com/learn/training/home)).
- **Section focus:** Schema changes, quarantine, invalid records (recommended focus; verify lesson title after company sign-in).
- **Lab:** Reconcile bad rows, quarantine and rerun safely.
- **Exam:** **Data Engineer Professional; Associate** ([official exam guide catalog](https://www.databricks.com/learn/training/certification)).
- **Evidence:** runnable pipeline, negative/failure test, architecture decision and Git commit.

## Assigned official curriculum

**Databricks Partner Academy:** [Partner Academy](https://partner-academy.databricks.com/) — log in using an approved company account and locate **Data Ingestion with Lakeflow Connect; Deploy Workloads with Lakeflow Jobs; Build Data Pipelines with Spark Declarative Pipelines**. The public [Databricks role-based training catalog](https://www.databricks.com/learn/training/home) lists relevant course titles.

**Today's official reading links:**
1. [Lakeflow overview](https://docs.databricks.com/aws/en/ingestion/)
2. [Lakeflow Jobs](https://docs.databricks.com/aws/en/jobs/)
3. [Lakeflow Declarative Pipelines](https://docs.databricks.com/aws/en/ldp/)

## Learning outcomes

Inject malformed schemas, duplicates and late-arriving data.

## Daily timetable

| Time | Action | Evidence |
|---|---|---|
| 00:00–00:40 | Study the named academy path and linked docs | Notes / runnable artifact |
| 00:40–01:45 | Reconcile bad rows, quarantine and rerun safely | Notes / runnable artifact |
| 01:45–02:00 | Verify results, explain one trade-off and commit | Notes / runnable artifact |

## Practical assignment and success criteria

**Build:** Reconcile bad rows, quarantine and rerun safely.

**Pass when:** the implementation or design can be reproduced, at least one failure/negative case has been tested, and a Git commit or learning log records results, a trade-off and remaining questions. Sunday is a recap/gap-analysis day rather than a new large build.

- [ ] Assigned reading and concept notes
- [ ] Lab / review delivered
- [ ] Validation evidence and failure case
- [ ] Git commit / ADR and short English explanation

---

<a id="traditional-chinese"></a>

# Day 12 — Schema Evolution 與隔離區

**2026-11-06 · 2 小時 · 第 2 週** · [首頁](../README.md)

## 今日課程 → Section → Lab → 證照

- **打開：** [Databricks Partner Academy](https://partner-academy.databricks.com/) → **Build Data Pipelines with Spark Declarative Pipelines**（[官方課程目錄](https://www.databricks.com/learn/training/home)）。
- **指定 Section：** Schema changes, quarantine, invalid records（建議學習內容，內部 Lesson 名稱以登入顯示為準）。
- **Lab：** Reconcile bad rows, quarantine and rerun safely。
- **對應認證：** **Data Engineer Professional; Associate**。
- **交付：** 可執行 Pipeline、負面測試、架構決策與 Commit。

## 指定官方課程

**Databricks Partner Academy：** [Partner Academy](https://partner-academy.databricks.com/)（使用公司帳號登入），尋找 **Data Ingestion with Lakeflow Connect; Deploy Workloads with Lakeflow Jobs; Build Data Pipelines with Spark Declarative Pipelines** 對應課程。課程名稱可在[官方 Learning Pathway 目錄](https://www.databricks.com/learn/training/home)確認。

**今日官方文件直達連結：**
1. [Lakeflow overview](https://docs.databricks.com/aws/en/ingestion/)
2. [Lakeflow Jobs](https://docs.databricks.com/aws/en/jobs/)
3. [Lakeflow Declarative Pipelines](https://docs.databricks.com/aws/en/ldp/)

## 今日學習目標

**Schema Evolution 與隔離區**：深入理解 Inject malformed schemas, duplicates and late-arriving data，並能說明其技術取捨與企業使用情境。

## 每日學習時間線

| 時段 | 學習與實作 | 交付證據 |
|---|---|---|
| 00:00–00:40 | 學習指定 Academy 主題與官方文件 | 筆記、可重現實作 |
| 00:40–01:45 | 實作指定內容與測試 | 筆記、可重現實作 |
| 01:45–02:00 | 驗收、技術取捨與 Commit | 筆記、可重現實作 |

## 實戰驗收

**任務：** Reconcile bad rows, quarantine and rerun safely。

**通過標準：** 可重現實作或設計、至少測試一個失敗／邊界案例，並提交 Commit 或筆記，記錄測試、架構取捨與後續缺口。週日以複習為主，不增加大型新功能。

- [ ] 完成指定課程與筆記
- [ ] 完成當日實作或複習
- [ ] 保存測試與失敗案例證據
- [ ] Git Commit／ADR 與英文簡報

