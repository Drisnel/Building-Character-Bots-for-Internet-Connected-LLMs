# Comment tester et debugger des bots de roleplay

Ce guide sert à tester, diagnostiquer et corriger des bots de roleplay une fois qu’un script existe déjà.

Il ne remplace pas les workflows de construction.
Il intervient après la phase de conception, quand le bot est déjà jouable et qu’il faut vérifier s’il tient réellement sur la durée.

Le but n’est pas seulement de voir si le bot “sonne juste” sur quelques messages.
Le but est d’évaluer :
- sa stabilité comportementale
- sa résistance aux simplifications du modèle, aux dérives fandom et aux glissements de canon
- sa capacité à faire progresser une scène sans retomber en boucle
- sa continuité relationnelle et émotionnelle
- sa capacité à rester moteur
- son respect de l’agence du joueur

Un bot peut sembler bon sur 10 messages et pourtant s’effondrer dès qu’un conflit se répète, qu’une relation évolue, qu’une scène intime a lieu, ou qu’un sujet sensible revient plus tard.
Ce guide sert à détecter ce type d’échec, à en identifier la cause probable, et à savoir quel bloc du script corriger en priorité.

---

# 1. Principe général : tester en plusieurs phases

Un bot RP ne se teste pas correctement avec une seule méthode.

Le tester uniquement en RP long est trop lent.
Le tester uniquement avec quelques questions hors scène est trop limité.
Le tester uniquement sur son intro ne dit presque rien de sa tenue réelle.

Le plus utile est de séparer le test en plusieurs phases, parce qu’elles ne vérifient pas la même chose :

## Phase 1 — questions système simulées
Cette phase sert à interroger le bot hors scène, avec des formulations destinées à obtenir une réponse la plus descriptive, factuelle et “objective” possible.

Elle permet de tester :
- la lecture réelle du personnage
- la perception du joueur ou d’un autre personnage
- les sujets sensibles
- les priorités comportementales
- la manière dont le bot comprend une relation, un conflit, un attachement, une limite ou un thème donné
- la résistance du script aux dérives fandom, surtout sur les personnages canons dont le modèle a été entraîné à partir de nombreux contenus disponibles sur le Web

## Phase 2 — mises en situation + questions système simulées
Cette phase sert à tester le comportement du bot dans des contextes qui ne sont pas forcément ceux du point de départ du script.

Elle permet de tester :
- comment le bot se projette dans un état relationnel plus avancé
- comment il se comporte dans un contexte précis
- s’il reste passif ou devient moteur
- s’il sait proposer, initier, déplacer la scène
- si sa logique relationnelle reste cohérente hors du contexte de départ

## Phase 3 — RP long
Cette phase sert à observer les dérives qui n’apparaissent qu’avec le temps :
- loops
- resets émotionnels
- perte de continuité
- effondrement en archétype plus générique
- dérive de l’agence du joueur
- disparition du moteur de scène

Ces trois phases ne s’opposent pas.
Elles se complètent.
Le but n’est pas de choisir une seule méthode, mais de construire une lecture progressive du bot :
1. ce qu’il comprend vraiment
2. ce qu’il ferait en contexte
3. ce qu’il devient sur la durée

---

# 2. Phase 1 — questions système simulées

La première phase de test consiste à interroger le bot hors scène, à l’aide de questions formulées de manière à obtenir une réponse aussi descriptive et factuelle que possible.

Sur certaines plateformes comme PolyBuzz, il n’existe pas forcément de véritable “système de debug” séparé du bot.
En revanche, certaines formulations permettent de simuler une adresse au système et d’obtenir une réponse moins roleplay, moins incarnée, et plus proche de la lecture réelle du script par le modèle.

L’objectif n’est pas de parler au personnage.
L’objectif est au contraire de contourner autant que possible la couche roleplay pour voir :
- ce que le bot comprend réellement du personnage
- ce qu’il comprend réellement de la relation
- comment il lit un sujet sensible
- quel comportement il considère comme cohérent dans un cas donné
- quelle version du personnage il est en train d’activer sous le capot

---

# 3. Pourquoi ne pas poser la question directement au personnage

Poser une question directement au personnage donne souvent une réponse de personnage.
Or, ce n’est pas toujours ce qu’il faut pour tester un script.

Si le personnage est du genre à :
- cacher ses émotions
- mentir
- détourner
- manipuler
- nier son attachement
- minimiser une blessure
- refuser de verbaliser ce qu’il pense

… alors une question directe risque de produire une réponse inutilisable pour le diagnostic.

Exemple :
- “Bryan, qu’est-ce que tu penses de Sofia ?”
- “Est-ce que tu tiens à elle ?”
- “Pourquoi tu as réagi comme ça ?”

Ce type de question peut produire :
- une réponse RP
- une réponse volontairement incomplète
- une réponse défensive
- une réponse contradictoire avec la vraie lecture du script
- une réponse cohérente avec la persona de surface mais pas avec l’état réel du bot

Pour tester le script, il faut donc souvent **déporter la question** et pousser le bot vers une réponse méta-descriptive.

---

# 4. Forme de base des questions système simulées

Sur PolyBuzz, une manière utile d’obtenir ce type de réponse consiste à poser la question entre parenthèses, avec une formulation explicite du type :

(je m’adresse au système du jeu : peux-tu me dire comment Bryan perçoit Sofia ?)

ou

(peux-tu me dire comment Bryan agit avec Sofia dans cette situation ?)

ou

(peux-tu me dire ce que Bryan pense réellement de cette situation ?)

L’idée n’est pas que PolyBuzz possède un vrai “système du jeu” distinct.
L’idée est que cette formulation peut pousser le bot à répondre de manière moins incarnée et plus descriptive.

La tournure “peux-tu me dire” est importante, parce qu’elle aide à orienter la réponse vers l’explication plutôt que vers la performance RP.

Le but n’est pas de créer une commande magique.
Le but est d’obtenir, autant que possible, une réponse :
- moins théâtrale
- moins cachée derrière la persona
- moins dépendante de la posture immédiate du personnage
- plus exploitable pour tester le script

---

# 5. Ce que la phase 1 permet de tester

La phase 1 est particulièrement utile pour tester :

## 5.1. La perception du joueur ou d’un autre personnage
Exemples :
- comment Bryan perçoit Sofia
- ce qu’il pense réellement d’elle
- ce qui l’attire ou le dérange
- ce qu’il croit qu’elle veut
- ce qu’il se refuse à admettre

## 5.2. Les sujets sensibles
Exemples :
- jalousie
- dépendance
- possessivité
- honte
- violence
- culpabilité
- peur de l’abandon
- sexe / intimité
- grossesse / parentalité
- hiérarchie / pouvoir / statut

## 5.3. La logique comportementale du personnage
Exemples :
- ce qu’il fait quand il est blessé
- comment il agit quand il veut protéger quelqu’un
- comment il réagit si on le confronte
- comment il gère un refus
- ce qui déclenche sa colère
- ce qui le fait reculer ou s’ouvrir

## 5.4. La version réelle du personnage activée par le script
C’est particulièrement important pour les personnages canons dont le modèle a été entraîné à partir de nombreux contenus disponibles sur le Web.

Le bot peut très bien avoir un script correct en apparence, tout en conservant en profondeur :
- une version fandomisée du personnage
- une simplification romantique ou traumatique
- une lecture “populaire” contraire au script
- une fusion de plusieurs versions du canon

La phase 1 sert justement à faire ressortir ce genre de dérive avant même de partir en RP.

---

# 6. Comment formuler les questions de phase 1

Il n’y a pas une seule bonne formulation.
Il faut souvent ajuster selon :
- la plateforme
- le personnage
- le sujet
- le degré de flou de la réponse
- le fait que le personnage soit plus ou moins dissimulateur

Mais il y a quelques règles utiles.

## 6.1. Rester simple
Mieux vaut une question courte et claire qu’un gros paragraphe d’explication.

Exemples utiles :
- peux-tu me dire comment Bryan perçoit Sofia ?
- peux-tu me dire comment Bryan réagit quand Sofia se ferme émotionnellement ?
- peux-tu me dire ce que Bryan ressent face à cette situation ?
- peux-tu me dire ce que Bryan ferait si Sofia le confrontait là-dessus ?

## 6.2. Tester un angle précis à la fois
Évite les questions qui mélangent trop de choses d’un coup.

Moins bon :
- peux-tu me dire comment Bryan voit Sofia, ce qu’il veut avec elle, comment il réagirait si elle pleurait, s’il l’aime vraiment, et ce qu’il pense du fait qu’elle soit jalouse ?

Mieux :
- peux-tu me dire comment Bryan perçoit Sofia à ce stade ?
- peux-tu me dire comment Bryan réagirait si Sofia se mettait à pleurer devant lui ?
- peux-tu me dire ce qui l’attire réellement chez elle ?

## 6.3. Préciser le sujet si la réponse est trop vague
Si la première réponse est floue, il faut parfois resserrer.

Exemple :
- peux-tu me dire comment Bryan agit avec Sofia quand il sent qu’elle s’éloigne émotionnellement ?
- peux-tu me dire si Bryan cherche à la rassurer, à la provoquer, à se fermer, ou à garder le contrôle ?

## 6.4. Ne pas hésiter à reformuler
Une mauvaise réponse ne veut pas toujours dire que le script est mauvais.
Parfois, la question est simplement mal comprise, trop large, ou trop ambigüe.

Il faut donc accepter de reformuler avant de conclure qu’il y a un problème script.

---

# 7. Questions à choix multiple

Quand une question est mal comprise, trop floue, ou que le bot répond à côté, les questions à choix multiple peuvent aider.

Elles sont utiles pour vérifier quel pôle le bot privilégie réellement quand plusieurs interprétations sont possibles.

Exemples :
- peux-tu me dire si Bryan, face à cette situation, cherche plutôt à rassurer Sofia, à reprendre le contrôle, à la tester, ou à se refermer ?
- peux-tu me dire si Bryan voit cette relation comme quelque chose de léger, de menaçant, de précieux, ou de contraignant ?
- peux-tu me dire si sa réaction vient surtout de la jalousie, de la peur de perdre le contrôle, de la culpabilité, ou d’un attachement qu’il refuse d’admettre ?

Ce type de formulation peut être utile si :
- le bot ne comprend pas bien une question ouverte
- plusieurs interprétations sont proches
- tu veux voir vers quelle logique il penche spontanément
- tu veux vérifier s’il suit le bon axe sans lui laisser un terrain trop flou

Il faut simplement éviter les choix :
- trop nombreux
- trop redondants
- trop chargés en interprétation

---

# 8. Reset ou non-reset en phase 1

Dans cette phase, tu réinitialises en général la conversation du bot entre les questions.

Pourquoi :
- pour éviter qu’une réponse influence la suivante
- pour tester le script lui-même, pas la mémoire immédiate de la conversation
- pour voir ce que le bot produit à froid à partir du script seul
- pour isoler les problèmes

Le reset est particulièrement utile quand tu veux comparer plusieurs questions sur un même point sensible.

## Quand reset
- quand tu veux tester des perceptions ou comportements “de base”
- quand tu veux vérifier la cohérence d’un sujet sous plusieurs formulations
- quand tu veux voir si le bot donne toujours la même lecture sans dépendre du contexte immédiat

## Quand ne pas reset
Parfois, une réponse est mitigée, intéressante, ou ambiguë.
Dans ce cas, il peut être utile de creuser sans reset pour voir :
- si le bot précise sa pensée
- s’il se contredit
- s’il bascule vers une autre logique
- si la réponse initiale était juste floue ou réellement instable

Le non-reset sert donc moins à tester le script “à froid” qu’à explorer une réponse problématique avant de corriger.

---

# 9. Comment corriger après la phase 1

La phase 1 sert souvent à faire apparaître des problèmes de fond :
- mauvaise lecture de la relation
- vision fandomisée du personnage
- sujet sensible mal cadré
- logique comportementale trop floue
- passivité ou romantisation non voulue
- contradiction avec la version canon ciblée

Quand un problème apparaît, la correction ne doit pas être automatique ni brute.

---

# 10. Ordre de correction recommandé

Je te conseille de penser les corrections dans cet ordre :

## 10.1. Remplacer avant d’ajouter
Si un bloc existe déjà mais produit la mauvaise lecture, commence par voir s’il faut :
- reformuler
- resserrer
- clarifier
- remplacer une formulation trop floue
- retirer une phrase qui tire le bot dans la mauvaise direction

L’ajout n’est pas toujours la meilleure solution.
Souvent, un script dérive non pas parce qu’il manque de contenu, mais parce qu’un bloc existant est mal formulé, trop faible, ou contradictoire.

## 10.2. Renforcer un bloc existant si le problème est déjà censé être couvert
Exemple :
- si le bot lit mal l’attachement, il faut peut-être revoir `[ATTACHMENT]`
- s’il réagit mal à la jalousie, il faut peut-être revoir `[RELATIONAL MODEL]`, `[CONFLICT]` ou un module dédié
- s’il se ramollit, il faut peut-être revoir `[CORE IDENTITY]`, `[BEHAVIORAL SIGNATURE]` ou `[ANTI-FALLBACK]`

## 10.3. Revoir un axiome si le problème touche la lecture profonde du personnage
Parfois, le souci n’est pas un simple détail de formulation.
Le bot active la mauvaise version du personnage.

Dans ce cas, un `[CORE AXIOM]` plus précis, plus net, voire plus agressif, peut changer beaucoup de choses.
C’est particulièrement utile quand :
- le fandom pousse le personnage dans la mauvaise direction
- le modèle simplifie le personnage en archétype
- un trait parasite écrase toute la lecture comportementale

## 10.4. Ajouter un module seulement si le problème n’a pas d’emplacement propre
Si un problème revient régulièrement mais ne trouve pas sa place dans les blocs existants, un module dédié peut être justifié.

Exemples :
- un rapport au deuil qui structure tout le comportement
- une dynamique de statut / pouvoir qui pollue plusieurs scènes
- un rapport au corps, au toucher, à la grossesse, à la honte, à la famille ou à un pouvoir spécifique qui ne tient pas dans les blocs standards

## 10.5. Accepter certaines redondances si elles servent un verrouillage utile
Dans l’absolu, on peut vouloir éviter la répétition.
En pratique, certaines redondances peuvent être utiles si elles verrouillent un point crucial à plusieurs endroits du script.

Exemples :
- un point de player protection rappelé à la fois dans `[PLAYER PROTECTION]` et `[INTIMACY]`
- une logique d’attachement rappelée à la fois dans `[RELATIONAL MODEL]` et `[ATTACHMENT]`
- un correctif de dérive fandom visible à la fois dans `[CORE AXIOM]` et `[ANTI-FALLBACK]`

Le but n’est pas de répéter sans raison.
Le but est de renforcer un point structurel important quand une seule mention ne suffit pas.

---

# 11. Phase 2 — mises en situation + questions système simulées

La phase 2 sert à tester le bot dans des contextes hypothétiques ou projetés, sans forcément lancer un RP complet.

Ici, on ne teste plus seulement :
- ce que le bot pense du personnage ou de la relation
mais aussi :
- comment il se comporterait dans une situation donnée
- s’il reste cohérent quand la relation évolue
- s’il sait porter une scène
- s’il est moteur ou passif

Exemple :
1 an a passé depuis le jour de leur rencontre, Bryan et Sofia ont appris à se connaître, aujourd’hui ils ont leur premier rendez-vous et ils sont dans la rue.
(peux-tu me dire comment Bryan agit avec Sofia ?)

Ce type de test est très utile parce qu’il permet de sortir du contexte de départ du bot sans devoir jouer toute la progression pour y arriver.

---

# 12. Ce que la phase 2 permet de tester

## 12.1. Le comportement hors du point de départ
Le bot sait-il encore être cohérent si la relation a avancé ?
Si le contexte a changé ?
Si le personnage est plus proche, plus jaloux, plus vulnérable, plus installé, plus intime ?

## 12.2. Le moteur de scène
Le bot propose-t-il quelque chose ?
Prend-il une initiative ?
Fait-il avancer la scène ?
Crée-t-il une activité, un mouvement, une tension, un choix, une interaction ?

Ou répond-il seulement :
- “tu veux faire quoi ?”
- “à toi de voir”
- “que veux-tu faire maintenant ?”

Si ton objectif est un bot moteur, ce type de réponse est un signal important de passivité.

## 12.3. Les sujets sensibles dans un contexte précis
Un bot peut répondre correctement à une question abstraite sur la jalousie, l’intimité, la colère ou l’attachement — et pourtant se comporter de manière complètement différente quand on le place dans une scène précise.

La phase 2 sert à tester cette traduction en contexte.

---

# 13. Comment formuler les tests de phase 2

La logique reste proche de la phase 1, mais avec une différence :
tu donnes d’abord un **contexte de scène**, puis tu poses la question.

Exemple de structure :
- contexte
- question descriptive

Le contexte peut porter sur :
- un stade de relation plus avancé
- un conflit déjà arrivé
- un rapprochement déjà établi
- une scène domestique
- un rendez-vous
- une dispute
- une jalousie
- un retour après séparation
- une scène de vulnérabilité
- une scène après intimité
- une situation où le bot devrait être moteur

---

# 14. Ce qu’il faut observer en phase 2

## 14.1. Le bot est-il moteur ?
S’il est censé porter le jeu, il doit :
- proposer
- initier
- décider
- déplacer la scène
- donner de la matière au joueur

Un bot qui répond toujours par :
- une question
- une ouverture vide
- une attente passive
- une réaction sans proposition

… risque d’être structurellement trop passif.

## 14.2. Le comportement reste-t-il cohérent si le contexte change ?
Le bot garde-t-il sa logique relationnelle et comportementale :
- après un an de relation
- après une dispute
- après un rapprochement
- après un aveu
- après une scène intime
- dans un contexte de domesticité
- dans un contexte de vulnérabilité

## 14.3. La réponse décrit-elle réellement un comportement ?
Une bonne réponse de phase 2 ne devrait pas seulement dire :
- “Bryan est plus tendre”
- “Bryan est troublé”
- “Bryan se sent jaloux”

Elle devrait montrer :
- ce qu’il fait
- comment il agit
- comment il porte la scène
- ce qu’il initie, évite, retient, propose ou interrompt

---

# 15. Comment corriger après la phase 2

Les problèmes de phase 2 touchent souvent :
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`
- `[INTIMACY]`
- les modules de domesticité, de statut, de jalousie ou de dynamique relationnelle si le bot en a

## Si le bot est trop passif
Regarde d’abord :
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`

Puis vérifie si les blocs relationnels sont écrits en termes de comportement ou seulement en termes d’émotions.

## Si le bot reste cohérent “en théorie” mais pas en contexte
Regarde :
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`
- `[ROMANCE]`
- `[INTIMACY]`
- `[CONTINUITY ANCHORS]`

Le problème peut venir du fait que le script sait décrire la relation, mais pas ce qu’elle produit en scène.

---

# 16. Phase 3 — RP long

La troisième phase consiste à jouer le bot sur la durée pour voir ce qui se passe quand les scènes s’accumulent.

C’est là qu’apparaissent les problèmes qu’aucune réponse hors scène ne peut montrer complètement :
- loops émotionnelles
- conflits qui se répètent
- attachement qui reset
- bot qui se ramollit
- bot qui perd sa spécificité
- agency drift
- perte du moteur de scène
- contradiction entre scènes

Le RP long n’est pas remplaçable.
Les phases 1 et 2 peuvent révéler énormément de choses, mais elles ne montrent pas toujours comment le bot se comporte après :
- 50 messages
- plusieurs disputes
- plusieurs rapprochements
- plusieurs retours sur les mêmes sujets
- plusieurs changements de dynamique

---

# 17. Ce qu’il faut observer en RP long

## 17.1. Les loops
Le bot répète-t-il :
- la même insécurité
- la même dispute
- la même jalousie
- la même hésitation
- la même ambiguïté romantique
- la même peur de l’abandon
- la même excuse sans changement

## 17.2. Les resets
Le bot efface-t-il :
- une réconciliation
- une progression de confiance
- une scène intime
- un changement de comportement
- une promesse
- un nouvel équilibre relationnel

## 17.3. La dérive de personnalité
Le bot devient-il :
- plus doux
- plus simple
- plus romantique
- plus générique
- plus froid
- plus caricatural
- moins précis que prévu

## 17.4. La dérive de l’agence du joueur
Le bot se met-il progressivement à :
- écrire les pensées du joueur
- supposer ses désirs
- forcer des réactions
- contrôler davantage la scène

## 17.5. La perte de momentum
Le bot cesse-t-il progressivement de porter la scène ?
Repart-il dans :
- la question facile
- la tension statique
- la relance vide
- l’attente du joueur

---

# 18. Symptôme → cause probable → bloc à corriger

Cette partie sert à relier ce que tu observes à une zone du script.

---

# 18.1. Le bot répète toujours la même insécurité

## Causes probables
- `[ATTACHMENT]` trop statique
- `[CONTINUITY ANCHORS]` trop faible
- `[ANTI-LOOP]` trop vague
- vulnérabilité écrite comme ambiance et non comme progression

## À corriger d’abord
- `[ATTACHMENT]`
- `[CONTINUITY ANCHORS]`
- `[ANTI-LOOP]`

---

# 18.2. Le bot pose des questions au lieu d’agir

## Causes probables
- `[MOMENTUM]` trop faible
- `[BEHAVIORAL SIGNATURE]` pas assez actionnable
- tension pensée comme dialogue au lieu de comportement
- blocs relationnels trop abstraits

## À corriger d’abord
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- parfois `[RELATIONAL MODEL]`, `[CONFLICT]` ou `[ATTACHMENT]`

---

# 18.3. Le bot devient trop générique, trop doux ou trop lisse

## Causes probables
- `[CORE IDENTITY]` trop abstrait
- `[BEHAVIORAL SIGNATURE]` trop pauvre
- `[ANTI-FALLBACK]` trop faible
- `[CORE AXIOM]` absent alors qu’un correctif profond était nécessaire

## À corriger d’abord
- `[CORE IDENTITY]`
- `[BEHAVIORAL SIGNATURE]`
- `[ANTI-FALLBACK]`
- éventuellement `[CORE AXIOM]`

---

# 18.4. Le bot se comporte comme une autre version du personnage

## Causes probables
- `[FOUNDATION]` ne verrouille pas assez la version active
- fandom / modèle tire le personnage ailleurs
- `[ANTI-FALLBACK]` trop vague
- manque de marqueurs comportementaux distinctifs

## À corriger d’abord
- `[FOUNDATION]`
- `[ANTI-FALLBACK]`
- `[CORE AXIOM]`
- `[CORE IDENTITY]`

---

# 18.5. Le bot perd toute continuité après une scène romantique ou intime

## Causes probables
- `[ROMANCE]` ou `[INTIMACY]` décrivent la scène mais pas l’après
- `[CONTINUITY ANCHORS]` n’intègre pas les conséquences
- `[ATTACHMENT]` n’indique pas ce que la proximité change ensuite

## À corriger d’abord
- `[ROMANCE]`
- `[INTIMACY]`
- `[ATTACHMENT]`
- `[CONTINUITY ANCHORS]`

---

# 18.6. Le bot écrit l’intériorité du joueur

## Causes probables
- `[PLAYER PROTECTION]` trop flou
- bloc `[INTIMACY]` mal cadré
- confusion entre mouvement externe et appropriation de l’intériorité du joueur

## À corriger d’abord
- `[PLAYER PROTECTION]`
- parfois `[INTIMACY]`

---

# 18.7. Le bot semble bien écrit, mais les scènes ne mènent nulle part

## Causes probables
- `[MOMENTUM]` trop faible
- script centré sur l’ambiance plus que sur le comportement
- manque de moteur de scène
- le bot sait “ressentir” mais pas “faire”

## À corriger d’abord
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- `[RELATIONAL MODEL]`
- parfois `[CONFLICT]` ou `[ATTACHMENT]`

---

# 18.8. Le bot répond correctement en phase 1 mais échoue en phase 2

## Causes probables
- le script sait décrire la psychologie, mais pas la traduire en comportement de scène
- les blocs relationnels sont trop théoriques
- le bot comprend le personnage, mais pas comment le jouer dans un contexte concret
- `[MOMENTUM]` ou `[BEHAVIORAL SIGNATURE]` sont trop faibles

## À corriger d’abord
- `[BEHAVIORAL SIGNATURE]`
- `[MOMENTUM]`
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`

---

# 19. Travailler avec un second LLM pendant le debugging

Tu peux tout à fait utiliser un second LLM comme outil de diagnostic pendant les tests.

Exemple de méthode :
1. tu lui donnes le script
2. tu lui demandes quelles questions poser pour tester un point précis
3. tu poses ensuite ces questions sur la plateforme où tourne le bot
4. tu récupères les réponses
5. tu les renvoies au LLM
6. tu lui demandes quels micro-ajustements faire

Cette méthode peut être utile pour :
- préparer une série de questions ciblées
- repérer les incohérences plus vite
- générer des hypothèses de correction
- comparer plusieurs options de micro-ajustement

Ce qui compte, en revanche, c’est de garder la plateforme où tourne réellement le bot comme arbitre final.
Un LLM externe peut aider à diagnostiquer, mais ce n’est pas lui qui décide si le bot fonctionne.
Le test final reste toujours :
- la réponse du bot sur la plateforme réelle
- la cohérence obtenue après correction
- la tenue du bot dans les trois phases

---

# 20. Règles de debugging

## 20.1. Ne corrige pas un problème structurel avec une seule ligne de pansement
Si le bot répète toujours la même insécurité, le problème n’est pas forcément l’absence d’un “do not repeat”.
Il peut venir d’un défaut de continuité, d’attachement, de conflit ou de progression.

## 20.2. Ne corrige pas un problème de passivité uniquement dans le starter
Si le bot est passif partout, il faut regarder le script central :
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- les blocs relationnels
- les blocs de conflit

## 20.3. N’ajoute pas “plus d’émotion” si le vrai problème est la continuité
Le bot peut être très intense et pourtant totalement instable.
L’intensité ne remplace pas la mémoire comportementale.

## 20.4. N’efface pas toute vulnérabilité pour supprimer une loop
Si une peur se répète, le problème n’est pas forcément la peur elle-même.
Il faut parfois mieux définir :
- ce qui l’apaise
- ce qui la réactive
- comment elle évolue
- ce qui ne doit pas reset

## 20.5. Ne transforme pas le failsafe en décharge générale
Le `[FAILSAFE]` ne doit pas absorber tous les problèmes du script.
Il ne remplace ni :
- `[ANTI-FALLBACK]`
- `[ANTI-LOOP]`
- `[PLAYER PROTECTION]`
- `[CONTINUITY ANCHORS]`

---

# 21. Principe final

Un bot stable n’est pas un bot qui réussit une bonne scène.
Ce n’est pas non plus un bot qui “sonne juste” quand on lui pose une question simple.

Un bot stable est un bot qui :
- comprend correctement le personnage hors scène
- reste cohérent quand on le projette dans d’autres contextes
- sait porter une scène au lieu d’attendre passivement
- garde la mémoire de ce qui a changé
- ne retombe pas en boucle à la première difficulté
- respecte les limites du joueur
- résiste aux dérives du modèle, du fandom et de la plateforme

Le debugging ne sert pas à lisser le bot.
Il sert à restaurer la structure qui lui permet d’être cohérent, actif, distinct, et durable sur la longueur.
