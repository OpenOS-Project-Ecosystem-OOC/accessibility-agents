# accessibility-agents

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/accessibility-agents) [![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria)


<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install


```bash
npm install
node scripts/install.mjs
```

That copies the skills to `~/.agents/skills`, the shared location Codex,
Copilot, Gemini and Antigravity read, and writes the hook manifest for whichever
clients are present. It never overwrites a hooks file or a skill you have
edited. Add `--dry-run` to see what it would do.

As a plugin, which wires the hooks for you:

```text
Claude Code   /plugin marketplace add Community-Access/accessibility-agents
Copilot       copilot plugin install accessibility-agents
Codex         /plugins, then add this repository
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/accessibility-agents`](https://github.com/Interested-Deving-1896/accessibility-agents) and mirrored through:

```
Interested-Deving-1896/accessibility-agents  ──►  OpenOS-Project-OSP/accessibility-agents  ──►  OpenOS-Project-Ecosystem-OOC/accessibility-agents
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
| Contributor | Commits |
|---|---|
| [@accesswatch](https://github.com/accesswatch) | 223 |
| [@taylorarndt](https://github.com/taylorarndt) | 76 |
| [@dependabot[bot]](https://github.com/apps/dependabot) | 27 |
| [@Copilot](https://github.com/apps/copilot-swe-agent) | 11 |
| [@github-actions[bot]](https://github.com/apps/github-actions) | 10 |
| [@tesles](https://github.com/tesles) | 8 |
| [@Orinks](https://github.com/Orinks) | 4 |
| [@ChrisDuffley](https://github.com/ChrisDuffley) | 4 |
| [@zuhairmahd](https://github.com/zuhairmahd) | 1 |
| [@devinprater](https://github.com/devinprater) | 1 |
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream influences recorded._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## Accessibility

<!-- AI:start:accessibility -->
This repo uses automated accessibility auditing via `check-accessibility.yml`.

Checks include: CODEOWNERS ownership coverage, README screen-reader compatibility,
WCAG 2.1 AA HTML compliance, audio overview (espeak-ng), and Braille output (liblouis).




Run the [Check Accessibility](https://github.com/Interested-Deving-1896/accessibility-agents/actions/workflows/check-accessibility.yml)
workflow to generate the first report and accessibility artifacts.
See the [W3C Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/)
for the underlying accessibility reference.
<!-- AI:end:accessibility -->

## License

<!-- AI:start:license -->
[MIT](https://github.com/Interested-Deving-1896/accessibility-agents/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
