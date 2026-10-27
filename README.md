# Context Engineering with Deep Agents

A hands-on notebook showing three ways a deep agent keeps its context small:

- **Offloading:** large tool results are saved to a file, and the model gets a preview.
- **Subagents:** source material stays in a separate context window.
- **Summarization:** older messages are condensed once a conversation gets long.

The data sources are swappable. The default uses fake market reports and works offline; you can switch to Wikipedia, a web page, a local file, or a tool you write yourself.

## Run it

**In Google Colab:** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/langchain-samples/context-engineering-deepagents-workshop/blob/main/context_engineering_colab.ipynb)

Add `ANTHROPIC_API_KEY` in Colab's Secrets tab (left sidebar) and turn on notebook access.

**Locally:** open `context_engineering.ipynb` and create a `.env` file next to it:

```
ANTHROPIC_API_KEY=your-key-here
```

## Learn more

For long-term memory, backends, skills, sandboxes, and deployment, see the [LangChain Academy Deep Agents course](https://academy.langchain.com/).
