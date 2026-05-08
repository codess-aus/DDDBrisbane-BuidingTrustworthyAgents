# Chapter 16: Robust Agents Under Uncertainty

![Image 16 - Ethical](../images/16.%20Ethical.png)

## Overview

Agents will face incomplete information, contradictory signals, and shifting objectives: conditions where humans themselves struggle.

Trustworthy systems are not built on the assumption that conditions are always clean and predictable. They are built to stay safe and useful when reality is messy.

### Failover Strategies

For critical processes, agents should degrade gracefully or escalate to a human-in-the-loop rather than make brittle or catastrophic decisions.

Design patterns include:

- **Safe Fallback Modes**: Switch to limited capability when confidence is low
- **Human Escalation Paths**: Route high-impact or ambiguous decisions to people
- **Stop Conditions**: Refuse to act when required evidence is missing

### Robustness Testing

Agents should be tested with the same rigor as disaster recovery drills.

Test beyond happy paths:

- **Edge Cases**: Rare but plausible operational scenarios
- **Adversarial Inputs**: Prompts designed to break policy or behavior
- **Unknown Unknowns**: Stress tests that expose hidden failure modes

### Continuous Learning Loops

Real-world feedback must be a core design principle, not an optional add-on.

Agents should learn from:

- **Past Errors**
- **User Corrections**
- **Operational Incidents**

This creates a closed-loop system that improves over time instead of relying only on periodic retraining over static datasets.

## Resources and Further Reading

### Online Resources
- 🌐 [Architect resilient systems in Azure](https://learn.microsoft.com/en-us/azure/well-architected/reliability/)
- 🌐 [Build and evaluate AI apps in Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/)
- 🌐 [Prompt Shields and safety controls](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection)
## Next Steps

Continue your learning journey:

[← Chapter 15](chapter-15.md) | [Chapter 17 →](chapter-17.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/DDDBrisbane-BuidingTrustworthyAgents) or connect with the community.

