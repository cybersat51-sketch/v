# v3.2 — Landscape & dynamic movie banner

- Application orientation defaults to sensorLandscape (including login, home, catalog and player).
- Home hero retrieves real movie artwork from get_vod_streams and cycles every 6.5 seconds.
- Banner button opens the selected film, rather than a generic TV category.
- Stops rotation on navigation and activity destruction.
- Fallback hero when no artwork is supplied.
- Existing server settings, EPG, favorites and downloads retained.

Note: The movie endpoint does not guarantee newest-first order. The banner uses the last catalog items as an approximation; accurate newest sorting requires a reliable added-date field.
Not built or tested on an Android device in this environment.
