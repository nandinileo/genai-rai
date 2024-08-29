**Mitigate**

Mitigation is a iterative and layered approach. 

![image](https://github.com/user-attachments/assets/a10f7798-d7f7-4b18-bf60-b6c8c494d42e)

 
At the model level, it's important to understand the model(s) you'll be using and what fine-tuning steps may have been taken by the model developers to align the model towards its intended uses and to reduce the risk of potentially harmful uses and outcomes.
-- For example, for GPT-4, model developers have been able to use reinforcement learning methods as a responsible AI tool to better align the model towards the designers' intended goals.
 
Transparency notes – provides capabilities for various models and their Different versions.
, you can use powerful benchmarking and evaluation capabilities from Azure AI studio allow you to compare the performance of multiple models side-by-side to pick the one that would perform best for your use case.

 
At the safety system level, you should understand the platform level mitigations that have been implemented, such as the Azure OpenAI content filters which help to block the output of harmful content. This is in built. 

In many applications at Microsoft, we use another state of the art  AI-based safety system, Azure AI Content Safety, to provide an independent layer of protection, helping you to block the output of risky content. Azure AI Content Safety is a content moderation offering that goes around the model and monitors the inputs and outputs to help identify and prevent attacks from being successful and catches places where the models make a mistake. This is much more granular and configurable than the in-built content filtering. You can enable prompt shield for jail breaks, protected material detection, groundedness detection.
 
At the application level, application developers can implement metaprompt and user-centered design and user experience mitigations. Metaprompts are instructions provided to the model to guide its behavior; their use can make a critical difference in guiding the system to behave in accordance with your expectations. This is where prompt engineering is really helpful. We combine the general reasoning capabilities of LLMs with specific information relevant to your business use-cases.

User-centered design and user experience (UX) interventions are also key mitigation tools to prevent misuse and overreliance on AI.
 
If you’re interested in more UX design insights, I recommend checking out our HAX Toolkit which provides a ton of resources for UX design teams.
The HAX Toolkit is for teams building user-facing AI products. It helps you conceptualize what the AI system will do and how it will behave. Use it early in your design process.
 
Guidelines for Human-AI interaction: Best practices for how AI systems should behave during interaction. Use them to guide your AI product planning.
HAX Design Library: Learn the Guidelines for Human-AI Interaction and how to apply them, using patterns and examples.
HAX Workbook: Work together with your team to prioritize which Guidelines to implement in your product.
HAX Playbook: For applications using natural language processing, identify common failures so you can plan for mitigating them.
 
 
Review and edit the responses, take responsibility, highlight the potential inaccuracies caught during measurement phase, Disclose AI's role in the interaction, cite references and information sources, when applicable structure the system output, have pre-determined responses for certain interactions.
 
At the positioning level, there are many ways to educate the people who will use or be affected by your system about its capabilities and limitations. Such as Transparency Notes, FAQ, system documentation, user guideline and best practices.

Appendix:
Prompt Engineering: https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/prompt-engineering
UX - HAX : https://www.microsoft.com/en-us/haxtoolkit
![image](https://github.com/user-attachments/assets/7bfa9064-6cd7-4710-9e0c-08e78298ed92)

