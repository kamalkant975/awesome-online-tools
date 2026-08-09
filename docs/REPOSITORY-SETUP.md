# Repository Setup Reference

Copy-paste values for GitHub repo settings, plus the growth strategy behind this list. This file is for you (the maintainer) — it's not linked from the README.

## Repository Description (GitHub "About" field)

```
A curated list of 200+ free online tools for PDF, image, AI, developer, SEO, text, and everyday tasks — no sign-up, no watermark, no upload limits.
```

## Social Preview Description

Used for the Open Graph / link-preview card GitHub generates when this repo is shared:

```
Awesome Online Tools — a curated, community-maintained list of 200+ free
browser-based tools (PDF, image, AI, developer, SEO, calculators, text)
for developers, students, freelancers, and businesses.
```

Upload a custom 1280×640 social preview image in **Settings → Options → Social Preview** for best results — reuse the same OG image already live on the website (`onlinetoolkithub.com/opengraph-image`) or a variant with the repo name overlaid.

## GitHub Topics (Repository Tags)

Add these under **Settings → Topics** (GitHub allows up to 20; these are ranked by relevance):

```
awesome awesome-list online-tools free-tools pdf-tools image-tools
developer-tools seo-tools text-tools calculator webdev productivity
free-resources tools-list curated-list open-source resources
webtools utilities hacktoberfest
```

## SEO Keywords (for README content and repo description)

Primary: `free online tools`, `awesome list`, `pdf tools`, `image tools`, `developer tools`, `seo tools`, `text tools`, `online calculator`

Secondary/long-tail: `free tools for developers`, `free online tools no sign up`, `awesome list of free tools`, `browser based tools`, `free pdf and image tools 2026`

Use these naturally in section headers and descriptions — GitHub's own search and Google both index README content, so keyword-stuffing isn't necessary, but natural inclusion in headers helps both.

## Folder Structure

```
awesome-online-tools/
├── README.md                          # Main list — entry point
├── CONTRIBUTING.md                    # How to contribute
├── CODE_OF_CONDUCT.md                 # Community standards
├── LICENSE                            # CC0 1.0
├── SECURITY.md                        # Vulnerability/bad-link reporting
├── SUPPORT.md                         # Where to get help
├── CHANGELOG.md                       # Notable changes over time
├── ROADMAP.md                         # Platform + list roadmap
├── docs/
│   └── REPOSITORY-SETUP.md            # This file
└── .github/
    ├── PULL_REQUEST_TEMPLATE.md
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        ├── feature_request.md
        └── tool_request.md
```

## Best Practices to Earn GitHub Stars

1. **Submit to `sindresorhus/awesome`** — the master list of awesome lists. Getting listed there is the single highest-leverage star driver available; it sends steady, compounding traffic. Follow their strict quality guidelines (they're picky about README structure, badges, and license — this repo is already built to match).
2. **Post the launch on Hacker News (Show HN), r/webdev, r/opensource, and Indie Hackers** — framed as "I built a curated list of tools I actually use," not as a promotion.
3. **Add topics/tags** (above) — GitHub's topic pages are a real discovery surface; a well-tagged repo gets found by people browsing `github.com/topics/awesome-list`.
4. **Keep it actively maintained** — a repo with commits in the last 30 days ranks better in GitHub's own search and looks more trustworthy to potential stargazers than a stale one. Merge contributions promptly.
5. **Cross-link from the website** — add a "View on GitHub" link/badge on the OnlineToolkitHub footer or About page; visitors who are developers are your highest-propensity stargazers.
6. **Encourage first-time contributors** — label a few issues `good first issue`; first-PR contributors reliably star repos they've contributed to.
7. **Add a `hacktoberfest` topic** in October — well-curated awesome lists get a real traffic and PR spike during Hacktoberfest.

## Suggestions to Rank on Google

- GitHub READMEs are indexed by Google and often rank for "awesome [category] tools" style queries — the H2 section headers here (PDF Tools, Image Tools, etc.) are deliberately phrased to match how people search.
- Backlinks to the repo (from the sindresorhus list, Hacker News, blog mentions) are what actually move the ranking needle — the content structure alone won't outrank established lists without them.
- Keep the repo name and description keyword-relevant (`awesome-online-tools` already matches the "awesome-x" naming convention Google associates with curated lists).
- A repo with a real star count and recent activity outranks a stale, unstarred one for the same query — the "GitHub Stars" and "Google ranking" strategies reinforce each other.

## Driving Website Traffic Without Looking Spammy

The list only works as a growth channel if it reads as genuinely useful on its own, independent of the website. A few rules to keep it from feeling like a thinly-veiled ad:

- **Include real third-party tools, not just OnlineToolkitHub ones**, especially in categories where the platform doesn't yet have deep coverage (AI tools, for instance). A list that only links to one domain reads as self-promotion and won't get accepted into `sindresorhus/awesome` or shared organically.
- **Let the README stand alone.** Someone should be able to use this list without ever clicking through to onlinetoolkithub.com's homepage — the tool links, blog links, and collection links are the value, not a sales pitch.
- **Keep the Development Services section small and clearly labeled**, exactly as it is now — one section near the bottom, not scattered as calls-to-action throughout. That's the difference between "here's a resource, and by the way here's what I do" versus a list that feels like bait.
- **Don't gate anything.** Every link should go straight to the free tool, not to a landing page asking for an email first.
- Traffic will come naturally from people using the list, clicking through to try tools, and — for the subset who are developers/founders — noticing the Development Services section on their own.
