# Tools by Raul downloads

Public installers and signed update information for the Civil 3D toolset.

## Updater test

1. Download **0.8.203** for [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.203-updater-test/TBR-2024-v0.8.203.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.203-updater-test/TBR-2026-v0.8.203.zip).
2. Close AutoCAD/Civil 3D, extract the ZIP, and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle first. Civil 3D 2026 requires 2026.2.2 or later.
3. Start Civil 3D, run `TBRUPDATE` (or click **Check for Updates**), select **test**, and click **Check again**.
4. Install **0.8.204** through the updater. Save your work and close all AutoCAD/Civil 3D sessions when prompted; the updater never closes drawings or kills processes.
5. Reopen Civil 3D and generate or refresh a checklist table. Section headings now use the native **Header** row style.

The default **approved** channel is empty during this test. Return to it using the channel selector after testing. Existing users need to install the updater bootstrap once; older bundles cannot check for updates themselves.

Custom checklist/configuration files are preserved. The prior bundle is retained for **Restore previous version** while Civil 3D is closed. Updates verify a signed feed and package size/hash before installing; no GitHub account or token is needed.

These are test releases. Windows builds, focused tests, and package checks have passed. Interactive Civil 3D installation, update, rollback, table appearance, and plotting acceptance remain pending.

All downloads are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases). Each release includes a package checksum manifest. This repository contains public distribution files and update information.
