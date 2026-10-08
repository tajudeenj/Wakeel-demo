# Wakeel (وكيل) — live demo

The trust layer for the agent economy. An AI agent opens a café in Dubai, but it can only act inside a signed, revocable mandate.

**Live demo:** https://tajudeenj.github.io/Wakeel-demo/

## What the demo shows
- A digital mandate (scope, spend cap, approval threshold, expiry) signed with ECDSA P-256
- A policy guard that checks every agent action before it runs
- A compliance stop against a sandbox watchlist
- Step-up approval by the principal
- A kill switch that revokes the mandate instantly
- A SHA-256 hash-chained evidence ledger with tamper detection

Counterparty agents and the watchlist are sandboxed and fictional. The signing, guard rules, kill switch and ledger are real and run in the browser.

## Run locally
```
python -m http.server 8080
```
Then open http://localhost:8080

Built for the Create AI Agents Championship, Dubai 2026–27.
