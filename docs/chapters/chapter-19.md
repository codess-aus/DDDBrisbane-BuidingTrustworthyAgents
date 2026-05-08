# Chapter 19: AI red teams uncover and identify risks  


![Image 19 - Red Team](../images/19.%20Red%20Team.png)  

## Overview

When GPT-4 first came out, Microsoft brought together a group of experts to test the technology and understand what the potential benefits were. We also started digging into the potential risks that we would need to mitigate.

Our process looks like this.

First, we start with a manual approach where we bring together both experts who are coming in and trying to break the system through more sophisticated techniques, which is what we call red teaming, but also people who are just representing average users to help stress test the system.

And we have this diverse team manually probe the model or application - we have them look at different types of topics or different types of harms or risk and prioritize and probe the system for those.

Then we look at those results, look at the patterns where the system is still failing, and we use that to improve our mitigations and our evaluations.

When we're shipping an AI model or application, we have week over week sprints of this manual testing process, and we use that to make our system better.

We acknowledge that not every company has the resources or expertise to red team generative AI models and systems.

That's why we do it—thoroughly--and we pour our learnings directly into the Azure AI platform for you.

### The Microsoft Red Team Process

Microsoft's approach combines expert adversarial testing with iterative improvement:

- **Diverse Team Assembly**: Security experts, domain specialists, and representative users
- **Systematic Probing**: Test across harm categories and use case scenarios
- **Pattern Analysis**: Identify common failure modes from test results
- **Mitigation Development**: Build defenses based on discovered vulnerabilities
- **Weekly Iteration**: Continuous red team sprints during development

### Red Team Learnings in Azure

Microsoft's red team findings are built into Azure AI Foundry:

- **Content Safety Filters**: Trained on adversarial attack patterns
- **Evaluation Metrics**: Test for known vulnerability classes
- **PyRIT Framework**: Microsoft's red team tools available to all developers
- **Best Practice Guidance**: Documentation informed by production red team experience

You benefit from Microsoft's investment in red teaming—the patterns we discover, the mitigations we develop, and the tools we build all flow into Azure AI Foundry.

## Resources and Further Reading### Online Resources  

- 🌐 [Microsoft AI Red Team](https://learn.microsoft.com/en-us/security/ai-red-team/)  
- 🌐 [Red Teaming](https://learn.microsoft.com/en-us/azure/ai-foundry/openai/concepts/red-teaming)  
- 🌐 [AI Red Teaming Agent](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/ai-red-teaming-agent)  

## Next Steps

Continue your learning journey:

[← Chapter 18](chapter-18.md) | [Chapter 20 →](chapter-20.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

