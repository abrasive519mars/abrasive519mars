# Sai Saran Susarla

GenAI backend engineer. I build retrieval systems, LLM agents, and the evals that say whether they work.

**What I work on**

- RAG over documents with citations, measured on a fixed question set: recall@k, answer faithfulness, p50 latency, cost per query.
- Tool-calling agents over internal APIs with guardrails, typed errors and logging.
- Evaluation design: blinded LLM-judge panels, rank-AUC validation, distilled classifiers that replace LLM calls.

**Background**

- Amazon, SDE intern, Alexa: LLM content-validation system on Bedrock, rules stored as versioned data.
- Hivemind (fintech news), founding engineer: entity resolution over 14K companies at ~99% precision, a DistilBERT gate distilled from 5.2K LLM labels (recall 65% to 90% at 91% precision), a research agent with p50 latency down 57%.
- B.E. Electrical and Electronics, BITS Pilani Hyderabad, 2027.

Most of my production work lives in employer repos. The pinned projects are the public showcases.

**Pinned**

| Project | What it shows | Live |
|---|---|---|
| [rag-evals-demo](https://github.com/abrasive519mars/rag-evals-demo) | Grounded QA with citations over 759k MS MARCO passages; BM25, MiniLM over HNSW, reciprocal rank fusion and a cross-encoder reranker, each measured on 1,000 held-out queries with bootstrap intervals; answers graded by an independent judge | repo |
| [forensiq](https://github.com/abrasive519mars/forensiq) | Credit appraisal pipeline: document parsing, forensic checks, LightGBM + SHAP scoring, circular-trading graph detection | soon |
| [hybrid-search-engine](https://github.com/abrasive519mars/hybrid-search-engine) | BM25 + MiniLM/HNSW fused with reciprocal rank fusion on MS MARCO; Recall@10 0.825 to 0.890, MRR down 2.9%, measured over 200 queries | repo |
| [kindscore](https://github.com/abrasive519mars/kindscore) | Production Next.js app with Stripe payments, Supabase, Vitest and Playwright suites | [kindscore.vercel.app](https://kindscore.vercel.app) |
| [mini-gpt](https://github.com/abrasive519mars/mini-gpt) | 15.8M-parameter GPT written from scratch in PyTorch: causal multi-head attention, weight-tied head, AMP training, val loss 1.76 | repo |


**Contact**: [LinkedIn](https://www.linkedin.com/in/saran-susarla)

<!-- Optional stats card. Only counts private contributions after the GitHub setting "Include private contributions on my profile" is on. -->
<!-- ![stats](https://github-readme-stats.vercel.app/api?username=abrasive519mars&show_icons=true&count_private=true&hide=stars,issues&hide_title=true) -->
