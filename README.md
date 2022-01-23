# Tp_DevOps
# Bastien Corré et Laura Bojon
## Namespaces 
* DEV, namespace dans lequel les développements se font. Seul le développeur est autoriser à regarder ce qu'il y a dans l'environnement dev.
* PROD, version finale de l'application, du site ou du logiciel. Le client est autorisé ainsi que le développeur à regarder les fichiers de prod.
* Nous aurions, pour plus de réalisme pu rajouter deux namespaces, à savoir RECETTE (REC) et PRÉPROD (PREP), ce sont deux filtres de développement pour tester le comportement des développements réalisés et vérifier si tout se comporte comme prévu. Le projet ne nécessitait pas un filtre si grand pour vérifier le comportement.
*** 
## Comportement de l'application
L'application fonctionne avec un sytème de localhost. L'image hello-world ainsi que celle de devops303 sont bindées sur le port 80 de la machine sur laquelle elles sont lancées. Il s'agit de ressources kubernetees. Nous pouvons aussi démarrer les images avec le chemin 'hello-world.laura' et 'devops-303.laura'
