# Tools by Raul downloads

## Beta 0.8.218

Manual Coverage (PCSDWGCOVERAGE) now checks the installed MapGuide coordinate methods instead of requiring one Civil 3D update version. Strict coordinate validation and warning rejection remain in place.

Enable Advanced Mode, run `TBRUPDATE`, select **beta**, click **Check again**, then install and restart Civil 3D. Open Project CS > Files > Manual Coverage and retry the polygon/point export on the updated Civil 3D 2024 installation. Native export and geographic accuracy on that installation remain to be checked.

For a first Beta installation: [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.218-beta/TBR-2024-v0.8.218.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.218-beta/TBR-2026-v0.8.218.zip). Approved remains 0.8.217.

## Approved 0.8.217

GIS Import now refreshes newly imported objects automatically, shows a short completion message, and gives smaller-area guidance when a GIS service response limit is reached. Pano Import restores regular JPEG location/heading handling, and VC preserves the selection while toggling point-cloud visibility.

Run `TBRUPDATE`, select **approved**, click **Check again**, and install 0.8.217. Close Civil 3D when prompted, then restart. Existing 0.8.217 Beta users already have the same files and do not need to reinstall; select Approved for future updates.

For a first installation: [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.217-beta/TBR-2024-v0.8.217.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.217-beta/TBR-2026-v0.8.217.zip). The original tag is retained so existing download links keep working. Close Civil 3D, extract and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle before installation. Civil 3D 2026 requires 2026.2.2 or later.

The owner confirmed normal GIS imports, concise output, oversized-area guidance and existing-output preservation, GIS Undo/Redo/save-reopen, Pano photos and VC selection on their setup. This does not claim testing across every Civil 3D version or drawing. The packaged source catalog remains included; default-location catalogs are backed up and replaced only when the packaged catalog changes, while custom locations are untouched.

Beta offers 0.8.218. The legacy test migration feed remains at 0.8.205.

## Update behavior

The updater remembers the selected channel. Beta requires Advanced Mode; disabling it switches future checks to Approved without changing the installed bundle. Automatic checks run at Civil 3D startup, at most once every 24 hours per year/channel. Manual Check again bypasses that interval. Installation requires user action; the updater waits for every AutoCAD/Civil 3D session to close. Custom checklists and configuration are preserved, with rollback available. Signed feeds and package size/hash are verified without a GitHub account or token.

Both Windows builds, package checks and focused managed compatibility checks passed. Independent coordinate-control testing and coverage of other Civil 3D/MapGuide configurations remain pending. All downloads and checksum manifests are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases).
