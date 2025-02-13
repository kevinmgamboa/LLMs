# Course Notes

## Introduction by Andrew Ng
Generative AI applications are becoming more complex, sophisticated, and agentic. Agentic applications have workloads that can be hard to predict in advance -- for example, what tools will it decide to call? -- and a serverless architecture helps you efficiently providing on-demand resources.

This course teaches you to build and deploy a serverless agentic application. You’ll learn to create agents with tools, code execution, and guardrails, and build responsible agents for business use cases:
- Build a customer service bot for a fictional tea mug business that can answering questions, retrieve information, and process orders.
- Connect your customer service agent to a CRM to get customer info and log support tickets in real-time.
- Explore how you invoke the agent, and see the trace to review the agent’s thought process and observation loop until it reaches its final output.
- Attach a code interpreter to your agent, giving it the ability to perform accurate calculations by writing and running its own Python code.
- Implement guardrails to prevent your agent from revealing sensitive information or using inappropriate language.

By the end, you will have built a sophisticated AI agent capable of handling real-world customer support scenarios.

## Notes
* Agents in order to solve the problem may call other APIs .. serverless application can help 
* Think and learn to create Agents as a standalone service