# ICO Accountability Assessment — AiLA

Self-assessment tool based on the ICO's Accountability Framework. Evaluates an organisation's data protection compliance position across the ICO's 10 framework categories, generates a scored report with prioritised remediation actions.

## What it covers

42 questions across 10 categories matching the ICO's framework:

1. Leadership & Oversight
2. Policies & Procedures
3. Training & Awareness
4. Individuals' Rights
5. Transparency
6. Records of Processing & Lawful Basis
7. Contracts & Data Sharing
8. Risks & DPIAs
9. Records Management & Security
10. Breach Response & Monitoring

## How scoring works

Each question is answered as: fully in place (3), partially in place (2), not started (1), or not applicable. Questions carry weights (1–3) reflecting the ICO's priorities. Scores are calculated per section and overall as a weighted percentage.

Every gap is assigned a severity (critical / high / medium / low) and effort estimate (quick win / moderate / significant). The action plan ranks gaps by a priority score combining severity, effort, and status — so critical gaps with quick fixes surface first.

## Report output

- Executive summary with overall score and narrative
- Section-by-section scores with progress bars
- Prioritised action plan with specific remediation steps per gap
- Summary table with owner and target date columns (blank for user to complete)

## Tech stack

- React 18
- Vite
- No backend — runs entirely in the browser
- Deployed on Vercel

## Local development

```bash
npm install
npm run dev
```

## Deployment

Push to GitHub, connect repo to Vercel. Auto-deploys on every commit.

## Sources

- ICO Accountability Framework (2024)
- UK GDPR (Articles 5, 13–15, 17, 24–25, 28, 30, 32–36)
- Data Protection Act 2018
- ICO enforcement actions and guidance 2022–2025

## Related

- [DSAR Readiness Assessment](https://dsar-readiness.vercel.app/) — companion tool assessing DSAR handling capability
- [LOCS:23 Gap Analysis](https://locs23-tool.vercel.app/) — assessment against the Law Society's LOCS:23 certification standard

---

© AiLA AI Ltd · [trustaila.com](https://trustaila.com)# ico-accountability
