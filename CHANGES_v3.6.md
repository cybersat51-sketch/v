# IPTV PRO2 v3.6 — stability fixes

- Fixed compile-time references to nonexistent `content` and `search` variables in Favorites and Downloads screens.
- Search icon now opens a search hub with live, film and series catalog choices instead of unexpectedly opening Films.
- Removed pending search callbacks before re-rendering lists.
- Sidebar category click explicitly preserves the owning catalog type.
- Version code/name updated to 36 / 3.6.0.
- Server configuration, player, EPG, download and favorites behavior retained.

**Validation:** ZIP and static source checks only; Android build and device testing not performed.
