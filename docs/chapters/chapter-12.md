# Chapter 12: Manual and automated evaluations.

![Image 12 - Measure](../images/12.%20Measure.png)  

## Overview

You can thoroughly assess the performance of your generative AI application by applying it to a substantial dataset. Evaluate the application in your development environment with the Azure AI Evaluation SDK.

When you provide either a test dataset or a target, your generative AI application outputs are quantitatively measured with both mathematical-based metrics and AI-assisted quality and safety evaluators. Built-in or custom evaluators can provide you with comprehensive insights into the application's capabilities and limitations.

### Manual and Automated Evaluation Approaches

Effective evaluation combines human judgment with automated measurement:

- **Manual Evaluation**: Human graders assess outputs for nuanced quality factors
- **Automated Metrics**: Mathematical measures (F1, BLEU) and AI-assisted evaluators (groundedness, relevance)
- **Iterative Testing**: Start manual, scale to automated once patterns emerge
- **Domain Expertise**: Involve subject matter experts for specialized applications

### Azure AI Evaluation SDK

The Azure AI Evaluation SDK provides comprehensive evaluation capabilities:

- **Built-in Evaluators**: Groundedness, relevance, coherence, fluency, safety metrics
- **Custom Evaluators**: Define domain-specific quality criteria
- **Batch Evaluation**: Test against large datasets locally or in the cloud
- **Integration**: Works seamlessly with Azure AI Foundry and GitHub workflows

Manual evaluation builds intuition; automated evaluation provides scale. Together, they give you confidence that your AI system performs reliably before it reaches users.

### Online Resources
- 🌐 [Evaluate your generative AI application locally with the Azure AI Evaluation SDK](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/evaluate-sdk)

## Next Steps

Continue your learning journey:

[← Chapter 11](chapter-11.md) | [Chapter 13 →](chapter-13.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

