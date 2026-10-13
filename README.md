# Hoshimi Localify EN

English translation module for **Idol Pride** (LSPatch). This repository builds and
releases the module app; users patch their own game — no patched game is distributed here.

This is a **modified derivative** of Hoshimi Localify (GPL-3.0) — see *Upstream & credits*.

## Install

1. Install LSPatch `manager.apk` from the official JingMatrix/LSPatch release.
2. Install **`HoshimiLocalify-en-lite-<ver>.apk`** (recommended). Use
   `HoshimiLocalify-en-full-<ver>.apk` if you want the breast-physics parameters.
3. In the manager: **New Patch -> Local mode -> Select an installed app -> Idol Pride**,
   then install the patched app.
4. Open **Hoshimi Localify EN -> Home**; it auto-downloads the translation data
   (~35-40 MB) on first visit.
5. Update translations later from the same Home tab — no re-patch.

## Warnings

- **Uninstall the store game first.** LSPatch re-signs the APK, so the patched build cannot
  be installed over the store build. Your account is server-side; this costs a re-login only.
- **Keep the LSPatch manager installed.** Local mode is bound to it; removing the manager
  breaks module loading.
- **Never install the KR module** (`io.github.cylear.hoshimi.localify`) alongside this one —
  identical package id, only one can be active.
- Each live-client version bump needs a re-verify pass.

## Upstream & credits

This repository is a **modified derivative** of **Hoshimi Localify** (GPL-3.0). Original
code and prior work:

- **Chinosk6** — [gakuen-imas-localify](https://github.com/chinosk6/gakuen-imas-localify) (original code)
- **Vilebbit** — [HoshimiToolkit](https://github.com/Vilebbit/HoshimiToolkit), [SolisClient](https://github.com/Vilebbit/SolisClient)

Changes made here: English translation data wiring, `full`/`lite` build flavors, the public
update flow, and narrowing the module scope to the JP client. Not affiliated with Idolm@ster
or Bandai Namco.

## License

GPL-3.0. As a modified derivative of a GPL-3.0 work, this repository is distributed under the
same license. See `LICENSE`.

## Source / sync

This repo is a snapshot of a private source-of-truth fork. See `SYNC.md`.
