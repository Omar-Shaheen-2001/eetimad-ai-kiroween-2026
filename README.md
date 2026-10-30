# Eetimad AI — Ownership Verification Lab

> **Hackathon experimental prototype** by PIDEA (Professional Innovation & Digital Engineering Agency).

**Tagline:** Secure Your Assets. Verify Ownership. Build Digital Trust.

## What is implemented
A browser-local, self-declared asset record demonstration with:
- Asset entry (name, category, example serial/reference)
- UUID-based local record IDs
- Search and deletion
- Browser localStorage persistence
- Clear distinction between registered and independently verified ownership

**Important:** This is not a verified ownership registry. No AI, blockchain, genuine transfer workflow, independent identity checks, or backend service is implemented. Do not enter real IMEI numbers, ownership documents, or sensitive personal data.

## Quick start
Requires Node.js 20.9+ and npm.

```bash
npm install
npm run dev
```

Open http://localhost:3000. To run basic checks: `npm run typecheck` and `npm run build`.

## Kiro documentation
The repository includes `.kiro/steering/` product and tech principles and `.kiro/specs/asset-verification/` requirements, design and task checklists. These are **initial author-written starter files**, not a claim that Kiro created or executed them. Open the project in Kiro, use its spec-driven workflow, and commit the genuine output before submitting.

## Hackathon category
Intended candidate: **Frankenstein**, subject to delivering a demonstrable integration of distinct components during the eligible timeframe. The current local-only MVP does **not** yet demonstrate that category.

## Origin and prior work
The wider Eetimad concept and a separate prior platform predate this repository. This repository is a new standalone lab starter, not a copy of or claim to have rebuilt the prior platform. Reused code, assets or research should be explicitly acknowledged if added.

## Project status and evidence
- Initial code: provided as a standalone starter; working build not verified in this packaging environment.
- Real Kiro usage: not yet documented.
- AI verification: planned, not implemented.
- Demo video: an authentic walkthrough of working code still required.

See [submission checklist](docs/DEVPOST_CHECKLIST.md).

## License
MIT — see [LICENSE](LICENSE). The owner must confirm authority to release all committed components under this license.
