Pour compiler les fichiers de la probl�matique dans Geany:

  - Ouvrir le menu d�roulant de "Construire" et choisir "D�finir les commandes de construction". Ceci ouvre un dialogue.

  - Dans ce dialogue, changer l'instruction associ�e � "Construire" ("Build", en anglais) pour la suivante:
    gcc -Wall -o gestion_images gestion_images.c bibliotheque_images.c

Le fichier ex�cutable qui est g�n�r� se nomme "gestion_images.exe" 
