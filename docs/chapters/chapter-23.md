# Chapter 23: Risk Mitigation Layers

![Image 23 - Defence in depth](../images/23.%20Defence%20in%20depth.png)

## Overview

We find that most production applications require a mitigation plan with four layers of technical mitigations: (1) the model, (2) safety system, (3) system message and grounding, and (4) user experience layers.

The model and safety system layers are typically platform layers, where built-in mitigations would be common across many applications. They are built into Azure for you.

The next two layers largely depend on the application's purpose and design, meaning the implementation of mitigations can vary a lot from one application to the next.

Note that, while the foundation model you're using is obviously an important component of the system, it's not the complete system.

### The Four Layers of Defense

Effective mitigation requires defense in depth across all layers:

**Layer 1 - Model**: Choose models with built-in safety training (GPT-4, GPT-4o)
**Layer 2 - Safety System**: Azure AI Content Safety filters for inputs and outputs
**Layer 3 - Application**: System prompts, grounding with Azure AI Search, function calling constraints
**Layer 4 - User Experience**: Disclaimers, rate limiting, human review workflows, feedback mechanisms

### Azure's Built-in Defense Layers

Azure AI Foundry provides Layers 1 and 2 out of the box:

- **Safety-Trained Models**: All Azure OpenAI models include safety training
- **Content Safety Service**: Configurable filters integrated directly into endpoints
- **Automatic Monitoring**: Built-in tracking of content safety violations
- **Regional Compliance**: Data residency and regulatory compliance built-in

Layers 3 and 4 are application-specific, but Azure provides the tools: prompt templates, Azure AI Search for grounding, and APIs for building custom UX controls. Defense in depth isn't just theory—it's operationalized in Azure's architecture.

### Online Resources

- 🌐 [Measure and mitigate risks for a generative AI app in Azure AI Foundry](https://learn.microsoft.com/en-us/training/modules/measure-mitigate-risks-azure-ai-studio/)


## Next Steps

Continue your learning journey:

[← Chapter 22](chapter-22.md) | [Chapter 24 →](chapter-24.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

