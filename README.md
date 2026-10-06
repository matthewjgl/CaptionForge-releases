# CaptionForge — Friends Beta

Free, unlimited local captions for Final Cut Pro on Apple silicon. This repository hosts installers and the signed update feed only; application source, models, personal projects and signing keys are not included.

## Download and install

[Download CaptionForge 1.0.5 Friends Beta](https://github.com/matthewjgl/CaptionForge-releases/releases/tag/v1.0.5-build-6)

Requires **Apple silicon, macOS 26.6+ and Final Cut Pro 12.4+**. Quit Final Cut and CaptionForge, open the `.pkg`, and follow the normal macOS Installer prompts including administrator authorization. The package installs the editor, Final Cut extension, Timeline Helper, speech engine and all twelve title presets. Models download on first use. Fonts depend on those installed on your Mac.

Open CaptionForge in Applications, or Final Cut → Window → Extensions → CaptionForge. Use the standalone editor for its protected minimum window size. Optional automatic title separation requires the user to grant Timeline Helper Accessibility permission.

## Updates

Choose **CaptionForge → Check for Updates…** in the standalone editor. Updates are downloaded from GitHub, cryptographically verified and installed through macOS Installer, then the app relaunches. Quit Final Cut before updating. Existing settings, saved drafts, custom presets and downloaded models are preserved; managed app bundles/templates are replaced.

## Verified and remaining

Apple accepts the signed, notarized apps and installer; Gatekeeper and update-signature checks pass. An actual first install and GitHub update from 1.0.4 to 1.0.5, including automatic relaunch and restoration of settings, passed on the developer's Mac. Existing draft/model files were preserved and installed bundles matched the package without obsolete files.

This is a **friends beta**. Clean install/playback on a second Mac is not yet verified. Final Cut can restore/tile its extension below the requested minimum, and repeated timeline-drop placement/separation remains in testing. Speech and word timing may need review; XML project import/manual Break Apart remain alternatives. This is not a guarantee of perfect captions or parity with another product.

Future requested fixes will be tested locally and released together as a batch.
