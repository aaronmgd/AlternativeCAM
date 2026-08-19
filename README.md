# AlternativeCAM

### Alternative CNC Toolpath Software by GabrielMaker

**Current Application:** CNC Drag Knife Workbench  
**Current Version:** v0.4.9.7 Beta  
**Status:** First Public GitHub Release

AlternativeCAM is the home of **CNC Drag Knife Workbench** and future software for CNC processes that do not fit neatly into traditional milling CAM workflows.

The project currently focuses on drag-knife cutting for desktop CNC machines. Future development is intended to expand into additional alternative CNC processes such as pen/marker plotting, diamond-drag engraving, etching, and related workflows.

---

## Project Goal

The goal of AlternativeCAM is to build robust, practical CNC software that makers, hobbyists, educators, and businesses can use freely.

GabrielMaker wants future fixes, improvements, compatibility updates, and new features to remain centered in one place so the entire community can benefit from them. Rather than having useful changes scattered across separate modified versions, contributors are strongly encouraged to submit improvements back to this repository whenever possible.

If you fix a bug, improve machine compatibility, add a useful feature, improve documentation, or find a better way of doing something, contributing that work here helps everyone benefit and gives future development a shared, maintained foundation.

---

# CNC Drag Knife Workbench

CNC Drag Knife Workbench is a browser-based application for preparing SVG artwork, creating compensated drag-knife toolpaths, previewing CNC motion, and generating G-code for desktop CNC machines.

It was originally developed around Makera CNC machines and currently provides its most tested workflow on that platform.

## Current Capabilities — v0.4.9.7 Beta

### SVG & Artwork Import

- Standard SVG import
- Oversized-SVG preflight with cancel, actual-size, or shrink-to-fit handling
- Paste SVG from clipboard
- Drag-and-drop SVG import
- Multiple SVG import
- Auto-grouping of multi-path imported artwork

### Design & Artwork Tools

- Move, resize, rotate, mirror, duplicate
- Numeric Size, Rotation, and Position controls
- Position relative to Material WCS
- Group / Ungroup
- Solo Selection
- Object locking
- Rename and auto-number
- Stacking-order controls
- Align and distribute
- Align to material
- Center on material
- Array / Step-and-Repeat with Step or Gap spacing

### Shape & Vector Tools

- Shape Designer
- Offset Path: Inside / Outside / Both
- Live offset preview
- Single-corner Fillet / Round
- Single-corner Chamfer
- Simplify Paths
- Smooth Paths
- Path Cleanup / Repair
- Close open paths within tolerance
- Exact and reverse-direction duplicate detection
- Coincident / overlapping geometry detection
- Geometry Inspector

### Boolean Operations

- Union
- Subtract
- Intersect
- Divide

### Selection, Layers & Objects

- Selection filters
- Select Kiss / Thru / Open paths
- Select Same as Primary
- Invert and clear selection
- Object/group hierarchy
- Visibility and locking
- Output-to-G-code enable/disable
- Kiss / Thru / Multi-Pass identification
- Solo Selection
- Rename and auto-number utilities

### Design History & Diagnostics

- Design History
- Design Diagnostics
- CAM-preparation warnings
- Duplicate and overlapping geometry checks

### Material, Grid & Guides

- Configurable material size
- Factory default 150 × 100 mm
- Saved material presets
- Green visual-only Design Safe Margin
- Material/WCS origin configuration
- WCS X/Y offsets
- Configurable grid and snapping
- Rulers and drag-out guides
- Guide locking/deletion

---

# Drag Knife CAM

## Cut Types

Vectors can be assigned as:

- **Kiss Cut**
- **Thru Cut**
- **Multi-Pass Thru Cut**

Visual identification:

- Black = Kiss Cut
- Orange = Thru Cut
- Red = Multi-Pass Thru Cut

Kiss Cuts are generated before Thru Cuts.

## Drag-Knife Compensation

- Configurable blade offset
- Corner compensation
- Corner overshoot and return movement
- Smooth-join tolerance
- Micro-segment cleanup
- Compensated drag-knife toolpath generation

## Multi-Pass Thru Cutting

- Per-vector pass count
- Progressive Depth
- Same Depth Each Pass
- Per-vector Final Z
- Final Z initially inherits the global Thru Cut Z
- Red display for multi-pass paths
- Pass-count identification in Layers / Objects

## Holding Tabs

- Automatic tabs
- Manual tabs
- Configurable tab width
- Configurable Tab Depth / Lift Amount
- Configurable tab count
- Sharp-corner avoidance
- Manual tab locations retained across multi-pass operations

---

# Cut Setup & G-code Output

- Separate Kiss Cut and Thru Cut settings
- Cut-order controls
- Original SVG ordering option
- Per-path Output-to-G-code control
- Optional end-of-job `G28`
- Metric G-code output using `G21`
- Spindle forced OFF with `M5`
- Drag-knife output does not intentionally start the spindle with `M3` / `M4`
- Material-boundary export protection
- Source-geometry overlap checks before export

---

# Preview, Simulator & G-code Viewer

- Cut Preview
- Toolpath Simulator
- Generated G-code simulation
- Open external G-code files for inspection
- Show/hide G-code
- Zoom, pan, and fit-to-view
- 3D G-code inspection
- Tab visualization
- Toolpath and movement visualization

---

# Project & File Management

- Open Workbench jobs
- Save Job / Save Job As
- Close Job with unsaved-change protection
- Connect Program Folder
- Built-in Calibration / Benchmark Test
- Protected benchmark/template workflow
- Browser-stored preferences
- Connected-folder settings/assets
- Reset configuration controls

---

## Expanded Tools

v0.4.9.7 Beta includes an expanded modular design-tool system. The core Workbench remains usable without connecting the Program Folder, while connecting it enables expanded design tools and enhanced SVG intake.

---

## Not Yet Included

The following are future development areas and should not be considered current v0.4.9.7 Beta functionality:

- Pen / Marker plotting mode
- Diamond Drag engraving mode
- Etching mode
- Redesigned Vector Drawing tool
- Redesigned Text Tool

---

# Download

The recommended way to obtain CNC Drag Knife Workbench is through the official **GitHub Releases** section of this repository.

**v0.4.9.7 Beta is the first public GitHub release.**

Use the official AlternativeCAM repository whenever possible rather than redistributed copies.

---

# Browser Requirements

Use a current desktop version of:

- Google Chrome
- Microsoft Edge

Some functionality relies on modern browser file-system capabilities and may not operate correctly in unsupported browsers.

---

# Supported Machines

Current development and testing primarily focuses on:

- Makera Carvera
- Makera Carvera Air
- Makera Z1

Support for additional CNC machines and controller profiles may be added in future releases.

**AlternativeCAM and GabrielMaker are independent community projects and are not affiliated with or endorsed by Makera.**

---

# Future Direction

AlternativeCAM is intended to grow beyond drag-knife cutting. Potential future tool modes include:

- Drag Knife Cutting
- Pen / Marker Plotting
- Diamond Drag Engraving
- Etching
- Other alternative CNC processes

The repository name **AlternativeCAM** was chosen so the project is not permanently tied to one CNC process.

As the software expands, the broader application may eventually be released under the name **Alternative CAM Workbench**.

---

# Source Available

## Free to Use — Commercial Exploitation Restricted

AlternativeCAM is **source available**, but it is not distributed under a conventional open-source license.

The software may be used freely for personal, hobby, educational, internal business, and commercial production work. Businesses may use the software to manufacture products and provide paid services.

The AlternativeCAM software or source code itself may not be commercially exploited without permission. This includes selling or rebranding the software, selling modified versions, charging for hosted access, commercial redistribution of forks, or incorporating substantial portions of the code into another commercial software product.

See [LICENSE.md](LICENSE.md) for complete terms.

---

# Contributions

Contributions are encouraged. If you fix a bug, improve compatibility, improve documentation, add a useful feature, improve the interface, improve toolpath generation, or identify a safer implementation, please consider contributing that work back to the main AlternativeCAM repository.

Keeping development centralized allows the entire CNC community to benefit and reduces fragmentation.

See [CONTRIBUTING.md](CONTRIBUTING.md).

---

# Reporting Bugs & Feature Requests

Please use GitHub Issues for reproducible problems and feature requests. Include the Workbench version, browser, operating system, CNC machine/controller information, reproduction steps, screenshots, and a minimal SVG/project/G-code file when useful.

Remove private or sensitive information before uploading files.

---

# CNC Safety

CNC machines can cause machine damage, tool damage, property damage, fire, or personal injury when operated improperly.

**Never blindly run generated G-code.**

Always verify machine/controller compatibility, tool selection, coordinate system, work origin, Z heights, depths, feeds, workholding, material position, toolpath boundaries, and expected spindle behavior.

Use of AlternativeCAM software is at your own risk.

---

# Development Status

AlternativeCAM is actively developed.

**CNC Drag Knife Workbench v0.4.9.7 Beta** is the first public GitHub release. Beta software may contain bugs, incomplete functionality, compatibility problems, or unexpected behavior.

---

# License

**Source Available — Commercial Exploitation Restricted**

AlternativeCAM, AlternativeCAM Software, Alternative CAM Workbench, and CNC Drag Knife Workbench are covered by the AlternativeCAM Software License.

Copyright © 2026 GabrielMaker. All Rights Reserved.

See [LICENSE.md](LICENSE.md).

---

## GabrielMaker

Developed by **GabrielMaker**

Community testing, feedback, bug reports, documentation improvements, and code contributions are appreciated.
