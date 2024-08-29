**Measure**

Once a list of prioritized harms has been identified, the next stage involves developing an approach for systematic measurement of each harm and conducting evaluations of the AI system. 
The measurement stage provides crucial information for steering development toward quality and safety. This measurement stage provides practitioners with signals that inform targeted mitigation steps such as prompt engineering and the application of content filters. Once mitigations are applied, one can repeat evaluations to test effectiveness.

There are manual and automated approaches to measurement. We recommend you do both, starting with manual measurement.
 
Manual measurement for small set of dataset until evidence of the risks is no longer observed  before moving to automated evaluation. Azure AI studio provides an easy no-code interface for developers or domain experts to grade model outputs.

Automated evaluation is useful for measuring quality and safety at scale with increased coverage to provide more comprehensive results. Automated evaluation tools also enable ongoing evaluations that periodically run to monitor for regression as the system, usage, and mitigations evolve. 

Performing Ongoing measurement is crucial for any regression as the system, usage evolves.
Make sure to measure the degree of severity of each potentially harmful content
 
Metric and Measurement sets should be continued to refined.

You can use, 
Prompt flow for built-in or custom evaluations
I highly recommend you go through the AI-assisted evaluation in Azure AI studio. I have provided links to all these tools. You will be able to see the input, output, and then the scoring across various metrics. We can even click into the reasoning provided for each score by the model. As a best practice, we recommend looking closely at a handful of these scores to make sure it aligns with your expectations.
You can even provide feedback so you can track where an evaluator may need adjustments to its scoring rubric to align with your expectations.

The goal with all of this is to make your evaluation results interpretable and actionable.

Resources:
1. <a href="https://learn.microsoft.com/en-us/azure/machine-learning/prompt-flow/how-to-bulk-test-evaluate-flow?view=azureml-api-2" style="text-decoration: underline;">Prompt flow</a>
2. <a href="https://learn.microsoft.com/en-us/azure/ai-studio/concepts/evaluation-approach-gen-ai" style="text-decoration: underline;">AI-assisted evaluation in Azure AI studio</a>

