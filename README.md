# arthome-studio-web

La **régie professionnelle** en **Angular 22**. Conduite du direct, programmation, modération, équipe et droits, recettes et versements.

15 entrées de navigation filtrées par rôle · 6 personas · régie, fiche de date à six volets

## État

**Pas encore commencé.** Palier 4 — la démonstration d'architecture. Deux piles hétérogènes, un seul domaine : le même `@arthome/core` que le storefront.

## Où est la conception

L'architecture, les contrats d'interface, les décisions et leurs raisons vivent dans
**[arthome-core](https://github.com/jubasse/arthome-core)** :

- `architecture/` — carte des contextes, modèle de données, catalogue d'événements, ADR
- `openapi/` — les contrats des deux BFF
- `proto/` — les schémas d'événements Kafka
- `DECISIONS.md` — le journal des arbitrages
- `architecture/critical-rules.md` — **à relire à chaque session**, dix-neuf lignes

## Arthome

Plateforme de diffusion en direct de spectacle vivant : billetterie, direct, tchat modéré,
rediffusions, boutique, versements aux artistes. Deux produits — un storefront public et un studio
professionnel — sur cinq surfaces, servis par sept microservices.
