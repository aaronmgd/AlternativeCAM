# Contributing to AlternativeCAM

Thank you for considering contributing to AlternativeCAM.

The goal of this project is to keep useful improvements to AlternativeCAM, CNC Drag Knife Workbench, and future AlternativeCAM applications centralized so the entire CNC community can benefit.

## Ways to Contribute

Contributions may include:

- Bug fixes
- Machine compatibility improvements
- Controller compatibility improvements
- User-interface improvements
- Toolpath improvements
- Documentation
- Testing
- Example files
- Feature development
- Code cleanup
- CNC safety improvements

## Before Starting a Major Feature

For significant changes, please open a Feature Request or GitHub Discussion first.

This helps prevent separate incompatible implementations of the same feature.

## Bug Fixes

Please explain:

1. What was wrong.
2. How to reproduce it.
3. What you changed.
4. How you tested it.
5. Whether the change affects generated G-code.

Whenever possible, include a minimal SVG or Workbench project demonstrating the problem.

## Pull Requests

Pull requests should:

- Focus on a specific change.
- Clearly describe the change.
- Avoid unrelated formatting/code changes.
- Preserve existing functionality unless intentionally changing it.
- Include testing information.
- Clearly identify changes affecting generated CNC instructions.

## CNC Safety

Changes affecting G-code require additional care.

Please verify:

- Spindle behavior
- Z movement
- Clearance moves
- Feed commands
- Tool changes
- Coordinate handling
- Controller-specific commands
- End-of-job behavior

Never assume machine code is safe merely because it is syntactically valid.

## Contributions and Licensing

By submitting a contribution, you confirm that you have the right to submit it.

Unless separately agreed in writing, contributors retain rights they hold in their original contribution while granting GabrielMaker permission to incorporate, modify, distribute, and relicense that contribution as part of AlternativeCAM.

Submitting a contribution does not transfer ownership of the original AlternativeCAM codebase.

See [LICENSE.md](LICENSE.md) for complete project terms.

## Keep Improvements Together

AlternativeCAM benefits most when improvements are returned to the primary project rather than becoming isolated versions scattered around the internet.

If you create something useful, please consider contributing it here so everyone can benefit.
