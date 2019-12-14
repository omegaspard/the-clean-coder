## Professinalism (Page 7)

Le professionalisme consiste à se tenir responsable de ce que l'on fait.

### First do not harm

*Do not harm to function*: développer des logiciels et des programmes introduits toujours de bugs.
Le développeur est responsable de ses bugs même si il y en aura toujours.
Le développeur doit être au courant de ses bugs et savoir s'excuser.
Le taux d'erreur doit tendre vers 0.

Tout code dont on est pas certain est un bug potentiel. Le code doit être compris dans son intégralité.
Si un bug est trouvé, s'excuser puis trouver comment il a échappé à la relecture du code.
QA = Quality assurance, correspond à la revue du produit.
Aucun bug ne doit être trouvé en QA.

Le développeur doit s'assurer que son code fonctionne et que le nouveau code n'ajoute pas d'erreurs dans la précédente strucuture du code.
Il doit pouvoir tester son développement facilement à plusieurs reprises.
Un code difficile à tester est un code mal conçu.
Concevoir les tests avant d'implémenter le code permet aussi de le tester facilement.
Toutes les lignes écrites par le développeur doivent être testées.

*Do not harm the strucuture*: Les projets en informatique grossissent vite.
Une des principales feature qu'apporte l'informatique est sa flexibilité.
Avoir un projet informatique qui n'est pas flexible c'est allé à l'encontre de l'informatique même.

Les patterns sont des règles à suivre pour avoir un projet ouvert à l'extension mais ne garantissent pas la flexibilité d'une strucuture.
Une strucuture flexible est une structure sur laquelle on fait des modifications facilements.
Si ce n'est pas le cas, alors on doit faire les modifications nécessaire pour que ça soit le cas lors de la prochaine itération.

Pour s'assurer qu'une structure reste flexible il faut en améliorer la qualité de manière constante, refactorer pour rendre le code plus confortable. Le réfactoration constante n'est pas dangereuse si toutes les feature du code sont entièrements testées.

### Work ethic

Le professionel doit se former constamment et répartir son temps de travail entre celui pour son employeur (40 heures) et celui pour sa carrère (20 heures).
Les 20 heures de travail personnel doivent servir à améliorer, concrétiser ses connaissances et faire grandir sa carrière.

Le professionel doit être à jour et connaitre l'actualité de ce qu'il utilise.
Quelles sont les technologies du marcher ? Que recherche les entreprises actuellement ?

Principes à connaitre de manière consistante:
- Design Pattern
- Design principles: SOLID, ACID etc...
- Methods: Agile
- Disciplines: TDD, OOP, CI/CD, Pair programming, documentation, scoping
- Artifacts: UML, decision tables etc...

Autres suggestions personnels :
- Algos
- Documentation
- Scoping

Un développeur doit apprendre constamment.

Un développeur doit pratiquer constamment. Coder pour son employeur est une performance pas un pratique. Pratiquer c'est se consentrer sur l'apprentissage et la progression.
Exemples :
- Faire des katas
- Collaborer sur des projets
- Apprendre à d'autres personnes

Un développeur doit connaitre son domaine, faire du code n'est pas suffisant. Les indsutries sont différentes et ces différences influent sur le produit que l'on réalise. Il faut en comprendre les principes et les valeurs.

Un développeur doit connaitre son employeur et ses clients. Il faut comprendre les problèmes du client et les solutions apportées par le produit de l'entreprise.

Un développeur doit être humble. Assumer ses erreurs, être fier de son travail et confiant.


## Saying No

Il faut savoir dire non de manière professionnel.
Lorsqu'on reçoit une demande impossible il ne faut pas éviter la confrontation, il faut dire non et arriver au meilleur point d'entente possible.

### What about the why

Les faits importent plus que le pourquoi. Lorsqu'on dit non, expliquer pourquoi peut aider le demandeur à comprendre mais il peut aussi pousser à remettre en cause
les étapes necessaires de la livraison. Expliquer le pourquoi peut encourager le micro management.

### High stakes

Plus l'enjeu est grand plus il est important de dire non.

### Trying

Demander d'essayer plus pour livrer des feature plus tôt implique que la personne effectuant cette demande estime que l'ingénieur garde des ressources.
Dans ce cas il faut dire non et se tenir au plan.

Note: Il est important de mettre sur écris les demandes et les engagements pour se protéger.

### Is it impossible to get good code ?

Question cachée: est-ce impossible d'être professionel dans le développement informatique.

Le développeur est responsable de ce qu'il accepte.
Le client n'a pas tord de demander ce pour quoi il est prêt a payer si le développeur
accepte la requète.
Le client est ignorant du cout technique.
C'est au développeur de dire ce qui est possible et ce qui n'est le pas.
Etre un héro codeur finira surement par un produit défectueux au prix de longue mauvaise heure de travail.


# Saying Yes

il faut savoir comment dire oui.

## A language of commitment

say, mean, do

annoncer ce qu'on va faire, le pensee vraiment, realiser

## Recognizing lack of commitment

Need/should

Hope/wish

Let's et ne s'inclue pas dans le reste de la phrase 

Un exemple de vrai commit est "I will do this by tuesday"

C'est un vrai engagement fait devant une ou plusieurs autres personnes. Il doit etre reflechi et faisable. L'acomplir rend le developpeur reliable.

Commit quand on depend d'un achevement d'une autre personne.

- idientifier les depzndances.
- cree une interface qui abtrait les dependances de l'autre module
- s'assurer que les changemenrs marcheront dans le systeme future
- creer un build personnel qui execute des testes d'integrations

Commit quand on est pas sur de la livraison
exemple : fix all the bugs
- reproduire les bugs cncretement
- refaire les bugs avec le QA
- best effort sur le fix dd bug.

Commit quand ca marche juste pas:
-changer les objectifs 'e plus tot possible
-prevenir le plus vite possible


# Coding

Règles à suivre:
- Le code doit fonctionner. Le développeur doit comprendre les problèmes qu'il résout. Toutes les solutions doivent rester cohérentes avec l'environnement de développement (Pas faire du java en python par exemple.)
- C'est au développeur de s'assurer que le problème qu'il résout est un plus pour l'utilisateur.
- Le code doit bien s'intégrer au reste du développement. Ne pas le rendre plus compliqué, ne pas le rendre plus fragile ou plus opaque.
- Le code doit être lisible par les autres programmeurs.

## Debugging

Utiliser des outils de debuggin.
Faire du TDD.

## Being late

Quand une livraison est en retard en terme de code, il faut le détecter le plus tot possible et rester transparent.
Un moyen de prévenir les retard de livraison le progrès du développement en fonction des objectifs.
Etablir 3 dates factuelles, Best case, nominal case, worst case.

## Hope

L'espoire n'a pas sa place dans une estimation.

## Rushing

Le rush n'existe pas. Rushé c'est mal codé plus vite. Rendre un rush possible c'est dire que le développeur ne se donne pas déjà au maximum. Le rush doit être évité car il ne fait que ralentir du au erreur qu'il ajoute.

## Overtime

Parfois l'overtime est necessaire.
3 check avant d'accepter un overtime :
- Le développeur peut se le permettre personnelement.
- C'est sur du court terme, l'overtime doit être cadrer.
- Le supérieur qui demande de l'overtime doit avoir un plan B si l'overtime échoue.
Si ces conditions ne sont pas remplis refuser l'overtime.

## False delivery

Il faut rester stricte sur la définition de "Done", une tâche "Done" est testé et validée, idéalement automatiquement.

# Test Driven Development

## The three law of TDD

1. Le développeur n'a pas le droit d'écrire du code en production si il n'a pas écris un test unitaire qui échoue.
2. Le développeur n'a pas le droit d'écrire plus de code que ce dont le test unitaire a besoin pour échouer.
3. Le développeur n'a pas le droit d'écrire plus de code de production qu'il n'en n'ait necessaire pour faire réussir les tests unitaires couraments en échec.

## The litany of benefits

### Certainity

Le TDD est couteux et doivent être executé à chaque changement de code.
Les test unitaires valident le bon fonctionnement des fonctionnalités.

### Defect injection rate

Le TDD réduit le taux de bug.

## Courage

On a moins peur d'itérer sur un code qui bien unitairement testé.
On a moins peur d'ajouter une feature lorsqu'on fait du TDD parceque chaque changement valide déjà un test.

## Documentation

Les tests unitaires sont une bonne documentation. Car ils représentent directement ce que le code fait.

## Design

Code difficile à tester = Mauvais design.
Itérer en TDD n'est pas confortable mais ça pousse à bien respecter les bonnes pratiques de programmation.
Notamment l'isolation des différents modules du code.
Lorsque chaque module du code est isolé, chacun de ces modules seront unitairements testables.
En écrivant les tests avant, on est forcé de bien découpler les différentes fonctions.
Le TDDs poussent à bien designer son code.


# Practicing

Le travail n'est pas de la pratique, le travail est une performance. Un développeur professionel se doit de pratiquer en dehors de son temps de travail afin de garder ses compétences aiguisées et même de les améliorées.

## Kata

Comme dans les art-martiaux, on apprend par la répétition. Les Katas sont des éxercices que l'on répète de manière quotidienne
afin de s'approprier certain réflexes. Par exemple faire des exercices en TDD qui necessite des va et vient rapide entre les tests unitaires et le code sont des bons entrainements. Le problème à résoudre est toujours le même mais ça n'a pas d'importance car on vise à être meilleur sur la réalisation. On peut inclure dans cette pratique la maitrise de l'IDE, de git etc...

## Open source

L'informatique est vaste, touché à plusieurs languages de manières applicatives permet d'avoir une meilleure vue d'ensemble et d'être plus créatif.
Commiter sur un projet open source est un bon moyen de pratiquer dans des millieux étrangés.


# Acceptance testing

## The definition of "Done"

Une tâche est rempli une fois qu'elle valide passe les tests d'acceptance, c'est pour cette raison qu'il est important de les définir en amont, car les tests d'acceptance valide les différentes feature auxquelles le composant doit répondre.
Les tests d'acceptances doivent être écris dans un language humain, ce ne sont pas des tests unitaires. Ils doivent aussi être fait avec le produit.

Example :

given the command LogFileDirectoryStartupCommand
givent that the old_inactive_logs directory does not exist
when the command is executed
then the old_inactive_logs_directory directory shoudl exist
and it should be empty

## Automation

Les tests d'acceptances doivent être automatisé. C'est au développeur de s'assurer que c'est bien le cas. Le coup de mise en place de cette automatisation est minuscule comparé à celui de refaire des tests d'acceptances de manuellement à chaque fois.

## Extra work
 
On peut penser que faire un stack de test automatique est de l'overkill. Il est vrai que tout mettre en place est lourde charge.
Cela dit, c'est uniquement cette stack qui assure au développeur que le contrat est rempli.

## Who Writes Acceptance Tests, and When ?

Les tests d'acceptance devraient être implémenté le plus tard possible, une fois que tout le dev est terminé.
Ils devraient être défini par le produit.

## The Developper's Role

Il s'assure que les tests d'acceptance sont connectés au système et il s'assure que ces test passent.

## Acceptance Tests and Unit Tests

Tests unitaires -> Par le programmeur pour les programmeurs
Tests d'acceptances -> Par le produit pour le produit

## Continous Integration

Les tests d'acceptances doivent être lancés à chaque changement de code, à chaque modification de composant par la CI.

### Stop the Presses

Quand les tests d'acceptances échouent, toutes l'équipe devraient s'arréter afin de passer sur la raison de cet echec.
C'est important car le developpement de résolution peut influer sur tous les développements en cours.


# Testing Strategies

## QA should find nothing.

Le produit en devrait pas trouver de bug. On doit tendre vers cet idéal.
Le produit fait partie de l'équipe.
C'est au produit de définir les tests d'acceptances et c'est au produit d'itérer sur tout le système pour en identifier les comportements.

## The Test Automation Pyramid

Unit tests > Compnent tests > Integration tests > System tests > M Exploratory

## Unit Test

Les premiers tests à écrire. Fait par le programmeur pour le programmeur.
Spécifie le system à son plus bas niveau (les fonctions).
Ils sont écris avant et aide à écrire.
Ils font parti de la CI et garantisse la non regression du code.
Ces tests doivent atteindre un couverture de 90% et doivent assurer qu'ils testent bien le comportement des fonctions.
Fait avec un framework de test unitaire.

## Component Tests

Ce sont les tests d'acceptances.
On écris ces tests pour tester un composant en entier qui inclut les règles du produits.
Ces tests prennent des données en entrées de composant et on compare les données en sortie de composant.
Les autres composants du système n'interviennent pas.
Ils sont écris par le produit avec l'aide d'un developpeur, le produit doit pouvopir les lire ou même les écrire.
Ces tests check les happy-path (on regarde si tout s'exécute bien).
Fait avec un framework de test de composant (Fiteness etc..)
Couvre 50 % du projet.

## Integration Tests

N'ont d'utilité seulement pour les systèmes complexes (qui incluent beaucoup de composant).
On teste comment les différents vont communiquer entre eux et se choéragrphy bien.
Ces tests n'ont pas besoin de vrai données.
Ces tests s'assurent que tout est bien connecté.
Ils sont écris par les architectes.
C'est a ce niveau qu'on teste les performances.
Ils sont écris dans le même language que les tests de composants (même framework).
Ils ne font pas partie de la CI car ils sont lourds.
Couvre 20 % du projet.

## System Tests

Les tests d'intégration ultime. Il s'assure que tout le système est bien connecté.
Devrait faire ressurgir des problèmes de performances.
Désigné par les architects et les tech lead.
Fait avec un framework.
Leur but est d'assurer la construction du système et non son comportement.

## Manual Exporatory Tests

Ce sont des tests fait à la main.
Ils ne sont pas automatisés.
Ils s'appuient sur la créativité du testeur.
Le but n'est pas de tout couvrir mais de s'assurer que le système répond bien sous l'action humaine.

# Time Management

## Meetings

Les meetings prennent du temps. Il faut choisir ceux ou on va et décliner ceux qui ne représentent pas d'intéret. Si un meeting n'est pas intéressant, on peut partir.

## Have an Agenda And a Goal

Le développeur doit savoir le meeting auquel il assiste et dans quel but il y assiste.
Le meeting doit énoncer son sujet de manière claire et dans un temps délimité.
Le meeting doit avoir un but: qu'est ce qu'on attend comme résultat à la fin de ce meeting ?

## Stand-Up Meetings

1. Qu'ai-je fais hier ?
2. Que vais-je faire aujourd'hui ?
3. Qu'est ce qui me bloque ?

Pas plus de 10 minutes.

## Iteration Planning Meetings

On assigne les tâches au différentes personnes de l'équipe.
Pas plus de 5 minutes par tâche, si il y'a besoin de plus, il faut reporter le sujet avec seulement les membres de l'équipe concernés.
Pas plus de deux heures par semaine.

## Iteration Restropective And Demo

20 minutes retro
25 minutes demo

Il ne devrait pas y avoir beaucoup à montrer/discuter après un sprint de deux semaines.

## Arguments/Disagreements

"Un argument qui ne se conclut pas en 5 mintues ne peut pas être conlcut".
La raison est que des deux côtés il n'y a pas de vrai preuve qui supporte un coté ou l'autre.
Les arguments ne sont pas factuels.
Le moyen de résolution est de faire présenter les deux parties leur cas dans en 5 minutes et faire un vote de l'équipe.
Il ne faut pas être de mauvoise fois, si on s'est mis d'accord sur unr solution, il faut s'engager honnetement même si ce n'était pas la préférée.
Faire attention au meeting qui sont juste en place pour montrer son désaccord de manière flou.
Eviter les meetings ou il n'y a qu'un seul point de vue présenté.

## Time Boxing And Tomatoes

Répartir tout son temps en tomate.
Chaque tomate représente 20 minutes.
Prendre une pause de 5 minutes entre chaque tomates.
Regarder combien de tomate on été réalisé en une journée et regarder ce qui a été fait avec ce nombre de tomate.

## Avoidance

### Priority Inversion

Un mensonge que le développeur se dit à lui même car il ne veut pas faire une tâche. Il va se convaincre que cette tâche est moins importante qu'une autre. Ne pas faire ça. Le professionel doit rester factuel.

## Blind Alleys

Quand on fait un choix qui s'avère ne pas donner de résultat, c'est un trou.
Par exemple une décision technique qui soulève encore plus de barière technique.
Il faut savoir reconnaitre les trous le plus vite possible.
Si on est dans un trou, on s'arrête de creuser.

## Marshes, Bogs, Swamps, And Other Messes

Quand on entre dans un gros bordel, on est tenté de s'accomoder le bordel et d'itérer dessus.
Parfois cette situation est inévitable et on doit garder le travail le plus propre possible.
Cela dit plus les demandes auguementent sur le bordel plus il est dur d'itérer sur le code.
En continuant dans cette direction on s'expose à une perte de productivité future car le code ne s'accord plus avec les demandes du produit.
A ce moment la il faut faire le choix de fixer le design, plus on auguemente plus il sera dur de revenir en arrière plus tard.

# Estimation

## A Commitement

Un engagement est un chose que l'on doit fini. Si on s'engage, on doit faire tout ce qui est nécessaire pour réaliser cet engagement. On ne s'engage pas avant d'avor tous les éléments necessaire qui assure la réussite de cete engagement.
Dans le développement, d'autre personne vont se baser sur cet engagement pour leur travail, c'est important de ne pas échouer quand on s'engage.

## An Estimate

Une estimation est une supposition, on fait des suppositions car on ne sait pas combien de temps une tâche pourrait prendre.
Une estimation est une probabilté de distribution, par exemple pour une tâche dont on peut scorer le cout de 1 à 11, on peut supposer que la distribution serait la suivante :
10 % de chance que la tâche coute 1
20 % de chance que la tâche coute 2
50 % de chance que la tâche coute 3
10 % de chance que la tâche coute 4
(Les 10 dernier % distribués sur les notes restantes)

### Implied Commitment

Il ne faut pas accepter "d'essayer" pour une estimation donnée, c'est un engagement caché. Jusqu'ou s'arrete la définition d'essayer ? 

## Pert

Pour estimer on donne trois chiffres.
O, pour Estimation optimiste. Il a peu de chance d'arriver car ça signifie qu'il y 0 surprise.
N, pour estimation nominal.
P, pour estimation pessimiste. L'inverse de O.

micro = (O + 4N + P)/ 6 -> La durée de la tâche.
teta = (P - O)/6 -> la deviation standard, la certainité de la tâches.

Pour la durée de plusieur tâches on en fait la somme.
Pour la déviation standard de plusieurs tâches on fait -> racince carré(somme(deviation standard)²)

## Estimating Tasks

C'est quelque chose qui se fait en équipe.
Différentes méthodes:
- Wideband Delphi
- Flying Fingers
- Planning Poker
- Affinity Estimation
- Rivariate Estimates


# Pressure

Règle à suivre pour éviter la pression :
- **Commitments**. On peut refuser des engagements, on ne s'engage que lorsqu'on est sur.
- **Staying Clean**. Quand c'est le bordel on est tenté de faire du "quick and dirty", c'est un oxymore. Salle veut toujours dire lent. Dans n'importe quel situation, les productions d'un professionels doivent rester consistante ou faire au mieux.
- **Crisis Dicipline**. Il faut rester fidèle à ses principes même en temps de crise. Toujours faire du TDD, toujours faire de la doc, toujours automatisé etc...
- **Don't panic**
- **Communicate** Quand on a un problème, on le communique.
- **Rely on your dicipline** Ne pas perdre confiance dans les bonnes pratiques, elles sont la pour gérer les cas compliqués.
- **Get Help** Demander de l'aide quand on en a besoin.


# Collaboration

## Programmer Versus Employer

Un développeur doit être conscient de son environment, déplier des tickets et débugger ne sont pas suffisant. Il doit prendre en compte les demande de son employeur et être présent pour le produit. Il doit avoir une attitude professionel (respecter le code vestimentaire, les horaires, ne pas faire autre chose que son boulot etc)

## Programmer Versus Progrmmer

### Owned Code and Collective Onwership

Le code doit être partagé. Il n'appartient pas à un développeur mais à l'équipe. On peut être amener à reprendre/maintenir/debugger la pile de travail de quelqu'un d'autres.

### Pairing

Le pragrammation groupé est optimal. En effet quand on débug dans un moment de crise, on le fait souvent en groupe, c'est aussi le cas pour le developpement. C'est un bon moyen de partager la connaissance.
Le meilleur moyen de vérifier du code et de collaborer lors de son écriture.

## Cerebellums

C'est une partie dans le dos du crane.
Le professionel travaille en groupe, il collabore. C'est une équipe.
Un développeur peut penser qu'il travaille mieux tout seul mais la team ne marchera pas mieux avec ce genre d'individualité.
Le plus important est le fonctionnement de l'équipe.


# Teams And Projects

Critère d'une bonne équipe:
- Tous les membres de l'équipe sont assignés sur un seul projet. Un membre ne peut pas être sur deux projets à la foix.
- Les membres de l'équipe ont appris à travailler ensemble, ils ont des rôles bien définis (developpeur, testeurs, analiste, chef de projet), 2 développeur pour 1 testeur est un bon ratio.
- Le chef de projet traque les évolutions des projets et de l'équipe.
- Un membre de l'équipe peut être un leader, coaching et garde des bonnes disciplines.

L'équipe est plus importante que le projet.


# Mentoring, Apprenticeship And Craftmanship

Le développement est un travail que l'on peut comparer à celui de l'artisant.
C'est une personne qui travaille vite mais sans se précipité, il donne de bonne estimation et réalise ses engagements. Il sait quand dire non et essayement honnetement de dire oui. C'est un professionel.

Parfois on peut se retrouver dans un environment qui ne répond pas à cette définition du professinalisme. La meilleur chose à faire dans ce cas est de montrer l'exemple.


# Tooling

Les outils à avoir dans un projet:
- Source code control (git)
- IDE
- Logiciel de suivi de tâches/problèmes
- CI/CD
- Outils de tests unitaire
- Outils de tests de composant (intégration, système etc)

