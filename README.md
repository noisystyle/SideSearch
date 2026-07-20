# SideSearch

**A fast Android launcher and search panel for apps, commands, notifications, widgets, weather, and media.**

[![Android 8.0+](https://img.shields.io/badge/Android-8.0%2B-3DDC84?logo=android&logoColor=white)](https://www.android.com/)
[![Version 0.5.0](https://img.shields.io/badge/version-0.5.0-555555)](#current-status)
[![Proprietary](https://img.shields.io/badge/license-proprietary-yellow)](EULA.md)

SideSearch is a native Android app that lets you search and launch apps, run quick commands, use Home-screen widgets, check and reply to compatible notifications, control media playback, and access useful information from one fluid panel.

Use it as your Home launcher, set it as the default Android assistant, add its search widget, or open it through the optional edge handles.

## Get SideSearch

SideSearch is distributed free of charge. Download the official signed APK from GitHub Releases:

### [Download SideSearch](https://github.com/noisystyle/SideSearch/releases/latest)

No payment is required to download or use the app. The release includes the signed Android APK and its SHA-256 checksum.

> This is the official public information and release repository. It intentionally contains no application source code. SideSearch is proprietary software and is not open source.

## Preview

<p align="center">
  <img src="assets/sidesearch-search.png" alt="SideSearch universal app and command search" width="360">
</p>

## Features

- Fast app search with exact, prefix, acronym, fuzzy, typo-tolerant, and usage-aware matching.
- Recent apps, contextual Android app shortcuts, native uninstall, and split-screen actions.
- Configurable favorite apps before recents, with direct contextual reordering.
- Optional Home launcher mode with the same search, quick controls, media, notifications, and widget panel, plus stable single-instance task reuse and launcher-specific keyboard behavior.
- Animated full-height search mode that gives results more room while typing and returns to the dashboard when the keyboard closes.
- Search-bar shortcuts for Google Lens and Google song recognition, plus a compact modern settings menu.
- Recently used commands suggested as soon as a matching command prefix is entered.
- Gesture contextual menus for apps and recent apps, with haptic drag selection and smooth slide-down dismissal.
- Android assistant integration for access from the system gesture or button.
- Optional persistent edge handles for opening search or notifications over other apps.
- Adaptive quick settings with connectivity, rotation, flashlight, brightness, auto-brightness, volume, ringer mode, wallet, and system settings controls.
- Compact portrait quick settings with a promoted media player when enough vertical space is available.
- Multi-session media pager with active playback selected first, page dots, snap feedback, and duplicate notification filtering.
- Full-width media timeline with live playback progress, drag-to-seek, haptic feedback, a scrub tooltip, and animated start/end time labels.
- Adaptive recent-app widget and a compact monochrome search-bar widget with Lens and song-recognition shortcuts.
- A paged widget panel that loads widgets only when needed, restores the previous page, supports Samsung Calendar widgets, and keeps media state live while open.
- Interactive notifications grouped under their source apps, with clearer sender, conversation, message, time, and app hierarchy.
- Direct reply inside compatible messaging notifications, including local sent-message confirmation; reply text is not saved by SideSearch.
- Rich media cards with artwork, available previous, play/pause, next, like, close controls, and seek support when exposed by Android.
- Binding Focus boundaries with schedules, daily/session/opening limits, cooldowns, app-specific notification handling, delayed changes, and randomized minigames for temporary access.
- Weather cards with current conditions, hourly data, and a five-day forecast.
- Contact commands for calls, SMS, email, WhatsApp, Telegram, and Signal.
- Natural-language calendar event drafts in English and Italian that open in the system-default calendar.
- Quick commands for Google, Maps, YouTube, ChatGPT, Gemini, and messaging apps.
- User-defined commands for opening URL templates, launching apps, or sending text to target apps.
- Automatic recognition of email addresses, URLs, phone numbers, and calculations.
- Material You light, dark, and system themes, including Samsung/ColorBlendr monochrome palettes, tonal icons, and native Samsung icon shaping.
- Adaptive layouts for phones, landscape displays, tablets, and foldables.
- High-refresh-rate support where available, lazy app-icon loading, bounded caches, and reduced media-progress redraws.
- Softer panel, widget, pager, app-entry, and dismissal animations with consistent physical haptic feedback.

Weather data by [Open-Meteo.com](https://open-meteo.com/).

## Example commands

| Action | Example |
| --- | --- |
| Weather | `we Naples` or `meteo Rome` |
| Google | `g android split screen` |
| Maps | `maps pizza nearby` |
| YouTube | `yt phone review` |
| ChatGPT | `ch summarize this text` |
| Gemini | `ge explain this` |
| Contact | `tel Martina`, `wa Marco`, `email Anna` |
| Calendar | `meeting tomorrow at 6:30 pm` |
| Calculator | `24*7+3` |

## Requirements

- Android 8.0/API 26 or later.
- Sideloading permission for the browser or file manager used to open the APK.
- Optional notification access for notification and media features.
- Optional Contacts permission for contact commands.
- Optional Camera permission for the flashlight quick setting.
- Optional system-settings access for brightness and auto-rotation controls.
- Optional display-over-other-apps, notification, and background-operation access for persistent edge handles.
- Optional Usage access for accurate Focus time limits.
- Optional Accessibility service for enforcing Focus boundaries outside SideSearch. It observes only window/app changes and is configured not to retrieve window content.
- A device that allows SideSearch to be selected as the Home launcher or default digital assistant for those opening modes.

## Current status

The current release is **SideSearch 0.5.0**, a work-in-progress preview. Feature availability can vary by Android version, device manufacturer, installed applications, and the capabilities exposed by notifications, media sessions, widgets, and manufacturer customizations.

This update focuses on launcher reliability, native Samsung integration, and more intentional app access. It adds favorite apps with contextual reordering, expanded natural-language calendar parsing that respects the default calendar, stricter Focus boundaries with persistent randomized minigames, localized reading alternatives, and a 24-hour delay for later boundary changes. Material You colors now follow Samsung and ColorBlendr monochrome palettes, while icon rendering supports tonal colors and Samsung-style shaping. Notification and media handling now removes technical System UI duplicates, keeps media apps searchable, follows track and play/pause changes in real time even with the widget panel open, and improves reply reconciliation. Weather loading, keyboard focus, navigation-bar continuity, launcher task reuse, hosted Samsung Calendar widgets, and quick-panel interactions have also been hardened.

The release includes `SideSearch-0.5.0-SHA256SUMS.txt` so the signed APK can be verified after download.

## Privacy and legal

- Read the [Privacy Policy](PRIVACY.md).
- Read the [End User License Agreement](EULA.md).
- Read the [repository notice](NOTICE.md).

Lawfully obtaining SideSearch grants a limited personal-use license. It does not grant access to the source code or permission to redistribute, resell, modify, or republish the APK.

## Support

Supporting SideSearch is entirely optional and does not unlock features or affect access to the app.

### [Support SideSearch on Buy Me a Coffee](https://buymeacoffee.com/marcoprattv)

For questions or permission requests, use the repository's [issue tracker](https://github.com/noisystyle/SideSearch/issues).

Copyright (c) 2026 Marco Pratticò. All rights reserved.
