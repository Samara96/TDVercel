
3/ npm i -g vercel
4/ vercel -v
5/ vercel init
6/ cd angular
	vercel
7/ vercel list
8/ vercel logs samara-pppjbyb14.vercel.app
9/ vercel inspect <id> vercel inspect samara-pppjbyb14.vercel.app 
	Sert à afficher des informations relatives à un déploiement.
10/ les variables d'environnement: Permet de gèrer les variables d'environnement de notre projet actuel
    Ces sont accessibles à la fois pendant l' étape de construction et pendant l' exécution. Elles permettent d'injecter des valeurs que nous ne souhaitons 
    pas placer directement dans notre code source et de modifier son comportement en fonction de l'environnement dans lequel il s'exécute.
11/ vercel env add plain
	var1
	 test
	  Production
12/ vercel env list
	 var1    test     Production          49s ago
13/ Si on souhaite partager une information dans des variables d'environnement sur plusieurs projets au sein du même compte personnel ou de la même équipe sur Vercel,
    les secrets sont le meilleur moyen d'y parvenir. 
    Les commandes secrets permettent de gérer les secrets utilisés dans les variables d'environnement sous un compte, fournissant des fonctionnalités pour répertorier, 
    ajouter, renommer et supprimer des secrets.
15/ vercel secret add var2 test
16/ Les trois environnements que met automatiquement Vercel à notre disposition pour un meme projet sont:
	Production, preview et developement
17/ Pour un projet, on trouve plusieurs environnement. En effet, pour un même projet, on doit trouver la production pour le projet qui est déja en cours de production 
    peut être considéré comme un environnement en temps réel dans lequel les programmes sont exécutés et les configurations matérielles sont installées et utilisées pour
    l'organisation ou les opérations commerciales quotidiennes,
    preview pour la phase du test et developement pour la phase de conception et de dévelopement.

19/ Un pull request permet de proposer du code à l'administrateur du projet git afin qu'il puissent autoriser ou non les modifications et les merge sur la branche cible.
 Souvent des tests sont lancés avant de merge les deux branches. Un pullRequest est tout simplement une demande de relecture de code par un pair développeur avant le merge d'une branche sur une autre.
