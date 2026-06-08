# genesys-contact-center-risk-board

Board-readable Kinetic Gain proof repo for **Genesys** platform and company signal coverage.

## Product thesis

Customer-contact risk is difficult to explain when queues, agent readiness, outage posture, and escalation signals are fragmented.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** CX leaders, contact-center operators, support executives, and incident commanders
- **Signal domain:** CX / Contact Center
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product maps queue leakage, agent readiness, service outages, customer impact, and executive comms into one risk surface.
- **Value architecture:** Leaders can prioritize where service quality, staffing, routing, and customer-trust remediation need investment.

## What this repo proves

- **Normalize:** messy Genesys operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: Genesys queues, agent states, routing rules, service incidents, SLAs, and escalation messages.

This is synthetic proof only. It does not connect to live Genesys tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- Genesys
- contact center
- CX operations
- queue risk
- agent readiness
