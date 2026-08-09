# Contributing to Awesome Online Tools

Thanks for considering a contribution. This repository stays useful only if it stays accurate, so contributions of any size — a new tool, a fixed link, a clearer description — are genuinely welcome.

## Ways to Contribute

1. **Suggest a new tool** — either from [onlinetoolkithub.com](https://www.onlinetoolkithub.com) or a third-party free tool worth listing
2. **Fix a broken or outdated link**
3. **Improve a description** for clarity or accuracy
4. **Suggest a new category or collection**
5. **Report an issue** using the templates in `.github/ISSUE_TEMPLATE`

## Suggesting a Tool

Before opening a pull request, check that the tool:

- Is **free to use** (a free tier is fine; a tool that's entirely paywalled is not)
- **Works reliably** — no broken pages, expired domains, or excessive pop-ups
- **Does not require a mandatory account/sign-up** just to try the core feature
- Fits one of the existing categories, or makes a reasonable case for a new one

If you're not sure, open an issue first using the **Tool Request** template instead of a pull request — it's faster to discuss before writing.

## Coding / Formatting Standards

This repository is markdown-only. Keep entries consistent with the existing style:

```markdown
| [Tool Name](https://example.com/tool) | One-sentence description, no marketing language |
```

- One row per tool, alphabetized within its category table where practical
- Descriptions should be factual and under ~15 words — no "the best," "amazing," or "revolutionary"
- Use sentence case for descriptions, not Title Case
- Run entries through a markdown linter (e.g. `markdownlint`) before submitting if you're adding more than a couple of lines
- Do not add affiliate links, tracking parameters, or referral codes to any URL

## Pull Request Process

1. Fork the repository and create a branch from `main`: `git checkout -b add-tool-name`
2. Make your change, keeping the diff focused on a single addition or fix
3. Confirm all links in your change resolve (no 404s, no redirects to unrelated pages)
4. Fill out the pull request template completely — incomplete PRs will be asked for more detail before review
5. One maintainer review is required before merge; expect feedback within a few days, not hours
6. Once merged, you'll be credited in the next entry of [CHANGELOG.md](CHANGELOG.md)

## Issue Guidelines

Use the appropriate template:

- **Bug Report** — a broken link, wrong description, or formatting issue
- **Feature Request** — a new section, category, or structural change to the list
- **Tool Request** — suggesting a specific tool be added

Please search existing issues before opening a new one to avoid duplicates.

## Code of Conduct

Participation in this project is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). Be respectful — disagreements about whether a tool belongs on the list are fine; personal attacks are not.

## License

By contributing, you agree that your contributions will be licensed under this repository's [CC0 1.0](LICENSE) license, meaning your additions become part of the public-domain-dedicated list.
