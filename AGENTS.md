# Repository instructions for AI/code agents

Read the [canonical guidebook](https://github.com/Cucklord420/Toe-Tickling/blob/main/GUIDEBOOK.md) on its current default branch before substantive work. Apply it alongside the instruction hierarchy and existing project requirements. Record the revision actually consulted, and do not claim unperformed checks as passed.

## Repository-specific boundaries

- This is an inherited ClearVision v6 BetterDiscord theme. Its source is SCSS and its distributed output is CSS. Preserve these native formats, selectors, customization variables, theme metadata, and compatibility requirements; their continued existence is not a failed Rust migration.
- Under the guidebook, **new first-party executable code and tests** must be Rust. Do not replace working inherited Sass or platform interfaces without independently verified source-to-output and runtime parity.
- Before changing styles or build behavior, inspect `main.scss`, `hljs.scss`, `package.json`, `package-lock.json`, `.github/workflows/build.yml`, and `.github/workflows/test.yml`. Existing build entry points are `npm ci`, `npm run build`, and `npm test`. Compare compiled CSS and verify the actual distributed theme; a successful compile does not prove current BetterDiscord compatibility.
- Preserve the inherited Apache-2.0 license and original attribution; a project instruction does not silently relicense third-party assets or upstream code. Preserve upstream notices and don't assume ownership of remotely imported styles or images.
- Keep changes isolated and reversible. Check open PRs before editing. Do not expose credentials, private user data, or repository deployment tokens; do not deploy or claim deployment without verified authorization and execution.

This file links to the owner's operating guidebook but does not override platform instructions or grant new permissions.
