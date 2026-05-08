# Chapter 26: Layered Safety with Azure AI Content Safety

![Image 26 - Content Safety](../images/26.%20Content.png)

## Overview

Choosing a strong base model is only the first step. For most real-world applications, it is not enough to rely only on built-in model safeguards.

Even with fine-tuning, LLMs can still make mistakes and remain susceptible to attacks such as jailbreak attempts.

That is why Microsoft uses a defense-in-depth approach for AI systems, similar to modern cybersecurity architecture. An AI safety layer sits around the model and monitors both inputs and outputs to reduce successful attacks and catch unsafe or low-quality responses.

At Microsoft, this state-of-the-art safety layer is Azure AI Content Safety. The same technology used in Microsoft Copilot is available to developers through Azure AI.

### Configurable Safety Controls by Use Case

Safety controls are configurable for both input and output because acceptable risk varies by scenario.

Example:

A gaming company may allow more violent language in user inputs but still block violent language in model outputs.

This flexibility enables teams to meet business needs while staying within policy and safety boundaries.

### Three Core Filter Categories

Azure AI Content Safety provides three core filter categories:

1. **Configurable Content Filters**
Detect harmful text and imagery such as hate or violence, with adjustable severity thresholds. Default thresholds are set to medium.

2. **Prompt Shields**
Detection models for model inputs that identify prompt attacks and manipulation attempts, including document attacks.

3. **Risk Detection Models**
Models that flag additional risky outputs, including protected material, protected code, and hallucinations where output is not aligned with source material.

Teams can also create custom content filters using small training datasets and define custom blocklists for domain-specific terms.

### Moderation and Quality Features

Azure AI Content Safety supports real-time monitoring and moderation for applications and services:

- **Text Moderation**: Detect and filter hate, violence, and other unsafe language
- **Image Moderation**: Analyze images for unsafe or offensive content
- **Multimodal Analysis**: Apply safety controls across different content types
- **Groundedness Detection**: Flag responses that are not supported by provided source material
- **Protected Material Detection**: Detect outputs that may violate copyright against third-party content indexes

These capabilities help ensure user-generated and AI-generated content aligns with organizational guidelines.

### Severity Levels and Tuning

Each harm category includes a severity level that indicates the seriousness of showing flagged content.

- Severity scale ranges from 0 to 7
- Text models support both full scale (0-7) and trimmed scale (0, 2, 4, 6)
- Current image models support the trimmed scale

This severity framework allows safety policies to be tuned precisely to context, risk appetite, and compliance requirements.

## Resources and Further Reading

### Online Resources
- 🌐 [What is Azure AI Content Safety?](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview)
- 🌐 [Content Safety concepts and categories](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/harm-categories)
- 🌐 [Prompt Shields documentation](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection)
- 🌐 [Groundedness detection](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/groundedness)

## Next Steps

Continue your learning journey:

[← Chapter 25](chapter-25.md) | [Chapter 27 →](chapter-27.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

