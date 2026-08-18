# # AlternativeCAM

### Alternative CNC Toolpath Software by GabrielMaker

**Current Application: CNC Drag Knife Workbench**

AlternativeCAM is the home of CNC Drag Knife Workbench and future software for CNC processes that do not fit neatly into traditional milling CAM workflows.

The project currently focuses on drag-knife cutting for desktop CNC machines, with future development intended to expand into additional processes such as pen/marker plotting, diamond-drag engraving, etching, and other alternative CNC operations.

---

## Project Goal

The goal of AlternativeCAM is to develop robust, practical CNC software that everyone can use freely — from hobbyists and makers to educators and businesses.

GabrielMaker wants future improvements, fixes, compatibility updates, and new features to remain centered in one place so the entire community can benefit from them.

Rather than having separate modified versions scattered across the internet, contributors are strongly encouraged to submit useful changes back to this repository whenever possible.

If you improve compatibility, fix a bug, add a useful feature, improve documentation, or find a better way of doing something, contributing that work here helps ensure those improvements remain available to everyone.

The goal is to allow AlternativeCAM to grow from a shared and maintained foundation while remaining accessible to the CNC community.

---

# CNC Drag Knife Workbench

**Current Version: v0.4.9.3 Beta**

CNC Drag Knife Workbench is a browser-based application designed to prepare vector artwork and generate compensated drag-knife toolpaths for desktop CNC machines.

It was originally developed around Makera CNC machines and currently provides its most tested workflow for that platform.

### Current capabilities include

- SVG import
- Artwork positioning and manipulation
- Vector editing
- Text tools
- Grouping and object management
- Cut-type assignment
- Kiss cuts
- Through cuts
- Drag-knife blade-offset compensation
- Corner handling
- Manual and automatic tabs
- Path ordering
- Toolpath preview
- G-code simulation
- G-code generation
- Job saving and loading
- Material and workspace configuration

The project remains in **Beta**. Generated G-code should always be reviewed before being run on a CNC machine.

---

## Future Direction

AlternativeCAM is intended to eventually support additional CNC processes from the same general workspace.

Potential future tool modes include:

- Drag Knife Cutting
- Pen / Marker Plotting
- Diamond Drag Engraving
- Etching
- Other alternative CNC processes

The repository name **AlternativeCAM** was chosen so development is not permanently tied to drag-knife cutting alone.

A future expanded application may be released under the name:

**Alternative CAM Workbench**

---

# Download

The recommended way to install CNC Drag Knife Workbench is through the official GitHub Releases page.

Download the latest release from:

**Releases → Latest Release**

Do not download unofficial redistributed copies when an official release is available.

---

# Browser Requirements

CNC Drag Knife Workbench is intended for current desktop versions of:

- Google Chrome
- Microsoft Edge

Some functionality relies on modern browser file-system capabilities and may not operate correctly in unsupported browsers.

---

# Supported Machines

CNC Drag Knife Workbench was initially developed for Makera CNC machines.

Current development and testing primarily focuses on:

- Makera Carvera
- Makera Carvera Air
- Makera Z1

Support for more generic CNC/controller profiles may be expanded in future releases.

AlternativeCAM and GabrielMaker are independent community projects and are not affiliated with or endorsed by Makera.

---

# Safety

CNC machines can cause machine damage, tool damage, property damage, fire, or personal injury when operated improperly.

**Never blindly run generated G-code.**

Before running a job:

- Review the generated toolpath.
- Confirm your machine and controller are compatible.
- Confirm tool selection.
- Confirm work coordinates.
- Confirm Z heights and cutting depths.
- Confirm feeds and machine movement.
- Confirm workholding.
- Confirm material dimensions.
- Verify that unexpected spindle commands are not present.
- Remain responsible for safe machine operation.

Use of AlternativeCAM software is at your own risk.

---

# Source Available

### Free to Use — Commercial Exploitation Restricted

AlternativeCAM is **source available**, but it is not distributed under a conventional open-source license.

The software may be used freely for:

- Personal use
- Hobby use
- Educational use
- Internal business use
- Commercial production work

Businesses may use AlternativeCAM to manufacture products and provide services for paying customers.

For example, you may use CNC Drag Knife Workbench to create decals or manufactured products and sell those products.

However, you may not commercially exploit the AlternativeCAM software or source code itself without permission.

This includes restrictions on:

- Selling the software
- Selling modified versions
- Rebranding the software
- Charging for access to it
- Commercially hosting it
- Incorporating substantial portions of the code into commercial software
- Commercially distributing forks
- Otherwise monetizing the AlternativeCAM source code or application itself

See [LICENSE.md](LICENSE.md) for the complete license terms.

---

# Contributions

Contributions are encouraged.

If you:

- Fix a bug
- Improve machine compatibility
- Improve documentation
- Add a useful feature
- Improve user experience
- Improve toolpath generation
- Find a safer or more reliable implementation

please consider contributing the improvement back to the main AlternativeCAM repository.

Keeping improvements centralized allows the entire CNC community to benefit and reduces the chance of incompatible or abandoned versions spreading across the internet.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting changes.

---

# Reporting Bugs

Please use GitHub Issues for reproducible software problems.

When reporting a bug, include whenever possible:

- AlternativeCAM / CNC Drag Knife Workbench version
- Browser and browser version
- CNC machine
- Controller or firmware information
- Steps required to reproduce the issue
- Screenshots
- Relevant SVG or `.dragknife` project file
- Generated G-code when applicable

**Remove private or sensitive information before uploading files.**

---

# Feature Requests

Feature suggestions are welcome through GitHub Issues.

Please explain:

- The problem you are trying to solve
- Your proposed workflow
- Why it would be useful to other users

Features that benefit the broader user community are especially encouraged.

---

# Development Status

AlternativeCAM is actively developed.

CNC Drag Knife Workbench is currently Beta software and may contain bugs, incomplete features, or compatibility issues.

Major releases and important changes will be documented through GitHub Releases and the project changelog.

---

# License

Copyright © 2026 GabrielMaker.

AlternativeCAM, Alternative CAM Workbench, AlternativeCAM Software, and CNC Drag Knife Workbench are covered by the AlternativeCAM Software License.

See [LICENSE.md](LICENSE.md).

---

## GabrielMaker

Developed by **GabrielMaker**

Community feedback, testing, bug reports, documentation improvements, and code contributions are appreciated.
