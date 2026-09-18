# Hi, I'm Reza 👋

Independent security researcher focused on **authorization-revocation risk in ERC-4337 / ERC-7579 smart accounts** — cases where session keys, permission modules, or guardian confirmations stay valid after a revocation or configuration change, because the authorization evidence isn't invalidated atomically with the underlying state.

## What I work on

- 🔎 **Security research** — hands-on vulnerability research into how session keys and modular smart accounts actually fail in production, not just how they're supposed to work.
- 🛠️ **[Pylon](https://pylon-security.pyloncore.workers.dev)** — a session-key manager and paymaster SDK I built myself, which is the technical foundation the research is grounded in.
- 📝 **Writing** — [*Revocation Isn't Atomic*](https://paragraph.com/@pyloncore/revocation-isnt-atomic-a-recurring-bug-class-in-account-abstraction-wallets), on a recurring bug class in account abstraction wallets.
- 🕵️ Currently in **responsible disclosure** on a live finding — details embargoed until publication.

## Security reviews

I offer focused reviews of revocation and authorization-lifecycle flows in AA/modular-account systems — session-key expiry and revocation, policy/signer module removal sequencing, recovery and guardian confirmation handling, and related state-consistency issues.

## Contact

- 🌐 [pylon-security.pyloncore.workers.dev](https://pylon-security.pyloncore.workers.dev/#contact)
- 📧 pyloncore@gmail.com
- 🐦 [@pyloninfra](https://x.com/pyloninfra)

---

> *Still looking for the cracks in the code nobody else bothered to check.*
