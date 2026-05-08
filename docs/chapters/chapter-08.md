# Chapter 8: Security as Core Design, Not Perimeter Defence  

![Image 8 - Security](../images/8.%20Security.png)  


## Overview

Agents will interact with sensitive data, make financial transactions, and initiate workflows. The attack surface increases exponentially as agency increases.

### Security-First Agent Design

Modern AI security goes beyond perimeter defenses—it requires security embedded at every layer:

- **Principle of Least Privilege**: Limit the scope of what an agent can do. Start with minimal permissions, expand as proven trustworthy.
- **Identity & Access Management**: Every agent must have an immutable identity and verifiable credentials. Actions must be signed and attributable.
- **Real-time Threat Detection**: Agents should be able to detect and respond to anomalous behavior, their own and others'. Self-awareness of compromise is as vital as external defenses.

### Azure Security for AI Systems

Azure AI Foundry and Microsoft's Secure Future Initiative provide comprehensive security:

- **Managed Identity**: Use Azure AD to authenticate agents without credentials in code
- **Content Safety**: Built-in protection against prompt injection and jailbreak attempts
- **Network Isolation**: Deploy models in VNets with private endpoints for data residency
- **Threat Intelligence**: Integrate Azure Sentinel for real-time anomaly detection
- **Secret Management**: Store API keys and credentials in Azure Key Vault

With GitHub Advanced Security scanning your code and Azure securing your infrastructure, you build AI systems where security is core design, not perimeter defense.

## Resources and Further Reading

### Online Resources
- 🌐 [Principle of Least Privilege](https://learn.microsoft.com/en-us/entra/identity-platform/secure-least-privileged-access)  
- 🌐 [Identity & Access Management](https://learn.microsoft.com/en-us/credentials/certifications/identity-and-access-administrator)  
- 🌐 [Real time threat detection](https://learn.microsoft.com/en-us/defender-office-365/threat-explorer-real-time-detections-about)  


## Next Steps

Continue your learning journey:

[← Chapter 7](chapter-07.md) | [Chapter 9 →](chapter-09.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

