# genesys-contact-center-risk-board

Board-readable Kinetic Gain proof repo for **Genesys** signal coverage.

## Signal lane

- Vendor / platform: Genesys
- Domain: Contact Center
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

Contact-center risk, journey handoffs, service quality, and operational evidence posture.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for Genesys without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.
