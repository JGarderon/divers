

# Que souhaitons-nous ?

Ce questionnaire est là pour nous permettre de mieux vous connaître. Toutes les réponses que nous indiquons ici peuvent être bonnes (ou presque !) : mais toutes doivent être justifiées. 

--- 

### Métier de développeur 

Êtes-vous sûr que vous pourriez y arriver seul ? 

	Q. Quelle est votre position sur la documentation technique ? 

		R. Avec parcimonie, car cela alourdit le code 

			S-Q. Comment jugez de la difficulté d'un algorythme, d'un module ou d'une fonction ? 

				R = 2p. En débattant ensemble et en se mettant au niveau du plus faible 
				R = 1p. En étudiant quelle partie a été la plus buggée et celle plus complexe à appréhender 
				R = 0p. Laisser cela au jugement de chacun, en fonction de la situation 

		R. Aussi souvent que possible, car cela facilite l'accès à un nouveau arrivé dans le projet 

			S-Q. Pour vous un nouvel entrant aurait quel principal défaut : 

				R = 2p. Il doit être accompagné et faire ses preuves sans excés de défis   
				R = 2p. Il a un regard neuf sur ce qui est fait bien qu'il doit éviter tout jugement
				R = 0p. Il désorganise le travail en cours 

		R. Une documentation technique ne devrait jamais figurer dans le code 

			S-Q. Pour écrire de la documentation, que outil vous semble le plus adapté ? 

				R = 2p. Un outil collaboratif type Wiki 
				R = 1p. Un document de référence partagé librement mais éditable seulement par une poignée de responsable 
				R = 0p. Un résumé des commentaires de commit  

	Q. Dans les réponses suivantes, laquelle vous semble la plus pertinente pour justifier l'adoption du WASM ? 

		R. Il est en cours d'adoption par les grands éditeurs de logiciel 

			Q. Pour vous, la différence entre 'standards' et 'normes' en informatique : 

				R = 2p. Est une réalité qui s'applique constamment, par méconnaissance du sujet
				R = 1p. Existe sur quelques sujets, suivant le rôle institutionnel et du poids économique des acteurs
				R = 0p. Cela n'existe pas et c'est un piège courant.  

		R. Il contourne des limitations conceptuelles et techniques de Javascript 

			S-Q. Aujourd'hui le rôle de Javascript sur un navigateur Web et seulement là... 

				R = 2p. Est le poids de l'histoire mais surtout du comportement des éditeurs de logiciel 
				R = 1p. Vient par la quantité de ressources de code disponibles comme de l'habitude  
				R = 0p. Est normal compte tenu de son exceptionnelle efficacité 

		R. Il déporte des traitements habituellement côté serveur vers le client 

			S-Q. Selon vous, peut-on faire une base de données persistente sur un navigateur client lourd ? 

				R = 2p. Possible avec LocalStorage mais risquée car le navigateur ne prévient pas l'effacement des données  
				R = 1p. Souhaitable avec les API existentes, surtout si l'on a des ressources lourdes à gérer 
				R = 0p. La persitence réelle sur plus qu'une session n'est pas possible sur un navigateur 

	Q.  Pour vous l'architecture logicielle doit-elle prioritairement : 

		R. Répondre à un besoin de scalabilité, "commencer petit et finir grand" 

			S-Q. Doit-on privilégier des langages facilitant la scalabilité, comme Erlang par exemple ? 

				R = 2p. Oui parfois, si et seulement si l'on a des compétences de suivi en interne  
				R = 0p. Non jamais, ce n'est qu'une question d'approche 
				R = 0p. Difficile de juger, ça dépend du contexte, il n'y a pas de bonne réponse 

		R. Être maintenable dans le temps et ouvert à d'autres applicatifs  

			S-Q. En règle général, quel est le poids de la maintenance d'un applicatif vis-à-vis de son développement ? 

				R = 2p. La maintenance en premier : elle dure longtemps et l'effort croît avec le temps 
				R = 1p. A égalité si l'applicatif est bien conçu, car l'effort de maintenance est mineur 
				R = 0p. Dans la réalité le développement représente la quasi-totalité de l'effort applicatif  

		R. Être pensée comme un outil en réponse à besoin métier 

			S-Q. Qui définir le mieux un besoin métier ? 

				R = 2p. Le client final, c'est-à-dire celui qui utilisera effectivement l'outil 
				R = 1p. L'entreprise qui reçoit l'applicatif, pour ses besoins internes 
				R = 0p. Le chef de projet car c'est sa responsabilité de le définir 

--- 

### Métier de mainteneur 

Pas le plus facile, souvent ingrat mais essentiel. 

	Q. La sécurité informatique c'est pour vous ? 

		R. Un mal nécessaire 

			S-Q. Pour vous cette notion de "sécurité" c'est d'abord : 

				R = 2p. Une logique plus globale qui comprend aussi sûreté et confidentialité 
				R = 1p. Se protèger d'actions néfastes d'un agent mal intentionné 
				R = 0p. Quelque chose qui n'a d'intérêt économique que sur des services ouverts à l'extérieur 

		R. Une approche métier 

			S-Q. La sécurité est d'abord l'affaire : 

				R = 2p. Une question globale, qui se traite à différents niveaux et implique tout le monde 
				R = 1p. Du RSSI de l'organisation faisant usage de l'applicatif, qui définit des règles 
				R = 0p. D'un comportement individuel d'où le besoin de formation et d'accompagnement 

		R. Une conception des outils 

			S-Q. Le Secure By Design doit-il être : 

				R = 2p. La stratégie du développement au sein de l'entreprise 
				R = 1p. Un impératif dans le cahier des charges 
				R = 1p. Une déclaration dans l'expression des besoins 

	Q. L'efficacité d'un serveur dépend prioritairement de quel aspect ? 

		R. D'un équilibre dans la configuration de la machine 

			S-Q. Comment définit-on cet équilibre ? 

				R = 2p. Sur la base de tests qualibrés avec les retours chiffrés 
				R = 1p. Sur les exigences applicatives en prenant une marge 
				R = 0p. Sur les ratios standards entre RAM, réseau et CPU 

		R. Des usages logiciels (nombre, qualité, mises à jour) 

			S-Q. Comment mesure t-on l'efficacité d'un applicatif ? 

				R = 2p. Par un indicateur composite qui aura été convenu par le cahier des charges 
				R = 1p. Par l'évolution du débit de traitement unitaire par seconde dans le temps 
				R = 1p. Par la satisfaction du client final avant tout 

		R. De la durée de traitement et du nombre possible de demandes simultanées 

			S-Q. Pour vous une SLA doit-elle comprendre en priorité : 

				R = 2p. Taux de disponibilité, durée d'indisponibilité, Description du service 
				R = 1p. Délai de réponse, des interlocuteurs et des délais de remise en service 
				R = 0p. Bonnes pratiques à l'usage du client, clause de non-responsabilité et taux de disponibilité 

	Q. L'usage du concept de virtualisation est selon vous... 

		R. Adapté à la plupart des sujets 

			S-Q. Dans quel cas on évitera la virtualisation matérielle prioritairement selon vous ? 

				R = 2p. Des besoins d'une latence réduite (traitement audio, réseaux, etc.) 
				R = 2p. En cas de problématiques de sûreté ou de stabilité mal assurée 
				R = 0p. Pour du traitement de type Bash car la performance n'est pas au rendez-vous 

		R. Une approche vaste, indépassable, propre à l'informatique 

			S-Q. Dans quel cas on évitera la virtualisation applicative prioritairement selon vous ? 

				R = 2p. Sur un système d'exploitation non-mis à jour fréquemment ou mal configuré 
				R = 1p. Sur un système Windows client pour des questions de compatibilité 
				R = 1p. Il n'y a pas de limite pratique réelle à la virtualisation applicative 

		R. Une question d'outils et de situations 

			S-Q. Que pensez-vous de Docker vis-à-vis de LXD ? aura

				R = 2p. D'abord un logique industrielle qui accompagne le besoin d'orchestration de la virtualisation applicative 
				R = 1p. Une généralisation grand public et multiplateforme qui doit se distinguer pour faire évoluer le principe 
				R = 0p. Une nouvelle génération plus performante et qui remplace à un programme vieillissant

---

### Métier de "cheffeur" 

"Parce qu'un chef doit savoir cheffer" dit le dicton. 

	Q. Dans un projet, qui arbitre une problématique qui fait débat ? 

		R. Personne, le consensus doit exister à tout moment. 

			S-Q. Comment arrive t-on à un consensus dans une situation complexe ? 

				R = 1p. En faisant des compromis au détriment d'un des aspects du projet 
				R = 1p. En mettant avec respect, chacun devant sa responsabilité  
				R = 0p. En repoussant un problème dans l'attente d'avoir une solution applicable 

		R. Le chef de projet (CdP), qui est garant des intérêts du projet. 

			S-Q. Quelle phrase vous semble t-elle la plus juste ? 

				R = 1p. Le CdP doit pouvoir faire évoluer avec client le cahier des charges décidé antérieurement 
				R = 1p. Le CdP doit écouter l'équipe technique qui comprend les problèmes rencontrés  
				R = 0p. Le CdP justifie de sa décision qu'une fois qu'il l'a prise en autonomie 

		R. Tout dépend du sujet : parfois le client, parfois le développeur... 

			S-Q. Quelle situation vous semble la plus problématique dans un projet ? 

				R = 2p. L'absence de coordination ou d'écoute de chacun, qui crée des tensions dans l'équipe 
				R = 1p. Des changements importants dans le cahier des charges, sur des besoins métiers 
				R = 1p. Le retard, source de coûts pour l'entreprise, et de stress pour les équipes 

	Q. Existe t-il une vie après le projet ? 

		R. Oui et c'est le rôle de la maintenance 

			S-Q. Comment améliorer la situation de la maintenance ? 

				R = 2p. Avant le début du développement, en choisissant des outils et logiques pérennes 
				R = 1p. En facilitant la documentation durant tout le projet 
				R = 0p. Difficile de savoir car on ne peut pas prévoir l'avenir : c'est après le projet 

		R. Non car toute évolution est en soi un projet qui se pérennise sans réelle fin 

			S-Q. Quel est le principal risque d'un développement applicatif ? 

				R = 2p. Un applicatif qui fonctionne mal et génère des erreurs régulièrement 
				R = 1p. Un projet finalement abandonné en cours de route pour une somme de raison 
				R = 1p. Un client insatisfait parce que son expression du besoin a été mal étudié 

		R. Oui et non : tout dépend de la méthode de gestion de projet choisie 

			S-Q. Diriez-vous que le cycle en V sera remplacé dans toutes les situations par des méthodes agiles ? 

				R = 2p. Non car les méthodes agiles ont aussi leurs pièges et leurs limites 
				R = 1p. Le plus souvent ce sont des mixtes qui sont utilisés, il ne faut pas raisonner en absolu 
				R = 0p. Oui certainement, car c'est la tendance actuelle 

	Q. Comment voyez-vous le fonctionnement d'un projet dans une société d'édition de logiciel "sur-mesure" ? 

		R. Pas différemment de ce que pourrait faire une DSI au sein d'une entreprise 

			S-Q. Quelles sont les fondamentaux qui lient une société de service informatique à son client ? 

				R = 2p. Un relation de confiance, objectivée et objectivable, avec un but et contractualisé 
				R = 1p. D'abord un contrat légal où repose une somme de documents contractuels 
				R = 0p. Une relation de prestation comme pourrait l'être un fournisseur ou une société de service quelconque 

		R. Comme une méthode de gestion de l'entreprise, c'est-à-dire d'organisation d'une production 

			S-Q. Doit-il exister une seule méthode de projet au sein d'une société de service ? 

				R = 1p. La variété est une force et certains profils sont plus à l'aise avec telle ou telle méthode 
				R = 1p. La réalité veut qu'on s'adapte au client, qui décide donc de notre organisation in fine 
				R = 0p. Par cohérence, oui, au risque sinon d'avoir de (mauvaise) surprise 

		R. Il est difficile d'avoir une réponse unique : ça dépend de la société 

			S-Q. Comment mesurer l'efficacité d'un développeur ? 

				R = 2p. Travailler dans un groupe, en faisant remonter des éventuels problèmes de manière claire 
				R = 1p. Sa capacité à résoudre des problèmes en autonomie et de tester avec rigueur
				R = 0p. La quantité de code produit par jour (lignes / personne), ramené au nombre de bugs détectés sur une période données 

--- 

### Rapport à l'enterprise

L'idée est de fixer un trait de caractère plus dominant chez la personne. ] 

	Q. Pour vous, l'entreprise est : 
		
		R. un lieu de création de richesse collective 

			S-Q. Cette richesse collective passe par :

				R. une rentalité économique, donc salariale, grâce aux efforts de chacun			=> besognieux 
				R. une communauté de savoirs communs qui croîent 									=> idéaliste 
				R. des réseaux qui se créent pour d'autres opportunités 							=> opportuniste 

		R. un lieu d'épanouissement professionnel 

			S-Q. L'épanouissement professionnel doit être :

				R. mesurable et constant dans le temps 												=> comptable 
				R. comme un sentiment de bien⁻être 													=> troublé 
				R. l'apprentissage permanent 														=> perfectionniste

		R. un lieu d'équilibre avec sa vie personnelle 

			S-Q. Vous diriez que votre premier choix est : 

				R. d'avoir du temps pour soi et ses proches 										=> détaché
				R. l'entreprise comme un repère dans sa vie 										=> déséquilibré 
				R. de considérer votre emploi comme un revenu nécessaire							=> démotivé 


