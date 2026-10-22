# Contributing

Thanks for taking the time to contribute! These guidelines apply to all of
[Diamond Rubinny's](https://github.com/diamondrubinny) open-source projects,
unless a repository has its own `CONTRIBUTING.md`.

## Ways to help
- ⭐ **Star** the project — it helps others discover it
- 🐛 **Report bugs** using the Bug report template
- 💡 **Suggest features** using the Feature request template (or Discussions, where enabled)
- 🌍 **Translate** — Hebrew/RTL and multilingual support matter in every project
- 🔀 **Send a pull request**

## Pull request workflow
1. Open an issue first for anything larger than a small fix, so we can agree on the approach.
2. Fork the repo and create a branch: `fix/short-description` or `feat/short-description`.
3. Keep changes focused — one topic per PR.
4. Follow the existing code style; run the project's linter and tests before pushing.
5. Update docs (README, `.env.example`) when behavior or configuration changes.
6. Fill in the pull request template.

## Ground rules
- **Never commit secrets** — API keys, tokens, passwords or real personal data. Use `.env` files (git-ignored) and update `.env.example` with placeholders only.
- **Accessibility** — UI changes must keep keyboard navigation, visible focus, labels and contrast (target: WCAG 2.1 AA).
- **RTL** — UI changes must work in both LTR and RTL layouts.
- **Security** — validate input on the server, check authorization on every protected action.

## Commit messages
Use short, imperative messages, e.g. `Fix RTL alignment in settings page`.
[Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`) are welcome.

## Security issues
Do **not** open public issues for vulnerabilities — see [SECURITY.md](SECURITY.md).

## License
By contributing, you agree that your contributions are licensed under the license of the repository you contribute to.
