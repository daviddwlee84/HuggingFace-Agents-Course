# The Hugging Face Agents Course

![course-icon](images/course-icon.png)

Course Related Links:

- [Official Website](https://huggingface.co/agents-course)
  - [Welcome to the 🤗 AI Agents Course - Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)
- [Sign up](https://bit.ly/hf-learn-agents)
- [YouTube Playlist](https://youtube.com/playlist?list=PLo2EIpI_JMQvNwIEfFWkqFrKdFr-ikRUP&si=3dPnoV9GmDQNAwTL)
- [GitHub](https://github.com/huggingface/agents-course)
- [Discord](https://discord.gg/UrrTSsSyjb)

Authors

- Joffrey Thomas
- Ben Burtenshaw
- Thomas Simonini

## Schedule

![recommended-pace](https://huggingface.co/datasets/agents-course/course-images/resolve/main/en/unit0/recommended-pace.jpg)

| Week           | Unit | Topic                                                                                      | Lectures | Quiz                                                                          | Assignments |
| -------------- | ---- | ------------------------------------------------------------------------------------------ | -------- | ----------------------------------------------------------------------------- | ----------- |
| 2025/2/10~2/16 | 0    | [Welcome to the Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)  | -        | -                                                                             | -           |
| 2025/2/17~2/23 | 1    | [Introduction to Agents](https://huggingface.co/learn/agents-course/en/unit1/introduction) | -        | [Unit 1 Quiz](https://huggingface.co/learn/agents-course/en/unit1/final-quiz) | -           |
| 2025/2/24~3/9  | 2    | [2_frameworks](units/en/unit2/README.md)                                                   | -        | -                                                                             | -           |
| 2025/3/10~3/31 | 3    | [3_use_cases](units/en/unit3/README.md)                                                    | -        | -                                                                             | -           |
| 2025/4/1~4/30  | 4    | [4_final_assignment_with_benchmark](units/en/unit4/README.md)                              | -        | -                                                                             | -           |

### Unit 0. Welcome to the Course

> Welcome, guidelines, necessary tools, and course overview.

- [Welcome To The Agents Course! Introduction to the Course and Q&A - YouTube](https://www.youtube.com/watch?v=PopqUt3MGyQ&list=PLo2EIpI_JMQvNwIEfFWkqFrKdFr-ikRUP&index=1) (2025/2/13 00:00 UTC+8)

1. [X] [Welcome to the 🤗 AI Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction)
2. [X] [Onboarding: Your First Steps ⛵](https://huggingface.co/learn/agents-course/en/unit0/onboarding)
   1. [X] [Create your Hugging Face Account](https://huggingface.co/)
   2. [X] [Sign up to Discord and introduce yourself](https://discord.gg/UrrTSsSyjb)
   3. [X] [Follow the Hugging Face Agents Course](https://huggingface.co/agents-course)
   4. [X] [Spread the word about the course](https://github.com/huggingface/agents-course)
3. [X] [(Optional) Discord 101](https://huggingface.co/learn/agents-course/en/unit0/discord101)

### Unit 1. Introduction to Agents

> Definition of agents, LLMs, model family tree, and special tokens.

![whiteboard-no-check](https://huggingface.co/datasets/agents-course/course-images/resolve/main/en/unit1/whiteboard-no-check.jpg)

1. [X] [Introduction to Agents](https://huggingface.co/learn/agents-course/en/unit1/introduction)
   - **Understanding Agents**
     - What is an Agent, and how does it work?
     - How do Agents make decisions using reasoning and planning?
   - **The Role of LLMs (Large Language Models) in Agents**
     - How LLMs serve as the “brain” behind an Agent.
     - How LLMs structure conversations via the Messages system.
   - **Tools and Actions**
     - How Agents use external tools to interact with the environment.
     - How to build and integrate tools for your Agent.
   - **The Agent Workflow:**
     - _Think_ → _Act_ → _Observe_.
2. [X] [What is an Agent?](https://huggingface.co/learn/agents-course/en/unit1/what-are-agents)
   - An Agent is a system that leverages an AI model to interact with its environment in order to achieve a user-defined objective. It combines reasoning, planning, and the execution of actions (often via external tools) to fulfill tasks.
     1. The Brain (AI Model)
        - LLM (Large Language Model): e.g. GPT4 from OpenAI, LLama from Meta, Gemini from Google, ...
        - VLM (Vision Language Model)
     2. The Body (Capabilities and Tools)
   -  To summarize, an Agent is a system that uses an AI Model (typically a LLM) as its core reasoning engine, to
      - Understand natural language: Interpret and respond to human instructions in a meaningful way.
      - Reason and plan: Analyze information, make decisions, and devise strategies to solve problems.
      - Interact with its environment: Gather information, take actions, and observe the results of those actions.
3. [X] [Small Quiz (ungraded)](https://huggingface.co/learn/agents-course/en/unit1/quiz1) (Quick Quiz 1)
4. [ ] [What are LLMs?](https://huggingface.co/learn/agents-course/en/unit1/what-are-llms)
5. [ ] [Messages and Special Tokens](https://huggingface.co/learn/agents-course/en/unit1/messages-and-special-tokens)
6. [ ] [What are Tools?](https://huggingface.co/learn/agents-course/en/unit1/tools)
7. [ ] [Quick Self-Check (ungraded)](https://huggingface.co/learn/agents-course/en/unit1/quiz2) (Quick Quiz 2)
8. [ ] [Understanding AI Agents through the Thought-Action-Observation Cycle](https://huggingface.co/learn/agents-course/en/unit1/agent-steps-and-structure)
9.  [ ] [Thought: Internal Reasoning and the Re-Act Approach](https://huggingface.co/learn/agents-course/en/unit1/thoughts)
10. [ ] [Actions: Enabling the Agent to Engage with Its Environment](https://huggingface.co/learn/agents-course/en/unit1/actions)
11. [ ] [Observe: Integrating Feedback to Reflect and Adapt](https://huggingface.co/learn/agents-course/en/unit1/observations)
12. [ ] [Dummy Agent Library](https://huggingface.co/learn/agents-course/en/unit1/dummy-agent-library)
13. [ ] [Let’s Create Our First Agent Using smolagents](https://huggingface.co/learn/agents-course/en/unit1/tutorial)
14. [ ] [**Unit 1 Quiz**](https://huggingface.co/learn/agents-course/en/unit1/final-quiz)
15. [ ] [Get your certificate](https://huggingface.co/learn/agents-course/en/unit1/get-your-certificate)
16. [ ] [Conclusion](https://huggingface.co/learn/agents-course/en/unit1/conclusion)

### Unit 2.

> Overview of smolagents, LangChain, LangGraph, and LlamaIndex.

### Unit 3.

> SQL, code, retrieval, and on-device agents using various frameworks.

### Unit 4.

> Automated evaluation of agents and leaderboard with student results.

## Resources

- `smolagents`
  - [Smolagents : Huggingface AI Agent Framework](https://smolagents.org/)
  - [huggingface/smolagents: 🤗 smolagents: a barebones library for agents. Agents write python code to call tools and orchestrate other agents.](https://github.com/huggingface/smolagents)
  - [smolagents](https://huggingface.co/docs/smolagents/index)
