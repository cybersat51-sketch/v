# IPTV PRO2 v3.5 — Correctifs ciblés

- Barre de recherche enfin attachée à la vue du catalogue.
- Navigation des catégories liée au type de catalogue capturé, évitant une dépendance à currentType mutable.
- Conservation du conteneur racine pour éviter le détournement de la référence root vers le panneau droit.
- Réinitialisation de l’image avant chargement asynchrone; vérification de l’URL attendue et de la présence de la vue avant application.
- Barre latérale ajustée à la largeur de l’écran.
- Version Android 3.5.0 (code 35).
- Serveur et configuration réseau inchangés.

## Limites de validation
Vérifications statiques effectuées. Build Gradle et essais sur appareil non exécutés dans cet environnement.
