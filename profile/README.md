<div align="center">

# construct.computer

**Your AI agent gets its own computer.**

Give your agent a full desktop environment — files, email, calendar, Slack, Telegram, a browser, and a terminal. Watch it work in real time, take over anytime, collaborate mid-task.

[**Try it**](https://construct.computer) &nbsp;&middot;&nbsp; [**App Store**](https://registry.construct.computer) &nbsp;&middot;&nbsp; [**Docs**](https://registry.construct.computer/publish)

</div>

---

### What is Construct?

Construct is a serverless AI agent platform. Instead of chatting *about* tasks, you give the AI an actual computer and let it use it — autonomously clicking, typing, reading, writing, and navigating just like you would.

- **Persistent agent** that remembers across sessions and learns your preferences
- **Desktop in the browser** with windowed apps you can watch and use alongside the agent
- **Multi-platform** — chat from the web, Slack, Telegram, email, or the macOS notch companion
- **20+ built-in tools** — file management, web search, email, calendar, code execution, and more
- **Extensible with apps** — standard MCP servers that plug into the platform

### Platform

| Repo | Description |
|------|-------------|
| [**construct**](https://github.com/construct-computer/construct) | Core platform — agent backend, API, and deployment |
| [**web-desktop**](https://github.com/construct-computer/web-desktop) | React + TypeScript desktop environment (the browser-based OS) |
| [**notch**](https://github.com/construct-computer/notch) | macOS companion app that lives in the MacBook notch |

### Apps & Registry

| Repo | Description |
|------|-------------|
| [**app-registry**](https://github.com/construct-computer/app-registry) | App store — registry of installable MCP apps |
| [**construct-app-sample**](https://github.com/construct-computer/construct-app-sample) | Reference app — developer toolkit with 6 tools + UI |
| [**construct-app-mercadolibre**](https://github.com/construct-computer/construct-app-mercadolibre) | MercadoLibre integration — 21 tools for e-commerce |

### Developer Tools

| Package | Version | Description |
|---------|---------|-------------|
| [`@construct-computer/app-sdk`](https://www.npmjs.com/package/@construct-computer/app-sdk) | [![npm](https://img.shields.io/npm/v/@construct-computer/app-sdk?color=blue)](https://www.npmjs.com/package/@construct-computer/app-sdk) | SDK for building Construct apps |
| [`@construct-computer/create-construct-app`](https://www.npmjs.com/package/@construct-computer/create-construct-app) | [![npm](https://img.shields.io/npm/v/@construct-computer/create-construct-app?color=blue)](https://www.npmjs.com/package/@construct-computer/create-construct-app) | Scaffold a new app in seconds |

### Build an App

```bash
npx @construct-computer/create-construct-app my-app
cd my-app
npm install && npm run dev
```

Test locally with curl, then install in Construct via **App Registry > Installed > Developer Tools > Install from URL**.

Publish to the store by opening a PR on [app-registry](https://github.com/construct-computer/app-registry). See the [publishing guide](https://registry.construct.computer/publish) for details.
