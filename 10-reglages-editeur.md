---
layout: page
title: Réglages éditeur
permalink: reglages-editeur.html
---

Réglages utilisateur vs. réglages du workspace.

#### Réglages Utilisateur (`settings.json` global)

- S'appliquent à **toutes tes instances VS Code**, quel que soit le projet ouvert
- Stockés dans ton profil système (`~/Library/Application Support/Code/User/` sur macOS)
- Idéal pour tes préférences personnelles : fonte, thème, raccourcis, comportement général

#### Réglages Espace de travail (`.vscode/settings.json` à la racine du projet)

- S'appliquent **uniquement au projet courant**
- Stockés dans le dossier du projet, donc **versionnables avec Git**
- Écrasent les réglages Utilisateur en cas de conflit
- Idéal pour les conventions d'équipe : *indentation, formateur de code, linter*


## Word Wrap

"editor.wordWrap": "on"

## Désactiver les références à MDN

Par défaut, dans un fichier HTML, VSCode affiche des informations au survol d'un élément. Ces fenêtres modales peuvent être désactivées. 

Le réglage se trouve dans le profil utilisateur, on peut le trouver en cherchant avec le mot clé «Hover».

Les réglages en code:

```
"html.hover.references": false,
    "less.hover.references": false,
    "html.hover.documentation": false,
    "less.hover.documentation": false,
```

## Désactiver l'IA

Sous Conversation > Divers : Disable AI Features

Correspond au code suivant:
```
"chat.disableAIFeatures": true,
```