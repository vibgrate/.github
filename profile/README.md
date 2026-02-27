<!-- vibgrate/.github/profile/README.md -->

# Vibgrate

**Drift Intelligence for your software stack.**

Vibgrate scans your runtimes, frameworks, and every dependency — then produces an Upgrade Drift Score so you can see exactly where your stack is falling behind. One command. One number. Full visibility.

```bash
npx @vibgrate/cli scan .
```

---

### What we build

| Repository | Description |
|---|---|
| [cli](https://github.com/vibgrate/cli) | The Vibgrate CLI — scan, score, baseline, and report upgrade drift across Node, .NET, Python, and Java projects |
| [manifests](https://github.com/vibgrate/manifests) | Downloadable package-version manifests for offline and air-gapped drift scoring |

### How it works

1. **Detects** runtime versions, target frameworks, and all dependencies
2. **Scores** how far behind each component is — major version lag, EOL proximity, dependency age
3. **Reports** a deterministic Upgrade Drift Score (0–100) with findings in text, JSON, SARIF, or Markdown
4. **Gates** CI pipelines with configurable thresholds so drift never creeps back in

### Get started

```bash
# Scan your project
npx @vibgrate/cli scan .

# Save a baseline on main
npx @vibgrate/cli baseline .

# Enforce in CI
npx @vibgrate/cli scan . --fail-on error
```

No sign-up required. No source code leaves your machine.

### Links

- **Website** — [vibgrate.com](https://vibgrate.com)
- **Dashboard** — [dash.vibgrate.com](https://dash.vibgrate.com)
- **npm** — [@vibgrate/cli](https://www.npmjs.com/package/@vibgrate/cli)
- **Documentation** — [vibgrate.com/cli](https://vibgrate.com/cli)
- **X** — [@vibgrate](https://x.com/vibgrate)

---

<sub>© 2026 Vibgrate. All rights reserved.</sub>
