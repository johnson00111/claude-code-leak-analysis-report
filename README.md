# Claude Code Source Code Leak — Technical Analysis Report

> 31-slide technical deep dive into the March 31, 2026 Claude Code source code leak

## 🔗 [View Presentation →](https://johnson00111.github.io/claude-code-leak-analysis-report/)
## 📝 [Read the Blog Post →](https://johnson00111.github.io/blog/claude-code-leak-analysis/)

## What's Inside

A comprehensive technical analysis of the Claude Code npm source map leak, covering:

- **Architecture**: Seven-layer breakdown from UI to Security, with leaked/gated status per module
- **Core Systems**: Agent loop, three-layer memory, prompt cache, 40+ tools, bash security (23 checks)
- **Security Mechanisms**: Undercover Mode, Anti-Distillation, Client Attestation, Frustration Detection
- **Gated Features**: KAIROS autonomous daemon, autoDream memory consolidation, Voice, Buddy
- **Community Reaction**: claw-code Python rewrite, Kuberwastaken Rust clean-room, PR #41568, DMCA response
- **Impact Analysis**: Industry competition, design pattern democratization, security implications

## Languages

| Version | Slides | Download |
|---------|--------|----------|
| 中文 | 31 | [`claude-code-leak-zh.pptx`](pptx/claude-code-leak-zh.pptx) |
| English | 31 | [`claude-code-leak-en.pptx`](pptx/claude-code-leak-en.pptx) |

## Sources

17 sources including VentureBeat, Fortune, CNBC, The Register, eWeek, Decrypt, Hacker News, and multiple GitHub repositories. Full list on slide 30.

## Repo Structure

```
├── index.html              # Slide viewer (dark theme, language toggle, keyboard nav)
├── slides/
│   ├── zh/                 # Chinese slide images (31 JPGs)
│   └── en/                 # English slide images (31 JPGs)
├── pptx/
│   ├── claude-code-leak-zh.pptx
│   └── claude-code-leak-en.pptx
└── README.md
```

## GitHub Pages Setup

1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Save

## Author

**Johnson Jao (Tsung-Han Jao)** — University of Pittsburgh, M.S. Telecommunications

---

## ⚠️ Disclaimer

This repository is created purely for **educational and research purposes**.

On March 31, 2026, news broke that Anthropic had accidentally leaked the source code of Claude Code via an npm source map file. Out of personal curiosity, I researched the incident by reading publicly available news articles, blog posts, and community analyses, then compiled my findings into this presentation.

**This repository:**
- Does **NOT** contain, host, distribute, or link to any proprietary source code from Anthropic
- Does **NOT** contain any model weights, customer data, or credentials
- Contains **only** my own analysis slides, based entirely on publicly available reporting
- Is intended as a learning exercise to understand agentic AI architecture and software supply chain security

All source code referenced in the analysis remains the intellectual property of Anthropic, PBC. All information is sourced from publicly available reporting as of March 31, 2026.

If you are the copyright holder and believe any content in this repository infringes your rights, please open an issue and I will address it promptly.

---

*If you found this analysis useful, please consider giving this repo a ⭐!*
