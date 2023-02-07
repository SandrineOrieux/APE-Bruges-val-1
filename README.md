Site  "association des parents d'élèves de Bruges-Capbis-Mifaget" (APE Bruges)

  *GESTION DES BRANCHES :*

Branche principale : main contient site stable.
Branche secondaire : 1 branche par fonction ou techno.

# Convention nommage des branches : 
- 1er lettre maj.
- nom en anglais.
- si plusieurs mots  : Word-word.

Exemple :

    *--*--*--------*--------*------*------ main
        \                    \
         *--Style             *---New-page   ....

ex de branche : Style-home, New-page, hover...

  *GESTION DES COMMITS :*

Le workflow se fait avec Jira celon la méthode Agile/Kanban.

- Pour chaques tâches terminées sur Jira commit obligatoire.
- Commit régulier intermédiaire pour les sous-tâches et sauvegarder régulièrement le travail.

# Convention nommage des commits :

Préfixes :
I- pour initialisation (commit avec fichier vierge pour reset si besoin)
F- pour modification/ajout de fonction/contenue site
D- pour modification/ajout de documentation
B- corection de bug

-n°ticket Jira :
-§{n°}-

*Si un seul fichier modifié on met le -nom du fichier-

-Commentaires simple explicite.

Exemples :

"I-§1-README.md" -> Initialisation du fichier README.md
"D-§2-README.md-Description of Branch management" -> Modification de la section gestion des branches du fichier README.md
"B-§10-Style ignore on main" -> Correction d'un bug de style sur plusieurs fichiers




