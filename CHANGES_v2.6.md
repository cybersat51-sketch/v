# IPTV PRO2 v2.6 — targeted UI/navigation fixes
- Player controls placed in a scrollable 180dp panel to preserve video viewing area on smaller screens.
- Player return from movie/live catalog restores the existing filtered list rather than downloading it again.
- Search text retained in current list state; favorites refresh preserves the filter.
- Button padding and corner radii use density-independent dp values.
- Defensive parsing of download labels avoids substring errors with unexpected preference keys.
- All previous server settings, playback, EPG, downloads and GitHub workflow files retained.

## Validation limitations
Source reviewed and ZIP structure checked. Android SDK/Gradle build environment is unavailable here, so no APK compilation, emulator run, real server connection, or exhaustive button test was performed. This is not a verified production release.
