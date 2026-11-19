# IPTV PRO2 v5.2 — Live Player Fixes

- Live streams: disable Media3 playback controller and its time/seek bar (VOD retains it).
- Add previous/next channel controls that replace the stream inside the same ExoPlayer instance.
- Use the currently selected channel category or home shelf as the channel switching queue.
- Refresh channel title and EPG target on channel changes.
- Compact player actions to 34dp and remove duplicate back button in normal view.
- In fullscreen show the overlay back control; hide toolbar and actions.
- Hide Android status bar while playing; restore it on leaving player.
- Keep auto-login, cached home, no movie banner, favorites, resume and VOD controls.

Note: APK runtime tests are still needed on an Android device; GitHub Actions builds the APK.
