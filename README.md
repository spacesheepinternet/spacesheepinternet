# Hi, I'm Rehan 👋

AI engineer focused on **LLM evaluation, RAG systems, and fine-tuning**. I find bugs by running tools against real workloads, then fix them upstream — three merged into libraries that ship in production.

## Open-source contributions

| Project | Contribution |
|---|---|
| **[Haystack](https://github.com/deepset-ai/haystack)** | ✅ **Merged** — [#12726](https://github.com/deepset-ai/haystack/pull/12726) `fix: strip UTF-8 BOM in text, CSV, Markdown and JSON converters`. A BOM-prefixed file silently carried a zero-width `U+FEFF` into the first `Document`. Reviewed across five rounds by a deepset maintainer. |
| **[Arize Phoenix](https://github.com/Arize-ai/phoenix)** | ✅ **Merged** — [#14995](https://github.com/Arize-ai/phoenix/pull/14995) `fix(traces): render ReasoningPart in gen_ai message flattening` |
| **[pydantic-ai](https://github.com/pydantic/pydantic-ai)** | ✅ **Merged** — [#7290](https://github.com/pydantic/pydantic-ai/pull/7290), written from my [issue #7281](https://github.com/pydantic/pydantic-ai/issues/7281) and verified on Windows at the maintainer's request |
| **[Braintrust autoevals](https://github.com/braintrustdata/autoevals)** | [PR #209](https://github.com/braintrustdata/autoevals/pull/209) — `AnswerRelevancy` silently ignores `embedding_model` · [Issue #211](https://github.com/braintrustdata/autoevals/issues/211) — cross-model embedding-cache poisoning. Both found by running autoevals against my own RAG eval harness. |

## Projects

### [PeatLearn](https://github.com/spacesheepinternet/PeatLearn) — grounded biomedical RAG · [live site](https://peatlearn.com)

Citation-backed RAG chatbot over a 552-document biomedical corpus. Multi-stage retrieval (HyDE → two-pass Pinecone → reranking, with a cross-encoder fine-tuned on hard-negative-mined pairs), tiered data-cleaning pipeline, LLM-as-judge eval harness scoring **9.64/10** answer quality, ~$0.008/query in production.

### [metal-llm](https://github.com/spacesheepinternet/metal-llm) — LLM-generated guitar tablature

Fine-tuning a small LLM to write heavy-metal guitar tab (DadaGP token format) — QLoRA on 8 GB VRAM. Built a before/after eval suite (validity, decodability, novelty): tab validity **2.1% → 99.5%** over the base model. Pilot adapter on [Hugging Face](https://huggingface.co/spacesheepinternet/metal-llm-pilot). Includes an audio demo where the model continues a real intro into an original solo.

---

📫 Open to early-career AI/ML engineering roles — evals, RAG, LLM tooling.
