# Tessera

Keep the whole case in one place.

A case notebook for an incident: findings and how sure you are, the key events, indicators, scope, evidence with its hashes, and every decision. Paste any alert and it pulls the indicators out, defanged or not. Recap and Hexes send straight into it, and it exports the report, the indicators as CSV or a YARA rule, and the case file to keep or hand in.

**Good for:** Running an investigation, writing it up, and handing in coursework.

**Live:** https://jon.glass/tessera/

A single self-contained page with no build step. Open `index.html` or serve the folder over HTTPS.

Uses the shared suite script at `/assets/suite/handoff.js` from [jon.glass](https://jon.glass) to pass data between tools, so cross-tool handoff only works when served from jon.glass.

## License

MIT © 2026 [Jon Glass](https://jon.glass/). Use it however you like; just keep the copyright notice. See [LICENSE](LICENSE).
