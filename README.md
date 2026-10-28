# Tools by Raul downloads

Public installers and signed update information for the Civil 3D toolset.

## Beta 0.8.206

Check for Updates now has its own Updates panel at the right-hand end of the Tools by Raul tab.

Already on .205? Leave **beta** selected in `TBRUPDATE`, with Advanced Mode enabled. Automatic checks occur at Civil 3D startup, at most once every 24 hours per Civil 3D year/channel. The updater window appears when a newer release is offered. Use `TBRUPDATE` to check immediately. It never installs without the user's action.

On .203/.204, select **test** and install .205 first; restart Civil 3D and choose Beta to get .206. Existing test preferences become Beta if Advanced Mode is enabled, otherwise Approved.

For a first installation, download .206 for [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.206-beta/TBR-2024-v0.8.206.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.206-beta/TBR-2026-v0.8.206.zip). Close Civil 3D, extract the ZIP and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle first. Civil 3D 2026 requires 2026.2.2 or later.

## Channels and installation

**Approved** is available to everyone and remains empty until a regular release is approved. **Beta** requires Advanced Mode. Turning Advanced Mode off switches future checks to Approved without changing the installed version. The last selected eligible channel is remembered. The existing Advanced Mode password remains valid.

Save work and close all AutoCAD/Civil 3D sessions when prompted. The updater never closes drawings or kills processes. Custom checklist/configuration files are preserved; the previous bundle is retained for rollback. Signed feeds and package size/hash are verified, with no GitHub account or token needed.

These are beta releases. Native Civil 3D layout and automatic notification acceptance remain pending. Owner testing confirmed the earlier updater and checklist section headings on their setup.

All downloads are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases), with package checksum manifests. This repository contains distribution files and update information.
