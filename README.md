# Linux 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Linux - TP 1


* **Category:** category
* **Points:** points

## Exercice 1 : Premières commandes et raccourcis claviers
* **Question 1:** Tester chacune des commandes suivantes dans un terminal. Décrire en une phrase son utilité,
indiquer le nom de la commande et son nombre d’arguments.

  **date :**
Cette fonction retourne la date du systeme.

  **cal :**
Cette fonction affiche le calendrier selon l'argument. 

  **cal 3 2000 :**
Cette commande retourne le calendrier du mois Mars en 2000.

  **who :**
Cette commande donne des informations sur les utilisateurs qui sont actuellement connectes.

  **whoami :**
Cette commande retourne l'utilisateur qu'on utilise actuellement.

  **echo hello world! :**
Cette commande affiche le text "hello world!".

* **Question 2 :** Appuyer sur la flèche du haut ou taper C-p (la touche Ctrl en même temps que la touche plusieurs fois, jusqu’à l’affichage de la commande date. Maintenant appuyer sur la flèche du bas ou taper C-n jusqu’à afficher la commande who puis taper sur entrée. Noter à quoi servent ces raccourcis et les apprendre.

Ces raccourcis peuvent etre utilise pour afficher les commandes qu'on a executer precedament et naviguer l'historique des commandes.

* **Question 3 :**  Appuyer sur C-l. Noter à quoi sert ce raccourci et l’apprendre.

Cette commande a le meme fonctionnement du CLEAR, qui efface le contenu du terminal.

* **Question 5 :**  Taper C-u, noter à quoi sert ce raccourci et l’apprendre.

Cette commande efface tous apartir du position du curseur jusqu'a la debut du ligne. C'est efficace quand on l'utilise si on a fait un faute dans la commande.


* **Question 6 :**  Faire apparaître de nouveau, toujours sans la taper ni l’exécuter, la commande cal. Puis
taper C-d. Que s’est-il passé ?

Cette commande fait un " Sign Out " du terminal. Ceci est efficace si on utilise sudo et on veur retourner vers l'utilisateur initiale.

* **Question 7 :**  Faire apparaître de nouveau, toujours sans la taper ni l’exécuter, la commande cal. Puis taper C-d. Que s’est-il passé ?

Ceci ferme le terminal can on envoie un SIGINT que le BASH interprete comme une demande de quitter le programme

* **Question 8 :**  Rouvrir un terminal et taper C-p plusieurs fois. Commenter.

On ne trouve rien comme historique de commande.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Exercice 1 : Premières commandes et raccourcis claviers

* **Question 1:**  Entrer la commande pwd (pour « print working directory », c’est-à-dire, afficher le nom du répertoire courant) et noter ce qui est imprimé à l’écran  * c’est le chemin absolu de votre home, répertoire personnel.

![pwd](https://user-images.githubusercontent.com/91763346/194708843-ab584a03-e862-4bea-8e90-51cde88b3390.PNG)

* **Question 2:**  Entrer successivement les commandes cd .. (avec un espace entre cd et ..) et pwd, jusqu’à
ce que le résultat ne change plus. Commenter

![image](https://user-images.githubusercontent.com/91763346/194709167-3ada093d-7975-4e4f-8d5d-ffe1a0cfd853.png)

* **Question 3:**   Entrer la commande cd (sans argument), puis pwd. Commenter.

![image](https://user-images.githubusercontent.com/91763346/194709302-8af2386d-055f-4bc2-a047-00718a071f76.png)

* **Question 4:**   Entrer la commande cd /, puis pwd

![image](https://user-images.githubusercontent.com/91763346/194709167-3ada093d-7975-4e4f-8d5d-ffe1a0cfd853.png)

* **Question 5:**   Entrer la commande cd /usr/include. Utiliser la commande ls. À quoi semble servir ce
répertoire ?

![image](https://user-images.githubusercontent.com/91763346/194709398-d83215d6-d15f-43e3-8faf-a553a6936df0.png)

* **Question 6:**    La commande wc (pour « word count ») affiche
(dans cet ordre) le nombre de lignes, de mots et de caractères des fichiers donnés en argument, puis, s’il y en a plusieurs, les sommes de ces nombres pour tous les fichiers. Afficher le contenu le nombre de lignes du fichier stdlib.h. Donner le nombre total de lignes des fichiers stdlib.h et stdio.h.

![image](https://user-images.githubusercontent.com/91763346/194709470-e3e13f4c-7a17-42f6-afb1-38b651dfecae.png)

* **Question 7:**   Entrer les commandes cd .., pwd puis ls.

Cette question est comme la question 

* **Question 8:**    Entrer les commande cd share/man, puis pwd et ls. Pouvez-vous deviner ce que désignent
certains des résultats affichés ?

Ce sont les manuels qu'on utlise avec la commande " man "

![image](https://user-images.githubusercontent.com/91763346/194709571-9dc28bb1-8606-432b-9a51-bda1eb516b97.png)

* **Question 9:**    Entrer les commande cd share/man, puis pwd et ls. Pouvez-vous deviner ce que désignent
certains des résultats affichés ?

Ce sont les commandes comme ls, cat, echo, gcc etc...

![image](https://user-images.githubusercontent.com/91763346/194709688-f2277eee-6044-447b-92db-3c2c21e7cb64.png)

* **Question 10:**   Le caractère ∼ (qui se lit « tilde ») est saisi au clavier avec la combinaison de touches Alt
Gr-2. Entrer la commande echo ∼, puis la commande cd ∼. Qu’a fait le shell au caractère ∼ ?

![image](https://user-images.githubusercontent.com/91763346/194710018-a9817e4e-de0b-4783-a177-217259d2db54.png)

> The text of 
> the challenge.
## Solution

The solution.

```
The flag.
```
