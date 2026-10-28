# Tools by Raul downloads

Public installers and signed update information for the Civil 3D toolset.

## Beta 0.8.208 — Plugin Data correction

Beta .208 corrects an invalid cast in the Plugin Data scan and related GIS/Base Map cleanup dictionary traversal. Enable Advanced Mode, run `TBRUPDATE`, select **beta**, click **Check again**, install .208 and restart Civil 3D. Open the affected template, return to QC Dashboard → Plugin Data and click **Refresh**. Test purge on a copy of the drawing and check the intended results before submittal. Native Civil 3D scan/purge/save-reopen verification is pending.

Approved .207 and Beta .206 contain the faulty cast. The correction is available in Beta .208 while Approved remains .207.

## Approved 0.8.207

The Approved channel now offers .207. It has the same plugin behavior as .206, with a higher bundle version for an owner-requested update-alert test.

For the alert test, install [0.8.206](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/tag/tools-by-raul-v0.8.206-beta), leave **approved** selected and start Civil 3D after .207 is offered. A fresh installation should announce .207. Advanced Mode is not required. Automatic checks occur at startup, at most once every 24 hours per Civil 3D year/channel; a recent Approved check delays the next automatic check. `TBRUPDATE` checks immediately through the manual route.

For a normal first installation, download the current Approved .207 for [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.207-approved/TBR-2024-v0.8.207.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.207-approved/TBR-2026-v0.8.207.zip). Close Civil 3D, extract and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle first. Civil 3D 2026 requires 2026.2.2 or later.

## Channels and installation

The updater remembers the selected channel. **Approved** is available to everyone. **Beta** requires Advanced Mode; turning Advanced Mode off switches future checks to Approved without changing the installed bundle. Beta currently offers .208. The legacy test feed offers .205 to migrate .203/.204 installations.

An available update opens the updater window; installation needs the user's action. Save work and close every AutoCAD/Civil 3D session when prompted. No drawings are closed and no processes are killed automatically. Custom checklist/configuration files are preserved, with a previous-bundle rollback copy. Signed feeds and package size/hash are verified, without a GitHub account or token. The existing Advanced Mode password remains valid.

Owner testing confirmed earlier updating and checklist section headings on their setup. Native automatic-alert/ribbon and broader Civil 3D acceptance remain pending.

All downloads are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases), with checksum manifests. This repository contains distribution files and update information.
