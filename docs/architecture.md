# Enterprise Architecture & Security

Design decisions: compute modes, streaming vs batch, Delta schema evolution, catalog-permission boundaries, MCP/SQL read-only authorization, retrieval provenance, agent serving, identity, isolation, monitoring and workload costs.

**Threats to test:** unauthorized reads, unauthorized writes, malformed data, prompt-injected documents, retry replay, runaway costs, credential leakage and failed ingestion.

**Document as ADRs:** context, options, latency/cost/reliability/security trade-offs, evidence, decision, owner and revisit trigger.

---

<a id="traditional-chinese"></a>

# 企業架構與安全

重點包含 Compute 選型、Streaming vs Batch、Delta Schema Evolution、Unity Catalog 權限、MCP/SQL 唯讀授權、RAG 來源追溯、Agent 身分、部署隔離、監控與成本。

**必測風險：** 越權讀寫、資料格式錯誤、文件注入、重複執行、成本失控、密鑰洩漏、Pipeline 失敗。

使用 ADR 記錄問題、替代方案、取捨、測試證據、負責人與重新評估條件。
