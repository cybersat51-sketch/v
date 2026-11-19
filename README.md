# IPTV PRO2 v1.8 — GitHub-ready Android source

Upload **the contents of this folder**, not the folder itself, to the repository root.
Expected root: `.github/workflows/android.yml`, `app/`, `build.gradle`, `settings.gradle`, `gradle.properties`.

## Build
1. GitHub → repository → Add file → Upload files. Upload the folder contents preserving directories (prefer git push or GitHub web editor for nested paths).
2. Actions → IPTV PRO2 - Build APK → Run workflow (or push to main).
3. After the green check, open the run → Artifacts → IPTV-PRO2-APK → download ZIP → extract APK.

## Notes
- This is source, **not a built APK**. CI has not been run in this environment.
- Java 17, Gradle 8.9, Android Gradle Plugin 8.7.3, AndroidX enabled.
- Existing IPTV login endpoint and playback code retained; no live server verification.
- Do not create an `https:` directory: `gradle.properties` belongs at the repository root.
- Do not keep two conflicting workflow YAML files; use only `.github/workflows/android.yml`.
- The APK is a debug build for testing, not a signed production release.


## v2.0 EPG et téléchargements
- Dans le lecteur Live TV : bouton GUIDE TV • EPG, requête Xtream `get_short_epg`. Les données doivent être fournies par le serveur.
- Dans le lecteur Films et Épisodes : bouton TÉLÉCHARGER. Téléchargement direct via Android DownloadManager, uniquement pour MP4/MKV/AVI/MOV/TS/WEBM.
- Fichiers enregistrés dans le dossier de téléchargements propre à l'application (Android/data/com.iptvpro2.player/files/Download), pas nécessairement dans le dossier Téléchargements public.
- Pas de support de téléchargement HLS/m3u8 ni DRM. Les URLs doivent être accessibles et les droits de téléchargement respectés.
- Code source modifié ; APK non compilé ni testé sur un appareil dans cet environnement.


Version 4.8: one featured movie on the home screen, with no auto-rotation.
