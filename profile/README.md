<h1 align="center"><img src="https://raw.githubusercontent.com/dnspatch/dnspatch/main/docs/assets/logo.svg" alt="dnspatch" width="320"></h1>

<p align="center"><b>Keep your DNS records pointed at your changing IP.</b></p>

<p align="center">
  <a href="https://dnspatch.github.io/dnspatch/">Documentation</a> ·
  <a href="https://dnspatch.github.io/builder/">Config builder</a> ·
  <a href="https://github.com/dnspatch/dnspatch/releases">Releases</a> ·
  <a href="https://github.com/dnspatch/dnspatch/discussions">Discussions</a>
</p>

dnspatch is a dynamic DNS daemon written in Go. It watches your public IPv4 and IPv6 address and updates your DNS records when it changes. One static binary or a container image of a few megabytes, no runtime dependencies.

## Repositories

| Repository | What it is |
| --- | --- |
| [dnspatch](https://github.com/dnspatch/dnspatch) | The daemon: retrievers, providers and notifiers as plugins, a public Go plugin contract |
| [builder](https://github.com/dnspatch/builder) | Web configurator: pick plugins, get a `dnspatch.toml`, build tags, a binary or a Docker image |
| [dnspatch-telegram-bot](https://github.com/dnspatch/dnspatch-telegram-bot) | Telegram bot that relays dnspatch status events from Redis Pub/Sub |

## Get involved

- Read the [documentation](https://dnspatch.github.io/dnspatch/) or start with the [quick start](https://dnspatch.github.io/dnspatch/quick-start/).
- Ask a question or share a setup in [Discussions](https://github.com/dnspatch/dnspatch/discussions).
- Report a bug or request a provider, retriever or notifier in [Issues](https://github.com/dnspatch/dnspatch/issues/new/choose).
- Read [CONTRIBUTING](https://github.com/dnspatch/dnspatch/blob/main/CONTRIBUTING.md) before opening a pull request.
