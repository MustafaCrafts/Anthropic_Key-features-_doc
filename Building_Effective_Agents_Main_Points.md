# Summary: Building Effective Agents

**Date:** December 20, 2024

## Main Points

- **Simple is Best:**  
  Most successful projects use simple, mix-and-match patterns instead of very complex frameworks.

- **What are Agents?**  
  - **Agents** are smart helpers that can either follow a fixed plan or decide their own steps.  
  - **Workflows** follow set paths (like a recipe), while **agents** can change the plan as needed.

- **When to Use Which:**  
  - Use simple calls with language models for most tasks.
  - Choose workflows when tasks can be clearly broken into steps.
  - Use agents for tasks that need flexibility and smart decision-making.

- **Frameworks and Tools:**  
  Tools like LangGraph, Amazon Bedrock, Rivet, and Vellum help start projects quickly.  
  But, they sometimes add extra layers that make it hard to see what’s happening.  
  It’s better to start simple and learn what’s really under the hood.

- **Building Blocks of an Agent System:**  
  - **Augmented LLM:** A basic language model boosted with extra features (like memory and tools).  
  - **Prompt Chaining:** Break a task into a sequence of small steps, each helping the next.  
  - **Routing:** Send different types of queries to special tools designed to handle them.  
  - **Parallelization:** Run tasks at the same time for faster and more reliable results.  
  - **Orchestrator-Workers:** A main controller splits tasks and sends them to helpers.  
  - **Evaluator-Optimizer:** One model makes a draft and another checks and improves it.

- **Real-World Use:**  
  Agents can be used in customer support and coding tasks. They start with a user’s command, plan their own steps, use tools, and even ask for human help when needed. Testing and feedback are key to make sure they work well.

- **Key Advice:**  
  Start simple. Make your agent’s design easy to understand.  
  Keep everything transparent so that you can easily check each step.  
  Build clear and simple interfaces for any tools you use.

## Final Thought

Building effective agents is not about creating the most complicated system but about creating the right one for your needs. Keep it simple, test well, and add complexity only if it really makes things better.

**Acknowledgements:**  
This summary is based on insights from experts at Anthropic and their work with many teams.
