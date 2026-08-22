# ADHD Documentation

Mintlify documentation for [**ADHD**](https://github.com/UditAkhourii/adhd) — parallel divergent ideation for coding agents, an architectural fix for premature convergence in autoregressive reasoning.

## Structure

- `docs.json` — Mintlify site configuration (theme, navigation, navbar, footer)
- `index.mdx` — introduction
- `quickstart.mdx`, `installation.mdx` — getting started
- `concepts/` — how it works, frames, vs CoT & ToT, when to use
- `usage/` — the agent skill, CLI reference, library reference, agent integration
- `evals/` — results, methodology, roadmap
- `community/` — adopters & ecosystem, contributing

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview changes locally:

```bash
npm i -g mint
```

Run the following at the root of the repo, where `docs.json` is located:

```bash
mint dev
```

View the local preview at `http://localhost:3000`.

## Publishing changes

Changes are deployed to production automatically after pushing to the default branch (via the Mintlify GitHub app — manage it from the [dashboard](https://dashboard.mintlify.com/settings/organization/github-app)).

## Troubleshooting

- If the dev environment isn't running: run `mint update` to get the latest CLI.
- If a page loads as a 404: make sure you are running in the folder with `docs.json`.

## License

MIT — same as the [ADHD project](https://github.com/UditAkhourii/adhd).
