# MLI-Knot-ScriptPackage-Showcase

> **Status:** vitrine pública sanitizada do ScriptPackage v0.1 usado por um protótipo funcional privado/local.
> **Projeto fonte:** `MLI-Knot-VideoForge-Lite`, mantido privado/local.
> **Regra de publicação:** apenas documentação e exemplos fictícios, sanitizados e revisados.

<div align="center">

<img src="assets/matrix-inspired-banner.gif" width="100%" alt="Cyber banner" />

</div>

Public sanitized showcase of **ScriptPackage v0.1** as currently used by the private/local **MLI-Knot Video Forge Lite** functional prototype.

This repository documents the public-safe ScriptPackage structure and its current prototype flow without exposing private source code, private prompts, real outputs, internal history, or unrevised development material.

---

## Status

```text
Type: public sanitized showcase
Source project: MLI-Knot Video Forge Lite
Source project state: functional private/local prototype
Source project visibility: private/local
Central format: ScriptPackage v0.1
External AI: no
Separate backend: no
Own API: no
Database: no
Authentication: no
Code included here: no
Real outputs included here: no
Private prompts included here: no
Sensitive material included here: no
Production application represented here: no
```

---

## What is ScriptPackage v0.1?

**ScriptPackage v0.1** is a structured package format used by the private prototype to organize a video idea into reusable parts.

It can represent:

- title;
- hook;
- summary;
- scenes;
- narration text;
- on-screen text;
- visual prompts;
- caption;
- hashtags;
- metadata;
- preset;
- estimated duration;
- integrity status.

It is not a market standard, not a public API contract, and not a production format.

The current private prototype generates ScriptPackage v0.1 through local deterministic generation, without external AI.

---

## Current prototype flow

prompt -> local deterministic generation -> ScriptPackage v0.1 -> storyboard -> preview -> export -> history -> reopen saved package

The private prototype currently supports a public-safe description of the following behavior:

- receives a prompt and local generation settings;
- generates a ScriptPackage v0.1;
- organizes scenes, narration text, on-screen text and visual prompts;
- presents storyboard and simple visual preview;
- exports structured and human-readable package material;
- can generate a simple optional video artifact;
- can generate optional procedural audio;
- keeps local export history;
- can reopen an exported package as the active package.

This showcase describes those behaviors without publishing the private implementation.

---

## Exportable prototype artifacts

Depending on the prototype export configuration, a saved package can include artifacts such as:

- `scriptpackage-v0.1.json`;
- `scriptpackage-v0.1.md`;
- `storyboard.txt`;
- `storyboard.html`;
- `manifest.json`;
- optional `video.mp4`;
- optional `audio.wav`.

Real private exports are not included in this showcase.

---

## What this showcase contains

- Public explanation of ScriptPackage v0.1.
- Sanitized structure documentation.
- Fictional example package.
- Fictional storyboard example.
- Public-safe export-flow documentation.
- Public boundary for safe showcase use.

---

## What this showcase does not contain

- Private source code.
- Real exported packages.
- Private prompts.
- Personal data.
- Credentials.
- Internal development history.
- Internal operational details.
- Production backend.
- Real unrevised video outputs.
- Experimental private UI implementation details.
- Unreviewed material from the private repository.

---

## Current limits

ScriptPackage v0.1 remains:

- experimental;
- local-first;
- not a public standard;
- not a stable public API contract;
- not guaranteed to be backward compatible;
- not a replacement for a full video editor;
- not a final production workflow.

The private prototype does not use external AI, a separate backend, its own API, a database, or authentication.

---

## Documentation

- [`docs/scriptpackage-v0.1.md`](docs/scriptpackage-v0.1.md)
- [`docs/storyboard-example.md`](docs/storyboard-example.md)
- [`docs/export-flow.md`](docs/export-flow.md)
- [`docs/public-boundary.md`](docs/public-boundary.md)

---

## Examples

- [`examples/sanitized-scriptpackage.json`](examples/sanitized-scriptpackage.json)
- [`examples/sanitized-scriptpackage.md`](examples/sanitized-scriptpackage.md)

All examples are fictional and sanitized.

---

## License and notice

- [`LICENSE.md`](LICENSE.md)
- [`NOTICE.md`](NOTICE.md)

---

## Relationship with the private project

The private/local **MLI-Knot Video Forge Lite** repository remains the technical source for the prototype.

This public repository presents only ScriptPackage v0.1 material that can be explained safely and reviewably.

The broader experimental private UI evolution remains outside this showcase unless separately reviewed for publication.

---

## Related repositories

- [MLI-Knot Mind Showcase](https://github.com/proftectiagocosta-hash/MLI-Knot-Mind-Showcase)
- [MLI-Knot-Cursos Showcase](https://github.com/proftectiagocosta-hash/MLI-Knot-Cursos-Showcase)
- MLI-Knot Video Forge Lite — private technical source for ScriptPackage v0.1.

---

## Public boundary

This showcase should only receive public, fictional, sanitized, and reviewed material.

If a file, prompt, output, screenshot, or example comes from the private prototype, it must be reviewed and sanitized before being published here.
