# Activité 1 : modification d'une image en Python


Nous allons jouer avec les pixels de l'image ci-dessous.

![](data/fleur.jpg){: .center}

## 1. Ouverture de l'activité Capytale.

1. Connectez-vous à [Monlycée.net](https://ent.iledefrance.fr/auth/login?callback=https%3A%2F%2Fent.iledefrance.fr%2F#/){. target="_blank"}.
2. Cliquez ensuite sur [ce lien](https://capytale2.ac-paris.fr/web/c/5a45-2677237). 


Vous êtes alors renvoyés vers le service Capytale, qui permet le partage d'activités Python.

## 2. Modification des couleurs de l'image ```fleur.jpg```.

!!! abstract "Principe"
    - On parcourt l'image pixel par pixel. Pour chaque pixel :
    - On récupère ses composantes RGB dans des variables ```r```, ```g```, et ```b```.
    - On crée 3 nouvelles variables   ```new_r```, ```new_g```, et ```new_b``` et on teste des permutations avec les composantes initiales  ```r```, ```g```, et ```b```.
    - On modifie le pixel actuel avec ces nouvelles composantes ```new_r```, ```new_g```, et ```new_b```.

*Remarque : pour les pixels blanc (255, 255, 255), les permutations n'ont aucun effet !*  

## 3. Autres filtres

Manipulations à réaliser sur le notebook.  

### Si on souhaite travailler avec sa propre image :


![image](data/methode.png){: .center }


Cliquer sur Capytale / Fichiers annexes / Disponibles le temps de la session / Ajouter un fichier disponible le temps de la session.
