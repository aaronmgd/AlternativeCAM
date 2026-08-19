# Security Policy

If you discover a security vulnerability in AlternativeCAM, please avoid publicly posting sensitive exploit information before GabrielMaker has had an opportunity to review it.

Ordinary software bugs, compatibility problems, incorrect toolpaths, or G-code issues should be reported through GitHub Issues.

## CNC Safety Issues

If you discover behavior that may cause:

- Unexpected machine motion
- Unintended spindle activation
- Unsafe Z movement
- Incorrect tool changes
- Unsafe rapid movement
- Dangerous generated G-code

please clearly identify the report as:

**SAFETY ISSUE**

Include:

- Software version
- CNC machine
- Controller / firmware
- Reproduction steps
- Relevant project/G-code files when possible

Never run unverified machine code solely to reproduce a suspected safety issue.
