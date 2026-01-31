# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0] - 2026-01-31

### Added
- **Firebase Authentication** - Google sign-in for family sharing
- **Cloud Firestore Database** - Real-time data sync across devices
- **Multi-device Sync** - All family members see same data in real-time

### Changed
- Data storage moved from localStorage to Firebase Cloud

### Added
- **Theme Support** - Light/Dark mode toggle
- **Due Dates** - Set deadlines for tasks with visual indicators (overdue, due soon)
- **Tags/Labels** - Categorize tasks with custom tags (Work, Personal, Urgent, Other)
- **Sub-tasks** - Add and track subtasks within tasks with checkboxes
- **Multiple Boards** - Create and switch between different project boards
- **Archive** - Archive completed tasks for later reference
- **Task Description** - Add descriptions to tasks
- **Drag & Drop** - Move tasks between columns easily

### Improved
- Better responsive design for mobile devices
- Enhanced visual styling with smooth animations
- Dark mode support with proper color scheme

### Technical
- Data persistence using localStorage
- Self-contained single HTML file (no external dependencies)