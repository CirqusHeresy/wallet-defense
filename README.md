# 🛡 Wallet Defense for Creators

*Raise the cost of deception. Lower the cost of trust.* — The Inquisition

A field guide from a real theft. One of our founders' wallets was drained on **31 October 2024**. Sixteen months later the Inquisition traced the attacker's footprint: a marketplace profile linking nine wallets — the victim's among them — and assets parked on a centralized exchange.

We are not publishing names or addresses here. We are publishing what it taught us, so it costs you nothing to learn.

- 📋 **[CHECKLIST.md](CHECKLIST.md)** — 15 minutes, do it today
- 🚨 **[INCIDENT.md](INCIDENT.md)** — what to do in the first hour after a theft

---

## The case, in short

| | |
|---|---|
| **What was lost** | Hot-wallet assets, swept in one session |
| **How** | **[FOUNDER: the confirmed or most likely vector — e.g. signed malicious approval, leaked seed phrase, compromised device. Leave "unknown" if unknown.]** |
| **What the attacker did next** | Converted assets and moved them to a centralized exchange |
| **How he was found** | The attacker reused his own identity: a public NFT-marketplace profile connected the stolen wallet to eight others |
| **What it proved** | On-chain theft is not anonymous by default. Attackers get lazy. Evidence survives. |

## Seven lessons

**1. Your hot wallet is a till, not a vault.**
Keep in a browser or mobile wallet only what you'd carry in a pocket. Everything else goes to a hardware wallet or cold storage.

**2. One wallet per purpose.**
A *vault* (cold, never connects to dApps), a *daily* wallet (small balance), a *burner* (mints, airdrops, unknown sites). A drained burner is a lesson; a drained vault is a disaster.

**3. Approvals outlive the moment.**
Signing `setApprovalForAll` or an unlimited token approval gives a contract the right to move your assets *later*. Review and revoke old approvals regularly.

**4. Read what you sign.**
"Sign to verify", "claim your airdrop", "gasless listing" are classic drainer prompts. If the wallet shows a permit, an approval or a transfer you didn't intend — reject.

**5. Your seed phrase never touches a screen.**
No photos, no cloud notes, no password manager on the same device you sign with, no "support agent" ever asking for it. Metal or paper, offline.

**6. Exchanges are part of the attack surface — and part of the defense.**
Stolen funds often pass through a centralized exchange. Exchanges can freeze accounts — but only if you reach them fast, with evidence, through the right channel.

**7. Evidence decays, so collect it immediately.**
Transaction hashes, screenshots of approvals, timestamps, the URL you visited. The Inquisition's work started from screenshots taken on the day.

## Contributing

Seen a new drainer pattern? Have a case that taught you something? Open an issue or a pull request — anonymise third parties, never post private keys. Active incidents go to the [Inquisition](https://cirqusheresy.com/inquisition), not here.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — share and adapt with attribution to Cirqus Heresy.
