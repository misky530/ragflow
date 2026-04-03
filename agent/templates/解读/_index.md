# RAGFlow Agent Templates 解读索引

> 从**产品经理、开发者、业务**三个视角系统解读 RAGFlow 官方 Agent 模板。
> 每篇解读对应 `agent/templates/` 目录下的同名 `.json` 源文件。

---

## 解读进度

| 模板文件 | 概览 | 产品经理 | 开发者 | 业务 | 状态 |
|---|---|---|---|---|---|
| `deep_research.json` | [概览](./deep_research/概览.md) | [产品经理视角](./deep_research/产品经理视角.md) | [开发者视角](./deep_research/开发者视角.md) | [业务视角](./deep_research/业务视角.md) | ✅ 已完成 |
| `cv_analysis_and_candidate_evaluation.json` | [概览](./cv_analysis/概览.md) | [产品经理视角](./cv_analysis/产品经理视角.md) | [开发者视角](./cv_analysis/开发者视角.md) | [业务视角](./cv_analysis/业务视角.md) | ✅ 已完成 |
| `customer_review_analysis.json` | [概览](./customer_review_analysis/概览.md) | [产品经理视角](./customer_review_analysis/产品经理视角.md) | [开发者视角](./customer_review_analysis/开发者视角.md) | [业务视角](./customer_review_analysis/业务视角.md) | ✅ 已完成 |
| `technical_docs_qa.json` | [概览](./technical_docs_qa/概览.md) | [产品经理视角](./technical_docs_qa/产品经理视角.md) | [开发者视角](./technical_docs_qa/开发者视角.md) | [业务视角](./technical_docs_qa/业务视角.md) | ✅ 已完成 |
| `user_interaction.json` | [概览](./user_interaction/概览.md) | [产品经理视角](./user_interaction/产品经理视角.md) | [开发者视角](./user_interaction/开发者视角.md) | [业务视角](./user_interaction/业务视角.md) | ✅ 已完成 |
| `image_lingo.json` | [概览](./image_lingo/概览.md) | [产品经理视角](./image_lingo/产品经理视角.md) | [开发者视角](./image_lingo/开发者视角.md) | [业务视角](./image_lingo/业务视角.md) | ✅ 已完成 |
| `sql_assistant.json` | [概览](./sql_assistant/概览.md) | [产品经理视角](./sql_assistant/产品经理视角.md) | [开发者视角](./sql_assistant/开发者视角.md) | [业务视角](./sql_assistant/业务视角.md) | ✅ 已完成 |
| `stock_research_report.json` | [概览](./stock_research_report/概览.md) | [产品经理视角](./stock_research_report/产品经理视角.md) | [开发者视角](./stock_research_report/开发者视角.md) | [业务视角](./stock_research_report/业务视角.md) | ✅ 已完成 |
| `web_search_assistant.json` | [概览](./web_search_assistant/概览.md) | [产品经理视角](./web_search_assistant/产品经理视角.md) | [开发者视角](./web_search_assistant/开发者视角.md) | [业务视角](./web_search_assistant/业务视角.md) | ✅ 已完成 |
| `choose_your_knowledge_base_agent.json` | [概览](./choose_your_knowledge_base_agent/概览.md) | [产品经理视角](./choose_your_knowledge_base_agent/产品经理视角.md) | [开发者视角](./choose_your_knowledge_base_agent/开发者视角.md) | [业务视角](./choose_your_knowledge_base_agent/业务视角.md) | ✅ 已完成 |
| `choose_your_knowledge_base_workflow.json` | [概览](./choose_your_knowledge_base_workflow/概览.md) | [产品经理视角](./choose_your_knowledge_base_workflow/产品经理视角.md) | [开发者视角](./choose_your_knowledge_base_workflow/开发者视角.md) | [业务视角](./choose_your_knowledge_base_workflow/业务视角.md) | ✅ 已完成 |
| `knowledge_base_report.json` | [概览](./knowledge_base_report/概览.md) | [产品经理视角](./knowledge_base_report/产品经理视角.md) | [开发者视角](./knowledge_base_report/开发者视角.md) | [业务视角](./knowledge_base_report/业务视角.md) | ✅ 已完成 |
| `knowledge_base_report_r.json` | [概览](./knowledge_base_report_r/概览.md) | [产品经理视角](./knowledge_base_report_r/产品经理视角.md) | [开发者视角](./knowledge_base_report_r/开发者视角.md) | [业务视角](./knowledge_base_report_r/业务视角.md) | ✅ 已完成 |
| `customer_service.json` | [概览](./customer_service/概览.md) | [产品经理视角](./customer_service/产品经理视角.md) | [开发者视角](./customer_service/开发者视角.md) | [业务视角](./customer_service/业务视角.md) | ✅ 已完成 |
| `customer_support.json` | [概览](./customer_support/概览.md) | [产品经理视角](./customer_support/产品经理视角.md) | [开发者视角](./customer_support/开发者视角.md) | [业务视角](./customer_support/业务视角.md) | ✅ 已完成 |
| `ecommerce_customer_service_workflow.json` | [概览](./ecommerce_customer_service_workflow/概览.md) | [产品经理视角](./ecommerce_customer_service_workflow/产品经理视角.md) | [开发者视角](./ecommerce_customer_service_workflow/开发者视角.md) | [业务视角](./ecommerce_customer_service_workflow/业务视角.md) | ✅ 已完成 |
| `generate_SEO_blog.json` | [概览](./generate_SEO_blog/概览.md) | [产品经理视角](./generate_SEO_blog/产品经理视角.md) | [开发者视角](./generate_SEO_blog/开发者视角.md) | [业务视角](./generate_SEO_blog/业务视角.md) | ✅ 已完成 |
| `market_generate_seo_blog.json` | [概览](./market_generate_seo_blog/概览.md) | [产品经理视角](./market_generate_seo_blog/产品经理视角.md) | [开发者视角](./market_generate_seo_blog/开发者视角.md) | [业务视角](./market_generate_seo_blog/业务视角.md) | ✅ 已完成 |
| `seo_blog.json` | [概览](./seo_blog/概览.md) | [产品经理视角](./seo_blog/产品经理视角.md) | [开发者视角](./seo_blog/开发者视角.md) | [业务视角](./seo_blog/业务视角.md) | ✅ 已完成 |
| `trip_planner.json` | [概览](./trip_planner/概览.md) | [产品经理视角](./trip_planner/产品经理视角.md) | [开发者视角](./trip_planner/开发者视角.md) | [业务视角](./trip_planner/业务视角.md) | ✅ 已完成 |
| `deep_search_r.json` | [概览](./deep_search_r/概览.md) | [产品经理视角](./deep_search_r/产品经理视角.md) | [开发者视角](./deep_search_r/开发者视角.md) | [业务视角](./deep_search_r/业务视角.md) | ✅ 已完成 |
| `advanced_ingestion_pipeline.json` | [概览](./advanced_ingestion_pipeline/概览.md) | [产品经理视角](./advanced_ingestion_pipeline/产品经理视角.md) | [开发者视角](./advanced_ingestion_pipeline/开发者视角.md) | [业务视角](./advanced_ingestion_pipeline/业务视角.md) | ✅ 已完成 |
| `chunk_summary.json` | [概览](./chunk_summary/概览.md) | [产品经理视角](./chunk_summary/产品经理视角.md) | [开发者视角](./chunk_summary/开发者视角.md) | [业务视角](./chunk_summary/业务视角.md) | ✅ 已完成 |
| `title_chunker.json` | [概览](./title_chunker/概览.md) | [产品经理视角](./title_chunker/产品经理视角.md) | [开发者视角](./title_chunker/开发者视角.md) | [业务视角](./title_chunker/业务视角.md) | ✅ 已完成 |

---

## 分析框架

每个模板拆分为三份独立文档，面向不同读者：

| 文档 | 面向读者 | 核心问题 |
|---|---|---|
| **产品经理视角** | 产品经理、业务负责人 | 解决谁的问题？边界在哪？怎么迭代？ |
| **开发者视角** | 技术负责人、工程师 | 架构怎么设计的？有哪些坑？怎么改造落地？ |
| **业务视角** | 销售、BD、决策者 | ROI 多少？卖给谁？怎么定价？有什么风险？ |

---

## 架构模式速查

| 模式 | 代表模板 | 核心节点组合 |
|---|---|---|
| **单 Agent + RAG** | technical_docs_qa | Begin → Retrieval → Agent → Message |
| **主控 + 嵌套子 Agent** | deep_research, generate_SEO_blog, deep_search_r | Lead Agent（tools=子Agent） |
| **多 Agent 串行** | market_generate_seo_blog, trip_planner | Agent1 → Agent2 → Agent3 |
| **Categorize 分流** | customer_service, ecommerce_customer_service | Begin → Categorize → 分支 Agent |
| **Iteration 批量** | cv_analysis | Begin → Iteration → Agent |
| **Switch 路由** | stock_research_report | Agent → Switch → 分支处理 |
| **UserFillUp 人机协作** | user_interaction | Begin → Agent → UserFillUp → Agent |
| **VLM 多模态** | image_lingo | Begin → Agent（visual_files_var） |
| **Text-to-SQL** | sql_assistant | Begin → Agent → ExeSQL → Agent |
| **Ingestion Pipeline** | advanced_ingestion_pipeline, chunk_summary, title_chunker | File → Parser → (Splitter) → Extractor/HierarchicalMerger → Tokenizer |

---

*最后更新：2026-04-03*
