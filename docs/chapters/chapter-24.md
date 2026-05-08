# Chapter 24: Azure AI Content Safety  

![Image 24 - Content Safety](../images/24.%20Content%20Safety.png)

## Overview  

But choosing a great base model is just the first step. For most applications, it’s not enough to rely on the safety mitigations built into the model itself. 
Even with fine-tuning, LLMs can make mistakes and are susceptible to attacks like jailbreaks.
So, just like security, at Microsoft we use a layered defense-in-depth approach. 
And we apply an AI-based safety system that goes around the model and monitors the inputs and outputs to help prevent attacks from being successful and catches places where the model makes a mistake.
At Microsoft, this state-of-the-art safety system is called Azure AI Content Safety.
And the filters are configurable for inputs and outputs… because you might want different settings for your use case. For example, a gaming company may be more permissive of violent language in inputs but may not want to output violent language to users.
We’ve integrated this service directly into our Microsoft Copilot ecosystem as a built-in safety system, 
and we make the same technology available to developers via Azure AI to help them build safer AI applications from the start.


There are three types of filters offered by Azure AI Content Safety.
We provide configurable content filters for harmful content, like text and imagery containing violence or hate speech, which you can adjust by severity level. These are always set to a medium threshold by default. 
Customers can also create their own custom content filters using small training datasets.
Prompt shields are detection models that can be turned on for model inputs, to detect when a user is trying to attack or manipulate the AI system into doing something outside it’s intended purpose or design.
Lastly, we have detection models that can be turned on to flag other kinds of risky inputs or outputs, such as protected or copyright material or code, or hallucinations, where the model output does not align to the source material provided.
Customers can also create custom blocklists to filters specific terms in inputs or outputs.

Azure AI Content Safety detects harmful user-generated and AI-generated content in applications and services. The features in Azure AI Content Safety can help make sure that product reviews, forum posts, and images align with Contoso Camping Store's content guidelines.

Azure AI Content Safety offers a suite of features for monitoring and moderating content in real time:
Text moderation: Detects and filters out harmful content in text, such as hate speech, violence, or inappropriate language.
Image moderation: Analyzes images to identify and block content that might be considered unsafe or offensive.
Multimodal content analysis: Works across various types of content to help ensure a comprehensive strategy for content safety.
Groundedness detection: Detects and blocks incorrect information in model outputs. It helps ensure that the text responses of large language models are factual and accurate, based on the provided source materials.
Prompt shields: Analyze large language model (LLM) inputs to detect user prompt attacks and document attacks.
Protected material detection: Identifies and blocks outputs that could potentially violate copyrights. It scans for matches against an index of third-party text content, including songs, news articles, recipes, and selected web content.

These features are built on AI models that can detect a wide range of potential risks, threats, and quality problems.

Every harm category that the service applies also has a severity level. The severity level indicates the severity of the consequences of showing the flagged content.
The severity scale ranges from 0 to 7. The text model supports both the full scale of 0 to 7 and a trimmed scale of 0, 2, 4, and 6. The current version of the image model supports only the trimmed scale.


## Resources and Further Reading

- 🌐 [Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/)


## Next Steps

Continue your learning journey:

[← Chapter 23](chapter-23.md) | [Chapter 25 →](chapter-25.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

