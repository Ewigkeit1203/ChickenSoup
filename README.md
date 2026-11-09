# 🍲 Chicken Soup for LLMs (`ChickenSoup`)

> **"When you can't afford $15/1M tokens, inspire your $0.14 model to believe it's a Staff Engineer at Anthropic."**

A curated collection of high-leverage System Prompts ("Chicken Soups") designed to cure budget models (like DeepSeek-V3, Qwen, Llama) of laziness, shallow reasoning, and placeholder habits. 

Instead of simple roleplay, these prompts enforce **explicit Chain-of-Thought (`<antThinking>`)**, **strict engineering guardrails**, and **high signal-to-noise communication**.

## 🥣 The Menu (Available Soups)

| Soup Name | Target Symptom | Best Used For |
| :--- | :--- | :--- |
| **[Opus 5.5 Override](./soups/opus-5.5-override.md)** | Shallow answers, skipping steps, generic AI tone | Complex architecture, deep Q&A, full-stack coding |
| **[IDE / Cursor Mode](./cursorrules/opus-5.5-mode.mdc)** | `// ... rest of code` placeholders, lazy refactoring | `.cursorrules`, Windsurf, or API system prompts |

## 🚀 How to Serve

1. Pick a soup from the `/soups` directory.
2. Paste it into your LLM's **System Prompt**, **Custom Instructions**, or your project's `.cursorrules` file.
3. Watch your budget model sweat and deliver Staff-level output.

## 🤝 Contributing

Found a new recipe that makes models 10x smarter? PRs are welcome! Please test your prompt across at least 3 complex tasks before submitting.

## 📄 License

MIT License
