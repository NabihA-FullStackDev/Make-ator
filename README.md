# Make-ator

Description:

Make-ator est un "petit" script de creation de Makefile, c'est egalement mon premier script.
N'hesitez a faire des feedbacks :)

Installation:

Telecharger le script et lancer le.

Version:

Il y a deux versions:

- Une avec des 'echo -e' qui permettent de prendre en compte les \t et autre.
- L'autre sans les '-e'

Tout dependra du terminal que vous utilisez. Dans le doute, essayez les deux.

Le script vous demandera:
- Le nom de votre programme
- Le chemin vers les fichiers sources
- S'il y a plusieurs dossiers vous aurez la possibilite de le lui dire
- De meme pour les chemins des fichiers headers

- Pour la librairie, pensez a ne donner que le nom, Exemple: libft.a -> ft
- Le script considere que votre lib a un Makefile pour la preparer et tentera de l'integrer de cette maniere.
- Enfin, il prendra le chemin vers les headers de votre lib

Les chemin mis dans le Makefile son ABSOLUE, pensez a les modifier en cas de besoin :)
