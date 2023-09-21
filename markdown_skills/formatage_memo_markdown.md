# Memo du formatage markdown
=============================

**En-têtes** : utilisez le signe dièse (#) suivi d'un espace vide pour les titres et les en-têtes de section de bloc-notes :

# pour le titre
## pour les principaux en-têtes
### pour les sous-titres
#### pour les sous-titres de 4ème niveau

**Mise en évidence** : utilisez ce code : Gras : __string__ ou ``` **string** ```, Italique : _string_ ou *string*, Barré : ~~string~~

**Symboles mathématiques** : utilisez ce code : $ mathematical symbols $

**Police à espacement fixe** : texte encadré avec un guillemet simple inversé (`). Utilisez l'espacement fixe pour les chemins d'accès aux fichiers et les noms de fichier et pour le texte que les utilisateurs saisissent ou le texte de message que les utilisateurs visualisent.

**Retours à la ligne** : il arrive parfois que Markdown ne crée pas de retours à la ligne à l'endroit où vous le souhaitez. Placez deux espaces à la fin de la ligne ou utilisez ce code pour un retour à la ligne manuel : <br>

**Déclaration en retrait** : utilisez un signe supérieur à (> ), puis un espace, et tapez le texte. Le texte est en retrait et comporte une ligne horizontale grise sur sa gauche jusqu'au retour chariot suivant.

**Puces** : utilisez le tiret (- ) suivi d'un espace, ou un espace, un tiret et un espace ( - ) pour créer une puce circulaire. Pour créer une sous-puce, utilisez une tabulation suivie d'un tiret et d'un espace. Vous pouvez aussi utiliser un astérisque à la place d'un tiret.

**Listes numérotées** : tapez 1. puis un espace, puis votre texte. Le retour chariot et la numérotation sont automatiques. Commencez chaque ligne par un nombre et un point, puis un espace. Appuyez sur la touche de tabulation pour effectuer une mise en retrait et obtenir la sous-numérotation.

**Graphiques dans les blocs-notes** : faites glisser et déposez des images dans la cellule Markdown pour la joindre au bloc-notes. Pour ajouter des images à d'autres types de cellule, utilisez des graphiques qui sont hébergés sur le Web avec ce code, en remplaçant url/nom par l'URL complète et le nom de l'image :<img src="url/filename.gif" alt="Alt text" title="Title text" />

**Formes géométriques** : utilisez ce code avec une valeur décimale ou un numéro de référence hexadécimal à partir d'ici : UTF-8 Geometric shapes &#reference_number;

**Lignes horizontales** : utilisez trois astérisques : ***

**Liens internes** : pour créer un lien vers une section avec le bloc-notes, utilisez ce code : [section title](#section-title) Pour le texte entre les parenthèses, remplacez les espaces et les caractères spéciaux par un trait d'union. Prenez soin de tester tous les liens.

Sinon, vous pouvez ajouter un ID pour une section juste au-dessus du titre de cette dernière. Utilisez ce code : <a id="section_ID"></a> Assurez-vous que la valeur de section_ID est unique dans le bloc-notes.