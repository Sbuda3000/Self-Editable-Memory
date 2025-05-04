# Lab 1: Implementing self-editing memory from scratch

There are a variety of ways to enable long-term memory in LLM agents, such as RAG and recursive summarization. The MemGPT paper first introduced the notion of *self-editing memory*. Essentially, offload memory management to the LLM. After all, the LLM is the most "intelligent" part of our programs, so why not have the LLM figure out memory instead of hard coding some solution?

In this section, we'll walk through how to use OpenAI's tool calling to implement some simple memory management tools.l
