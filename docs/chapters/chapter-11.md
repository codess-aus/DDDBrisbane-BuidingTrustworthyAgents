# Chapter 11: Identifying Harms 

![Image 11 - Harms](../images/11.%20Harms.png)  

## Overview

Facing the Shadows – Identifying Harms

"Before you build, you must know what could go wrong."

So what type of risks do we see most often in generative AI systems?

The first category of risk is overall quality of the application.

We want to ensure that the application is not producing errors or what people often call hallucinating, which would be like adding additional incorrect information or just sort of making up information.

We also need to make sure that our system is robust to adversarial attacks.

This could be a jailbreak, which is when a user tries to manipulate or confuse the system to get it to produce something that it's not supposed to produce, or new types of attacks where an attacker embeds hidden instructions in data sources like emails or documents.

We also look at traditional harmful content, whether that is harmful natural language content, for example, or harmful imagery or code that contains security vulnerabilities.

Then one of the newer areas that's emerging is that these models can seem very human-like when interacting with end users.

When is it okay for a system to be conversing and acting like a human? And when is that going to be misleading, inappropriate, or harmful?

### Common Risk Categories in Generative AI

Understanding potential harms is the first step toward building safe systems:

- **Quality Risks**: Hallucinations, factual errors, irrelevant responses
- **Safety Risks**: Harmful content (hate speech, violence, self-harm)
- **Security Risks**: Prompt injection, jailbreaks, data leakage
- **Fairness Risks**: Biased outputs, stereotyping, exclusionary language
- **Anthropomorphism Risks**: Misleading human-like behavior

### Mapping Harms with Azure AI Foundry

Azure AI Foundry provides structured approaches to harm identification:

- **Risk Assessment Templates**: Start with Microsoft's pre-built risk taxonomies
- **Use Case Analysis**: Map specific risks to your application's context
- **Stakeholder Input**: Gather diverse perspectives on potential impacts
- **Red Team Planning**: Prepare adversarial test scenarios based on identified risks

This "Map" phase is critical—you can't measure or mitigate what you haven't identified. Azure AI Foundry's responsible AI tools guide you through systematic harm identification before development begins.

## Resources and Further Reading  

So, you need to be looking across all of these different dimensions, which may sound like a lot, but we’ve found that same technological approach works for each of these different types of attacks.


## Resources and Further Reading

### Online Resources
- 🌐 [Defence in Depth and Zero Trust](https://learn.microsoft.com/en-us/training/modules/describe-security-concepts-methodologies/)  


## Next Steps

Continue your learning journey:

[← Chapter 10](chapter-10.md) | [Chapter 12 →](chapter-12.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

