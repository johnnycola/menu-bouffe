# Menu Bouffe

App Mac qui prépare les soupers de la semaine avec ce qui est en spécial dans les circulaires
(Metro, Val-Mont, IGA…), et qui apprend tes goûts.

## Installer

1. Télécharge **[Menu-Bouffe-mac.zip](https://github.com/johnnycola/menu-bouffe/releases/latest/download/Menu-Bouffe-mac.zip)** et ouvre-le.
2. Glisse **Menu Bouffe** dans le dossier **Applications**.
3. La première fois : **clic droit sur l'app → Ouvrir → Ouvrir** (macOS ne connaît pas le développeur).

Pour mettre à jour : même chose, en remplaçant l'ancienne app. Tes goûts et réglages sont gardés.
L'app t'avertit elle-même quand une nouvelle version est disponible.

## Contenu de ce dépôt

- `version.json` : dernière version de l'app et date de la base de recettes.
- `index/*.json.gz` : la base de recettes (nom, ingrédients, temps, lien vers le site d'origine).
  Pas d'étapes ni de descriptions : pour cuisiner, l'app renvoie vers la recette sur le site
  (Ricardo, Metro, 5 ingredients 15 minutes, Trois fois par jour).

Les apps installées lisent ces fichiers une fois par jour pour se tenir à jour.
