# Boxdawn

**Open your AI agents' black box. The waste is between your agents, not inside them.**

APMs watch services. Trace tools watch a single agent. Gateways watch calls. The failure that costs the most in production, agents doing work that was already done, happens in the gaps between them.

**[Try it on one trace →](https://boxdawn.com/analyze)**. No install, no account.

---

## Running today

| | |
|---|---|
| **Hosted analyzer** | Drop a trace at **[boxdawn.com/analyze](https://boxdawn.com/analyze)** and get the full report in the browser. Nothing is stored unless you ask for it. |
| **Measurements dashboard** | Sign in and your waste rate accumulates per project, keyed on the day your sessions actually ran, so a backfill of old traces lands on the days they happened. |
| **API keys** | Issue a key per project and revoke it from the same screen, so traces can arrive with no browser in the loop. |
| **Open-source CLI** | `pip install boxdawn`. The deterministic detectors run on your machine, with no API calls and no signup. |

## Where we are on the chain

**monitor → detect → alert → auto-fix → auto-optimize + govern**

**Detection is the link that runs today**, as a service and as a library. The rest is being built in that order, because each link needs the one before it to be trustworthy first.

Next up: baseline alerts that compare a project against **its own** previous measurement rather than a fixed threshold: *"this week is worse than your own last week"* is the question worth answering. Then real-time monitoring, loop detection, visual session flow, and latency alongside cost.

Our [product page](https://boxdawn.com/product) keeps the current split of what runs and what is being built, so you can check it rather than take our word for it.

## Measured, and checkable

Four deterministic detectors (repeated tool cascades, re-sent context, redundant reads, duplicate creation), plus an opt-in LLM-as-judge pass for the pairs a byte comparison cannot separate.

Measured across **17,881 traces in four public corpora**, one of which we did not collect. Every number we publish names the corpus it came from and the date it was measured, and the report on our product page was produced from a publicly published trace, so anyone can run the same command and check the figure.

## Links

- **[boxdawn.com](https://boxdawn.com)**: the product
- **[boxdawn/boxdawn](https://github.com/boxdawn/boxdawn)**: the analyzer, open source
- **[PyPI](https://pypi.org/project/boxdawn/)**: `pip install boxdawn`
- Questions and bug reports: **[GitHub Issues](https://github.com/boxdawn/boxdawn/issues)**

Boxdawn is a startup in Seoul, South Korea, founded by [Sewon Jeon](https://x.com/imwon_dev).



