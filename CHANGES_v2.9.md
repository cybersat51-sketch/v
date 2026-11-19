# IPTV PRO2 v2.9 — Category artwork

- Category cards now reserve a dedicated 82 × 94 dp poster thumbnail area.
- For Films and Séries, the app asynchronously retrieves the catalog and uses the first available real poster for each category.
- Posters are associated by `category_id` and loaded through the existing artwork cache.
- Categories without artwork retain a styled gradient placeholder (no fake movie posters).
- Existing navigation, search, player, favorites, downloads, EPG, GitHub workflow, and server settings remain unchanged.

Note: Android APK compilation and real-server behavior have not been tested in this environment.
