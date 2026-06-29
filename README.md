# JavaScript Built-in Functions — Interview Cheatsheet

> A comprehensive, interactive reference for JavaScript's most important predefined functions — built for senior-level interview preparation.

**🌐 Live site:** [ManikandanRajendran.github.io/js-builtins-cheatsheet](https://ManikandanRajendran.github.io/js-builtins-cheatsheet)

---

## What's inside

| Category | Functions | Examples | LeetCode Problems |
|---|---|---|---|
| Array | 14 | 5–6 each | 5 each |
| String | 9 | 5–6 each | 5 each |
| Object | 6 | 5 each | 5 each |
| Set & Map | 2 | 5–6 each | 5 each |
| Number / Math | 8 | 5 each | 5 each |
| **Total** | **39 functions** | **200+ examples** | **195 problems** |

## Features

- **Tabbed examples** — 5–6 real, runnable code examples per function
- **LeetCode integration** — 5 curated problems per function with difficulty badges (Easy / Medium / Hard) and a one-line hint explaining which concept to apply
- **Day / Night theme** — toggles with one click, persists via localStorage, auto-detects system preference
- **Live search** — instantly filters by function name, description, or use case
- **Category filter** — focus on Array, String, Object, Set & Map, or Number/Math
- **Zero dependencies** — single HTML file, no frameworks, no build step

## Key interview concepts covered

- **Mutation vs immutability** — which methods mutate (`sort`, `reverse`, `splice`) vs return new arrays (`map`, `filter`, `slice`)
- **`map` vs `forEach`** — when to use each and why `forEach` always returns `undefined`
- **`find` vs `filter`** — early exit vs full scan
- **`reduce` as the universal tool** — how it subsumes map, filter, and more
- **`Set` for O(1) deduplication** — the `[...new Set(arr)]` pattern
- **`Map` over plain objects** — when any-type keys, `.size`, and insertion order matter
- **`Number.isNaN` vs global `isNaN`** — why strict checking matters

## Tech stack

- Vanilla HTML / CSS / JavaScript — no frameworks
- Single-file architecture (everything in `index.html`)
- Hosted on GitHub Pages

## Local development

```bash
git clone https://github.com/ManikandanRajendran/js-builtins-cheatsheet.git
cd js-builtins-cheatsheet
# Open index.html in your browser — no build step needed
open index.html
```

## Deploying to GitHub Pages

See [DEPLOY.md](./DEPLOY.md) for step-by-step instructions.

---

## Author

**Manikandan Rajendran** — Senior Test Automation Engineer with 14+ years of experience across Playwright, Cypress, Appium, Detox, WebdriverIO, JavaScript, TypeScript, and Python.

- GitHub: [github.com/ManikandanRajendran](https://github.com/ManikandanRajendran)
- LinkedIn: [linkedin.com/in/manikandan-rajendran-48863b36](https://www.linkedin.com/in/manikandan-rajendran-48863b36/)

---

## Contributing

Found a bug or want to add more functions? PRs welcome. Please keep the single-file architecture and zero-dependency principle.

## License

MIT — free to use, share, and adapt with attribution.
