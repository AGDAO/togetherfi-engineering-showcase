# Security and Disclosure Boundary

## Purpose of this repository

This repository demonstrates engineering scope without exposing a reproducible implementation of TogetherFi.

## Public here

- High-level product and architecture descriptions
- Aggregate, anonymized engineering-activity metrics
- Milestone themes
- Technology categories
- Risk and status language
- Security principles without operational procedures

## Intentionally private

- Application source and raw Git history
- Smart-contract source, bytecode, deployable interfaces, and storage design
- Contract, wallet, signer, endpoint, and infrastructure identifiers
- Database schemas, migrations, records, and internal APIs
- Scoring formulas, anti-abuse rules, ranking logic, and confidence calculations
- Trading thresholds, routing, safety heuristics, spend controls, and exit logic
- Custody procedures, deployment scripts, incident runbooks, and recovery operations
- Environment configuration, secrets, credentials, RPC providers, and internal URLs
- Creator, customer, partner, legal, KYC, wallet, payout, and mission data
- AI prompts, private outputs, permissions, and internal model-routing policy

## No security-by-obscurity claim

Keeping proprietary implementation private is not the only security control. The platform also uses authorization, explicit state transitions, reconciliation, review gates, and chain-aware validation. Those mechanisms are described only at a principle level here to avoid giving attackers or competitors an operational map.

## Reporting a concern

Do not publish suspected vulnerabilities, personal data, wallet information, or private operational details in a public issue. Contact AGDAO through an established official channel and provide only the minimum information needed to begin a private review.

## Financial and legal notice

Nothing in this repository is investment, trading, legal, or financial advice. Automated and chain-based systems can fail. Assets can lose value. Network conditions, liquidity, counterparties, software defects, and configuration errors can cause loss. LegalFi outputs require appropriate professional review.
