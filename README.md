# Laboratoire 1 — Application de stationnement intelligent

## Description

Prototype dynamique d'une application mobile permettant à un utilisateur de gérer son stationnement dans une ville équipée de parcomètres intelligents connectés (zones A, B, C avec tarifs horaires différents).

Deux versions intégrées dans un seul projet Axure via Adaptive Views :
- **Téléphone** — utilisation rapide, en mobilité
- **Tablette** — vue plus détaillée

## Lien Axure Cloud

> À compléter une fois le projet publié : `https://...`

## Checklist des fonctionnalités

### Authentification
- [ ] Connexion avec compte hard-codé
- [ ] Création de compte (prénom, nom, courriel, mot de passe, confirmation, mode de paiement)
- [ ] Validation du mot de passe (8-12 caractères, lettres + chiffres, min. 1 majuscule + 1 minuscule)
- [ ] Reconnexion avec le compte nouvellement créé

### Gestion du véhicule
- [ ] Enregistrement d'un véhicule (numéro de plaque + surnom)

### Démarrage d'une session
- [ ] Option 1 — Démarrage immédiat (Zone C, 30 min, 0$)
- [ ] Option 2 — Choix d'une durée maximale (zone + minutes)
- [ ] Option 3 — Choix d'un budget maximal (zone + budget, durée calculée automatiquement)

### Session active
- [ ] Affichage : zone, temps restant, coût accumulé, véhicule actif
- [ ] Écoulement automatique du temps (accéléré pour la démo)
- [ ] Prolonger la session (temps ou argent)
- [ ] Changer de zone (nouveau tarif appliqué dès le changement)
- [ ] Mettre fin à la session
- [ ] Alerte modale si temps restant < 5 minutes

### Fin de session
- [ ] Modale de résumé : véhicule, zone, durée totale, coût total
- [ ] Mention d'amende potentielle (si temps tombé à zéro sans prolongation)

### Qualité générale
- [ ] Validation des champs
- [ ] Contrôles activés/désactivés selon le contexte
- [ ] Messages d'erreur explicites
- [ ] Interface adaptée au contexte (mobilité, stress, écran au soleil)
- [ ] Adaptive Views fonctionnelles (téléphone + tablette dans un seul projet)

## Structure du repo

```
docs/
├── enonce.pdf
├── specs-fonctionnelles.md
└── screenshots/
    ├── auth/
    ├── vehicule/
    ├── demarrage-session/
    ├── session-active/
    └── fin-session/
axure/
└── lien-cloud.md
```
