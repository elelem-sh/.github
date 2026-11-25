# elelem

A coding agent in your terminal. Written in Ruby. MIT licensed.

```bash
curl -fsSL https://elelem.sh/install | sh
elelem-shell
```

The script installs Ruby 4.0 with [rv](https://rv.dev), elelem and a local
model. No key. The model runs inside the process.

A plugin is one Ruby file. Models, tools and interfaces are plugins.

## Repositories

| Repository | What it is | Maturity |
|---|---|---|
| [elelem](https://github.com/elelem-sh/elelem) | The agent loop. 3 tools. | ready |
| [shell](https://github.com/elelem-sh/shell) | elelem, ready to use. | ready |
| [tools](https://github.com/elelem-sh/tools) | More tools. Permission prompts. | ready |
| [llama](https://github.com/elelem-sh/llama) | llama.cpp, in-process. | ready |
| [ollama](https://github.com/elelem-sh/ollama) | Local models through Ollama. | ready |
| [anthropic](https://github.com/elelem-sh/anthropic) | Anthropic models, hosted. | ready |
| [openai](https://github.com/elelem-sh/openai) | OpenAI chat completions. | alpha |
| [cerebras](https://github.com/elelem-sh/cerebras), [cloudflare](https://github.com/elelem-sh/cloudflare), [gemini](https://github.com/elelem-sh/gemini), [github](https://github.com/elelem-sh/github), [groq](https://github.com/elelem-sh/groq), [mistral](https://github.com/elelem-sh/mistral), [openrouter](https://github.com/elelem-sh/openrouter) | One gem per hosted API. | alpha |
| [mcp](https://github.com/elelem-sh/mcp) | MCP servers as tools. | ready |
| [skills](https://github.com/elelem-sh/skills) | Agent skills, on demand. | ready |
| [server](https://github.com/elelem-sh/server) | elelem in a browser tab. | alpha |
| [diffusion](https://github.com/elelem-sh/diffusion) | Images and video, locally. | lab |
| [elelem.sh](https://github.com/elelem-sh/elelem.sh) | The website. | |

Each gem is `elelem-NAME` on [RubyGems](https://rubygems.org/search?query=elelem-).

## Learn more

- [Start](https://elelem.sh/docs/start/)
- [Plugins](https://elelem.sh/plugins/)
- [Write a tool](https://elelem.sh/guides/write-a-tool/)
