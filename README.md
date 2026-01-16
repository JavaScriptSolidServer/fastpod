# fastpod

> The fastest way to run a Solid pod. Zero configuration, just works.

[![npm version](https://img.shields.io/npm/v/fastpod.svg)](https://www.npmjs.com/package/fastpod)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**fastpod** is the quickest way to get your own [Solid](https://solidproject.org) pod server running.

## 🚀 Quick Start

```bash
# Run instantly with npx (no installation required!)
npx fastpod

# That's it! Your Solid pod is running at http://localhost:5444
```

## ⚡ Features

- ✅ **Zero configuration** - Just works
- ✅ **Lightning fast** - Server starts in seconds
- ✅ **Solid Protocol** - Full spec compliance
- ✅ **WebID Authentication** - Decentralized identity
- ✅ **Passkey Support** - Modern passwordless auth
- ✅ **WebSocket Notifications** - Real-time updates
- ✅ **JSON-LD Native** - First-class linked data support

## 📦 Installation

### No Installation (Recommended)

```bash
npx fastpod
```

### Global Installation

```bash
npm install -g fastpod
fastpod
```

## 🎮 Usage

```bash
# Start with defaults
fastpod

# Custom port
fastpod --port 8080

# Custom data directory
fastpod --root /var/pods

# Multi-user mode
fastpod --multiuser

# Disable authentication
fastpod --no-auth

# Show help
fastpod --help
```

## 📖 How It Works

fastpod is a lightweight wrapper around [jspod](https://github.com/JavaScriptSolidServer/jspod), which provides a beautiful CLI for [JavaScriptSolidServer](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

**Stack:**
```
fastpod → jspod → JavaScriptSolidServer
```

Each layer adds value:
- **JavaScriptSolidServer**: Full-featured Solid server implementation
- **jspod**: Beautiful CLI with sensible defaults
- **fastpod**: Fastest, easiest way to get started

## 🌟 First Run

**Step 1**: Run the command
```bash
npx fastpod
```

**Step 2**: Open http://localhost:5444 in your browser

**Step 3**: Register with your device's passkey (fingerprint, Face ID, etc.)

**Step 4**: Start using your pod!

## 🎯 Why fastpod?

- **Fast to type**: Just 7 characters
- **Fast to start**: Server running in seconds
- **Fast to learn**: Zero configuration needed
- **Fast to deploy**: One command and you're live

## 📚 Learn More

- **Solid Project**: https://solidproject.org
- **Solid Protocol**: https://solidproject.org/TR/protocol
- **WebID**: https://www.w3.org/2005/Incubator/webid/spec
- **jspod**: https://github.com/JavaScriptSolidServer/jspod

## 🤝 Contributing

Contributions welcome! This package is intentionally minimal - just a friendly wrapper.

## 📄 License

MIT - see [LICENSE](./LICENSE)

## 🙏 Credits

Built on [jspod](https://github.com/JavaScriptSolidServer/jspod) and [JavaScriptSolidServer](https://github.com/JavaScriptSolidServer/JavaScriptSolidServer).

---

**Made with ❤️ for the Solid community**

*"Your pod, fast"*
