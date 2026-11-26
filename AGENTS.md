# AGENTS.md

Notes for AI coding agents working in `plugin_ABDesigner`.

- Part of the **CruGlobal-AI** AppBuilder stack (fork of the upstream CruGlobal / digi-serve repo). Start from `CruGlobal-AI/ab_runtime` and `CruGlobal-AI/ab-cli` for the big picture.
- Use `CruGlobal-AI/*` repos and `ghcr.io/cruglobal-ai/*` images. Never point back at upstream orgs or Docker Hub `digiserve/*`.
- CI uses reusable workflows from `CruGlobal-AI/ab-workflows`. Images are pushed to GHCR, never deployed to Cru infrastructure.
- `@digiserve/ab-utils` comes from `github:CruGlobal-AI/ab-utils#<tag>`.
- Before you finish, run the lint and test scripts in `package.json` if there are any.
