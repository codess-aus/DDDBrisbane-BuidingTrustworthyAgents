# Chapter 22: Mitigation Tools  

![Image 22 - Mitigation Tools](../images/22.%20Mitigation%20Tools.png)  

## Overview

Now that we've identified potential risks, we can implement ways to mitigate.

### Mitigation Strategy

After mapping harms and measuring their presence, mitigation becomes systematic:

- **Layer Defenses**: Apply multiple mitigation layers (model, safety system, prompt, UX)
- **Prioritize by Impact**: Focus on high-severity, high-probability risks first
- **Test Effectiveness**: Measure whether mitigations actually reduce harm
- **Iterate**: Refine mitigations based on ongoing evaluation results
- **Document Decisions**: Maintain clear records of what was mitigated and why

### Azure AI Foundry Mitigation Tools

Azure provides comprehensive mitigation capabilities across all layers:

- **Model Selection**: Choose models with built-in safety training
- **Content Safety**: Configurable filters for inputs and outputs
- **Prompt Engineering**: System message templates with safety guidelines
- **Grounding**: RAG with Azure AI Search to reduce hallucinations
- **UX Controls**: Rate limiting, disclaimers, human-in-the-loop

With Azure AI Foundry and GitHub working together, you can implement, test, and deploy mitigations confidently—knowing that each layer is measurable, auditable, and continuously improvable.

## Next Steps

Continue your learning journey:

[← Chapter 21](chapter-21.md) | [Chapter 23 →](chapter-23.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

