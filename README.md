# Openmoon docs

Source of [docs.openmoon.fun](https://docs.openmoon.fun), built with [Mintlify](https://mintlify.com).

- Pages are MDX files: `index.mdx`, `concepts/`, `launchpad/`, `resources/`, `faq.mdx`.
- Navigation, theme and links are in `docs.json`. A new page must be added there to appear in the sidebar.
- Changes pushed to `main` are deployed by Mintlify.

Preview locally with the Mintlify CLI:

```bash
npm i -g mint
mint dev
```

Facts in these pages describe the ACP program on Solana mainnet and the Openmoon services as they work today. When the code changes, update the page that describes it.
