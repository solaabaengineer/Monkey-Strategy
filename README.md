# Monkey Strategy 

![image (25)](https://github.com/user-attachments/assets/e053c4c1-e477-4040-8bd8-160026c193cc)

https://x.com/MonkeyStrategyy


Monkey Strategy is a crypto-native treasury token that routes protocol-generated creator fees into **real, transparent donations for monkey conservation**.

This project starts as a memecoin to bootstrap attention and liquidity, then evolves into a **donation-backed treasury system** where every contribution is tracked, verifiable, and publicly reported.

## Mission

Build an on-chain donation engine for primate preservation:
- protect monkeys and their habitats
- fund vetted sanctuaries / conservation orgs
- make every donation transparent and auditable

## How It Works (High Level)

1. **Fees In**
- Every buy/sell of $MONKEY generates creator fees
- Fees flow into the project treasury wallet (on-chain)

2. **Treasury → Donations**
- On a fixed schedule (daily/weekly) or threshold trigger:
	- fees are converted to a stable asset (ex: USDC)
	- a donation batch is prepared
	- funds are sent to approved conservation wallets

3. **Proof + Reporting**
- Every donation is logged with:
	- on-chain transaction link
	- recipient details
	- amount and timestamp
	- optional receipt / confirmation uploaded in `proof/`

## Key Principles

- **Transparency-first:** everything visible on-chain + in the repo
- **No vague promises:** fees go to donations, not “marketing”
- **Community-driven:** the community can propose and vote on recipients (future)
- **Automation-ready:** keeper bot executes donation cycles (future)

## What’s in this Repo

- `program/` — Solana program (treasury state, donation execution, safety controls)
- `keeper/` — automation bot (fee monitoring, batching, scheduled donations)
- `dashboard/` — live public dashboard (treasury balance, donation history, receipts)
- `docs/` — methodology, recipient policy, donation cadence, risk analysis
- `proof/` — donation proofs, recipient confirmations, receipts

## Treasury Flow (Simple)

Creator Fees  
→ Treasury Wallet  
→ Convert to USDC  
→ Donate to approved recipients  
→ Publish proof + update dashboard  

## Safety & Controls

- spending caps per cycle
- cooldown between donations
- recipient allowlist (with review process)
- emergency pause
- full audit trail (events + logs)

## Roadmap

- v0: manual donation batches + proof uploads
- v1: automated keeper + on-chain donation events
- v2: community proposals + governance for recipients
- v3: multi-recipient allocation strategies + transparency scoring

## Disclaimer

Monkey Strategy is an experimental memecoin + donation treasury mechanism.
Not affiliated with any charity or institution by default.
No investment guarantees. Use at your own risk.

## Contributing

PRs welcome. If you want to help:
- improve the dashboard
- add donation verification tooling
- strengthen safety / monitoring
- expand recipient vetting process

See `CONTRIBUTING.md`.

# Monkey-Strategy
