### Juri — I build systems that run offline, in production, on real constraints

Consulting open: **AI devtools + trading/quant engines + Next.js SaaS MVPs.**
Measured latency, reproducible backtests, deployable code — not demos.

📧 Contact: open an issue on any repo or find me via [murati.net](https://www.murati.net)
💼 Currently: booking freelance — MVP scoping → build → deploy → handoff, weekly demos

---

### What investors get

- **Shipped, not slides:** voice-to-code on 2GB VRAM, backtest engine with full provenance, live marketplace
- **Risk-honest:** every trading repo documents what can still lose money
- **Full-stack ownership:** Linux/systemd → Python/TS → DB → Vercel/Proxmox

### Featured builds

| Repo | What | Why it matters |
|---|---|---|
| [opencode-voice](https://github.com/toor11/opencode-voice) | Push-to-talk for OpenCode, 100% local STT/TTS | 1 inference at STOP, VAD-gated, ~0.5s on GTX 1050 2GB |
| [Stock_bot](https://github.com/toor11/Stock_bot) | Universal Portfolio research, offline | data → strategies → portfolio → costs → backtest chain, no live-trading footguns |
| [carlisting](https://github.com/toor11/carlisting) | mobile.de-style marketplace, SQ/EN | Next.js 15, Auth.js, Mongo Atlas, Vercel Blob, seed in 1 cmd |
| [IlanTrio](https://github.com/toor11/IlanTrio) | Martingale grid EA + capital protection | Caps tail risk: 141-pip buffer vs 27-pip original on $100 cent |
| [ufo](https://github.com/toor11/ufo) | war.gov declassified docs bulk downloader | ★5, data pipeline for bulk PDFs |
| [AI_prompts_DB](https://github.com/toor11/AI_prompts_DB) | Curated LLM prompts | Practical prompt library for agent work |

Private work I can demo on call: cyber blog platform, legal-support LLM system, BTC price predictor, X posting agent with memory.

---

### For developers

```bash
# voice tool — offline Whisper + Piper
cd opencode-voice && uv venv .venv && uv pip install faster-whisper piper-tts soundfile onnxruntime

# marketplace — Next.js 15 + TS
cd carlisting && npm install && cp .env.example .env.local && npm run dev

# quant — reproducible research, tests must pass
cd Stock_bot && uv venv .venv && uv pip install -e ".[dev]" && pytest
```

- Every original repo: README with architecture, tests, MIT, no `eval` on untrusted input
- Stack: `Python` `TypeScript` `Next.js 15` `FastAPI` `Postgres/Mongo` `Docker` `MQL4/5` `Whisper/Piper` `Hyprland/systemd`

![stats](https://github-readme-stats.vercel.app/api?username=toor11&show_icons=true&hide_border=true)
![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=toor11&layout=compact&hide_border=true)

---

### Security / infra background

Active in secret scanning, vuln scanning, net recon, Proxmox homelab, Linux Surface kernels.
Forks are labs — originals above are products.
