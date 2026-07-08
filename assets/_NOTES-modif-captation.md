# Fiche « Captation de la donnée » — modifications à appliquer

Statut : EN ATTENTE (moteur d'exécution de code indisponible lors de la session du 2026-07-07).
À reprendre dans une nouvelle conversation (le sandbox redémarre alors).

## Fichier source
`08_Fiches/ideeri-fiche-captation-donnee.html` (master à éditer, puis régénérer PDF + embed via WeasyPrint).

## Logos disponibles (vectoriels, prêts à intégrer)
- `assets/logo-ideeri.svg` — cercle blanc + swoosh jaune #EBBB00 + point vert #21341C
- `assets/logo-compagnon.svg` — « C » vert #2C8B57 sur fond transparent

## Les 3 modifications de cards (validées par Manon)
1. Card « app client » → titre **« App client Ideeri »** + logo Ideeri
2. Card « terrain compagnon mobile » → **« App professionnelle Compagnon »** (pour le terrain) + logo Compagnon
3. Card « messagerie emails centralisée » → **« Messagerie professionnelle »**
   avec sous-texte : *« échanges directs entre pro et particuliers »*

## Rappels techniques (charte poster Ideeri)
- Jaune #EBBC02 / Noir #1A1A1A / Papier #FAFAF7 / Vert #21341C
- Régénération : `HTML(src).write_pdf(dst)` (WeasyPrint) → PDF A4, puis builder d'embed (<200KiB, Google Fonts, #wrap + fit JS)
- Copier livrables dans `/mnt/outputs/`
- Notion « Fiches features » : section 2 déjà présente (Captation de la donnée) — seul le PDF sera à redéposer manuellement par Manon.
- Intégration logo dans une card : insérer le `<svg>` inline (ou `<img>` sur le SVG) dans la vignette de la card, à la place / au-dessus de l'icône existante, en respectant la taille des autres pictos.
