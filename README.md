# Hi, I'm Reza 👋

Independent security researcher working on **authorization and revocation in ERC-4337 / ERC-7579 smart accounts**: how session keys, permission modules, and guardian confirmations behave when authority is revoked or its configuration changes.

## What I work on

- 🔎 **Research**: code-reading comparisons and test patterns for revocation and authorization-path parity. I report a finding only when a PoC on the real code confirms it.
- 📐 **Spec work**: a conformance-property proposal for ERC-7579 (revocation monotonicity and authorization-path parity), on [Ethereum Magicians](https://ethereum-magicians.org/t/erc-7579-minimal-modular-smart-accounts/17336).
- 🛠️ **[Pylon](https://github.com/pyloninfra/pylon-sdk)**: an ERC-4337 paymaster SDK and session-key manager I built (Base Sepolia testnet, unaudited). It is the testbed for this research.
- 📝 **Writing**:
  - [Revocation in AA Wallets: Atomicity as a Design Question](https://paragraph.com/@pyloncore/revocation-isnt-atomic-a-recurring-bug-class-in-account-abstraction-wallets)
  - [When “Restricted” Only Means Restricted on One Path](https://paragraph.com/@pyloncore/when-restricted-only-means-restricted-on-one-path)
  - [Reading the Revocation Paths of Six AA Wallets](https://paragraph.com/@pyloncore/i-checked-six-major-aa-wallets-for-a-bug-class-that-broke-one-wallets-revocation-heres-what-i-found)

## Security reviews

I offer focused reviews of revocation and authorization-lifecycle flows in AA and modular-account systems: session-key expiry and revocation, policy and signer module removal sequencing, recovery and guardian confirmation handling, and related state-consistency issues.

## Contact

- 🌐 [pylon-security.pyloncore.workers.dev](https://pylon-security.pyloncore.workers.dev/#contact)
- 📧 <pyloncore@gmail.com>
- 🐦 [@pyloninfra](https://x.com/pyloninfra)

---

> I publish what I can reproduce, and I correct what I get wrong.