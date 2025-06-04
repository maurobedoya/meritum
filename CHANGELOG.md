# Changelog

All notable changes to Meritum will be documented in this file.

## [Unreleased]

### Added
- Working on: Font size control by users


## [0.3.0] - 2025-06-01

### Added
- **Report Tab**: New progress report with summary statistics, goals progress tracking, and GitHub-style activity timeline showing task completions, note creation, and milestone achievements.
- **Substask feature**: Now, it is possible to add subtasks to main tasks and is displayed in points in the Gantt Chart
- **Duplicate Task**: Added "Duplicate" button to Tasks tab, Gantt chart, and task details. Creates copy with reset progress and adjusted title.
- **New create buttons**: Create new Tasks, Subtasks and Notes is possible now in every tab

### Changed
- **Edit Notes**: Users can now edit both title and content of existing notes
- **Last Modified Tracking**: Notes show when they were last modified
- **Scrollable Notes Display**: Notes in Task Details are now displayed in a scrollable format
- **Search box**: The search box now updates as you type

### Fixed
- Were removed special characters that were not displayed
- Add subtask button in the Gantt Chart timeline was deactivated
- Filtering by goals in the Gantt Chart was fixed
- Search was fixed in Tasks, Subtasks and Notes tabs

## [0.2.9] - 2025-05-12

### Added
- A new way to store the configuration of the app in the system

### Changed
- CHANGELOG.md was updated
- meritum.py main was updated

### Fixed
- A bug related with saving the configuration of the app in the system


## [0.2.8] - 2025-05-12

### Added
- Proper instructions to setup Meritum for Teacher and Student

### Changed
- README.md updated
- CHANGELOG.md updated

### Fixed
- Required version of python to 2.7


## [0.2.7] - 2025-05-10

### Added
- New student profile fields for birth date, profession, and telephone
- Color indicators for goal-associated tasks in Gantt Chart
- Progress tracking for goals based on associated tasks
- Ability to mark tasks as not complete after completion

### Changed
- Improved task filtering by goal in Tasks view
- Enhanced Gantt chart with better zoom controls and view options
- Updated UI colors for better visibility and consistency

### Fixed
- Task completion status sometimes not updating correctly
- Goal progress calculation bug with completed tasks
- Path selection issues in student mode


[Unreleased]: https://github.com/maurobedoya/meritum/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/maurobedoya/meritum/compare/v0.2.9...v0.3.0
[0.2.9]: https://github.com/maurobedoya/meritum/compare/v0.2.8...v0.2.9
[0.2.8]: https://github.com/maurobedoya/meritum/compare/v0.2.7...v0.2.8
[0.2.7]: https://github.com/maurobedoya/meritum/releases/v0.2.7
