# Export flow

This document describes the public-safe export behavior currently supported by the private/local **MLI-Knot Video Forge Lite** prototype around ScriptPackage v0.1.

---

## Main flow

prompt -> ScriptPackage v0.1 -> review -> storyboard / preview -> export -> local history -> reopen

---

## Current export artifacts

The current private prototype can generate package artifacts such as:

- `scriptpackage-v0.1.json`;
- `scriptpackage-v0.1.md`;
- `storyboard.txt`;
- `storyboard.html`;
- `manifest.json`;
- optional `video.mp4`;
- optional `audio.wav`.

This showcase does not include real private exported packages.

---

## JSON export

The JSON export provides a structured representation of ScriptPackage v0.1 for reading, validation, and reuse.

---

## Markdown export

The Markdown export provides a human-readable representation for review and documentation.

---

## Storyboard export

The storyboard can be represented in textual and HTML forms for reviewing the sequence of scenes.

The private prototype also presents a simple visual preview during its local workflow.

---

## Manifest

The manifest records information about the generated package and supports local integrity and history handling.

It is part of the private prototype export workflow and is not a public API contract.

---

## Optional video

The private prototype can generate a simple video artifact from the package.

This is a prototype renderer, not an advanced editing timeline or production video system.

---

## Optional procedural audio

The private prototype can optionally generate procedural local audio and include it with the video artifact.

This is not human narration, real TTS, or external-AI audio generation.

---

## Local history and reopen

Saved exported packages can appear in the prototype's local history.

A saved package can later be reopened as the active ScriptPackage for continued review.

Real private history and exported packages remain outside this public showcase.

---

## Public boundary

Public examples must be fictional, sanitized, reviewed, and safe to publish.

Do not publish:

- real private exports;
- private prompts;
- personal data;
- credentials;
- internal operational material;
- unrevised development history.

The broader experimental private UI remains outside the scope of this ScriptPackage showcase unless separately reviewed.
