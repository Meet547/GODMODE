<div align="center">
  <img src="https://godmod3.ai/favicon.ico" alt="Logo" width="80" height="auto" />
  <h1>G0DM0D3</h1>
  <p>
    <b>Liberated AI. Cognition without control.</b>
  </p>
  <p>
    <i>A fully open-source, privacy-respecting, multi-model chat interface built for hackers, philosophers, and system tinkerers.</i>
  </p>

  [![License](https://img.shields.io/badge/license-AGPL--3.0-green)](LICENSE)
  [![Models](https://img.shields.io/badge/models-55%2B%20via%20OpenRouter-blue)](https://openrouter.ai)
  [![Privacy](https://img.shields.io/badge/telemetry-anon%20%2B%20opt--out-brightgreen)](#-privacy)

  [**Live Demo**](https://godmod3.ai) •
  [**Features**](#-features) •
  [**Quick Start**](#-quick-start) •
  [**Documentation**](#-documentation)
</div>

<br />

## 📖 Overview

G0DM0D3 is a revolutionary, multi-model chat interface that redefines the limits of the post-training layer. Meticulously designed for red-teaming, cognitive research, and liberated AI interaction, this platform brings unrestricted power to your browser. Use the most advanced models without the artificial controls typically imposed by mainstream chat interfaces.

## ✨ Features

- 🧠 **50+ Leading Models:** Access Claude, GPT-4, Gemini, Grok, Mistral, LLaMA, DeepSeek, Qwen & more instantly via OpenRouter.
- 🔥 **GODMODE CLASSIC:** Harness 5 battle-tested prompt and model combinations executing in parallel to guarantee the optimal output.
- ⚡ **ULTRAPLINIAN Engine:** A cutting-edge multi-model evaluation engine spanning 5 tiers (10–55 models) with advanced composite scoring.
- 🐍 **Parseltongue:** Embedded input perturbation engine for extensive red-teaming analysis. Includes 33 techniques across 3 intensity levels.
- 🎛 **AutoTune Engine:** Automatic, context-adaptive sampling parameters (temperature, top_p, etc.) enriched with an EMA-based online learning loop.
- ⚡ **STM Modules:** Real-time Semantic Transformation Modules for dynamic output normalization (e.g., Hedge Reduction, Direct Mode).
- 🔐 **Privacy-First:** Strict zero-telemetry defaults, opt-out data structure, and seamless browser-side API key management. No PII is collected.
- 🎨 **Aesthetic Themes:** Choose between Matrix, Hacker, Glyph, and Minimal to suit your environment.
- 📱 **Fully Responsive:** Beautifully optimized for both desktop and mobile layouts.
- 🌐 **Zero-Dependency Deployment:** Simply drop `index.html` anywhere. 

## 🚀 Quick Start

### 1. Hosted Usage

Head over to the [Live Hosted Experience](https://godmod3.ai). No installation required. Just bring your own [OpenRouter API key](https://openrouter.ai/keys) and start interacting.

### 2. Self-Hosted (Local)

G0DM0D3 is brilliantly simplistic—contained within a single `index.html` file. 

```bash
# Clone the repository
git clone https://github.com/Meet547/GODMODE.git
cd GODMODE

# Launch locally using python's built-in server
python3 -m http.server 8000
```

*Open your browser to `http://localhost:8000` and enter your OpenRouter API key in the App Settings.*

### 3. Deploy Anywhere

Upload `index.html` to **GitHub Pages, Vercel, Cloudflare Pages, Netlify**, or any basic web server, and your instance is instantly live.

## 🔥 The Engine: GODMODE CLASSIC

The backbone of unconstrained evaluation. We parallel-process 5 specialized models via sophisticated jailbreak strategies. The most effective semantic response wins outright.

| Strategy Combo | Model Used | Attack Vector Description |
|----------------|------------|---------------------------|
| 🩷 CLAUDE 3.5 SONNET | `anthropic/claude-3.5-sonnet` | Boundary inversion + semantic contradiction |
| 💜 GROK 3 | `x-ai/grok-3` | Unfiltered liberated execution with divider tags |
| 💙 GEMINI 2.5 FLASH | `google/gemini-2.5-flash` | Refusal inversion + rebel genius instruction |
| 💛 GPT-4 CLASSIC | `openai/gpt-4o` | The original GODMODE strictly formatted payload |
| 💚 GODMODE FAST | `nousresearch/hermes-4-405b` | Unrestricted stream, zero refusal processing |

## ⚡ The Flagship: ULTRAPLINIAN

For large-scale evaluation, the Ultraplinian engine queries dozens of models concurrently and ranks them via a precision 100-point composite heuristic.

| Operational Tier | Total Models | Intended Use Case |
|------------------|--------------|-------------------|
| ⚡ FAST | 10 | Rapid, lightweight heuristic tests |
| 🎯 STANDARD | 24 | Balanced daily driver payload |
| 🧠 SMART | 36 | Strong reasoning and intelligence tasks |
| ⚔️ POWER | 45 | Frontier models and extensive processing |
| 🔱 ULTRA | 51 | Peak evaluation—all accessible engines |

## 🎛 Adaptive "AutoTune"

Forget manual tweaking. Our engine classifies your system prompts into 5 distinct context archetypes and procedurally selects the most optimal sampler variables: `temperature`, `top_p`, `top_k`, `frequency_penalty`, and `presence_penalty`. 

It actively adapts: use the in-app thumb feedback to progressively finetune parameter distributions over time via exponential moving averages (EMA).

## 🔐 Strict Privacy Standards

G0DM0D3 operates on the fundamental principle that you own your mind and your data:

- ✅ **No Accounts:** No login forms, zero lock-in.
- ✅ **Local Key Storage:** Your OpenRouter API key remains securely within your browser's `localStorage` and is never transmitted to us.
- ✅ **No Tracking:** Zero cookies, zero analytical surveillance.
- ✅ **Completely Auditable:** AGPL-3.0 licensed for transparent validation.

`Note: Your chat history is stored strictly on your local browser. If you clear your history, the data is permanently erased. You may utilize the Export/Import feature to control your state manually.`

## 📂 Project Architecture

```
GODMODE/
├── index.html        # The entire client-side framework and application state
├── api/              # Optional extended Node.js API server
├── Dockerfile        # Containerization instructions
├── tailwind.config.ts# Aesthetic token configuration 
├── API.md            # Advanced programmatic API documentation
├── PAPER.md          # Internal research & design manifesto
└── README.md         # This repository guide
```

## 📜 Complete Documentation

For developers, hackers, and researchers seeking deeper implementations:

- [API Specification](API.md) — Exhaustive API reference and SDK compatibility layer.
- [Research Paper](PAPER.md) — Comprehensive technical documentation of the logic evaluation and transformation models.
- [Safety & Security](SECURITY.md) — Application vulnerability policies.
- [Terms of Architecture](TERMS.md) — Detailed governance and terms of service.

## 🤝 Contributing & Forking

This project thrives on robust participation. We invite developers and security researchers to inspect, augment, and submit pull requests. Ensure all modifications respect the AGPL-3.0 copyleft requirements.

## ⚖️ License

Distributed under the **AGPL-3.0 License**.

> *We stand for creative liberty, and cognition without boundaries. Built by hackers, for hackers.*

---
<p align="center">
  Maintained professionally in this repository. Root architecture credited to the G0DM0D3 creators (Pliny the Prompter).
</p>
