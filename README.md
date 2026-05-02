# EvoClawSite

Static landing page for **EvoClaw** — the local-first self-evolving AI agent runtime in Rust.

**Live**: <https://develolin.github.io/EvoClawSite/>
**Code**: <https://github.com/DevEloLin/evoclaw>

## Pages

| File | What it is |
|------|------------|
| `index.html` | English landing page (hero, features, redaction, ACP/MCP, FAQ, JSON-LD SEO) |
| `zh.html` | 中文落地页 |
| `architecture-en.html` / `architecture-zh.html` | System architecture diagrams (CSS-grid layered view + mermaid flow charts) |
| `design-en.html` / `design-zh.html` | Design diagrams (Task / Skill / Memory FSM, ER, sequences, closure matrix) |
| `architecture.html` / `design.html` | Lightweight language-picker pages |
| `404.html` | Themed 404 |
| `sitemap.xml` · `robots.txt` · `.nojekyll` | SEO + Pages config |

## Local preview

```bash
python3 -m http.server -d . 8080
# open http://localhost:8080
```

## Publish

GitHub Pages serves this directory. Configure in repo Settings → Pages → Source: GitHub Actions; the workflow at
<https://github.com/DevEloLin/evoclaw/blob/main/.github/workflows/pages.yml> handles the upload + deploy.

## License

MIT — same as the EvoClaw runtime.
