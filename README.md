# Overview
This is custom implementation of gemini-cli. For its usage, please refer to [the official documents](https://github.com/google-gemini/gemini-cli). Besides, the implementation of azureOpenAIContentGenerator.ts is based on [wr-fenglei's implementation](https://github.com/wr-fenglei/gemini-cli)

# What this implementation do
1. Add support for Azure OpenAI integration: you can connect to your LLM models deployed on Azure using API key.
1. Improve the authentication user experience: you can provide missing settings without restarting the cli.