# Chapter 19: Measuring Generative AI Systems

![Image 19 - Measure](../images/19.%20Measure.png)

## Overview

Evaluating generative AI systems can be challenging.

In traditional machine learning, teams often optimize one headline metric, such as accuracy. Accuracy is straightforward to compute: correct predictions divided by total predictions.

With generative AI, accuracy may still matter when ground truth exists, but it is rarely sufficient on its own.

### Why GenAI Evaluation Is Harder

Generative outputs are open-ended. Teams often need to evaluate dimensions such as:

- **Fairness**
- **Groundedness in source data**
- **Grammatical quality and coherence**
- **Safety and policy adherence**

This is more complex than a single accuracy score.

### Test Data Quality Challenges

High-quality evaluation depends on high-quality test data.

You may already have useful datasets, such as common customer questions and expected responses from business teams. But many organizations lack robust edge-case datasets, including prompts that reflect the latest jailbreak techniques and adversarial behavior.

### Explainability for Debugging and Decisions

Another core challenge is explainability.

To make data-driven development decisions and debug effectively, teams need to understand why a model or application received a particular score. Without this visibility, metric values are hard to trust and hard to act on.

### Repeatable and Transparent Evaluation in Azure

At Microsoft, solving these evaluation challenges was essential for systematically validating copilots before production deployment.

Azure AI now provides a robust toolkit to evaluate generative AI in a repeatable, transparent way, helping teams move from ad hoc checks to disciplined measurement.

## Resources and Further Reading

### Online Resources
- 🌐 [Evaluate generative AI models and applications](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluate-generative-ai-app)
- 🌐 [Cloud evaluations in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/cloud-evaluation)
- 🌐 [Develop a quality and safety eval strategy](https://learn.microsoft.com/en-us/training/paths/evaluate-generative-ai-apps/)

## Next Steps

Continue your learning journey:

[← Chapter 18](chapter-18.md) | [Chapter 20 →](chapter-20.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/DDDBrisbane-BuidingTrustworthyAgents) or connect with the community.

