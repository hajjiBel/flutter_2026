# flutter_2026 — TP Flutter / Dart (ISET)

Énoncés des 10 travaux pratiques du module Flutter (un semestre), construits autour d'un **projet fil rouge unique : LocalSwap**, une application de troc et d'entraide de quartier.

| TP | Thème | Séances | LocalSwap à la fin du TP |
|---|---|---|---|
| [TP1](TP1_Decouverte_Environnement.md) | Découverte, environnement, Hot Reload, qualité | 1 | Projet, Git, thème clair/sombre |
| [TP2](TP2_Dart_Avance.md) | Dart 3 : null safety, collections, records, patterns, `sealed`, async | 1 | Modèles immuables, JSON validé |
| [TP3](TP3_Widgets_Material.md) | Widgets, mise en page, Material 3 | 1 | Écran d'accueil, gabarit de carte |
| [TP4](TP4_Stateful_Listes.md) | Stateless/Stateful, cycle de vie, `InkWell`, listes, clés | 1 | `CarteAnnonce`, liste / grille |
| [TP5](TP5_Navigation_UI.md) | Navigation, dialogues, `NavigationBar`, `PopScope` | 1 | 3 onglets, détail, réservation |
| [TP6](TP6_Formulaires_Avances.md) | Formulaires, validation (y compris asynchrone), recherche | 1 | Publication d'annonce, filtres |
| [TP7](TP7_Provider_Etat.md) | État partagé avec Provider | 2 | `AnnoncesProvider`, Mes échanges |
| [TP8](TP8_HTTP_JSON.md) | HTTP, JSON, API REST (`json-server`) | 2 | Données persistées sur l'API |
| [TP9](TP9_Tests.md) | Tests unitaires, de widgets, `MockClient`, `mocktail` | 1 | Suite de tests |
| [TP10](TP10_Deploiement.md) | Build release, signature, CI, soutenance | 1 + soutenance | Application livrable |

## Organisation de chaque TP

- 🎯 Objectifs mesurables · 📋 Prérequis · 📘 Rappel de cours · 🗺️ Diagramme(s) Mermaid
- 🧪 **Partie A** : exercices indépendants (sans LocalSwap), code complet à taper et à observer
- 🏗️ **Partie B** : application au projet LocalSwap
- 🤖 **Partie C** : comprendre et maîtriser le code (prédire, trouver les bugs, critiquer du code généré par IA, modifier sous contrainte, expliquer, exercice papier, journal IA)
- 🚀 **Partie D** : défis bonus
- 🎤 Validation orale · ✅ Checklist · ⚠️ Erreurs fréquentes · 📝 Quiz · 📊 Barème (≈ 40 % code, ≈ 60 % compréhension)

## Environnement

- Flutter 3.x stable (≥ 3.27 ; ≥ 3.29 pour le Gradle Kotlin du TP10), Dart 3
- VS Code ou Android Studio, émulateur Android ou Chrome
- Packages utilisés : `provider` (TP7+), `http` (TP8+), `mocktail` (TP9, dev), `flutter_launcher_icons` (TP10, dev)
- Node.js pour `json-server@0.17.4` (TP8+)

## Utilisation de l'IA

Les étudiants peuvent utiliser une IA. Chaque TP est conçu pour que la **compréhension** soit indispensable et vérifiable (Partie C, oral individuel, quiz) ; tout usage doit être déclaré dans le **journal IA**.
