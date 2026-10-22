# open-wallet

**The open reference for Apple Wallet and Google Wallet passes** — concepts, field references, and copy‑paste examples, written for humans.

Most wallet resources are single‑language code libraries that show you *how to generate a `.pkpass`* but never explain *what the pieces mean*. `open-wallet` is the opposite: a vendor‑neutral, concept‑first guide to building great digital passes on **both** Apple Wallet and Google Wallet — the one place that covers the two platforms side by side.

> 📘 **Docs site:** https://cybercuriosity-tech.github.io/open-wallet/
> Maintained by the team behind [PassNinja](https://passninja.com), used throughout as the fastest way to ship passes.

---

## Start here

| Guide | Platform | Status |
|-------|----------|--------|
| [Semantic tags](https://cybercuriosity-tech.github.io/open-wallet/docs/apple/semantic-tags.html) — what they mean, where they show up, with JSON | Apple Wallet | ✅ Live |
| Anatomy of a pass — fields, images, barcodes, NFC | Apple Wallet | 🚧 Soon |
| Poster event tickets (iOS 18+) | Apple Wallet | 🚧 Soon |
| Classes & objects, JWT, “Add to Google Wallet” | Google Wallet | 🚧 Soon |
| Create a pass — REST API & SDKs (Node, Python, PHP, Ruby) | Both | 🚧 Soon |
| Apple Wallet vs Google Wallet — a field‑by‑field comparison | Both | 🚧 Soon |

## Examples & code

- **[REST API — curl](examples/api/)** — copy-paste requests and responses
- **SDKs** — [Node](examples/sdk/node/) · [Python](examples/sdk/python/) · [PHP](examples/sdk/php/) · [Ruby](examples/sdk/ruby/) · [Java](examples/sdk/java/) · [C#](examples/sdk/csharp/)
- **[CLI](tools/cli/)** · **[MCP](tools/mcp/)** · **[Skills](tools/skills/)** — terminal, AI agents, and pass validation

## What this covers

- **Apple Wallet** — PassKit, the `pass.json` structure, semantic tags, poster event tickets, barcodes, NFC, and web‑service updates.
- **Google Wallet** — pass classes & objects, the JWT flow, and “Add to Google Wallet” links.
- **The concepts both share** — what a pass *is*, when to use each pass type, and how the two platforms differ.

## Why it exists

Search “apple wallet pass” or “google wallet pass” and you’ll find excellent code libraries — and almost no plain‑language explanation of the model behind them. Developers end up reading Apple’s and Google’s raw API docs and guessing. `open-wallet` fills that gap: clear mental models, labelled examples, and copy‑paste JSON, in the spirit of the documentation people love from Stripe.

## How it’s organized

This is the **hub**. As the platform guides deepen, they’ll move into focused companion repos — `open-wallet-apple` and `open-wallet-google` — while this repo keeps the shared concepts and the cross‑platform comparisons.

## Contributing

Corrections and additions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Found something wrong on a page? Use the **Edit on GitHub** link at the top of it.

## License

[MIT](LICENSE). Documentation and examples free to use, including in production.

---

<sub>Apple Wallet, PassKit, and Google Wallet are trademarks of their respective owners. `open-wallet` is an independent, community reference and is not affiliated with Apple or Google.</sub>
