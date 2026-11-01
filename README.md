# Smart Contract Security Audit Solver (`audit-auto-solver`)

Autonomous EVM smart contract competitive security auditor and bug bounty solver for Code4rena and Sherlock.

- Orchestrates Claude Sonnet 4.6 multi-session reasoning with Foundry (`forge`) verification.
- Enforces a zero-false-positive invariant: all reported findings must have passing `Exploit.t.sol` proofs.
- 24/7 continuous discovery, auditing, and report generation via GitHub Actions.
