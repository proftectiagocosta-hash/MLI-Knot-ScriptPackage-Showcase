# ScriptPackage v0.1

ScriptPackage v0.1 is the structured package format currently used by the private/local **MLI-Knot Video Forge Lite** functional prototype.

It turns an initial video idea into organized material for scripting, storyboard review, preview, export, history, and later reuse.

---

## Purpose

The purpose of ScriptPackage v0.1 is to create a clear intermediate object between an idea and derived video artifacts.

It helps organize:

- what the video is about;
- the hook;
- required scenes;
- narration text;
- on-screen text;
- visual prompt notes;
- metadata;
- export-related information.

The format remains internal to the prototype.

It is not an external official format, a public standard, or a stable API contract.

---

## Current prototype flow

prompt -> local deterministic generation -> ScriptPackage v0.1 -> storyboard -> preview -> export -> history -> reopen saved package

The private prototype performs this flow locally and does not call an external AI model to generate the package.

---

## Package sections

A ScriptPackage v0.1 may include:

- package metadata;
- title;
- hook;
- summary;
- scene list;
- narration text;
- on-screen text;
- visual prompt notes;
- caption;
- hashtags;
- preset;
- estimated duration;
- integrity status.

---

## Scene structure

A scene may include:

- scene number;
- short title;
- visual description;
- narration text;
- on-screen text;
- visual prompt;
- estimated duration.

---

## Derived exports

The current private prototype can derive package artifacts such as:

- `scriptpackage-v0.1.json`;
- `scriptpackage-v0.1.md`;
- `storyboard.txt`;
- `storyboard.html`;
- `manifest.json`;
- optional `video.mp4`;
- optional `audio.wav`.

The video artifact is a simple prototype output, not an advanced editing workflow.

The optional audio is procedural and local; it is not real narration or external-AI TTS.

---

## History and reuse

Saved prototype packages can be listed in local history.

A previously exported package can be reopened as the active ScriptPackage for continued review.

This showcase documents that behavior without publishing real private package history or exports.

---

## Current limits

ScriptPackage v0.1 is:

- experimental;
- local-first;
- not a public standard;
- not a stable API contract;
- not guaranteed to be backward compatible;
- not a replacement for a full video editor;
- not a final production workflow.

The private prototype currently has no:

- external AI dependency for package generation;
- separate backend;
- own public API;
- database;
- authentication;
- real TTS narration.

---

## Public example rule

Any public ScriptPackage example must be:

- fictional;
- sanitized;
- safe to publish;
- free from private prompts;
- free from personal data;
- free from real unrevised outputs.

The broader experimental private UI evolution remains outside this showcase unless separately reviewed for publication.
