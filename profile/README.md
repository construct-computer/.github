<div align="center">

# construct.computer

**Your AI agent gets its own computer.**

Give your agent a full desktop environment — files, email, calendar, Slack, Telegram, a browser, and a terminal. Watch it work in real time, take over anytime, collaborate mid-task.

[**Try it**](https://construct.computer) &nbsp;&middot;&nbsp; [**Web Desktop**](https://github.com/construct-computer/web-desktop) &nbsp;&middot;&nbsp; [**App Registry**](https://github.com/construct-computer/app-registry) &nbsp;&middot;&nbsp; [**macOS Companion**](https://github.com/construct-computer/notch)

</div>

---

### What is Construct?

Construct is a serverless AI agent platform. Instead of chatting *about* tasks, you give the AI an actual computer and let it use it — autonomously clicking, typing, reading, writing, and navigating just like you would.

- **Persistent agent** that remembers across sessions and learns your preferences
- **Desktop in the browser** with windowed apps you can watch and use alongside the agent
- **Multi-platform** — chat from the web, Slack, Telegram, email, or the macOS notch companion
- **20+ built-in tools** — file management, web search, email, calendar, code execution, and more
- **Extensible with apps** — standard MCP servers that plug into the platform

### Repositories

| Repo | Description |
|------|-------------|
| [**web-desktop**](https://github.com/construct-computer/web-desktop) | React + TypeScript desktop environment — the browser-based OS |
| [**notch**](https://github.com/construct-computer/notch) | macOS companion app that lives in the MacBook notch |
| [**app-registry**](https://github.com/construct-computer/app-registry) | Registry of installable MCP apps for the platform |
| [**construct-app-sample**](https://github.com/construct-computer/construct-app-sample) | Starter template for building Construct apps |
| [**construct-app-mercadolibre**](https://github.com/construct-computer/construct-app-mercadolibre) | MercadoLibre integration — 21 tools for product search, orders, and more |

### Build an App

Construct apps are standard [MCP servers](https://modelcontextprotocol.io). Write your tools in any language, publish to the registry, and every Construct user can install them.

```bash
# Clone the starter template
git clone https://github.com/construct-computer/construct-app-sample
cd construct-app-sample
npm install && npm start
```

See the [app registry](https://github.com/construct-computer/app-registry) for publishing details.
