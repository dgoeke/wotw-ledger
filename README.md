# The Wake of the World — dice ledger

Every secret GM-side d20 in this campaign was fixed before session zero and is
consumed from hash chains committed at genesis. This repo receives the
published ledger after each session; its commit history is an append-only
witness the GM cannot quietly rewrite.

**Verify it yourself:** <https://dgoeke.github.io/wotw-ledger/> — or save
`verify.html` locally (it works from `file://`) and open `ledger.json` with it.
The verifier explains exactly what this proves and what it cannot.
