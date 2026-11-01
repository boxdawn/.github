<div align="center">
  <img src="https://avatars.githubusercontent.com/u/317308737?s=200&v=4" width="96" alt="Boxdawn" />
  <h1>Boxdawn</h1>
  <p><strong>Stop AI agent mistakes before they run.</strong></p>
  <p>
    <a href="https://boxdawn.com">Website</a> ·
    <a href="https://github.com/boxdawn/guard">Guard for Claude Code</a> ·
    <a href="https://boxdawn.com/analyze">Analyze a trace</a> ·
    <a href="https://boxdawn.com/privacy">Privacy</a>
  </p>
</div>

---

AI agents now run commands, change files and call cloud APIs on their own. Boxdawn sits between what an agent decides and what it does, so a destructive action is caught before it reaches your data, your systems or your bill.

## Products

### [Boxdawn guard](https://github.com/boxdawn/guard): a Claude Code plugin

Judges every Bash and PowerShell command before Claude Code runs it, and denies or holds for approval the ones that would wipe files outside your project, force-push over shared history, drop a database or destroy cloud resources. It runs on your machine, on Windows, macOS and Linux.

```
claude plugin marketplace add boxdawn/guard
claude plugin install boxdawn-guard@boxdawn
```

### [Trace analyzer](https://boxdawn.com/analyze): no account needed

Drop the trace file your agent already writes and get a report: four deterministic detectors (repeated tool cascades, re-sent context, redundant reads, duplicate creation) and the cost of each, from the trace's real usage fields with per-model rates pinned to their sources.

### [Dashboard](https://boxdawn.com): per-project history

Sign in to keep a daily waste rate per project, keyed on the day your sessions ran, and to issue and revoke API keys for CI and scripts. Project history keeps derived numbers, not the trace file.

## Contact

[contact@boxdawn.com](mailto:contact@boxdawn.com) · bugs and requests: [GitHub Issues](https://github.com/boxdawn/guard/issues)

Boxdawn is a startup in Seoul, South Korea, founded by [Sewon Jeon](https://x.com/imwon_dev).
