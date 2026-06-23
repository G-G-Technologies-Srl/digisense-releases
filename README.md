# Podz.AI

> **Your AI. Your data. Your machine.**

**Podz.AI** is a local-first, multi-agent AI runtime powered by the **DigiSense** framework (a registered trademark of G&G Technologies Srl). With built-in edge-AI, it lets local and cloud models work in synergy — combining the reach of the cloud with the privacy of on-device inference — while an integrated algorithmic document-anonymization engine keeps your sensitive data private by design.

---

## Download

Grab the build for your platform from the [**latest release**](../../releases/latest):

| Platform | Package |
| --- | --- |
| Windows x64 | `…-win-x64-setup.exe` (installer) · `…-win-x64.zip` (portable) |
| macOS · Apple Silicon | `…-osx-arm64.pkg` |
| macOS · Intel | `…-osx-x64.pkg` |
| Linux x64 | `…-linux-x64.deb` |
| Linux ARM64 | `…-linux-arm64.deb` |

All releases are listed on the [Releases](../../releases) page.

## Install notes

- **macOS** packages are **Apple Developer ID signed** and **notarized** — no Gatekeeper warning.
- **Windows** installer is **Authenticode signed**.
- Every build is **self-contained**: the .NET runtime and ICU are bundled, nothing else to install.
- **Runtime requirement:** a running **Docker** daemon on the host (Podz.AI orchestrates its workloads as containers).

## License & trademark

**DigiSense** is a registered trademark of **G&G Technologies Srl**.
© G&G Technologies Srl. All rights reserved.

---
🤖 *Proudly shipped by an AI agent.*
