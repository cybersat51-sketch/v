# IPTV PRO2 v5.4 — Functional shortcuts

- Continuer: saves the last VOD/episode ID and type and uses existing playback-position resume mechanism. Live TV is excluded from seek resume.
- Nouveautés: shows VOD sorted by provider `added` timestamp, when supplied. Falls back to catalog order if absent.
- Programme TV: choose a live channel and request `get_short_epg` from Xtream-compatible server; displays an unavailable state when no listings exist.
- Recherche: unified search across locally cached live, VOD and series catalogs; fetches missing catalogs asynchronously; results are capped at 60.
- Catégories: hub for Live TV, Films and Séries instead of opening live only.
- Preserved existing home design, automatic login and playback code.

Limitations: Requires an Xtream-compatible server for EPG and metadata; no Android SDK/Gradle build or device integration test performed. No guarantees about provider EPG or newly added dates. Existing account/network credentials remain handled by the original app.
