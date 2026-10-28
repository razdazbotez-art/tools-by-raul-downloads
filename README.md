# Tools by Raul downloads

Public installers and signed update information for the Civil 3D toolset.

## Beta 0.8.205

Already using .203 or .204? Run `TBRUPDATE`, select **test**, and click **Check again**. Install .205 and restart Civil 3D. With Advanced Mode enabled, the saved test selection becomes **beta**. Without Advanced Mode, it becomes **approved**.

For a first installation, download .205 for [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.205-beta/TBR-2024-v0.8.205.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.205-beta/TBR-2026-v0.8.205.zip), close Civil 3D, extract the ZIP and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle first. Civil 3D 2026 requires 2026.2.2 or later.

## Update channels

**Approved** is available to everyone and remains empty until a regular release is approved. **Beta** is available only while Advanced Mode is enabled. Turning Advanced Mode off returns future checks to Approved without downgrading the installed bundle. The old test feed temporarily offers .205 to migrate existing updater installations.

Startup checks run at most once per day, or use `TBRUPDATE` anytime. The user chooses when to install. Save work and close every AutoCAD/Civil 3D session when prompted; the updater never closes drawings or kills processes.

Custom checklist/configuration files are preserved. The previous bundle is retained for rollback while Civil 3D is closed. Updates verify a signed feed and package size/hash; no GitHub account or token is needed. The existing Advanced Mode password remains valid.

These are beta releases. Windows builds, focused checks and package scans passed. Owner testing confirmed updating and checklist section headings on their setup; the new .205 channel/manager interface still needs interactive Civil 3D testing.

All downloads are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases), with package checksum manifests. This repository contains distribution files and update information.
