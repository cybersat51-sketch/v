# GitHub build repair (v5.9 source retained)

- Existing settings.gradle already includes google() and mavenCentral(); these were not removed.
- GitHub Actions workflow now checks Maven Central connectivity for the four artifacts shown in the screenshots.
- Gradle build retries up to three times to tolerate temporary dependency/network failures.
- Build logs are uploaded as IPTV-PRO2-build-logs when a run fails.
- Both main and master branches trigger the workflow.
- No UI, login, player, Java, or dependency versions were changed.
- This does not guarantee a successful build: source compilation or persistent repository/network failures still require logs.
