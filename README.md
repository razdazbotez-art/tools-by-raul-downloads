# Tools by Raul downloads

## Approved 0.8.208

The Approved channel offers the Plugin Data correction in 0.8.208. Run `TBRUPDATE`, select **approved**, and click **Check again**, then install and restart Civil 3D. Advanced Mode is not required.

Users already running 0.8.208 Beta have the same files and need no reinstall. Beta also remains at 0.8.208; the legacy test migration feed remains at 0.8.205.

For a first installation, download [Civil 3D 2024](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.208-beta/TBR-2024-v0.8.208.zip) or [Civil 3D 2026](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases/download/tools-by-raul-v0.8.208-beta/TBR-2026-v0.8.208.zip). Close Civil 3D, extract and run `Install-ToolsByRaulBundle.cmd`. Remove the old standalone Detail Enlargement bundle before installation. Civil 3D 2026 requires 2026.2.2 or later. The existing release tag is retained so download links stay valid.

## Update behavior

The updater remembers the selected channel. Beta requires Advanced Mode; disabling it switches future checks to Approved without changing the installed bundle. Automatic checks run at Civil 3D startup, at most once every 24 hours per year/channel. Manual Check again bypasses that interval. Installation requires user action; the updater waits for every AutoCAD/Civil 3D session to close. Custom checklists and configuration are preserved, with rollback available. Signed feeds and package size/hash are verified without a GitHub account or token.

The owner approved this promotion after reporting that the correction looks good. Broader purge/result-preservation/save-reopen and other native checks remain separately tracked. All downloads and checksum manifests are under [Releases](https://github.com/razdazbotez-art/tools-by-raul-downloads/releases).
