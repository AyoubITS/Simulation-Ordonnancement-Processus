# Simulation-Ordonnancement-Processus

Objectifs 

Le but de travail est d’implémenter un logiciel de simulation d’ordonnancement des processus dans un système d’exploitation. Ce guide permet de guider un utilisateur à pouvoir exécuter et lancer le simulateur facilement.

Choix techniques

•Langage utilisé : C
•Environnement de travail : Visual Studio Code
•Environnement de compilation : gcc 

Exécution du programme

L’exécution se faire en ligne de commande, il faut préalablement disposer du compilateur du langage et se rendre se trouvant le fichier main.c.
Avant d’exécuter ce programme, il faut préalablement compiler le fichier par la commande:

>>make

Et ensuite pour lancer ce programme, il faut taper l’une de deux commandessuivantes en fonction des données à fournir :
Soit :

>>./main

Pour une insertion de données à travers la console.
Ou soit :

>>./main ‘nomfichier’

Si les données sont renseignées dans le fichier ‘nomfichier.txt’ et disponible dansle même répertoire.

Conclusion

Ce projet permet d’implémenter un logiciel de simulation d’ordonnancement de processus dans un système d’exploitation.
Les algorithmes utilisés dans le cadre de ce projet sont les suivants : FIFO, SJR et RR.
