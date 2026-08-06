# Hi, I'm Rehan 👋

AI engineer focused on **LLM evaluation, RAG systems, and fine-tuning**. I find bugs by running tools against real workloads — twice now in eval libraries used in production.

## Open-source contributions

| Project | Contribution |
|---|---|
| **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** | ✅ **Merged** — [#14995](https://github.com/Arize-ai/phoenix/pull/14995) `fix(traces): render ReasoningPart in gen_ai message flattening` |
| **[Braintrust autoevals](https://github.com/braintrustdata/autoevals)** | [PR #209](https://github.com/braintrustdata/autoevals/pull/209) — `AnswerRelevancy` silently ignores `embedding_model` · [Issue #211](https://github.com/braintrustdata/autoevals/issues/211) — cross-model embedding-cache poisoning. Both found by running autoevals against my own RAG eval harness. |

## Projects

### [PeatLearn](https://github.com/spacesheepinternet/PeatLearn) — grounded biomedical RAG · [live site](https://peatlearn.com)

Citation-backed RAG chatbot over a 552-document biomedical corpus. Embedding model fine-tuned with hard-negative mining, tiered data-cleaning pipeline, LLM-as-judge eval harness scoring **9.64/10** answer quality, ~$0.008/query in production.

### [metal-llm](https://github.com/spacesheepinternet/metal-llm) — LLM-generated guitar tablature

Fine-tuning a small LLM to write heavy-metal guitar tab (DadaGP token format) — QLoRA on 8 GB VRAM. Built a before/after eval suite (validity, decodability, novelty): tab validity **2.1% → 99.5%** over the base model. Pilot adapter on [Hugging Face](https://huggingface.co/spacesheepinternet/metal-llm-pilot). Includes an audio demo where the model continues a real intro into an original solo.

---

📫 Open to early-career AI/ML engineering roles — evals, RAG, LLM tooling.
