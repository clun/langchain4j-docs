!!! info "info"

    This project is in active development

## Project goals

The goal of this project is to simplify the integration of AI/LLM capabilities into your Java application. This can be achieved thanks to:

- **A simple and coherent layer of abstractions**, designed to ensure that your code does not depend on concrete implementations such as LLM providers, embedding store providers, etc. This allows for easy swapping of components.
- **Numerous implementations of the above-mentioned abstractions**, providing you with a variety of LLMs and embedding stores to choose from.
- **Range of in-demand features on top of LLMs, such as:**
    - The capability to **ingest your own data** (documentation, codebase, etc.), allowing the LLM to act and respond based on your data.
    - **Autonomous agents** for delegating tasks (defined on the fly) to the LLM, which will strive to complete them.
    - **Prompt templates** to help you achieve the highest possible quality of LLM responses.
    - **Memory** to provide context to the LLM for your current and past conversations.
    - **Structured outputs** for receiving responses from the LLM with a desired structure as Java POJOs.
    - **"AI Services"** for declaratively defining complex AI behavior behind a simple API.
    - **Chains** to reduce the need for extensive boilerplate code in common use-cases.
    - **Auto-moderation** to ensure that all inputs and outputs to/from the LLM are not harmful.