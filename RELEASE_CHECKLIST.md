# AlternativeCAM Release Checklist

Use this checklist for each public release.

## Before Publishing

- [ ] Confirm the application version displayed in the software matches the release version.
- [ ] Test the packaged HTML and `Assets` folder together.
- [ ] Confirm the built-in Calibration / Benchmark Test opens correctly.
- [ ] Confirm the benchmark/template file cannot be accidentally overwritten.
- [ ] Test SVG import.
- [ ] Test Kiss Cut generation.
- [ ] Test Thru Cut generation.
- [ ] Test Multi-Pass Thru Cut generation.
- [ ] Test manual and automatic tabs.
- [ ] Test Preview, Simulator, and G-code Viewer.
- [ ] Confirm spindle-start commands are not unintentionally emitted for drag-knife jobs.
- [ ] Confirm expected end-of-job behavior.
- [ ] Review generated G-code from representative test files.
- [ ] Update `README.md` if capabilities or compatibility changed.
- [ ] Update `CHANGELOG.md`.
- [ ] Prepare release notes.

## GitHub Release

- [ ] Create tag using the format `vX.Y.Z-beta` while the application remains Beta.
- [ ] Create a GitHub Release from that tag.
- [ ] Mark Beta releases as **Pre-release**.
- [ ] Use the title `CNC Drag Knife Workbench vX.Y.Z Beta`.
- [ ] Attach the complete ZIP containing the HTML and required `Assets` folder.
- [ ] Optionally attach the standalone HTML for users who only need Basic Mode.
- [ ] Attach the current user manual when available.
- [ ] Paste the prepared release notes into the GitHub Release description.
- [ ] Verify all downloadable assets after publishing.

## v0.4.9.7 Beta — First Public Release

Recommended tag:

`v0.4.9.7-beta`

Recommended release title:

`CNC Drag Knife Workbench v0.4.9.7 Beta`

Recommended ZIP asset name:

`CNC-Drag-Knife-Workbench-v0.4.9.7-Beta.zip`

The complete ZIP is the recommended download because Expanded Tools depend on the accompanying `Assets` directory.
