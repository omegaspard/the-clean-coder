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
