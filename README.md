# genai-rai
RAI practices for GenAI applications

<img src="https://github.com/user-attachments/assets/467b8b54-baf8-4e53-8f17-66f218656eb2" alt="image" width="400" height="200">

You can help create clarity across your organization by setting up principles for the responsible design and use of AI. Put those principles into practice by taking a human-centered approach to AI that spans roles, processes, and functions supported by tools and governance to help you build AI solutions grounded in trust.

Microsoft takes a human-centered approach to AI design and development that is always grounded in the principles of fairness, inclusiveness, reliability and safety, transparency, privacy and security, and accountability. These are what we call the Responsible AI Principles.

At Microsoft, we believe that when you create technologies that can change the world, you must also ensure that the technology is used responsibly.  
It all starts with our AI principles.
Our **Fairness** principle speaks to how AI allocates opportunities, resources, or information in ways that are fair to the humans who use it.
**Reliability** and **Safety and Privacy** and Security ensure we’re considering how the system functions well for people across different use conditions and contexts, including ones it was not originally intended for, and how we safeguard information.
**Inclusiveness** looks at how the system should be designed to be inclusive of people of all abilities.
Lastly, are our foundational principles of **Transparency** and **Accountability**. These account for how people could misunderstand, misuse, or incorrectly estimate the capabilities of the system, while creating the necessary oversight so that humans can be accountable and in control with these systems.
These 6 principles that have not changed since Microsoft first adopted them in 2018 – they continue to be durable, even as AI technologies evolve.

**So, what is Responsible AI in GenAI?**
It’s the same as it has always been – it’s about creating AI technologies and solutions that harness all of this amazing potential while anticipating and mitigating the risks.

Generative AI models that have demonstrated improvements in advanced capabilities such as content and code generation, summarization, and search. With many of these improvements also come increased responsible AI challenges related to harmful content, manipulation, human-like behavior, privacy, and more.
 
Responsible AI principles are crucial when building applications using large language models (LLMs) due to the unique challenges associated with generative AI. As I mentioned before, LLMs can produce biased, harmful, or low-quality outputs. Responsible AI practices help identify, measure, mitigate, and monitor these risks.
Security and Privacy: LLMs may inadvertently leak sensitive information. Responsible AI practices reduce security and privacy risks.
Trust and Transparency: By adhering to responsible AI principles, organizations build trust with users. Transparency ensures users understand how LLMs work and their limitations.
 
It is critical to understand that responsible AI isn’t just a theoretical concept—it’s essential for safe and ethical LLM applications. Within Azure AI today, we have 20 Responsible AI tools with more than 90 features to help customers bring generative AI to market with confidence.

**Something we get asked all the time is, how were we able to launch so many generative AI products so quickly and confidently?**
Well, we’ve been operationalizing responsible AI for a while now, so we already had strong governance mechanisms in place.

So, my goal is to provide you with an overview of resources available to help YOU operationalize AI responsibly.
These are the essential development steps we use in our own engineering teams, and these steps will guide our conversation today.
Now, this makes the process look linear, but in reality, like any software development process, it’s totally iterative and filled with experimentation. 

Microsoft Responsible AI Standard, sets the policy requirements that our own engineering teams follow. Much of the content of the Standard, follows a pattern, asking teams to Identify, Measure, and Mitigate potential harms, and plan for how to Operate the AI system as well. First I will give a high level overview of what these steps are and then we can dive deep into it each one.

**Identify :** We Identify and prioritize potential harms that could result from AI system through iterative red-teaming, stress-testing, and analysis.

**Measure :** We Measure the frequency and severity of those harms by establishing clear metrics, creating measurement test sets, and completing iterative, systematic testing (both manual and automated).

**Mitigate :** Mitigate harms by implementing tools and strategies such as prompt engineering and using our content filters. Repeat measurement to test effectiveness after implementing mitigations.

Once measurement and mitigation systems are in place, we define and execute a deployment and operational readiness plan. This stage includes completing appropriate reviews of the system and mitigation plans with relevant stakeholders, establishing pipelines to collect telemetry and feedback, and developing an incident response and rollback plan, prepare for immediate action for unanticipated harms, develop a mechanism to block people who are misusing the system, build a effective user feedback channels (like thumbs up or down)

If you want to learn more about our internal approach, I encourage you to read our Transparency Report.
In it, you’ll find information about how we build AI solutions and make decisions about AI, as well as how we invest in the global responsible AI community to keep advancing responsible AI policy, research, and products.
You will also find links to our Responsible AI Standard, Impact Assessment templates, and other resources to help you build out your own internal governance processes.

<img src="https://github.com/user-attachments/assets/0ca783c0-1670-4a9d-b283-bee22a2ed45c" alt="image" width="300" height="200">


