# 🔑 KeyB2: Long Document Ranking with Block Selection

**KeyB2** is a long document ranking method designed to enhance the efficiency and effectiveness of LLM-based reranking by selecting the most relevant document blocks.

## 📊 Quick Evaluation (TREC DL 2019)

To evaluate the ranking results on the **TREC DL 2019 document ranking** dataset using `pyserini`, run the following command:

```bash
python -m pyserini.eval.trec_eval -c -m ndcg_cut.10 -m map dl19-doc ${rerankBaseName}.trec

Code and other rerank files will be updated later.
