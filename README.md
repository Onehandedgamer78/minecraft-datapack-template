# Minecraft Datapack Starter

> **AI GENERATED — DEVELOPMENT SCAFFOLD**
>
> Initial documentation and templates generated using OpenAI ChatGPT/Codex, with project direction by **Ethan Kiefer (Onehandedgamer78)**. See [AI_DISCLOSURE.md](AI_DISCLOSURE.md).

A reusable starting point for separate Minecraft compatibility datapack projects. Each integration gets its own repository and downloadable release.

**Current status:** documentation and release templates only. No installable datapack, pack.mcmeta, gameplay data, or verified Minecraft compatibility is included yet.

## Use this starter

1. Create a separate repository for the integration using this repository as a template, or copy the starter documents.
2. Adapt [TEMPLATE_README.md](TEMPLATE_README.md), [TEMPLATE_AI_DISCLOSURE.md](TEMPLATE_AI_DISCLOSURE.md), and [TEMPLATE_RELEASE_NOTES.md](TEMPLATE_RELEASE_NOTES.md) for that specific project.
3. Confirm Minecraft, loader, and exact dependency versions before choosing metadata or implementing data files.
4. Implement and test the integration in a fresh test world.
5. Release an independently installable ZIP with the AI disclosure, installation instructions, version requirements, credits, and license.

The release ZIP must have pack.mcmeta and data/ at its root. Use the correct metadata schema for the target version.

## Required AI labeling

Display **AI GENERATED** in the repository description, immediately below the README title, in the in-game datapack description, and in every release title and its notes. Include AI_DISCLOSURE.md inside each release ZIP.

[PROJECT_STANDARDS.md](PROJECT_STANDARDS.md) records the full publishing requirements. [AGENTS.md](AGENTS.md) carries those requirements into future development.

## First planned integration

[Big Globe + Cobblemon compatibility](https://github.com/Onehandedgamer78/bigglobe-cobblemon-compat) is maintained separately. Additional biome-mod integrations will have their own repositories when selected.

## Reuse and credit

Original documentation and templates are provided under the [MIT license](LICENSE). Keep third-party material, authorship, and license exceptions documented separately. This starter does not include original mod code or assets.

