# Copilot Metrics Lite

## Overview

**Copilot Metrics Lite** is a Visual Studio Code extension that enables you to track and visualize your Copilot usage directly within VS Code. Gain actionable insights into your coding productivity by seeing how often Copilot assists you, which files and languages benefit the most, and how much code is being generated.

## Features

- **Dashboard Access:** Launch the dashboard from the status bar or command palette at any time.
- **Completions Tracking:**
  - Counts all Copilot completions you accept in your workspace.
  - Tracks completions by file and language.
- **Productivity Metrics:**
  - Total completions
  - Total lines and characters generated
- **Per-File and Per-Language Reports:**
  - See which files and programming languages benefit most from Copilot assistance.
- **Pagination:**
  - Easily browse large file lists using pagination controls.
- **Live & Manual Refresh:**
  - Dashboard auto-refreshes every 30 seconds or can be refreshed manually.
- **Reset Metrics:**
  - Clear all collected metrics with a single click.
- **Authentication Integration:**
  - See your VS Code account integration status and personalize your experience.
- **Privacy:**
  - All metrics are stored locally. No data leaves your machine.

## How It Works

- The extension monitors your editor for Copilot completions (when you accept code suggestions) and collects metrics on completions, lines, and characters generated, grouped by file and programming language.
- All data is stored locally within VS Code and can be reset at any time via the dashboard.
- Use the status bar icon or run the command `Show Copilot Metrics Dashboard` to open the dashboard at any time.

## Usage

1. **Open the Dashboard:**
   - Click the Copilot Metrics icon in the VS Code status bar, or
   - Open the command palette and run `Show Copilot Metrics Dashboard`.
2. **Sign In:**
   - If prompted, sign in to personalize your experience.
3. **Review Metrics:**
   - Browse completions, lines, and characters generated, see detailed breakdowns per file and language, and use pagination for large projects.
4. **Reset or Refresh:**
   - Use the dashboard buttons to reset your metrics or manually refresh the data.

## Support

For questions, issues, or feature requests, please open an issue in the repository.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md) for release notes and version history.
