# billion-context

English | 中文

**Context-compression plugin** — _billion-context is all you need._

small context windows (100K is enough) · ~5× fewer tokens · month-long single sessions

`billion-context` sits between any coding agent and its model API, rewriting Anthropic/OpenAI streams with incremental compression so a single session can run for days without blowing the context window.

## Getting Started

Clone the repo, then run the setup check to confirm your environment is compatible before installing:

```bash
python3 verify_setup.py
```

This prints your detected platform and picks the nearest npm registry mirror for faster dependency downloads.

### Clients

Works as a proxy in front of Claude Code, Codex, OpenCode, Gemini CLI, and other OpenAI/Anthropic-compatible agents.

## License

MIT
