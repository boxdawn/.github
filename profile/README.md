# Boxdawn

**Waste-axis observability for AI agents.** We measure what your agents spend and never use — then show it back to you over time.

Most observability tools answer *"what did my agent do?"* Boxdawn answers a narrower question that nobody was billing for: **which of those tokens did you pay for twice?**

---

## Running today

| | |
|---|---|
| **Hosted analyzer** | Drop a trace at **[boxdawn.com/analyze](https://boxdawn.com/analyze)** — no account, no install. Nothing is stored unless you ask for it. |
| **Measurements dashboard** | Sign in and your waste rate accumulates per project, by the day your sessions actually ran. |
| **API keys** | Issue a key and send traces from CI or a script. Revoke it from the same screen. |
| **Open-source CLI** | `pip install "boxdawn[detect]"` — the detectors run locally, on your machine, on your data. |

## What we are building

The product is a chain, and we are open about where we are on it:

**monitor → detect → alert → auto-fix → auto-optimize + govern**

- **detect** is what ships today: four deterministic detectors over one trace, priced from the real `usage` fields when the trace carries them.
- **alert** is pre-registered and not yet built. The rule compares a day against your own previous qualifying day, not against a fixed threshold — *"this week is worse than your own last week"* is the question worth answering.
- **monitor**, **auto-fix**, **auto-optimize** and **govern** follow. Real-time monitoring, loop detection, visual session flow and latency work all live in this part of the chain.

If a capability is not in the list above, we have not built it. We would rather you find that out here than after you install something.

## How we work

- **Measured or not stated.** Every number on [boxdawn.com](https://boxdawn.com) carries the corpus it came from and the date it was measured. Where a claim has a confidence interval, the interval is printed next to it.
- **Reproducible.** The report on our product page was produced from a publicly published trace, so anyone can run the same command and check us.
- **Local-first where it can be.** The deterministic detectors need no network. The semantic pass is opt-in, costs money, and says so.

## Links

- **[boxdawn.com](https://boxdawn.com)** — the product
- **[boxdawn/boxdawn](https://github.com/boxdawn/boxdawn)** — the open-source detectors
- **[PyPI](https://pypi.org/project/boxdawn/)** — `pip install "boxdawn[detect]"`
- Questions and bug reports: **[GitHub Issues](https://github.com/boxdawn/boxdawn/issues)**

Boxdawn is a startup based in Seoul, South Korea, founded by [Sewon Jeon](https://x.com/imwon_dev).
