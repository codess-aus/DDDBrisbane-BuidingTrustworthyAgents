# Chapter 8: Knowledge Bases and Grounded Responses

![Image 8 - Knowledge Base](../images/8.%20KB.png)

## Overview

The knowledge base stores information your agent can access to provide accurate and relevant responses. Designing this layer is one of the most important decisions in trustworthy agent architecture.

### Knowledge Base Building Blocks

Most production systems combine multiple storage patterns:

- **Vector Databases** for semantic search across meaning, not just keywords
- **Document Stores** for structured and semi-structured operational information
- **Graph Databases** for relationship mapping between entities, events, and concepts
- **Cache Layers** for performance optimization and faster response times

### Source of Truth Decisions

Before deployment, define clear boundaries for where your agent is allowed to get information:

- Should it only use approved company data sources as the source of truth?
- Must it cite references from those approved sources?
- Can it access the public internet?
- Can it rely on model training knowledge when no retrieved evidence exists?

These decisions directly shape risk, compliance, reliability, and user trust.

### Creativity vs Grounded Facts

Another key design choice is whether the agent should:

- Stay strictly grounded in retrieved evidence (cold, hard facts)
- Make reasonable assumptions and creative inferences when evidence is incomplete

Greater creativity can improve user experience and ideation, but it can also increase hallucination risk. Trustworthy systems set this behavior intentionally rather than by accident.

### Controls You Can Tune

These behaviors are controllable in your architecture and prompts:

- **System Prompts**: Define hard rules for retrieval, citation, and refusal behavior
- **Temperature**: Lower values for determinism and factual consistency, higher for creativity
- **Top-p**: Adjust token sampling diversity to control response variability

Strong agent design combines retrieval policy, prompt policy, and model settings so responses are both useful and appropriately grounded.

## Resources and Further Reading

### Online Resources
- 🌐 [Retrieval Augmented Generation pattern](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/guide/rag/rag-pattern)
- 🌐 [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- 🌐 [Prompt engineering techniques](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering)


## Next Steps

Continue your learning journey:

[← Chapter 7](chapter-07.md) | [Chapter 9 →](chapter-09.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

