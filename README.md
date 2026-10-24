# Videogen

Experiments in turning a small idea into a short film: a gesture, an unfinished object, a room that changes when nobody is looking.

The focus is moving scenes with a clear emotional thread—not a slideshow with narration. Work explores original anime-inspired visuals, conversational speech, blues-led soundtracks, and edits that leave room for quiet moments.

## Creative approach

- **Story before spectacle.** Give each shot a purpose and let details carry meaning.
- **Motion with restraint.** Favor readable gestures and deliberate camera movement over constant effects.
- **Sound as part of the scene.** Use space, rhythm, and instrumental responses rather than wall-to-wall narration.
- **Iterate honestly.** Check timing, continuity, visual artifacts, and encoded playback. A technically valid render is not the same as a finished film.

## What this repository is

This is a public overview of an ongoing private creative project. It is intentionally small: a README and a publication allowlist.

It is **not** a source-code release, media gallery, downloadable model, or reproducible production kit. No installation or execution is required.

## What stays private

Finished videos, audio, artwork, production scripts, prompts, reference material, personal notes, credentials, and generation records are not published here. The production workspace is kept separate from this checkout.

No private source material is included as an example, and no third-party reference footage is redistributed.

## Publication safeguards

The root `.gitignore` ignores everything except this README and itself. That reduces accidental additions, but it is **not a security boundary**:

- Already-tracked files remain tracked even after an ignore rule is added.
- `git add --force` can bypass ignore rules.
- Removing a file from the current tree does not erase Git history.
- Anything pushed to a public repository must be treated as public permanently.

Before publishing, review staged paths and content, inspect history for unexpected files, and confirm the exact destination. Never force-add production material. Do not place secrets in this checkout, even if they would be ignored.

## Scope and status

The creative work is experimental. Visual continuity, character details, and motion quality vary between generated shots. Upscaled delivery resolution should not be presented as native generation resolution.

This documentation-only repository has no application runtime, dependency manifest, package installation, or CI workflow. Security review here concerns accidental disclosure and publication configuration; it does not audit the separate private production tools or hosted generation services.
