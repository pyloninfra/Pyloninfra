Hi, I'm Reza 👋
Independent security researcher focused on authorization-revocation risk in ERC-4337 / ERC-7579 smart accounts — cases where session keys, permission modules, or guardian confirmations stay valid after a revocation or configuration change, because the authorization evidence isn't invalidated atomically with the underlying state.
What I work on

* 🔎 Security research — hands-on vulnerability research into how session keys and modular smart accounts actually fail in production, not just how they're supposed to work.
* 🛠️ [Pylon](https://pylon-security.pyloncore.workers.dev/) — a session-key manager and paymaster SDK I built myself, which is the technical foundation the research is grounded in.
* 📝 Writing — three writeups on a recurring bug class in account abstraction wallets:
   * [Revocation Isn't Atomic](https://paragraph.com/@pyloncore/revocation-isnt-atomic-a-recurring-bug-class-in-account-abstraction-wallets)
   * [When "Restricted" Only Means Restricted on One Path](https://paragraph.com/@pyloncore/when-restricted-only-means-restricted-on-one-path)
   * [I Checked Six Major AA Wallets for This Bug Class](https://paragraph.com/@pyloncore/i-checked-six-major-aa-wallets-for-a-bug-class-that-broke-one-wallets-revocation-heres-what-i-found)
* 📐 Proposed this as a [conformance property for ERC-7579](https://ethereum-magicians.org/t/erc-7579-minimal-modular-smart-accounts/17336) — pushing it toward spec language rather than leaving it as implementation guidance.

Security reviews
I offer focused reviews of revocation and authorization-lifecycle flows in AA/modular-account systems — session-key expiry and revocation, policy/signer module removal sequencing, recovery and guardian confirmation handling, and related state-consistency issues.
Contact

* 🌐 [pylon-security.pyloncore.workers.dev](https://pylon-security.pyloncore.workers.dev/#contact)
* 📧 [pyloncore@gmail.com](mailto:pyloncore@gmail.com)
* 🐦 [@pyloninfra](https://x.com/pyloninfra)

Still looking for the cracks in the code nobody else bothered to check.