# Tools by Raul downloads

## Approved 0.8.210

GIS Import now checks for the coordinate methods it needs instead of requiring one exact MapGuide version. Strict conversion checks remain in place. Run `TBRUPDATE`, select **approved**, click **Check again**, then install and restart Civil 3D. Open GIS Import in the affected drawing and test a small area.

The updated catalog from 0.8.209 remains included: **10 sources and 245 layers**. On first GIS use after a packaged catalog change, the default-location `sources.json` is backed up and replaced. Catalogs selected from other locations are untouched, and later edits survive reloads and restarts until the packaged catalog changes again.

For a first installation, download [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.210-approved/TBR-2024-v0.8.210.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.210-approved/TBR-2026-v0.8.210.zip). Close Civil 3D, extract and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle before installation. Civil 3D 2026 requires 2026.2.2 or later.

Beta remains at 0.8.208; the legacy test migration feed remains at 0.8.205.

## Update behavior

The updater remembers the selected channel. Beta requires Advanced Mode; disabling it switches future checks to Approved without changing the installed bundle. Automatic checks run at Civil 3D startup, at most once every 24 hours per year/channel. Manual Check again bypasses that interval. Installation requires user action; the updater waits for every AutoCAD/Civil 3D session to close. Custom checklists and configuration are preserved, with rollback available. Signed feeds and package size/hash are verified without a GitHub account or token.

Both Windows builds, package checks and focused managed compatibility checks passed. Interactive Civil 3D/MapGuide 3.4.747.0 and coordinate-control testing remain pending. All downloads and checksum manifests are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases).
