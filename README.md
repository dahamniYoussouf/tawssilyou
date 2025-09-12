# tawsil-delivery-platform

Plateforme de livraison de repas - Client, Restaurant, Livreur, Admin

# Workflow Git - Tawsil

- `main` : code stable (production). Pas de push direct.
- `develop` : branche d’intégration. Toutes les nouvelles features passent par ici.
- `feature/...` : créez une branche pour chaque fonctionnalité.

### Règles

1. Créez toujours vos branches à partir de `develop`.
2. Quand la feature est prête → ouvrez une Pull Request (PR) vers `develop`.
3. Les tests doivent passer avant merge.
4. `main` est protégé : uniquement merge depuis `develop` après validation.
