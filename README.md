# CaptionForge downloads

This public repository hosts installer downloads and the update feed only. CaptionForge source code, personal media, projects, models, license keys and signing secrets are not published here.

The friends beta is free: unlimited local transcription and all twelve original caption presets, with no license activation. Speech models download on first use; no cloud AI account is required.

**No friend-ready installer is published yet.** The local installer preview is not installer-signed or notarized. Apple installer signing, notarization, a clean second-Mac install and a real update/install/relaunch test must pass before the first release.

The current build requires Apple silicon, macOS 26.6 or later and Final Cut Pro 12.4 or later, matching the public Final Cut runtime used to build it. Quit Final Cut before installing or updating. The optional Timeline Helper needs user-granted Accessibility permission for automatic title separation. Fonts use those installed on each Mac. Transcriptions can need correction.

The CaptionForge app includes **Check for Updates…**. Released updates will replace the editor, extension, helper and managed title templates while preserving local projects, settings and downloaded models. The update feed remains empty until a signed, notarized installer is available.
## Latest local test build

CaptionForge1.0.4 adds named appearance presets in My Presets, including font/face, colors, size, Y, wrapping width, line count, caption limits and animation/formatting settings. Save, apply, rename, delete and persistence after reopening were tested in the installed editor. Presets retain current media, corrected timed words and project format. Custom template-preview wording updates the cards independently.

Optional local natural grouping uses one-to-three-word portrait captions, longer configurable landscape phrases and isolated long words. Preview and export preserve the chosen font size; ten-percent frame margins are checked and oversized text requires adjustment before export. Linguistic hints are heuristic; they cannot guarantee perfect phrasing or speech recognition. The preview has separate play/pause and selected-caption replay controls.

All80 core tests and Apple-silicon Debug/signed Release builds pass. The installed GitHub update check succeeds; official update signing verifies and rejects a modified package. Actual update installation/relaunch, clean installation on another Mac and repeatable timeline dragging remain acceptance gates. No release binary has been uploaded.

## Latest internal validation

The editor supports expansion with a protected minimum and stable left-side controls. Native opening, appearance persistence, expansion/restore and the GitHub update check passed. Final Cut's strict extension minimum-size behavior remains unaccepted.

The current internal package contains all12 original presets and10 Apple-silicon executables; matching versions, complete-bundle replacement, updater settings and absence of personal data are verified. Eighty core tests, Debug and Developer ID signed Release builds pass. Update signing/verification succeeds and altered packages are rejected.

**No friend-ready installer is available yet.** Developer ID Installer signing, Apple notarization, actual installation and update/relaunch, clean second-Mac workflow and repeatable timeline-drop acceptance remain open. This repository still contains documentation and an empty update feed, with no source code, personal projects, model caches or installer binary published.
