# Boîte à outils pédagogiques

Des outils pour composer des fiches pédagogiques personnalisées à partir de textes, d'images et de réglages adaptés aux activités de la classe.

**Classe des petits loups · Florence Zeghache**

## Démarrage rapide

1. Télécharger le dépôt avec **Code > Download ZIP**, puis extraire l'archive.
2. Ouvrir [index.html](index.html) dans un navigateur récent, de préférence Chrome ou Edge pour la sélection des dossiers d'images.
3. Choisir une activité et personnaliser ses réglages.
4. Importer les images ou les polices demandées par l'outil, si nécessaire.
5. Prévisualiser la fiche, puis l'imprimer ou l'enregistrer en PDF depuis la boîte d'impression du navigateur.

Aucune installation ni commande de compilation n'est nécessaire. Conserver les fichiers et les dossiers de ressources ensemble pour préserver les liens.

## Activités disponibles

| Activité | Objectif |
| --- | --- |
| [Compter et entourer](compter_entourer.html) | Compter les éléments et entourer la bonne réponse. |
| [Reconnaissance des lettres](reconnaissance_lettres.html) | Repérer des lettres parmi des chiffres et des symboles. |
| [Lettres du prénom](lettres_prenom.html) | Reconnaître l'initiale et les lettres d'un prénom. |
| [Numération doigts et chiffres](numeration_des_doigts_chiffres.html) | Associer différentes représentations des nombres. |
| [Compléter une collection](completer_collection.html) | Compléter une quantité pour atteindre le nombre demandé. |
| [Entourer le nombre ou la lettre](entourer_nombre_lettre.html) | Retrouver un nombre ou une lettre dans une liste. |
| [Gabarit vierge : une image](gabarit_vierge_1image.html) | Composer une fiche avec une image et une consigne. |
| [Gabarit vierge : deux images](gabarit_vierge_2images.html) | Disposer deux images côte à côte ou l'une au-dessus de l'autre. |
| [Légendes à découper](fiche_legendes.html) | Compléter une illustration avec jusqu'à huit légendes. |
| [Légendes à découper : version haut/bas](fiche_legendes_v2.html) | Disposer jusqu'à six légendes au-dessus et en dessous d'une image. |
| [Lexique du thème](lexique_du_theme.html) | Créer une grille de photos accompagnées de mots en capitales. |
| [Fiches Wooden Man](wooden_man.html) | Composer des silhouettes articulées sur quadrillage. |

Les liens ci-dessus pointent vers le code des pages sur GitHub. Pour utiliser les outils, ouvrir la copie téléchargée ou le site publié avec GitHub Pages.

## Lexique du thème

Le lexique reprend une présentation A4 avec un titre, un bandeau de thème et une grille de cases carrées.

1. Renseigner le thème et personnaliser le titre ou la couleur du bandeau.
2. Cliquer sur **Choisir un dossier** pour afficher les miniatures des images.
3. Cocher les photos souhaitées, avec les commandes de sélection globale si besoin.
4. Cliquer sur **Insérer** pour appliquer la sélection à la fiche. Une nouvelle insertion remplace les photos précédentes sans les cumuler.
5. Ajuster les lignes, les colonnes et la taille des mots avec les curseurs.
6. Cliquer sur **Imprimer / Enregistrer en PDF**.

La grille comporte **6 lignes et 6 colonnes par défaut** et occupe la largeur utile de la page. Le texte sous chaque photo correspond au nom du fichier, sans son extension, en **MAJUSCULES**. Renommer les fichiers avant l'import pour obtenir les mots souhaités.

Les mots longs sont réduits au besoin pour rester dans leur case. Si les photos sont trop nombreuses ou si la grille dépasse la hauteur A4, un avertissement demande d'ajuster la sélection ou la grille. La grille n'est pas automatiquement réduite ni répartie sur plusieurs pages.

## Impression

- Sélectionner le format **A4 portrait** pour le lexique.
- Désactiver les en-têtes et pieds de page ajoutés par le navigateur.
- Vérifier l'aperçu et les marges avant de lancer l'impression.
- Activer l'impression des arrière-plans si nécessaire pour conserver les couleurs.
- Choisir **Enregistrer au format PDF** comme destination pour produire un fichier PDF.

Les réglages et formats peuvent varier selon l'activité.

## Ressources

- [themes/](themes/) : images organisées par thème pédagogique.
- [icones/](icones/) : ressources graphiques.
- [prenoms_classe.txt](prenoms_classe.txt) : fichier de prénoms de la classe, à adapter à son usage.

Les pages utilisent HTML, CSS et JavaScript. Certaines activités demandent de sélectionner des ressources locales, notamment des images ou des polices.

## Publication avec GitHub Pages

1. Ajouter les fichiers du projet au dépôt GitHub en conservant leur organisation.
2. Ouvrir **Settings > Pages** dans le dépôt.
3. Dans **Build and deployment**, choisir **Deploy from a branch**.
4. Choisir la branche contenant le projet et le dossier **/(root)**, puis enregistrer.
5. Une fois le déploiement terminé, ouvrir l'adresse affichée par GitHub Pages.

La page [index.html](index.html) sert de point d'entrée au site. Aucun serveur applicatif n'est requis.

## Avant de partager

Vérifier que les fichiers publiés ne contiennent pas de données personnelles d'élèves, notamment dans le fichier de prénoms, les photos ou les documents joints. Un site GitHub Pages peut être accessible publiquement.

Vérifier également les droits d'utilisation et de redistribution des images, icônes, polices et documents avant de les publier. Leur présence dans ce dépôt ne constitue pas une autorisation de réutilisation.