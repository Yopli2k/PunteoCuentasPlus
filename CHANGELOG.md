# Changelog

All significant changes to this project will be documented in this file.

## [2.02] - 2026-11-02
### New Features and Improvements
- Raised the minimum core version to 2026.6.
- Removed the plugin's own template for the attached files tab; the core one is now used.

### Bug Fixes
- Fixed the bulk subaccount change, which did not receive the selected entry lines.
- The bulk subaccount change checks the update permission and the form token, and only modifies entry lines of the subaccount being edited.
- Translated the notice for file types without preview in the attached files tab.


## [2.01] - 2026-09-15
### New Features and Improvements
- Refactored the code for core 2026.
- Upgraded the php requirement to 8.1.
