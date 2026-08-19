# CNC Drag Knife Workbench v0.4.9.7 Beta

**First Public GitHub Release**  
Part of the **AlternativeCAM** project by GabrielMaker.

CNC Drag Knife Workbench is a browser-based application for preparing SVG artwork, creating compensated drag-knife toolpaths, previewing CNC motion, and generating G-code for desktop CNC machines.

The application was developed primarily around Makera CNC machines and remains in active Beta development.

## Highlights

- SVG import with oversized-artwork preflight
- Drag-and-drop, clipboard, and multiple-SVG intake
- Vector transforms, grouping, alignment, and distribution
- Shape Designer
- Advanced Offset Path tools
- Fillet and Chamfer tools
- Simplify and Smooth
- Path Cleanup / Repair
- Geometry Inspector
- Union, Subtract, Intersect, and Divide Boolean operations
- Selection filters and Layers / Objects management
- Array / Step-and-Repeat
- Material presets and Design Safe Margin
- Design History and Design Diagnostics
- Kiss Cut and Thru Cut assignment
- Drag-knife blade-offset and corner compensation
- Per-vector Multi-Pass Thru Cutting
- Progressive Depth and Same Depth Each Pass strategies
- Manual and automatic holding tabs
- Toolpath Preview and Simulator
- G-code Viewer and 3D inspection
- Project Save / Open workflow
- Program Folder expanded tools
- Material-boundary and geometry safety checks

## Browser Requirements

Use a current desktop version of:

- Google Chrome
- Microsoft Edge

Some functionality relies on modern browser file-system capabilities.

## Supported Machines

Development and testing currently focuses on:

- Makera Carvera
- Makera Carvera Air
- Makera Z1

Support for additional CNC/controller profiles may be added later.

AlternativeCAM and GabrielMaker are independent community projects and are not affiliated with or endorsed by Makera.

## Beta Notice

This software is currently **Beta**. Bugs, incomplete features, compatibility problems, or unexpected behavior may still exist.

**Never blindly run generated G-code.** Always verify the tool, work origin, Z heights, depths, feeds, material position, workholding, toolpath location, machine compatibility, and expected spindle behavior before running a job.

## License

AlternativeCAM is **Source Available — Commercial Exploitation Restricted**.

The software may be freely used personally, educationally, or within a business, including for manufacturing products and providing paid services.

The AlternativeCAM software or source code itself may not be sold, rebranded, commercially hosted, commercially redistributed, or otherwise monetized without permission.

See `LICENSE.md` for complete terms.

## Future Direction

AlternativeCAM is intended to expand beyond drag-knife cutting. Planned areas of exploration include:

- Pen / Marker Plotting
- Diamond Drag Engraving
- Etching
- Additional alternative CNC workflows

A major goal of AlternativeCAM is to keep useful development centralized so fixes and improvements can benefit the entire community.

— **GabrielMaker**
