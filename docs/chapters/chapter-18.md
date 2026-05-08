# Chapter 18: Automated evaluation metrics in Azure AI Foundry  

![Image 18 - Auto Eval](../images/18.%20Auto%20Eval.png)  

## Overview

We support two types of automated evaluation metrics with low-code and code-first paths.

In the context of generative AI, traditional ML metrics are useful when we want to quantify the accuracy of generated outputs compared to expected answers. For instance, in tasks such as classification or short-form question-answering, where there's typically one correct or expected answer, F1 scores can be used to measure the precision and recall of generated outputs against the expected answers, otherwise known as your golden dataset.

AI-assisted metrics can be beneficial in scenarios where ground truth and expected answers aren't available, such as open-ended question answering or creative writing.

We support pre-built metrics for quality such as groundedness, relevance, and fluency.

We also support pre-built metrics for Risk and Safety, so you can measure how frequently your app is generating problematic content, such as hateful or violent content, as well as how susceptible it is to jailbreak attacks.

### Evaluation Metric Types in Azure AI Foundry

Azure provides two complementary approaches to automated evaluation:

- **Traditional ML Metrics**: F1 score, precision, recall, BLEU, ROUGE (when ground truth exists)
- **AI-Assisted Quality Metrics**: Groundedness, relevance, coherence, fluency (for open-ended outputs)
- **Safety Metrics**: Hate speech, violence, self-harm, sexual content detection
- **Security Metrics**: Jailbreak susceptibility, prompt injection detection

### Code-First and Low-Code Paths

Azure AI Foundry supports both development approaches:

- **Azure AI Evaluation SDK**: Python-based evaluation for code-first developers
- **Azure AI Foundry Portal**: No-code evaluation UI for quick testing
- **GitHub Integration**: Run evaluations in CI/CD pipelines
- **Custom Evaluators**: Define your own metrics using Python or AI-assisted approaches

With Azure's comprehensive evaluation metrics, you can measure what matters for your application—from technical accuracy to user safety—all within a unified framework.

## Resources and Further Reading  

You can also define your own custom metrics to run more tailored evaluations for your use case.  


## Resources and Further Reading  

### Online Resources  

- 🌐 [Evaluate generative AI models and applications by using Azure AI Foundry](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluate-generative-ai-app)  
- 🌐 [See evaluation results in the Azure AI Foundry portal](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/evaluate-results)  


## Next Steps

Continue your learning journey:

[← Chapter 17](chapter-17.md) | [Chapter 19 →](chapter-19.md)

---

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

