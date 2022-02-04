# Java-RMI
Mise en oeuvre du service Calculator en utilisant Java RMI 


Apres avoir sauvegarder tous les codes dans un meme fichier, j'ai lancé en premier la commande "rmiregistry" sur ma ligne de commande.
Tant que le registry est entrain de tourner, j'ai ouvert 2 autres lignes de commandes ou j'ai executé:

1- java CalculatorServer qui va charger l'implementation et attendre la connexion du client; de plus elle appelle la classe CalculatorImpl.java qui hérite de
UnicastRemoteObject pour s'attacher au RMI ainsi que le Naming.

2- java CalculatorClient qui va executé le code et afficher la sortie voulue en faisant un lookup sur RMI.

![image](https://user-images.githubusercontent.com/91898869/152387836-c2210428-bf3f-47a5-9de2-59ff2f3e7fb5.png)
