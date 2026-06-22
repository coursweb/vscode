---
layout: page
title: Word Wrap
permalink: word-wrap.html
---

## Word Wrap

Par défaut, le "word wrap" (retour automatique à la ligne) n'est pas actif, les lignes longues peuvent donc dépasser la fenêtre visible.

Pour permettre à l'interface de faire des retours de ligne, il y a une commande : *Affichage > Retour automatique à la ligne* (raccourci: option+Z)

### Activer le Word Wrap de manière globale

Si on souhaite changer ce comportement de manière permanente, on existe un réglage utilisateur.

Dans *Préférences > Paramètres*, rechercher "Word Wrap", et mettre le réglage sur "on".

![Le réglage Word Wrap](images/editor-word-wrap.png)

Cela correspond à cette ligne dans `settings.json`:

```
"editor.wordWrap": "on"
```

