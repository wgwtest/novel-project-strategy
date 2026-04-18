# Novel Project Strategy

[![GitHub stars](https://img.shields.io/github/stars/wgwtest/novel-project-strategy?style=social)](https://github.com/wgwtest/novel-project-strategy/stargazers)
[![GitHub release](https://img.shields.io/github/v/release/wgwtest/novel-project-strategy)](https://github.com/wgwtest/novel-project-strategy/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

A Codex skill for longform fiction workflow, chapter-state tracking, reload discipline, and project recovery when a novel is too large to manage by reading the whole manuscript every session.

## Why Use It

This skill is for novel projects that need governance, not just better prose.

It helps Codex:

- recover a longform fiction project in a fresh session
- decide what to load first and what to leave cold
- separate chapter-local truth from outline, setting, and timeline truth
- keep drafted, confirmed, and synced states distinct
- stop project facts from drifting across chat, files, and manuscript layers

## Good Fit

Use this repo when the main problem is project structure:

- you need a workspace bootstrap for a novel project
- the manuscript is too large for full-text-first loading
- chapter-state or sync-state rules are unclear
- outline, timeline, setting, and prose are drifting apart
- you want stable cross-session recovery without losing context discipline

If your main problem is prose craft, chapter rhythm, or revision quality, use [novel-writing](https://github.com/wgwtest/novel-writing) alongside this skill.

## Example Prompts

- `Use novel-project-strategy. Design a reload order for this 250k-word novel workspace.`
- `Define chapter-state and sync-state rules so outline, timeline, and prose do not drift.`
- `Recover this fiction project in a new Codex session without loading the full manuscript first.`

## Install

Manual install:

```bash
git clone https://github.com/wgwtest/novel-project-strategy.git
mkdir -p ~/.codex/skills
cp -R novel-project-strategy/novel-project-strategy ~/.codex/skills/novel-project-strategy
```

For local development with easy upgrades:

```bash
git clone https://github.com/wgwtest/novel-project-strategy.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/novel-project-strategy/novel-project-strategy" ~/.codex/skills/novel-project-strategy
```

Restart Codex after installing or updating the skill.

Installer-style inputs:

- repo: `wgwtest/novel-project-strategy`
- path: `novel-project-strategy`

## Repository Layout

- `novel-project-strategy/`: installable skill package
- `README.md`: landing page for humans
- `.github/`: templates for issues and pull requests

The installable skill lives in a subdirectory so the repository root can hold public-facing files without leaking repo-specific metadata into the package.

## Related Repos

- [novel-writing](https://github.com/wgwtest/novel-writing): fiction planning, drafting, and revision
- [project-engineering-strategy](https://github.com/wgwtest/project-engineering-strategy): engineering workflow governance for code projects

## Contributing

If you want to improve the skill, start with [CONTRIBUTING.md](./CONTRIBUTING.md). The highest-value contributions are better state models, clearer reload patterns, and stronger examples that keep longform projects recoverable.

## License

MIT. See [LICENSE](./LICENSE).

## Maintainer Note

This public repository is synced from a separate source-of-truth workspace. Keep the root landing files and the installable package aligned in the same release.
