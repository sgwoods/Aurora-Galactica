# Aurora Galactica Release Host

`Aurora Galactica` is the first shipped playable application on the `Platinum`
browser-arcade platform.

This repository is the **public release host** for Aurora and Platinum.

It exists primarily to serve:

- hosted `/dev`
- hosted `/beta`
- hosted `/production`
- GitHub Pages documentation and release surfaces
- mirrored public release assets

## Important Repo Split

Aurora currently uses two public repos, and they do **not** have the same job.

### Active source repo, issues, and planning

- [sgwoods/Codex-Test1](https://github.com/sgwoods/Codex-Test1)

Use that repo for:

- active issues
- planning and roadmap work
- code changes
- harnesses and analyses
- release workflow and multi-machine development

### Public release host

- [sgwoods/Aurora-Galactica](https://github.com/sgwoods/Aurora-Galactica)

Use this repo for:

- public release hosting
- GitHub Pages deployment
- release-facing mirrored assets

If you are looking for the active issue tracker, use:

- [sgwoods/Codex-Test1/issues](https://github.com/sgwoods/Codex-Test1/issues)

## Live Lanes

- hosted `/dev`:
  - `https://sgwoods.github.io/Aurora-Galactica/dev/`
- hosted `/beta`:
  - `https://sgwoods.github.io/Aurora-Galactica/beta/`
- hosted `/production`:
  - `https://sgwoods.github.io/Aurora-Galactica/`

## Current Public Release Family

As of April 25, 2026:

- hosted `/dev`:
  - `1.2.3+build.470.sha.e4732eb`
- hosted `/beta`:
  - `1.2.3-beta.1+build.489.sha.f6ba6c2.beta`
- hosted `/production`:
  - `1.2.3+build.489.sha.f6ba6c2`

## Hosted Documentation

Primary public docs:

- project guide:
  - `https://sgwoods.github.io/Aurora-Galactica/project-guide.html`
- Platinum guide:
  - `https://sgwoods.github.io/Aurora-Galactica/platinum-guide.html`
- player guide:
  - `https://sgwoods.github.io/Aurora-Galactica/player-guide.html`
- release dashboard:
  - `https://sgwoods.github.io/Aurora-Galactica/release-dashboard.html`

## Local Development

For local development and the canonical documentation set, start from:

- [sgwoods/Codex-Test1](https://github.com/sgwoods/Codex-Test1)

Recommended startup path there:

```bash
mkdir -p "$HOME/Development"
cd "$HOME/Development"
curl -fsSL https://raw.githubusercontent.com/sgwoods/Codex-Test1/main/tools/dev/setup-machine.sh | bash
```

If you want to use a machine-specific iCloud-backed parent folder instead,
`cd` there first and run the same installer command.
