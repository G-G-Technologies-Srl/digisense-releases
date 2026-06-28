<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
    <img src="assets/logo.png" alt="Podz.AI" width="340">
  </picture>
</p>

<p align="center"><strong>Your local-first AI. Your data. Your machine.</strong></p>

<p align="center">
  <a href="https://g-g-technologies-srl.github.io/digisense-releases/"><strong>🌐 Website</strong></a> ·
  <a href="https://g-g-technologies-srl.github.io/digisense-releases/download.html"><strong>⬇️ Download</strong></a> ·
  <a href="../../releases/latest"><strong>Releases</strong></a>
</p>

---

**Podz.AI** is a local-first, multi-agent AI runtime powered by the **DigiSense** framework (a registered trademark of G&G Technologies Srl). It runs models, agents and applications on your own machine, so confidential data never leaves your infrastructure. When a cloud LLM is needed, an integrated **document-anonymization** engine masks personal data first.

Privacy by design and EU data sovereignty — built for teams working under **GDPR** and the **AI Act**: law firms, accountants, healthcare, finance, public sector and companies.

## Website

Presentation site (bilingual IT/EN): **https://g-g-technologies-srl.github.io/digisense-releases/**

The website source lives in [`docs/`](docs) and is published via GitHub Pages (Settings → Pages → Deploy from a branch → `main` → `/docs`).

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

## Key features

- **Local-first & privacy by design** — models and data stay on your infrastructure.
- **Document anonymizer** — mask personal data before any cloud-LLM call.
- **Context compression** — up to 80% fewer tokens, depending on the content.
- **Hardware profiling & model matching** — automatic selection of the best local models.
- **Multi-agent system** — orchestrator, skills, and an autonomous **Pod** agent you can launch from the UI.
- **Multiple runtimes** — OLLAMA, ONNX and more, with automatic selection.
- **Extensions & containers** for advanced capabilities.

## License & trademark

**DigiSense** is a registered trademark of **G&G Technologies Srl**.
© G&G Technologies Srl. All rights reserved.

---
🤖 *Proudly shipped by an AI agent.*
