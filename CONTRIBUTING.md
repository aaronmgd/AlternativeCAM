# Contributing to AlternativeCAM

Thank you for considering contributing to AlternativeCAM.

The goal of this project is to keep useful improvements to AlternativeCAM,
CNC Drag Knife Workbench, and future AlternativeCAM applications centralized
so the entire CNC community can benefit.

## Ways You Can Contribute

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
- Safety improvements

## Before Starting a Major Feature

For significant changes, please open a Feature Request or discussion first.

This helps avoid multiple people independently developing incompatible versions
of the same feature.

## Bug Fixes

Please explain:

1. What was wrong.
2. How to reproduce the problem.
3. What you changed.
4. How you tested the fix.
5. Whether the change affects generated G-code.

Whenever possible, include a small test file demonstrating the problem.

## Pull Requests

Pull requests should:

- Focus on a specific change.
- Clearly describe what was changed.
- Avoid unrelated formatting or code changes.
- Preserve existing functionality unless the change intentionally modifies it.
- Include testing information.
- Clearly identify changes affecting generated machine instructions.

## CNC Safety

Changes affecting G-code generation require additional care.

Please verify:

- Spindle behavior
- Z movement
- Clearance moves
- Feed commands
- Tool changes
- Coordinate handling
- Controller-specific commands
- End-of-job behavior

Never assume generated machine code is safe merely because it appears valid.

## Contributions and Licensing

By submitting a contribution to AlternativeCAM, you confirm that you have the
right to submit that contribution.

Unless separately agreed in writing, contributors retain rights they hold in
their original contribution while granting GabrielMaker permission to
incorporate, modify, distribute, and relicense the contribution as part of
AlternativeCAM.

Submitting a contribution does not transfer ownership of the original
AlternativeCAM codebase to the contributor.

See LICENSE.md for the complete project terms.

## Keep Improvements Together

AlternativeCAM benefits most when improvements are returned to the primary
project rather than becoming isolated versions scattered across the internet.

If you build something useful, please consider contributing it here so everyone
can benefit from it.
