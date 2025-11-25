---
"@solana/react-hooks": minor
---

Remove the Wallet Standard hook exports in favor of connector-driven flows. `useWalletConnection` now relies solely on client-registered (or explicitly provided) connectors, and signing is done via connector-provided session methods instead of Wallet Standard packages.
