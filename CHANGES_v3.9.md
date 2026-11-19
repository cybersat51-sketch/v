# v3.9 — catalogue concurrency and compact home
- Fixed request-generation invalidation: parallel home requests no longer cancel one another.
- Added guarded catalog callback handling and error logging.
- Reduced hero and shortcut sizes for landscape.
- Banner uses the first available real poster; placeholder remains if server returns no poster.
- Server configuration unchanged.
- APK/device tests still required.
