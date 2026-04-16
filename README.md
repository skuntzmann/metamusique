# 🎵 MétaMusique / NOTA

MétaMusique est un **méta-moteur de recherche musical** permettant de trouver rapidement, en un seul endroit :

- des partitions musicales
- des accords et tablatures
- des paroles
- des aperçus visuels de partitions
- des outils de conversion vers MusicXML

https://skuntzmann.github.io/metamusique/

---

## Fonctionnement

L’utilisateur saisit le titre d’une œuvre ou d’une chanson.

Le moteur génère automatiquement des liens vers des sources fiables en ligne, organisées par type de contenu :

### Partitions
- IMSLP (domaine public)
- MuseScore
- Free-scores
- 8notes

### Accords / Tablatures
- Ultimate Guitar
- GuitareTab
- Chordify
- La Boîte à Chansons

### Paroles
- Genius
- Paroles.net
- Lyrics.com
- LyricsTranslate

### Aperçu visuel
- Google Images (partitions)

---

## Logique intelligente

L’application adapte automatiquement les résultats :

- 🎼 **Œuvres classiques** → priorité aux partitions (IMSLP, etc.)
- 🎵 **Chansons** → priorité aux accords + paroles

---

## 🔄 Conversion MusicXML

MétaMusique ne convertit pas directement les fichiers, mais propose des outils externes :

- https://scoretxt.com  
- https://audiveris.github.io  

Workflow recommandé :
1. Trouver une partition (PDF ou image)
2. L’ouvrir
3. L’importer dans un outil de conversion
4. Récupérer le fichier MusicXML

---

## Fonctionnalités

- Historique des recherches (localStorage)
- Interface minimaliste et responsive
- Aucune dépendance externe
- Aucune API requise
- Fonctionne entièrement en front-end

---

## Légalité

MétaMusique est un **méta-moteur de liens** :

- ❌ Aucun contenu hébergé
- ❌ Aucun contournement de droits
- ✅ Accès uniquement à des ressources publiques existantes

---

## Architecture

- HTML / CSS / JavaScript pur
- Hébergement : GitHub Pages
- Aucune base de données
- Aucune exécution serveur

---

## Objectif

Créer un **hub musical simple, rapide et universel** pour :

- musiciens
- enseignants
- étudiants
- amateurs

---

## Évolutions possibles

- Mode sombre
- Multilingue (FR / EN)
- Meilleur filtrage des résultats
- Pondération des sources
- Détection plus fine des œuvres

---

## À propos du nom

À ne pas confondre avec le projet québécois :contentReference[oaicite:0]{index=0}, qui est un outil de gestion de métadonnées destiné à l'industrie musicale :contentReference[oaicite:1]{index=1}.

Ce projet est indépendant et a un objectif différent : la recherche de ressources musicales.

---

## Licence

Ce projet est distribué sous licence MIT.
