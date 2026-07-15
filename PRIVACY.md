# SideSearch Privacy Policy

**Effective date:** July 15, 2026

This Privacy Policy explains how SideSearch handles information when you install and use the Android application.

## 1. Developer

SideSearch is developed and distributed by Marco Pratticò. Privacy questions may be submitted through the official [SideSearch repository](https://github.com/noisystyle/SideSearch/issues).

## 2. Information SideSearch does not collect

The current version of SideSearch does not include:

- analytics or advertising SDKs;
- a SideSearch account system;
- a SideSearch cloud backend; or
- developer-operated tracking or telemetry.

SideSearch does not send your contacts or notifications to the developer.

## 3. Information stored on your device

SideSearch stores limited preferences locally on your Android device, including:

- onboarding completion;
- theme and icon preferences;
- search preferences;
- a short list of recently launched app package names;
- a short local history of recently used commands for command suggestions; and
- Focus rules, limits, temporary unlocks, and local usage counters for apps you configure.

This information remains on the device and can be removed by clearing the app's data or uninstalling SideSearch.

## 4. Optional permissions

### Contacts

If you grant Contacts permission and use a contact command, SideSearch searches the device address book locally to show matching recipients. Contact data is not sent to the developer.

### Notification access

If you grant notification access, SideSearch reads active notifications and media-session information locally so it can display notifications, expose supported actions, and provide media controls. This information is not sent to the developer.

When a compatible notification supports direct reply, the text you enter is passed directly to Android's notification action. SideSearch does not save or log the reply text. A temporary local confirmation may be shown in the notification card while the current SideSearch session remains open.

If you configure a Focus rule to pause or discard an app's notifications, SideSearch applies that choice only to notifications from the selected app. It does not pause notifications globally.

### Focus boundaries

Focus boundaries are optional. Usage access lets SideSearch read local Android app-usage events so it can calculate limits for apps you configure. The optional Accessibility service enforces those rules when a blocked app is opened outside SideSearch. The service listens only for window and app changes and is configured not to retrieve window content.

Focus processing and stored counters remain on your device. SideSearch does not send app-usage history, configured rules, or accessibility events to the developer.

### System controls and edge handles

If enabled, SideSearch uses Android system-settings access to adjust brightness and auto-rotation. Display-over-other-apps access is used only to show the optional left and right edge handles. A foreground-service notification and optional battery-optimization exemption keep those handles available in the background. These capabilities do not send device information to the developer.

### Home widgets

The optional Home widgets can open SideSearch, locally stored recent apps, Google Lens, and Google song recognition. The recent-app widget reads the locally stored package names described above so it can show the same recent apps as SideSearch. Widget data remains on the device.

You can revoke these permissions at any time through Android settings.

## 5. Network requests

### Weather

When you request weather information, SideSearch sends the location text you entered to the Open-Meteo geocoding and forecast APIs. The network request also exposes standard connection information, such as your IP address, to the service provider. Open-Meteo handles that information under its [Terms and Privacy Policy](https://open-meteo.com/en/terms).

### External apps and services

When you choose a command for another app or online service, Android may transfer the text or destination you selected to that app or service. Examples include Google, Google Maps, YouTube, ChatGPT, Gemini, WhatsApp, Telegram, and Signal. Their own privacy policies and terms apply.

SideSearch does not transfer command content to those services until you select the corresponding action.

## 6. Distribution and optional support

The official APK is distributed free of charge through GitHub Releases. SideSearch may include a link to an external service where users can optionally support the developer. Support is not required to download, install, or use the Application. SideSearch does not receive or process payment information.

## 7. Data retention

The developer does not receive or retain app usage data from SideSearch. Locally stored settings, command history, Focus rules, and counters remain on your device until you clear app data or uninstall the application. Third-party services may retain information according to their own policies.

## 8. Security

SideSearch uses Android permissions and platform APIs to limit access to protected device information. No method of software distribution or network communication is completely secure, and absolute security cannot be guaranteed.

## 9. Children's privacy

SideSearch is not specifically directed to children and does not knowingly collect personal information from children through a developer-operated service.

## 10. Changes to this policy

This policy may be updated when SideSearch features or data practices change. The effective date at the top of this document will be revised when changes are published.

## 11. Contact

For privacy questions, contact Marco Pratticò through the official [SideSearch repository](https://github.com/noisystyle/SideSearch/issues).
