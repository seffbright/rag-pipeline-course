
---

# 📄 `docs/concepts/rag.md`

```md
# What is Retrieval-Augmented Generation (RAG)?

Retrieval-Augmented Generation (RAG) is a technique that combines:

- **Information Retrieval** (searching documents)
- **Large Language Models** (generating answers)

Instead of relying only on a model’s training data, RAG systems **retrieve relevant documents at query time** and use them as context.

---

## Why RAG Exists

LLMs alone have limitations:
- Knowledge can be outdated
- No access to private/internal data
- Hallucinations when unsure

RAG solves this by grounding responses in **real, retrieved information**.

---

## High-Level RAG Flow

1. User asks a question
2. Question is converted into an embedding
3. Similar documents are retrieved from a vector database
4. Retrieved content is passed to the LLM
5. The model generates a grounded response

---

## When to Use RAG

RAG is ideal for:
- Internal knowledge bases
- Customer support automation
- Documentation search
- Enterprise Q&A systems

---

👉 **Next:** [Embeddings](embeddings.md)
