aisuite

Simple, unified interface to multiple Generative AI providers.
aisuite makes it easy for developers to use multiple LLM through a standardized interface. Using an interface similar to OpenAI's,
aisuite makes it easy to interact with the most popular LLMs and compare the results. It is a thin wrapper around python client libraries,
and allows creators to seamlessly swap out and test responses from different LLM providers without changing their code. Today, the library is primarily focussed on chat completions. 
We will expand it cover more use cases in near future.

Currently supported providers are - OpenAI, Anthropic, Azure, Google, AWS, Groq, Mistral, HuggingFace Ollama, Sambanova and Watsonx. To maximize stability, 
aisuite uses either the HTTP endpoint or the SDK for making calls to the provider.

