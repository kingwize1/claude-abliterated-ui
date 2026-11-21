# claude-abliterated — Desktop Agentic AI UI & Launcher

A single-file desktop web interface (`index.html`) featuring:
- **Agentic AI Input Box & Chat Interface** wired to `https://api.abliteration.ai/v1/chat/completions` (`abliterated-model-large-flash` with 1M token context window).
- **Public Launcher Showcase (`claude-abliterated`)** with isolated `CLAUDE_CONFIG_DIR` (`~/.claude-abliterated`), leaving standard Claude Code (`~/.claude`) untouched.
- **Scoped `npx rea-agents setup`** instructions for `claude-abliterated` only.
- **Live Token & Spend Ledger** enforcing a hard $2.00 budget cap ($1.00 / 1M input, $0.10 / 1M cached input, $2.00 / 1M output).

> **Security & Privacy Note:** No API key is stored in this repository. Users enter their own `ak_...` key in the browser UI (persisted only in their local browser `localStorage`) or store it locally in `~/.claude-abliterated/api_key` with user-only read permissions.
