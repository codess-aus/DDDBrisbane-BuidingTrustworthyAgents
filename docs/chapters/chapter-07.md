# Chapter 7: Reliability under Uncertainty  

![Image 7 - Reliability](../images/7.%20Reliability.png)  

## Overview

Enterprises operate under constraints like regulatory, legal, reputational. Agents must embody those boundaries.

How is this enforced?

**Policy Codification**: Encode company policies and ethical rules as first-class constraints in the agent's reasoning engine. For example: "Never approve spend above $10,000 without two signatures," or, "Never share PII outside the EU."

**Dynamic Policy Updates**: As regulations evolve, agents must be able to adapt without wholesale retraining. This demands modular architectures, where policy layers are abstracted from underlying ML models.

**Human Override**: At all times, ensure a path for human intervention and override. Trust is built not just on autonomy, but on the assurance that control can be regained.

### Building Reliable AI Under Uncertainty

Azure AI Foundry enables reliability through built-in safeguards and monitoring:

- **Confidence Thresholds**: Configure agents to escalate when certainty drops below acceptable levels
- **Fallback Mechanisms**: Implement graceful degradation with Azure Functions and Logic Apps
- **Real-time Monitoring**: Track performance metrics with Azure Monitor and Application Insights
- **Version Control**: Use GitHub to manage policy updates alongside code changes

Reliability isn't about perfection—it's about knowing your system's limits, designing for graceful failures, and maintaining human oversight when stakes are high. Azure and GitHub provide the infrastructure to build systems that stay reliable even when the world stays uncertain.

## Resources and Further Reading

### Online Resources
- 🌐 [Human-in-the-loop](https://learn.microsoft.com/en-us/semantic-kernel/frameworks/process/examples/example-human-in-loop)  
- 🌐 [Build AI Agents in Azure Logic Apps](https://techcommunity.microsoft.com/blog/integrationsonazureblog/%F0%9F%93%A2announcing-agent-loop-build-ai-agents-in-azure-logic-apps-%F0%9F%A4%96/4415052)  

## Next Steps

Continue your learning journey:

[← Chapter 6](chapter-06.md) | [Chapter 8 →](chapter-08.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

