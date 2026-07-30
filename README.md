# The Wake of the World: dice ledger

Every secret GM-side d20 in this campaign was fixed before session zero and is
consumed from hash chains committed at genesis. This repo receives the
published ledger after each session; its commit history is an append-only
witness the GM cannot quietly rewrite.

**Verify it yourself:** <https://dgoeke.github.io/wotw-ledger/>, or save
`verify.html` locally (it works from `file://`) and open `ledger.json` with it.
The verifier explains exactly what this proves and what it cannot.

## License

- The code in this repo (`verify.html`, `index.html`) is licensed under the
  [Apache License 2.0](LICENSE). It is published from
  [prophecy-dice](https://github.com/dgoeke/prophecy-dice).
- The ledger records (`ledger.json` and any other generated data files) are
  dedicated to the public domain under [CC0 1.0](LICENSE-DATA). Mirror them,
  archive them, embed them in your own tooling; no permission or attribution
  is needed. Their authenticity comes from the protocol's commitments, not from
  copyright: check any copy with `verify.html` rather than trusting the mirror.
