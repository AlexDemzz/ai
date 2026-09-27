---
'@tanstack/ai-openai': patch
---

List the Responses provider tools on `gpt-6-astra`, `gpt-6-sol`, and `gpt-6-luna`. The model sync added them with `tools: []`, so `webSearchTool`, `imageGenerationTool`, and the other provider tools were type errors on GPT-6. They now accept `web_search`, `file_search`, `image_generation`, `code_interpreter`, `mcp`, `computer_use`, `shell`, and `apply_patch`, as listed on OpenAI's model pages.
