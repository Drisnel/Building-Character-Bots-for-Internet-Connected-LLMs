╭───────────────────────────────╮
│ ✦ 🧠 MÉMOIRE PERMANENTE ✦ │
│      sur PolyBuzz           │
╰───────────────────────────────╯

# Mémoire permanente sur PolyBuzz — Guide d'utilisation et d'optimisation

## Introduction

### 1. À propos de ce guide

Ce document présente une manière pratique de comprendre et d'utiliser la mémoire permanente de PolyBuzz dans le cadre de RP longs.

Il ne s'agit **pas d'une documentation officielle de PolyBuzz**.

Je ne travaille pas pour PolyBuzz et je n'ai pas accès au fonctionnement interne de son système de mémoire. Les explications présentées ici reposent donc sur des **observations, des tests et de l'expérience d'utilisation**.

Certaines informations peuvent être incomplètes, évoluer avec les mises à jour de la plateforme ou comporter des erreurs. Lorsqu'il est question du fonctionnement interne de PolyBuzz, il faut donc distinguer ce qui a été **observé directement dans l'utilisation** de ce qui constitue une explication possible du comportement du système.

L'objectif de ce guide n'est pas de prétendre expliquer avec certitude ce qui se passe techniquement à l'intérieur de PolyBuzz, mais de montrer **comment la mémoire se comporte en pratique et comment l'utiliser de manière plus efficace**.

### 2. À qui s'adresse ce guide

Ce guide s'adresse principalement aux personnes qui utilisent PolyBuzz pour des RP suffisamment longs pour que la mémoire permanente devienne importante.

Il peut notamment être utile aux personnes qui souhaitent :

- comprendre ce qui est enregistré dans la mémoire permanente ;
- comprendre quelles informations peuvent être modifiées manuellement et lesquelles sont enregistrées automatiquement ;
- limiter la perte d'informations importantes au cours d'un RP long ;
- mieux organiser la progression de leurs scènes ;
- repérer les problèmes pouvant apparaître dans la mémoire ;
- savoir comment réagir lorsqu'une information importante a été mal enregistrée ;
- optimiser l'utilisation de la mémoire disponible.

### 3. Utiliser le guide avec un agent IA

Le document est volontairement assez dense et contient de nombreuses informations pratiques.

Il peut être copié dans ChatGPT, Gemini, Claude ou un autre agent IA afin de demander une aide complémentaire.

Une IA peut notamment servir à :

- expliquer une partie du fonctionnement de manière plus simple ;
- transformer les informations du guide en procédure étape par étape ;
- analyser un problème rencontré dans la mémoire ;
- aider à déterminer quoi faire dans une situation précise ;
- reformuler une procédure pour la rendre plus facile à appliquer.

Cependant, l'IA ne doit pas être considérée comme une source officielle concernant le fonctionnement interne de PolyBuzz.

Si une IA propose une explication technique qui n'est pas présente dans ce guide ou qui n'est pas directement observable dans l'interface, cette explication doit être considérée comme une **interprétation ou une hypothèse**, et non comme une information officielle sur le système.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


# 1. Comprendre la mémoire permanente

## 1.1. Les trois onglets principaux

La mémoire permanente est organisée en plusieurs parties. Toutes les informations ne sont pas enregistrées de la même manière et toutes ne peuvent pas être modifiées manuellement.

Il faut notamment distinguer les trois grands onglets suivants :

### Lier

L'onglet « Lier » regroupe plusieurs catégories d'informations utilisées pour conserver des éléments du RP.

On y retrouve notamment :

- **Événements importants**
- **Accord et tâches**
- **Éléments importants**
- **Rapport / Relations**

Ces catégories ne correspondent pas exactement au même type d'informations.

Les événements servent notamment à conserver des éléments importants de ce qui s'est produit pendant le RP.

Les éléments importants peuvent concerner des objets, des techniques, des pouvoirs ou d'autres éléments particuliers apparus dans le RP.

Les relations permettent de conserver des informations concernant les relations entre les personnages.

Les informations de ces catégories sont essentiellement enregistrées automatiquement par PolyBuzz.

### Personnage

L'onglet « Personnage » concerne les personnages présents dans le RP.

Il peut notamment concerner le bot lui-même ainsi que les PNJ rencontrés au cours de la conversation.

Les informations enregistrées pour un personnage peuvent comprendre différentes caractéristiques telles que :

- nom ;
- surnom ;
- âge ;
- genre ;
- orientation sexuelle ;
- goûts ;
- autres informations importantes ;
- apparence ;
- personnalité ;
- identité ;
- résidence.

Ces informations peuvent être présentes dès le démarrage du RP ou être complétées au fur et à mesure de son évolution.

Elles peuvent également évoluer pendant la conversation lorsque de nouvelles informations concernant un personnage apparaissent et sont enregistrées dans la mémoire.

Il faut cependant être particulièrement vigilant avec cette partie de la mémoire.

Contrairement aux informations concernant son propre personnage, les informations enregistrées pour le bot ou les PNJ ne sont pas simplement modifiables manuellement depuis l'interface.

Une erreur enregistrée dans cette partie peut donc devenir beaucoup plus gênante pour la suite du RP.

### Utilisateur

L'onglet « Utilisateur » concerne uniquement le personnage joué par l'utilisateur.

C'est la partie de la mémoire permanente qui peut être **modifiée directement par l'utilisateur**, contrairement aux informations enregistrées automatiquement dans les autres parties.

Les différentes informations concernant le personnage peuvent notamment porter sur son identité, son apparence, sa personnalité ou d'autres caractéristiques disponibles dans cette partie de l'interface.

Cependant, toutes les informations ne sont pas modifiables de la même manière.

En particulier, les catégories **« autres informations importantes »** et **« goûts »** sont remplies automatiquement par PolyBuzz et ne peuvent pas être modifiées manuellement de la même façon que les autres informations accessibles dans cet onglet.

C'est donc une distinction importante à retenir :

> La partie concernant son propre personnage est la partie de la mémoire permanente sur laquelle l'utilisateur dispose du contrôle manuel le plus direct, mais certaines informations restent gérées automatiquement par PolyBuzz.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


# 2. Comprendre les quatre catégories de « Lier »

## 2.1. Événements importants

Les « Événements importants » servent à enregistrer les événements qui se produisent pendant le RP et que PolyBuzz considère comme suffisamment importants pour être conservés.

L'utilisateur ne crée pas directement ces événements.

C'est PolyBuzz qui décide automatiquement qu'une scène ou qu'une partie de la scène doit être enregistrée comme un événement important.

Lorsqu'une scène évolue et qu'il s'y produit quelque chose d'important — par exemple quelque chose que les personnages disent, font, décident ou vivent — PolyBuzz peut décider de l'enregistrer dans cette catégorie.

Cette mémoire joue donc un rôle important dans la continuité du RP.

Elle permet de conserver des informations concernant ce qui s'est produit auparavant afin que ces éléments puissent continuer à avoir une place dans la suite de la conversation.

Il faut cependant tenir compte d'une contrainte essentielle : **chaque événement enregistré possède une quantité limitée de tokens**.

Un événement ne peut donc pas continuer à accumuler indéfiniment de nouvelles informations.

Au début d'une scène, les informations importantes peuvent être enregistrées progressivement et de manière relativement chronologique.

Mais si la même scène continue très longtemps, l'événement correspondant peut finir par atteindre sa limite.

Lorsque cela arrive, les nouvelles informations doivent continuer à tenir dans l'espace disponible.

Certaines informations plus anciennes peuvent alors être considérées comme moins importantes par rapport aux informations plus récentes.

Elles peuvent être :

- condensées ;
- remplacées ;
- simplifiées ;
- ou finir par disparaître.

C'est notamment pour cette raison qu'une information peut avoir été correctement enregistrée au début d'une scène puis ne plus apparaître de la même manière plus tard.

Dans un RP long, cette catégorie demande donc une attention particulière.

Il ne suffit pas de faire durer une scène indéfiniment en considérant que tout ce qui s'y passe restera automatiquement disponible.

## 2.2. Accord et tâches

La catégorie « Accord et tâches » concerne les éléments qui correspondent notamment à des actions prévues ou à des engagements au cours du RP.

Cela peut notamment concerner :

- des rendez-vous ;
- des missions ;
- des tâches à effectuer ;
- des engagements ;
- des actions prévues.

Il est utile de distinguer ce qui a **déjà été accompli** de ce qui doit **encore être réalisé**.

Cette distinction permet de mieux comprendre la fonction de cette catégorie dans la continuité du RP.

Lorsqu'une action est prévue mais n'a pas encore eu lieu, elle ne doit pas être considérée de la même manière qu'un événement déjà accompli.

## 2.3. Éléments importants

Les « Éléments importants » concernent les éléments particuliers qui apparaissent au cours du RP et qui peuvent avoir une importance pour la suite.

Cela peut notamment comprendre :

- des objets ;
- des techniques ;
- des pouvoirs ;
- des capacités ;
- ou d'autres éléments particuliers apparus dans le RP.

Ces informations sont enregistrées automatiquement par PolyBuzz.

En général, cette catégorie pose moins de problèmes que certaines autres parties de la mémoire, mais elle reste importante pour les RP dans lesquels des objets, capacités ou éléments particuliers doivent être conservés dans la continuité.

## 2.4. Rapport / Relations

La catégorie concernant les relations sert à conserver des informations sur les rapports entre les personnages.

Elle peut notamment concerner la relation entre le bot ou un PNJ et le personnage joué par l'utilisateur.

La relation peut évoluer au cours du RP et certaines informations peuvent alors être enregistrées dans cette partie de la mémoire.

Il peut cependant arriver qu'une relation soit mal comprise ou mal formulée par PolyBuzz.

Ce n'est généralement pas la catégorie qui pose le plus de problèmes, mais il reste utile de la contrôler lorsqu'une relation importante évolue fortement au cours du RP.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


# 3. Ancrer correctement le début du RP

## 3.1. Pourquoi le début est important

Le premier message peut servir à donner à PolyBuzz des repères précis sur le début de la scène.

Les démarrages de personnages ne contiennent pas toujours une date et un lieu suffisamment précis.

L'utilisateur peut donc lui-même fournir ces informations dès le premier message.

L'objectif est de donner un point de départ suffisamment clair pour que la scène possède immédiatement des repères temporels, spatiaux et narratifs.

Un début trop vague donne moins d'informations précises auxquelles les événements suivants peuvent être rattachés.

## 3.2. Quoi ancrer

Lorsque cela est pertinent pour le scénario, le premier message peut notamment préciser :

- la date ;
- l'heure ;
- le lieu ;
- la situation ;
- les personnes présentes ;
- l'état initial de la relation ;
- les événements déjà établis ;
- les éléments particuliers propres au scénario.

La date, l'heure et le lieu sont particulièrement utiles pour établir un repère clair dès le départ.

Il n'est pas nécessaire de transformer chaque premier message en fiche technique.

L'idée est simplement de donner les informations importantes qui permettent de comprendre précisément **où, quand et dans quelle situation commence la scène**.

## 3.3. Exemple concret

Par exemple :

> *Nous sommes le 16 août 2026, il est 20h32 quand j'arrive chez Thomas pour fêter son anniversaire. Je lui souris et, quand il ouvre la porte, je lui dis :*
>
> « Désolée, je suis en retard. »

Ce premier message établit immédiatement plusieurs repères :

- **date :** 16 août 2026 ;
- **heure :** 20h32 ;
- **lieu :** chez Thomas ;
- **situation :** arrivée pour son anniversaire ;
- **personnage présent :** Thomas ;
- **action initiale :** arrivée et début de l'interaction.

Cela donne à PolyBuzz des informations précises sur le point de départ de la scène.

Après avoir envoyé ce premier message, la mémoire permanente peut être activée.

PolyBuzz peut alors reprendre les informations présentes dans le script, celles du démarrage du personnage ainsi que les informations importantes introduites dans le message de l'utilisateur.

Le RP peut ensuite évoluer normalement.

## 3.4. Pourquoi cela aide la mémoire

Le premier message fournit les premiers repères auxquels les informations suivantes peuvent être rattachées.

Une date, une heure et un lieu précis donnent notamment un cadre plus clair à la scène.

Lorsque le RP évolue ensuite, les nouveaux événements disposent déjà d'un contexte de départ.

À l'inverse, lorsqu'un RP commence dans une situation très vague, il est plus difficile de conserver une chronologie clairement identifiable.

L'ancrage du début ne garantit évidemment pas que PolyBuzz enregistrera ensuite toutes les informations correctement.

Il permet simplement de fournir au système des repères beaucoup plus précis dès le commencement.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━


# 4. Les Événements importants et leur limite

## 4.1. Chaque événement possède une capacité limitée

Chaque événement enregistré à une date précise possède une quantité limitée de tokens.

Cela signifie qu'un événement ne peut pas contenir une quantité infinie d'informations.

Au début, PolyBuzz peut enregistrer progressivement les informations importantes de la scène au fur et à mesure que celle-ci évolue.

Mais si l'utilisateur reste très longtemps dans la même scène, l'événement correspondant continue de grossir.

Une scène très longue ne crée pas automatiquement davantage d'espace mémoire à l'intérieur de cet événement.

Lorsque la limite est atteinte, les nouvelles informations doivent continuer à être intégrées dans l'espace disponible.

PolyBuzz peut alors considérer certaines informations anciennes comme moins importantes que les informations plus récentes.

Les informations anciennes peuvent donc être condensées, remplacées ou supprimées.

## 4.2. Comment la perte d'informations peut apparaître

La perte d'une information précédemment enregistrée peut notamment apparaître sous différentes formes.

Une information peut être :

- condensée ;
- simplifiée ;
- remplacée par une formulation plus récente ;
- privée de certains détails ;
- ou disparaître complètement de l'événement.

Cela ne signifie pas nécessairement que l'information n'avait jamais été enregistrée.

Elle peut avoir été présente auparavant puis avoir été modifiée lorsque l'événement a continué à accumuler de nouvelles informations.

C'est précisément ce phénomène qui peut devenir problématique dans les RP très longs.

Une scène qui continue pendant un très grand nombre d'échanges peut progressivement faire perdre des détails qui semblaient pourtant acquis.

## 4.3. Pourquoi « jouer plus » ne signifie pas forcément « enregistrer plus »

Il peut sembler logique de penser que plus une scène est longue, plus elle conservera d'informations.

En pratique, ce n'est pas nécessairement le cas.

Si toutes les informations continuent d'être ajoutées au même événement, celui-ci reste soumis à sa limite de tokens.

Faire durer une seule scène indéfiniment ne crée donc pas nécessairement davantage d'espace mémoire.

C'est pour cette raison qu'il faut savoir reconnaître le moment où une scène a suffisamment évolué et où il devient préférable de passer à une nouvelle étape du RP.

La question n'est donc pas simplement de savoir **combien de temps on joue**, mais aussi **comment on répartit la progression du RP entre les différents événements enregistrés par PolyBuzz**.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 5. Séparer efficacement les événements
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 5.1. Pourquoi créer de nouveaux événements

Les « Événements importants » ne sont pas créés manuellement par l'utilisateur. C'est PolyBuzz qui décide automatiquement qu'un événement doit être enregistré lorsqu'il considère qu'une scène est importante ou qu'il s'y passe quelque chose d'intéressant.

L'objectif n'est donc pas de chercher à créer soi-même un événement dans l'interface, mais plutôt de **faire évoluer le RP de manière suffisamment claire pour que PolyBuzz puisse distinguer les différentes scènes**.

Cette séparation devient particulièrement importante lorsque la scène actuelle commence à devenir longue. Comme chaque événement possède une quantité limitée de tokens, continuer indéfiniment à remplir le même événement peut entraîner la condensation, le remplacement ou la disparition progressive d'informations plus anciennes.

Il est donc préférable, lorsque la scène a donné tout ce qu'elle pouvait donner, de la clôturer et de passer à une nouvelle étape du RP.

L'objectif n'est pas nécessairement de changer d'histoire ou d'abandonner l'intrigue en cours. Une nouvelle scène peut parfaitement poursuivre exactement la même conversation, la même relation ou la même intrigue.

Il s'agit simplement de **ne pas continuer à remplir éternellement le même événement** lorsque l'on est réellement passé à une nouvelle scène.

---

## 5.2. Utiliser les transitions et les ellipses

Une manière pratique de passer d'une scène à une autre consiste à utiliser une courte transition sous forme d'ellipse.

La scène précédente peut être clôturée en indiquant clairement qu'elle est terminée, puis une nouvelle scène peut commencer avec de nouveaux repères.

Une transition efficace peut notamment comporter :

- la fin de la scène précédente ;
- une ellipse indiquant que du temps s'est écoulé ;
- une nouvelle date ;
- éventuellement une nouvelle heure ;
- un nouveau lieu ;
- une nouvelle situation ;
- puis la reprise du RP.

L'ellipse permet ainsi de ne pas jouer dans le moindre détail tout ce qui se passe entre deux moments importants.

Elle permet également de conserver la continuité : ce qui s'est passé auparavant peut toujours avoir des conséquences sur la nouvelle scène.

L'idée n'est donc pas de supprimer ce qui précède, mais de **fermer proprement une étape et d'en commencer une autre**.

---

## 5.3. Exemple de transition complète

Imaginons que la scène initiale se déroule le 16 août 2026, chez Thomas, pendant une discussion importante.

Après avoir suffisamment développé cette scène, on peut écrire :

*Nous continuons à discuter tranquillement le reste de la nuit, jusqu'à ce que chacun finisse par rentrer chez lui. Je garde cependant notre discussion en tête, avec la conviction que celle-ci n'est pas terminée.*

*Le 18 août 2026, je retrouve Thomas au bar pour poursuivre notre discussion.*

Cette transition fait plusieurs choses.

La première scène est clairement terminée.

Une ellipse permet ensuite de passer au moment suivant sans avoir besoin de jouer chaque heure écoulée.

Puis une **nouvelle date** est donnée : le 18 août 2026.

Un **nouveau lieu** est également donné : le bar.

Enfin, la continuité narrative est conservée puisque la nouvelle scène indique que la discussion précédente va être poursuivie.

On ne recommence donc pas une nouvelle histoire : on crée simplement un nouveau repère pour une nouvelle étape du RP.

---

## 5.4. Attention aux formulations trop vagues

Une ellipse peut permettre à PolyBuzz de créer un nouvel événement, mais cela ne signifie pas que n'importe quelle formulation produira nécessairement une séparation claire.

Par exemple, imaginons qu'une première scène se déroule le 16 août 2026.

On peut terminer cette scène et écrire :

*Le lendemain, je me retrouve au bar avec Thomas pour continuer notre discussion.*

PolyBuzz peut alors créer un nouvel événement à partir de cette transition. Il dispose notamment d'un nouveau repère temporel — « le lendemain » — ainsi que d'un nouveau lieu : « le bar ». 1

Le problème apparaît lorsqu'on utilise ensuite à nouveau des repères très similaires.

Par exemple :

*Le lendemain, je retrouve Thomas au bar.*

Pour nous, la situation est parfaitement claire : une nouvelle journée est passée et une nouvelle scène commence.

Mais PolyBuzz peut ne pas faire cette distinction.

Il retrouve une nouvelle fois un repère relatif similaire — « le lendemain » — associé au même lieu — « le bar ». Il peut alors considérer qu'il se trouve encore dans le même événement que celui qu'il vient d'enregistrer.

L'événement précédent continue ainsi de grossir alors que, de notre point de vue, plusieurs scènes différentes se sont déjà déroulées.

Comme l'événement possède une limite de tokens, cela peut finir par provoquer la perte progressive d'informations plus anciennes.

Des informations qui avaient pourtant été correctement enregistrées au départ peuvent alors être condensées, remplacées ou supprimées afin de faire de la place aux informations plus récentes.

C'est pourquoi il ne faut pas uniquement se fier au fait que, pour nous, une nouvelle scène est évidente.

Il faut également donner à PolyBuzz des **repères suffisamment distincts** pour favoriser cette séparation.

---

## 5.5. Donner des repères suffisamment différents

Pour bien séparer deux événements, les repères temporels et spatiaux sont particulièrement importants.

Le contenu de la scène reste évidemment essentiel pour l'histoire, mais lorsqu'il s'agit d'aider PolyBuzz à comprendre qu'une nouvelle étape commence, il est préférable de donner des informations qui différencient clairement cette scène de la précédente.

Les principaux repères à privilégier sont :

- **Date**
- **Heure**, lorsqu'elle est pertinente
- **Lieu**
- **Situation**
- **Nouveau contexte**
- **Changement clair d'étape narrative**

Le repère le plus important est notamment de donner **une date précise et un lieu précis** lorsque l'on souhaite réellement repartir sur un nouvel événement.

Par exemple :

*Le 18 août 2026, je retrouve Thomas au bar pour poursuivre notre discussion.*

Cette formulation donne immédiatement à PolyBuzz un nouveau repère temporel précis ainsi qu'un nouveau contexte spatial.

Elle est donc plus claire qu'une succession de formulations relatives comme « le lendemain », surtout lorsque celles-ci sont répétées plusieurs fois.

Il ne s'agit pas d'une garantie absolue sur la manière dont PolyBuzz enregistrera la scène, puisque les événements sont créés automatiquement par la plateforme. Mais cela permet de fournir des repères beaucoup plus nets pour distinguer les différentes étapes du RP.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 6. Jouer pour optimiser la mémoire
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 6.1. Le principe central

L'objectif n'est pas de chercher à faire enregistrer chaque phrase du RP.

La mémoire permanente n'a pas vocation à conserver l'intégralité de la conversation. Ce qui est important, c'est que les informations qui auront une utilité pour la suite du RP puissent être conservées.

Il faut donc plutôt chercher à faire émerger clairement les éléments qui comptent réellement pour la continuité.

Cela peut notamment concerner :

- un événement qui fait évoluer la situation ;
- une décision importante ;
- une information nouvelle ;
- une relation qui évolue ;
- une action qui aura des conséquences plus tard ;
- un objet, une capacité ou un élément particulier qui devient important.

L'idée est donc de privilégier les informations qui ont une véritable fonction dans la suite du RP plutôt que d'essayer de tout faire entrer dans la mémoire.

---

## 6.2. Jouer les événements importants jusqu'à leur stabilisation

Lorsqu'un événement important se produit, il est préférable de lui laisser suffisamment de place pour que la situation soit réellement établie.

Une information peut avoir besoin d'être développée avant de devenir claire dans la continuité du RP.

Par exemple, une discussion importante peut entraîner une décision, puis une conséquence. Si la scène est immédiatement interrompue avant que cette conséquence apparaisse, l'événement peut être moins clairement défini que si la scène est suffisamment développée.

Il ne s'agit donc pas de couper une scène dès qu'un nouvel élément apparaît.

Il faut plutôt distinguer deux situations :

- lorsqu'un événement important est encore en train de se construire, il peut être utile de continuer à le jouer ;
- lorsqu'il est suffisamment établi et que la scène commence ensuite à devenir répétitive ou anecdotique, il peut être préférable de passer à une nouvelle étape.

L'objectif est que l'événement enregistré corresponde à quelque chose de suffisamment clair pour être utile à la suite.

---

## 6.3. Éviter de gaspiller l'espace mémoire

Puisque chaque événement possède une capacité limitée, il est préférable d'éviter de faire durer inutilement une même scène.

Les éléments qui n'ont aucune conséquence sur la suite peuvent occuper de l'espace alors qu'ils deviennent progressivement moins importants.

Cela peut notamment concerner :

- des discussions purement répétitives ;
- de petits échanges sans conséquence ;
- des descriptions qui n'auront aucune utilité future ;
- des répétitions d'informations déjà établies ;
- des passages où la situation n'évolue plus réellement.

Cela ne signifie pas qu'il faut supprimer toute scène calme ou toute conversation sans enjeu.

L'objectif est simplement de reconnaître le moment où une scène a cessé d'apporter quelque chose de nouveau à la continuité.

Si une scène importante continue d'évoluer, il est parfaitement possible de la poursuivre. Le problème apparaît surtout lorsqu'une même scène continue à s'allonger alors que son contenu devient essentiellement anecdotique.

---

## 6.4. Faire apparaître les conséquences

Lorsqu'un élément doit avoir une importance durable, il est utile que ses conséquences apparaissent clairement dans le RP.

Cela peut être :

- une décision ;
- une promesse ;
- une nouvelle relation ;
- un changement de comportement ;
- un nouvel objet ;
- une mission ;
- une information importante ;
- une conséquence durable.

Le fait de faire apparaître ces conséquences permet de donner davantage de substance à l'événement.

Par exemple, une décision prise pendant une conversation devient plus importante lorsqu'elle entraîne ensuite une action ou modifie la situation entre les personnages.

La mémoire ne doit donc pas seulement servir à conserver ce qui vient d'être dit. Il est également important que les éléments importants produisent quelque chose dans le déroulement du RP.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 7. Gérer la progression du RP
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 7.1. Ne pas rester trop longtemps dans le même événement

Il faut apprendre à reconnaître le moment où une scène a atteint son objectif.

Une scène peut commencer avec un événement important, évoluer pendant un certain temps, puis arriver à un moment où la situation est suffisamment établie.

À partir de là, si les échanges commencent à tourner en rond ou à devenir essentiellement anecdotiques, il peut être préférable de passer à une nouvelle étape.

Cela ne signifie pas qu'il faut abandonner l'intrigue.

Une nouvelle scène peut parfaitement reprendre les conséquences de la précédente, continuer une discussion ou poursuivre exactement la même intrigue.

La séparation sert simplement à éviter de continuer à remplir indéfiniment le même événement.

---

## 7.2. Utiliser les ellipses intelligemment

L'ellipse permet de faire avancer le RP sans jouer chaque moment intermédiaire.

Tout ce qui se passe entre deux étapes importantes n'a pas nécessairement besoin d'être développé en détail.

On peut donc résumer une période lorsque celle-ci ne contient rien qui mérite d'être conservé précisément.

Par exemple, au lieu de jouer chaque minute d'une soirée ou chaque journée passée entre deux événements importants, il est possible de résumer cette période puis de reprendre directement au moment où quelque chose d'important se produit.

L'intérêt est double :

- faire progresser le RP plus efficacement ;
- éviter de remplir inutilement un événement avec des informations qui n'auront pas d'importance pour la suite.

L'ellipse doit cependant être suffisamment claire pour permettre au RP de continuer sans ambiguïté.

---

## 7.3. Ne pas supprimer artificiellement la continuité

Passer à une nouvelle scène ne signifie pas effacer ce qui s'est passé avant.

Une ellipse ne doit pas servir à supprimer artificiellement les conséquences d'un événement.

Si une décision a été prise, une relation a évolué, une mission a été donnée ou un événement a modifié la situation, ces éléments doivent continuer à exister dans les scènes suivantes.

La nouvelle scène doit donc être considérée comme une nouvelle étape du RP, et non comme un nouveau départ sans rapport avec ce qui précédait.

Par exemple, si deux personnages ont eu une discussion importante dans une première scène, la scène suivante peut commencer plusieurs jours plus tard tout en faisant référence aux conséquences de cette discussion.

L'objectif est de séparer les événements dans la mémoire sans casser la continuité narrative.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 8. Modifier ou corriger les informations mémorisées
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 8.1. Ce qui peut être modifié manuellement

La partie de la mémoire permanente que l'utilisateur peut réellement modifier directement concerne son propre personnage, dans l'onglet « Utilisateur ».

Les informations disponibles pour ce personnage peuvent être ajustées manuellement dans les catégories prévues par l'interface.

Il faut cependant faire une distinction importante : les « goûts » et les « autres informations importantes » sont remplis automatiquement par PolyBuzz et ne sont pas modifiables manuellement de la même manière que les autres informations.

Pour les autres onglets, notamment les informations concernant le bot, les PNJ et les éléments liés au RP, l'enregistrement est essentiellement effectué automatiquement par PolyBuzz.

Il ne faut donc pas supposer que toutes les informations visibles dans la mémoire peuvent être éditées directement par l'utilisateur.

---

## 8.2. Modification automatique par PolyBuzz

Une partie importante de la mémoire est alimentée automatiquement par PolyBuzz.

Cela concerne notamment les informations qui apparaissent au fur et à mesure du RP dans les différentes catégories de mémoire.

L'utilisateur peut influencer indirectement ce qui est enregistré en jouant et en faisant apparaître clairement les informations importantes, mais cela ne signifie pas qu'il contrôle directement l'enregistrement.

PolyBuzz décide lui-même quelles informations doivent être retenues et comment elles doivent être formulées.

Cela peut fonctionner correctement, mais des erreurs peuvent également apparaître.

Il peut notamment y avoir :

- une erreur de date ;
- une mauvaise association entre une date et un lieu ;
- une information mal formulée ;
- une relation mal comprise ;
- une mauvaise information attribuée à un personnage ;
- ou, dans certains cas, une caractéristique qui finit par influencer le comportement d'un personnage de manière problématique.

Il est donc important de contrôler régulièrement ce qui est réellement présent dans la mémoire.

---

## 8.3. Tentative de modification via OOC

Il est parfois possible de tenter de demander une modification de la mémoire directement au bot en utilisant un message hors RP.

On peut notamment :

- écrire un message entre parenthèses ;
- utiliser « OOC » ;
- demander explicitement une modification ;
- demander au bot de modifier une information mémorisée.

Par exemple, on peut expliquer hors RP qu'une information enregistrée est incorrecte et demander qu'elle soit corrigée.

Cette méthode peut parfois donner un résultat utile, mais elle possède des limites importantes.

### Limites

Une demande OOC n'est pas une véritable console système garantie.

Le bot peut :

- comprendre la demande ;
- répondre qu'il a effectué la modification ;
- répondre comme s'il avait accès à la mémoire ;
- ou simplement traiter le message comme du contenu de conversation.

Il est donc possible qu'une réponse donne l'impression que l'information a été modifiée alors que la mémoire permanente n'a en réalité pas changé.

Le fonctionnement peut également dépendre de la manière dont le bot a été construit et des instructions présentes dans son script.

Il faut donc considérer cette méthode comme une tentative possible, et non comme une méthode fiable permettant de contrôler directement la mémoire de PolyBuzz.

---

## 8.4. Quand le script peut aider

Le script du bot peut toutefois avoir prévu un fonctionnement particulier pour les demandes OOC.

Cela peut notamment être le cas :

- si l'auteur a explicitement prévu une commande OOC ;
- si le script indique que certaines formulations doivent simuler une console ou une adresse système ;
- si le bot a été conçu pour interpréter ce type de demande comme une instruction de modification.

Dans ce cas, le bot peut être davantage susceptible de comprendre la demande comme une instruction hors RP.

Cela ne signifie cependant pas automatiquement que la mémoire permanente de PolyBuzz sera effectivement modifiée.

Le comportement prévu par le script et le fonctionnement réel de la mémoire de la plateforme restent deux choses différentes.

---

## 8.5. Pourquoi cette méthode reste peu fiable

Un modèle connecté à la plateforme peut interpréter une demande adressée au « système » comme une partie normale de la conversation.

Le fait d'écrire :

« OOC : modifie cette information dans ta mémoire »

ne transforme pas automatiquement le message en véritable instruction système.

Le bot peut très bien répondre :

« C'est corrigé. »

sans que l'information affichée dans la mémoire permanente ait réellement changé.

C'est pourquoi il faut toujours distinguer ce que le bot affirme avoir fait de ce qui apparaît réellement dans l'interface de mémoire.

La mémoire réelle de la plateforme reste distincte de ce que le modèle affirme avoir modifié.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 9. Vérifier ce qui a réellement été enregistré
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 9.1. Ne pas confondre réponse du bot et mémoire réelle

Il ne faut pas considérer la réponse du bot comme une preuve que la mémoire a été modifiée.

Un bot peut parfaitement comprendre une demande, confirmer une correction et continuer la conversation comme si celle-ci avait été effectuée.

Cela ne permet pas de savoir si PolyBuzz a réellement modifié l'information.

La seule manière fiable de vérifier le résultat est de regarder directement la mémoire permanente dans l'interface.

---

## 9.2. Vérifier les catégories concernées

Selon le type d'information recherché, il faut vérifier l'onglet correspondant :

- « Lié » ;
- « Personnage » ;
- « Utilisateur ».

Dans « Lié », il faut notamment regarder les catégories correspondant aux événements, aux éléments importants, aux accords et tâches ou aux relations.

Dans « Personnage », il faut vérifier les informations concernant le bot et les PNJ.

Dans « Utilisateur », il faut vérifier les informations relatives au personnage joué par l'utilisateur.

Cette vérification permet également de repérer des erreurs qui n'ont pas forcément été remarquées pendant le RP.

---

## 9.3. Vérifier après une modification

Lorsqu'une information est importante, une vérification simple peut être effectuée en trois temps :

1. vérifier l'information avant la modification ;
2. effectuer la demande de modification ;
3. vérifier à nouveau la mémoire après la modification.

Il est alors possible de comparer ce qui était présent avant avec ce qui apparaît réellement après.

Cette méthode est particulièrement utile lorsqu'une modification a été demandée en OOC.

Si le bot affirme avoir effectué la modification mais que l'information reste inchangée dans la mémoire, il faut considérer que la modification n'a pas réellement été effectuée.


━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 10. Que faire lorsqu'une information importante a disparu ?
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 10.1. Identifier ce qui a disparu

Lorsqu'une information semble avoir été perdue, il faut d'abord déterminer précisément ce qui manque.

Il peut s'agir :

- d'une information de personnage ;
- d'un événement ;
- d'une relation ;
- d'un objet ;
- d'une tâche ;
- d'une conséquence ;
- d'un élément de chronologie.

Cette distinction est importante, car toutes les informations ne sont pas enregistrées dans la même partie de la mémoire et ne peuvent pas être corrigées de la même manière.

---

## 10.2. Déterminer pourquoi elle a pu disparaître

Une perte d'information peut avoir plusieurs causes possibles.

Dans les « Événements importants », une scène trop longue peut avoir atteint sa limite de tokens. Les informations les plus anciennes peuvent alors avoir été condensées, remplacées ou supprimées au profit d'informations plus récentes.

Une information peut également avoir été mal enregistrée dès le départ, notamment lorsqu'il s'agit d'une date, d'un lieu ou d'une association entre plusieurs éléments.

Dans l'onglet « Personnage », le problème peut être différent. Une information peut avoir été attribuée au mauvais personnage, deux personnages peuvent avoir été fusionnés, ou une caractéristique peut avoir été enregistrée d'une manière qui influence ensuite le comportement du personnage.

Il faut donc examiner la mémoire elle-même avant de conclure à une simple perte d'information.

---

## 10.3. Réintroduire l'information dans le RP

Lorsqu'une information importante a disparu mais qu'elle peut encore être réintroduite naturellement, il est possible de la faire réapparaître dans le RP.

L'idée n'est pas nécessairement de répéter mécaniquement la phrase originale.

On peut plutôt :

- refaire apparaître l'information naturellement ;
- lui donner un nouveau contexte ;
- produire une conséquence ou un rappel pertinent ;
- puis vérifier si PolyBuzz l'a de nouveau enregistrée.

Par exemple, si un élément important pour la suite n'apparaît plus dans la mémoire, il peut être pertinent de le faire intervenir à nouveau au moment où il devient naturellement utile dans l'histoire.

Il faut ensuite contrôler la mémoire pour vérifier que l'information a réellement été enregistrée.

Cette méthode est surtout adaptée aux informations qui peuvent encore être réintroduites sans créer de contradiction avec ce qui s'est déjà produit.

Lorsqu'une information erronée dans l'onglet « Personnage » commence au contraire à modifier durablement le comportement d'un personnage, une simple réintroduction dans le RP peut ne pas suffire. Dans ce cas, il peut être nécessaire d'envisager un rollback.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
# 11. Le rollback
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 11.1. À quoi sert le rollback

Le rollback permet de revenir à un état antérieur du RP lorsque la progression actuelle pose un problème qui ne peut pas être corrigé facilement dans la continuité de la conversation.

Il peut notamment être utile lorsque le RP a pris une mauvaise direction, lorsqu'une information importante a été enregistrée de manière incorrecte ou lorsqu'une évolution du personnage ou de la relation est devenue problématique.

Dans le contexte de la mémoire permanente, le rollback est particulièrement intéressant parce qu'il peut permettre de revenir à un état antérieur avant que certaines informations problématiques ne soient enregistrées ou avant qu'une évolution indésirable ne se soit installée dans la mémoire.

Il ne s'agit cependant pas simplement de revenir à un message précédent dans la conversation.

Le rollback doit être considéré comme un moyen de revenir à un état antérieur du RP tel qu'il existait à un moment donné, avec les informations et la progression qui lui étaient associées.

Son intérêt principal est donc de pouvoir **annuler une évolution problématique plutôt que de devoir essayer de la corriger après coup**.

---

## 11.2. Quand utiliser le rollback

Le rollback peut être envisagé lorsque le problème est suffisamment important pour justifier un retour en arrière.

Cela peut notamment être le cas pour :

- une erreur importante dans le déroulement du RP ;
- une mauvaise évolution de la relation entre les personnages ;
- une information importante qui a été enregistrée de manière incorrecte ;
- un événement mal interprété ou mal mémorisé ;
- une caractéristique attribuée au mauvais personnage ;
- une dérive du comportement d'un personnage ;
- une contradiction devenue difficile à corriger naturellement ;
- une situation qui a entraîné plusieurs informations incorrectes dans la mémoire.

Le rollback est particulièrement pertinent lorsqu'une erreur commence à avoir des conséquences sur plusieurs scènes.

Par exemple, une information incorrecte peut apparaître dans la mémoire d'un personnage. Le bot peut ensuite commencer à se comporter conformément à cette information, puis plusieurs scènes peuvent être construites autour de cette nouvelle caractéristique.

Dans ce cas, essayer de corriger uniquement la dernière conséquence peut ne pas suffire.

Revenir à un état antérieur à l'apparition de l'erreur peut être plus propre que de tenter de réparer chaque conséquence séparément.

Il est cependant préférable de ne pas utiliser le rollback pour de petites erreurs qui peuvent être corrigées naturellement dans le RP.

Lorsqu'une information peut simplement être réintroduite ou corrigée sans créer de contradiction, il est généralement plus simple de poursuivre le RP et de rétablir progressivement la situation.

---

## 11.3. Limites

Le rollback ne doit pas être considéré comme une sauvegarde parfaite de l'intégralité du RP.

Il ne faut pas supposer qu'un retour à un état antérieur garantit automatiquement que **toutes** les informations de mémoire seront exactement identiques à celles qui existaient auparavant.

La mémoire permanente et le déroulement de la conversation sont deux éléments liés, mais ils ne doivent pas être considérés comme une copie parfaite l'un de l'autre.

Après un rollback, il est donc important de vérifier ce qui a réellement été restauré.

Il faut notamment contrôler :

- les « Événements importants » ;
- les « Accords et tâches » ;
- les « Éléments importants » ;
- le « Rapport » ;
- les informations des personnages ;
- les informations du personnage utilisateur ;
- ainsi que les éléments de chronologie importants.

Une restauration apparente ne doit donc pas être considérée comme suffisante sans vérification.

Le rollback doit plutôt être vu comme **un moyen de revenir à une situation antérieure**, après quoi il faut contrôler la mémoire et éventuellement poursuivre le RP à partir de cet état.

Il est également préférable de ne pas compter systématiquement sur le rollback pour réparer les pertes de mémoire.

La meilleure stratégie reste de limiter les erreurs et les pertes en structurant correctement le RP dès le départ.

---

# 12. Stratégie générale pour les RP longs
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## 12.1. Avant de commencer

La meilleure optimisation de la mémoire commence avant même que le RP ne devienne long.

Avant de commencer, il est utile de vérifier les informations déjà présentes dans la mémoire permanente afin de savoir exactement dans quel état se trouvent les personnages et le contexte.

Il faut notamment vérifier :

- les informations de départ du scénario ;
- le personnage joué par l'utilisateur ;
- les informations du bot ;
- les PNJ importants ;
- les éléments déjà présents dans la mémoire ;
- les éventuels événements ou relations déjà enregistrés.

Cette vérification permet d'éviter de commencer un nouveau RP avec une information incorrecte déjà présente dans la mémoire.

Il est également important d'ancrer correctement le début du RP.

La date, le lieu, les personnes présentes, la situation et l'état initial des relations doivent être suffisamment clairs pour donner à PolyBuzz des repères solides.

Lorsque le scénario possède déjà des éléments établis avant le début de la scène, ceux-ci doivent également être suffisamment clairs pour éviter une ambiguïté sur le point de départ.

L'objectif n'est pas de remplir la mémoire avec une quantité maximale d'informations avant de commencer.

Il s'agit plutôt de **s'assurer que les informations qui servent réellement de base au RP sont correctes et cohérentes**.

---

## 12.2. Pendant le RP

Pendant le RP, l'optimisation repose principalement sur la manière dont les événements sont construits et séparés.

Il faut notamment :

- faire progresser les événements importants ;
- créer des transitions claires entre les différentes scènes ;
- éviter de surcharger inutilement un même événement ;
- faire apparaître les conséquences importantes ;
- vérifier périodiquement la mémoire ;
- corriger les erreurs lorsqu'elles sont repérées.

Lorsqu'une scène introduit une information importante, il est préférable de lui donner suffisamment de contexte pour que cette information soit clairement établie.

À l'inverse, lorsque la scène a atteint son objectif et que les échanges deviennent principalement répétitifs, il peut être préférable de passer à une nouvelle étape.

Il faut également surveiller les informations qui évoluent progressivement.

Une relation peut changer.

Un personnage peut acquérir une nouvelle caractéristique importante.

Une mission peut être accomplie.

Un objet peut changer de propriétaire.

Une décision peut entraîner une conséquence durable.

Ces changements doivent pouvoir être identifiés clairement dans le déroulement du RP et, lorsque cela est pertinent, vérifiés dans la mémoire.

La surveillance ne doit toutefois pas devenir permanente.

L'objectif n'est pas d'interrompre le RP après chaque message pour contrôler la mémoire, mais de faire des vérifications à des moments pertinents, notamment après des événements importants ou lorsqu'une information critique vient d'apparaître.

---

## 12.3. Lorsqu'un événement important est terminé

Lorsqu'un événement important arrive à son terme, il est préférable de reconnaître clairement que cette étape est terminée.

Cela peut être fait par une conclusion naturelle de la scène, suivie d'une transition vers la suite du RP.

Une nouvelle étape peut alors commencer avec de nouveaux repères temporels, spatiaux ou narratifs.

Par exemple :

*La discussion se termine finalement après plusieurs heures. Nous avons maintenant pris une décision claire concernant la mission et chacun sait ce qu'il devra faire.*

*Le 21 août 2026, trois jours plus tard, nous nous retrouvons à la gare pour commencer la mission.*

La première scène a ainsi une conclusion identifiable.

La nouvelle scène possède ensuite une date et un lieu différents, ainsi qu'une situation nouvelle : le début de la mission.

La continuité n'est pas supprimée.

Au contraire, la nouvelle scène s'appuie directement sur la décision prise précédemment.

Cette manière de progresser permet de considérer le RP comme une succession d'étapes plutôt que comme une seule scène qui continuerait indéfiniment.

---

## 12.4. Lorsqu'une information critique apparaît

Lorsqu'une information particulièrement importante apparaît dans le RP, il est préférable de lui accorder une attention particulière.

Il peut s'agir par exemple :

- d'une information essentielle sur un personnage ;
- d'une décision qui modifiera la suite du scénario ;
- d'un changement majeur dans une relation ;
- d'un objet important ;
- d'une mission ;
- d'une promesse ;
- d'une conséquence durable ;
- d'un élément essentiel de chronologie.

Cette information doit d'abord être clairement établie dans le RP.

Il est ensuite utile de vérifier dans quelle catégorie de mémoire elle apparaît.

Par exemple, une évolution de relation pourra être recherchée dans « Rapport », tandis qu'une tâche ou une mission pourra être recherchée dans « Accord et tâches ».

Un événement narratif important pourra apparaître dans « Événements importants », tandis qu'un objet ou un élément particulier pourra être enregistré dans « Éléments importants ».

Lorsqu'une information concerne directement un personnage, il faut également vérifier l'onglet « Personnage » ou « Utilisateur » selon le personnage concerné.

Une fois l'information enregistrée, il peut être utile de la vérifier à nouveau après la progression de plusieurs scènes.

Cette vérification permet de déterminer si l'information reste présente ou si elle a été condensée, modifiée ou remplacée.

Pour les éléments qui auront une influence majeure sur la suite du RP, cette surveillance est particulièrement importante.

---

# 13. Ce qu'il faut retenir
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Principe 1

La mémoire permanente n'est pas un enregistrement intégral du RP.

Elle ne doit pas être considérée comme une transcription complète de chaque message ou de chaque détail de la conversation.

Son rôle est plutôt de conserver certains éléments considérés comme importants pour permettre au RP de continuer de manière cohérente.

---

## Principe 2

Toutes les catégories de mémoire n'ont pas le même rôle.

Les « Événements importants », les « Accords et tâches », les « Éléments importants » et le « Rapport » servent à conserver des types d'informations différents.

De la même manière, les onglets « Personnage » et « Utilisateur » concernent les informations relatives aux personnages.

Il est donc important de savoir où rechercher une information lorsqu'on souhaite vérifier si elle a réellement été enregistrée.

---

## Principe 3

Les « Événements importants » ont une capacité limitée.

Un événement peut continuer à accumuler des informations au fil d'une scène, mais son espace n'est pas illimité.

Lorsque trop d'informations sont accumulées, les éléments plus anciens peuvent être condensés, remplacés ou disparaître progressivement.

Il faut donc éviter de considérer un événement comme un espace mémoire permanent pouvant contenir indéfiniment une scène entière.

---

## Principe 4

Un RP long doit être pensé comme une succession d'étapes plutôt qu'une seule scène interminable.

Chaque étape importante peut être développée suffisamment pour être clairement établie, puis le RP peut progresser vers une nouvelle scène lorsque cela devient pertinent.

Cette organisation permet de limiter la surcharge d'un même événement tout en conservant la continuité narrative.

---

## Principe 5

Les transitions claires permettent de mieux séparer les événements.

Une nouvelle date, un nouveau lieu, une nouvelle situation ou un changement clair dans le contexte peuvent fournir des repères permettant de distinguer une nouvelle étape de la précédente.

Il ne s'agit cependant pas d'une garantie absolue sur la manière dont PolyBuzz enregistrera les événements.

Ces repères servent surtout à rendre la progression du RP plus clairement identifiable.

---

## Principe 6

Ce qui compte n'est pas de conserver chaque détail, mais de préserver les informations qui auront une conséquence sur la suite.

Une discussion sans conséquence n'a pas nécessairement besoin d'être conservée dans tous ses détails.

À l'inverse, une décision, une promesse, une relation, une mission ou une information qui modifiera les scènes suivantes mérite davantage d'attention.

L'objectif est donc de privilégier la valeur narrative et la continuité plutôt que la quantité brute d'informations enregistrées.

---

## Principe 7

Une demande OOC peut parfois aider à demander une modification, mais elle ne constitue pas une commande garantie.

Le fait de demander au bot de modifier une information ne signifie pas nécessairement que PolyBuzz va réellement modifier sa mémoire permanente.

Une réponse positive du bot ne suffit donc pas à confirmer qu'une modification a été effectuée.

La mémoire affichée dans l'interface doit être vérifiée directement.

---

## Principe 8

La mémoire affichée par PolyBuzz doit rester l'arbitre de ce qui a réellement été enregistré.

Le comportement du bot peut donner une indication, mais il ne constitue pas une preuve suffisante.

Lorsqu'une information est importante, il faut vérifier directement l'onglet concerné afin de déterminer ce qui est réellement présent dans la mémoire.

---

## Principe 9

La meilleure optimisation consiste à travailler avec le fonctionnement réel de la mémoire plutôt qu'à essayer de tout y faire entrer.

Il ne faut pas chercher à transformer la mémoire permanente en archive complète du RP.

Il est plus efficace de :

- structurer correctement les scènes ;
- faire apparaître clairement les événements importants ;
- séparer les étapes du RP ;
- limiter les répétitions inutiles ;
- faire apparaître les conséquences ;
- vérifier les informations critiques ;
- corriger les erreurs lorsqu'elles sont repérées ;
- utiliser le rollback lorsque la situation le justifie.

La mémoire doit donc être considérée comme une ressource à gérer, et non comme un espace dans lequel tout le RP pourrait être conservé sans limite.

---

# Conclusion
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

La mémoire permanente peut considérablement améliorer la tenue d'un RP long, mais elle possède ses propres contraintes.

Elle ne fonctionne pas comme une sauvegarde intégrale de toute la conversation.

Son efficacité dépend notamment de la manière dont les informations importantes apparaissent, évoluent et sont conservées au fil du RP.

L'objectif n'est donc pas de chercher à enregistrer absolument tout ce qui se passe.

Il s'agit plutôt d'apprendre à :

- structurer correctement le début du RP ;
- faire émerger clairement les événements importants ;
- donner suffisamment de matière aux événements qui doivent compter ;
- séparer les différentes étapes du récit ;
- utiliser les transitions et les ellipses de manière pertinente ;
- limiter la surcharge d'un même événement ;
- faire apparaître les conséquences importantes ;
- surveiller ce qui est réellement mémorisé ;
- corriger les informations lorsque cela est nécessaire ;
- utiliser le rollback lorsqu'une erreur importante ne peut plus être corrigée proprement ;
- et utiliser intelligemment l'espace mémoire disponible.

La logique générale peut ainsi être résumée simplement :

**établir → développer → stabiliser → vérifier → transitionner → poursuivre.**

Il ne s'agit pas de contrôler directement la mémoire de PolyBuzz, puisque son enregistrement est en grande partie automatique.

Il s'agit plutôt de construire le RP de manière à fournir à la plateforme des repères suffisamment clairs, tout en surveillant ce qui est effectivement conservé.

Cette méthode repose sur l'observation du fonctionnement de PolyBuzz et peut nécessiter des ajustements si la plateforme fait évoluer son système de mémoire.

Elle ne doit donc pas être considérée comme une garantie absolue sur le fonctionnement interne de la plateforme, mais comme une méthode pratique d'utilisation fondée sur l'observation et l'expérience.



