# Random-stuff

## Cursor Discord chatbot prompt

If you want a Cursor Agent to chat in Discord with a specific style/persona, use this copy/paste prompt:

- `docs/discord-cursor-agent-prompt.md`

## GitHub Pages

The site in `docs/` deploys automatically on push to `main` via [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml).

**One-time setup (repo admin):** In the repository on GitHub, open **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**, then re-run the latest failed **Deploy GitHub Pages** workflow (or push an empty commit to `main`). The public URL will be `https://neutro74.github.io/Random-stuff/`.
