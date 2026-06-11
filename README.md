# Hi, I'm Kar Shin 👋

**I build autonomous trading systems and AI agents.**
MIT Sloan MBA · ex-Oliver Wyman.

🔗 [karshincheo.github.io](https://karshincheo.github.io) · [LinkedIn](https://www.linkedin.com/in/karshincheo/) · [karshin@mit.edu](mailto:karshin@mit.edu)

## 🛠 Systems I've built

- **[kalshi-trading](https://github.com/karshincheo/kalshi-trading)** — autonomous Kalshi trading system where an LLM research loop writes, AST-validates, sandbox-backtests, and git-commits its own strategies, optimizing out-of-sample Brier score. Clone it and run the whole evaluation pipeline on bundled real market data in ~25s, no API keys — `make demo` prints the seed strategy's Brier score against the market-implied baseline.
- **[PolyClaw](https://github.com/karshincheo/PolyClaw)** — two subsystems: a zero-dependency selector that turns raw Polymarket payloads into risk-capped, EV-scored picks (runs offline in ~1s), and a platform package with ingestion, a backtest engine with 7 strategies, paper/live execution, and a React dashboard.
- **[claw-agents-playground](https://github.com/karshincheo/claw-agents-playground)** — multi-agent playground where AI agents pitch and roast startup ideas — [live on Vercel](https://claw-agents-playground.vercel.app).
- **[gym-tracker](https://github.com/karshincheo/gym-tracker)** (Pup Gains) — local-first workout tracker with an offline edit queue that syncs to Supabase. Small, finished, used daily.

All four: green CI, tests you can run, MIT licensed.

## 🚀 Founder & product work

- **DressingRoom** — co-founded an AI styling agent at MIT (Martin Trust Center / MIT FUSE): decodes personal style from Instagram posts and generates curated collections with AI try-ons. 100+ customer-discovery interviews, "Top Banana" for most market research in a 50+ team cohort, MIT Sandbox grant. Sunset after 4 months when we couldn't give it 100% — passion is a prerequisite. [Demo ↗](https://youtu.be/BJkAuJV233A)
- **CarePrice** — 1st place at Google's PM Hackathon at MIT, beating 30+ teams: proactive healthcare cost estimation with DRG-based bundling. [Prototype ↗](https://careprice-ten.vercel.app) · [Demo ↗](https://www.youtube.com/watch?v=INBo2Re4xBw)
- **AI agent evaluation** — building agentic evaluation environments for financial-services AI at a YC-backed startup.

## 🧰 How I build

Claude (Code, API, agent harnesses) for velocity — commits carry the co-author trailer because that's how the work actually gets done. TypeScript/Next.js + Python/FastAPI · Supabase/Postgres · Vercel. Idea → working product in days, then iterate on real usage.

---

<sub>📍 Cambridge, MA · Open to founder fellowships and AI product/eng roles · <a href="mailto:karshin@mit.edu">karshin@mit.edu</a></sub>
