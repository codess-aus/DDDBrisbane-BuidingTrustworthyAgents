# Chapter 9: Retrieval-Augmented Generation (RAG) in Practice

![Image 9 - RAG](../images/9.%20RAG.png)

## Overview

RAG combines the power of large language models with external knowledge sources. Instead of relying only on model training knowledge, the system retrieves relevant documents at runtime and uses them to ground its answer.

### Why RAG Matters

RAG is one of the most practical patterns for trustworthy agent systems because it:

- **Reduces Hallucinations** by grounding answers in retrieved evidence
- **Keeps Information Current** by using up-to-date data sources rather than static model memory
- **Enables Domain-Specific Knowledge** by connecting to enterprise repositories, policies, and operational documentation

### Core RAG Flow

Most RAG systems follow a repeatable flow:

1. Receive the user query
2. Retrieve relevant chunks from approved knowledge sources
3. Inject context into the prompt
4. Generate a grounded response
5. Optionally include citations so users can verify the answer

### Design Considerations for Trustworthy RAG

To improve reliability and trust, define these decisions explicitly:

- Which sources are allowed as system-of-record knowledge
- Whether internet retrieval is enabled or blocked
- When the model should abstain instead of guessing
- How references are surfaced to users

RAG is not just a performance technique; it is a governance and trust technique.

## Resources and Further Reading

### Online Resources
- 🌐 [Retrieval Augmented Generation pattern](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/rag/rag-pattern)
- 🌐 [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- 🌐 [Build a RAG solution](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)


## Next Steps

Continue your learning journey:

[← Chapter 8](chapter-08.md) | [Chapter 10 →](chapter-10.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

