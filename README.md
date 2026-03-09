# homebrew-squish

Homebrew tap for [Squish](https://github.com/wesleyscholl/squish) — local LLM inference at sub-second load times on Apple Silicon.

> Run 70B language models on a MacBook. OpenAI + Ollama drop-in. No cloud. No API key. Free.

## Install

```bash
brew tap wesleyscholl/squish
brew install squish
```

Or in a single command:

```bash
brew install wesleyscholl/squish/squish
```

To install the latest development version from `main`:

```bash
brew install --HEAD wesleyscholl/squish/squish
```

## Quick Start

```bash
squish pull qwen3:8b        # download + compress once (~5 min)
squish serve qwen3:8b       # start server on :11435
squish chat qwen3:8b        # interactive terminal chat
```

Open **http://localhost:11435/chat** in any browser for the web UI.

## Requirements

- macOS 13 Ventura or later
- Apple Silicon (M1 – M5)

## Upgrade

```bash
brew upgrade squish
```

## Uninstall

```bash
brew uninstall squish
brew untap wesleyscholl/squish
```

## Links

- [Documentation](https://wesleyscholl.github.io/squish)
- [Source repo](https://github.com/wesleyscholl/squish)
- [Releases](https://github.com/wesleyscholl/squish/releases)
- [Issue tracker](https://github.com/wesleyscholl/squish/issues)
