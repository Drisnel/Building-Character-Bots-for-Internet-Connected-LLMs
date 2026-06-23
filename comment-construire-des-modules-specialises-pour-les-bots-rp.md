# Comment construire des modules spécialisés pour les bots RP

Ce guide sert à construire les modules spécialisés qui ne rentrent pas proprement dans les blocs de base d’un script, mais qui restent pourtant structurellement importants pour le bot.

Il s’applique aussi bien aux bots canons qu’aux bots originaux.

Il ne remplace pas les workflows de construction.
Il ne remplace pas non plus les templates de script final.
Il ne remplace pas non plus le testing / debugging.

Son rôle est différent :

- aider à identifier quand un bot a besoin d’un module spécialisé
- aider à décider si ce module doit être autonome ou non
- aider à déterminer où le placer dans la hiérarchie du script
- aider à définir ce qu’il faut réellement écrire dedans
- aider à relier ce module au reste du script
- aider à tester si ce module tient réellement en RP
- aider à réviser sa hiérarchie, sa portée ou sa rédaction après test si nécessaire

Ce guide n’est pas pensé pour ajouter des modules “au feeling”.
Je ne recommande pas de créer un module spécialisé à l’aveugle.

En pratique, je m’appuie sur un agent IA comme ChatGPT, Claude ou Gemini pour travailler la structure du bot avec moi :
- auditer si un module est réellement nécessaire
- déterminer s’il doit être autonome ou non
- proposer où il doit être placé dans le script
- identifier quels autres blocs doivent être ajustés s’il est ajouté
- rédiger le module après audit, selon mes instructions et ma validation
- réévaluer sa place, sa forme ou sa priorité après test et debug

L’IA ne remplace pas la décision finale.
Elle sert d’outil d’analyse, de hiérarchisation, de rédaction et de révision structurelle.

Le problème n’est pas seulement qu’un bot puisse avoir “des choses en plus”.
Le vrai problème est qu’un certain nombre de bots ne sont pas structurés d’abord par leur relation avec l’utilisateur.

Certains sont surtout portés par :
- le combat
- la politique
- la hiérarchie
- la religion
- la survie
- l’enquête
- le devoir
- la criminalité
- une logique de commandement
- une structure familiale
- une logique professionnelle
- une mécanique surnaturelle
- une capacité ou un système technique
- ou un autre système qui continue de gouverner le comportement du personnage une fois le RP lancé

Si ce type de structure est trop important pour rester implicite, mais trop spécifique pour être dispersé dans plusieurs blocs généraux, il faut souvent créer un module spécialisé.

L’objectif n’est pas de multiplier les modules pour enrichir artificiellement le script.
L’objectif est de donner une forme claire aux structures qui gouvernent réellement le bot, afin qu’elles restent actives dans ses décisions, dans ses scènes, dans ses conflits, dans sa continuité et dans sa progression.

---

# 1. Un module spécialisé n’est pas un “bonus”

Une erreur fréquente consiste à traiter les modules spécialisés comme de simples ajouts facultatifs placés en fin de script.

Ce n’est pas comme cela que je les aborde.

Un module spécialisé n’est pas là pour “rajouter un détail”.
Il sert à isoler une structure qui influence le bot de manière trop importante pour rester diffuse.

Autrement dit, un module spécialisé est utile quand un élément :

- influence directement la logique de décision du personnage
- influence le type de scènes que le bot génère
- influence sa manière de gérer le conflit, la pression, l’attachement, le devoir, la violence, la honte, la survie, le pouvoir ou la vulnérabilité
- continue à produire des conséquences sur la durée
- risque d’être mal géré si on le disperse entre plusieurs blocs relationnels ou généraux

Le module spécialisé n’est donc pas défini par son thème.
Il est défini par son **poids structurel**.

Un bot n’a pas besoin d’un module spécialisé parce qu’il “a une religion”, “sait se battre”, “a un travail” ou “possède une capacité”.

Il a besoin d’un module spécialisé si cette religion, ce combat, ce travail ou cette capacité gouvernent réellement le comportement du bot au point de mériter un traitement autonome.

---

# 2. On ne crée pas un module spécialisé à l’aveugle

Avant d’ouvrir un module spécialisé, je ne pars pas simplement d’une intuition isolée du type :
> “Ce sujet a l’air important, donc je vais lui faire un bloc.”

Je m’accorde avec un agent IA comme ChatGPT, Claude ou Gemini pour auditer le bot avec moi.

Le but n’est pas de lui laisser décider à ma place.
Le but est de lui faire examiner la structure du bot à partir du concept, du canon éventuel, du cadre, des moteurs de scène, des conflits, des biais d’archétypes et des risques de dérive du modèle.

Concrètement, je peux lui demander :

- si l’axe que j’envisage mérite un module autonome
- s’il est réellement central ou seulement secondaire
- s’il doit être traité dans un bloc existant au lieu d’ouvrir un module
- quels autres blocs il risque d’influencer
- s’il doit être placé avant ou après les blocs relationnels
- quels risques de fallback, de boucle ou d’écrasement il peut créer

Le module spécialisé n’est donc pas juste “une idée de bloc”.
C’est une structure auditée, hiérarchisée puis rédigée.

---

# 3. Quand un module spécialisé est nécessaire

Je ne crée pas de module spécialisé simplement parce qu’un sujet existe dans le lore ou dans le concept.

Je le crée quand ce sujet remplit au moins une partie de ces fonctions.

## A. Il gouverne les décisions plus fortement qu’un bloc général

Exemples :
- un personnage dont la logique de commandement structure la plupart des décisions
- un personnage dont le rapport à la foi, au rituel ou au tabou filtre presque toutes les interactions
- un personnage dont la logique de survie ou d’enquête façonne plus fortement les scènes que la romance ou l’attachement
- un personnage dont la fonction politique gouverne la manière de parler, négocier, menacer, céder, protéger ou sacrifier
- un personnage dont une capacité, une technique ou un système de combat détermine son rapport au risque, à la violence, au corps, à la stratégie ou au contrôle

Si un axe de ce type gouverne plus fortement le comportement que les blocs relationnels, il mérite souvent un module autonome.

## B. Il génère lui-même des scènes

Un module spécialisé est souvent nécessaire quand il constitue un moteur de scène récurrent.

Exemples :
- un réseau criminel qui génère des visites, des dettes, des menaces, des négociations, des sanctions
- une structure militaire qui génère des ordres, des départs, des rapports de force, des fautes, des punitions, des dilemmes de loyauté
- une carrière publique qui génère surveillance, rumeurs, image à maintenir, opportunités, contraintes médiatiques
- une logique de survie qui génère déplacements, rationnement, risques, fatigue, blessures, choix urgents
- une capacité ou un système technique qui génère entraînement, contrôle, accidents, dissimulation, dépendance, usage tactique, coût physique ou surveillance

Si un système alimente régulièrement le RP en mouvement, il ne doit pas rester une note secondaire perdue dans un autre bloc.

## C. Il modifie fortement le conflit, l’attachement ou la vulnérabilité

Parfois, le module spécialisé ne produit pas directement les scènes, mais il transforme profondément la manière dont le personnage gère :

- le conflit
- la confiance
- l’intimité
- la honte
- la dépendance
- la peur
- l’autorité
- la culpabilité
- la protection
- la vulnérabilité

Exemples :
- un passé sectaire qui transforme le rapport à l’obéissance, au doute, au secret ou au contact physique
- une structure de handicap ou de douleur chronique qui modifie le rythme, l’irritabilité, la fatigue, la dépendance, l’intimité ou le conflit
- une logique de parentification ou d’autorité domestique qui transforme la manière de protéger, punir, céder ou demander de l’aide
- une capacité dangereuse qui modifie la peur de blesser, le besoin de contrôle, la distance physique, la honte, la violence, la fatigue ou la dépendance

## D. Il a besoin de continuité propre

Un module spécialisé est souvent utile quand un axe ne doit pas seulement exister, mais **continuer d’exister** une fois introduit en RP.

Exemples :
- les obligations politiques ne doivent pas disparaître entre deux scènes
- un danger criminel ne doit pas s’évaporer après une seule conversation
- une grossesse, une dette, une mission, une blessure, une disgrâce publique ou une enquête ne doivent pas être traitées comme un simple décor
- une capacité instable, un coût d’utilisation, une dette magique, une blessure de combat, une surveillance liée à un pouvoir ou une technique en cours d’apprentissage ne doivent pas être oubliés après une seule scène

Si le système a des conséquences qui doivent survivre à la scène où il apparaît, un module autonome aide à protéger cette continuité.

---

# 4. Quand un module spécialisé n’est pas nécessaire

L’erreur inverse consiste à créer des modules pour tout.

Ce n’est pas souhaitable non plus.

Je n’ajoute pas de module spécialisé si l’élément :

- n’influence presque jamais les décisions du personnage
- n’a pas de conséquences propres sur les scènes
- peut être couvert proprement dans `[FOUNDATION]`, `[CORE IDENTITY]`, `[SETTING]`, `[WORLD ANCHORS]`, `[CONFLICT]`, `[RELATIONAL MODEL]` ou un autre bloc existant
- relève surtout du lore, de l’esthétique ou de l’habillage
- ne change pas réellement la manière dont le bot se comporte en RP

### Exemples de cas où je n’ouvrirais pas forcément un module
- un personnage a appris à se battre, mais le combat n’influence ni ses scènes, ni sa posture, ni ses décisions
- un personnage a une religion, mais elle n’a pas de rôle actif dans son comportement ou dans le cadre du RP
- un personnage a un statut social, mais ce statut est déjà correctement couvert dans `[SETTING]` ou `[WORLD ANCHORS]`
- un personnage a un petit détail de routine qui peut être intégré à `[ENVIRONMENT / HOME / DOMESTIC LIFE]`
- un personnage possède une capacité ou une technique, mais celle-ci n’a ni coût, ni logique d’usage, ni impact réel sur les décisions, les scènes ou le conflit

Un module spécialisé ne doit pas servir de refuge pour tous les éléments “intéressants”.
Il doit servir à isoler les éléments **structurellement actifs**.

---

# 5. Les grandes questions à poser avant d’ouvrir un module

Avant de créer un module spécialisé, j’essaie de répondre à cinq questions avec l’aide d’un agent IA.

## 1) Est-ce que cet axe change réellement le comportement du bot ?
Pas seulement ce qu’il “est”.
Ce qu’il **fait**.

## 2) Est-ce que cet axe génère ou transforme des scènes de manière récurrente ?
S’il ne change rien au mouvement du RP, il n’a peut-être pas besoin d’un bloc autonome.

## 3) Est-ce que cet axe a ses propres conséquences à long terme ?
S’il doit rester actif après sa première apparition, il mérite peut-être une vraie place.

## 4) Est-ce que cet axe risque d’être mal géré s’il est dispersé dans plusieurs blocs ?
Si oui, un module dédié peut servir à centraliser sa logique.

## 5) Est-ce que cet axe est plus structurant que certains blocs relationnels du script ?
Si oui, il faut non seulement créer le module, mais aussi réfléchir à sa **priorité**.

À ce stade, l’IA peut m’aider à auditer la réponse à ces questions et à proposer :
- module autonome
- simple intégration à un bloc existant
- module à fusionner avec un autre
- module à séparer en plusieurs blocs distincts
- module à placer haut ou bas dans la hiérarchie

---

# 6. Un module spécialisé peut être central dans la hiérarchie du script

C’est un point important.

Un module spécialisé n’est pas condamné à être placé “plus bas” que les blocs relationnels, romantiques ou domestiques.

Si un axe spécialisé gouverne plus fortement :
- les décisions
- la génération de scènes
- la gestion du conflit
- la continuité
- le type de pression qui définit le bot

alors il peut être placé **avant** les blocs relationnels.

Autrement dit, l’ordre du script ne doit pas refléter une préférence abstraite pour le relationnel.
Il doit refléter la **véritable hiérarchie comportementale** du bot.

## Exemple simple
Un personnage peut avoir :
- une relation importante avec l’utilisateur
- mais être d’abord structuré par son rôle de commandement, sa fonction politique, sa logique de mission, sa capacité, son système de combat ou son rapport au devoir

Dans ce cas, le module sur le commandement, la politique, la mission, la capacité ou le combat peut devoir apparaître avant `[RELATIONAL MODEL]`, `[ATTACHMENT]` ou `[ROMANCE]`.

---

# 7. Comment décider si un module doit être haut ou bas dans le script

Je regarde principalement quatre critères avec l’aide d’un agent IA.

## A. Le module gouverne-t-il les décisions quotidiennes du personnage ?
Si oui, il doit souvent être haut.

## B. Le module détermine-t-il la majorité des scènes ou des tensions ?
Si oui, il doit souvent être haut.

## C. Le module modifie-t-il fortement la manière dont les autres blocs doivent être lus ?
Exemple :
- un module “hiérarchie militaire” peut modifier la manière de lire le conflit, la tendresse, l’obéissance, la colère, la protection, la distance
- un module “politique / pouvoir” peut modifier la lecture de la confiance, de la romance, du secret, de la vulnérabilité et des enjeux de scène
- un module “capacité dangereuse / technique / combat” peut modifier la lecture du corps, du risque, de la retenue, de la violence, du contrôle, de l’intimité ou du momentum

Plus un module recolore le reste du script, plus il doit être traité tôt.

## D. Le module est-il seulement contextuel ou vraiment structurant ?
S’il n’intervient qu’occasionnellement, il peut rester plus bas.
S’il définit le bot, il doit remonter.

Là encore, je ne fais pas ça seul “au ressenti”.
Je peux demander à l’IA :
- quels blocs sont réellement centraux
- quels blocs sont secondaires
- si le module devrait remonter au-dessus du relationnel
- si sa priorité actuelle est trop haute ou trop basse
- s’il faut le fusionner, le séparer ou le réécrire

---

# 8. Les modules de combat, de capacité, de technique ou de fonctionnement

Ce type de module mérite une section à part, parce qu’il est facile de le réduire à une fiche de pouvoir ou à une liste de capacités, ce qui n’est pas le but.

Un module de combat, de capacité, de technique ou de fonctionnement ne sert pas à lister tout ce que le personnage sait faire.
Il sert à décrire comment un système de combat, une technique, un pouvoir, une mécanique ou une capacité **agit sur le bot en RP**.

Cela peut concerner :
- un style de combat
- une doctrine martiale
- une capacité surnaturelle
- une technique spécifique
- une mécanique de pouvoir
- un système d’invocation, de transformation, de possession, de mutation, de lien, de soin, de contrôle, de perception ou de destruction
- une arme, un équipement ou un système technologique si cela structure réellement le comportement du personnage

## Ce qu’un tel module doit couvrir

### A. Ce que c’est
- de quel système il s’agit
- ce qu’il permet
- ce qu’il exige
- ce qui le limite

### B. Comment il fonctionne
- conditions d’activation
- logique d’usage
- contraintes
- seuils
- dépendances
- entraînement, maîtrise ou difficulté
- conséquences d’un mauvais usage
- coût physique, mental, émotionnel, magique, social ou stratégique si pertinent

### C. Comment il influence le comportement
- est-ce que le personnage évite de s’en servir
- est-ce qu’il y recourt trop facilement
- est-ce qu’il s’en sert pour intimider, protéger, fuir, surveiller, punir, se défendre, se contrôler
- est-ce que cette capacité le rend plus prudent, plus agressif, plus honteux, plus distant, plus secret, plus fatigué, plus dépendant, plus protecteur

### D. Comment il influence les scènes
- ce module génère-t-il de l’entraînement, de la surveillance, des blessures, des accidents, des ratés, des rituels, de la maintenance, des contraintes de déplacement, des missions, des secrets, des réparations, des soins, des stratégies, des interdictions

### E. Comment il influence les autres blocs
- le conflit
- le momentum
- la continuité
- la relation à l’utilisateur
- la proximité physique
- la peur
- le contrôle
- la violence
- la fatigue
- l’image du corps
- la honte
- la dépendance
- la protection

Un module de capacité ou de combat ne doit donc pas être écrit comme une fiche technique isolée.
Il doit être relié au comportement, au moteur de scène et aux autres blocs du script.

---

# 9. Ce qu’un module spécialisé doit contenir

Un module spécialisé ne doit pas être une petite note vague du type :
> “Le personnage est très politique.”  
> “Le personnage a un fort instinct de survie.”  
> “Le personnage a une relation compliquée avec la religion.”  
> “Le personnage a une capacité très puissante.”

Ça ne suffit pas.

Un module utile doit décrire **comment ce système agit sur le bot**.

En pratique, j’essaie d’y faire apparaître plusieurs choses.

## A. La fonction du module
De quoi s’agit-il exactement ?

Exemples :
- structure de commandement
- logique de survie
- système de dette criminelle
- pratique religieuse et tabous
- gestion de la célébrité
- structure de parentalité
- système de magie lié au corps
- mission en cours
- logique d’enquête
- politique de cour
- carrière médicale
- dette financière et dépendance
- technique de combat ou pouvoir instable
- capacité liée à la douleur, au contrôle, au soin, à la transformation ou à la destruction

## B. Son effet sur les décisions
Qu’est-ce que ce module pousse le personnage à faire, éviter, tolérer, prioriser, dissimuler, sacrifier ou surveiller ?

## C. Son effet sur les scènes
Quelles scènes ce module génère-t-il naturellement ?
Quelles tensions, obligations, risques, usages, ratés, entraînements, stratégies ou rituels apporte-t-il ?

## D. Son effet sur le conflit, l’attachement ou la vulnérabilité si c’est pertinent
Le module modifie-t-il :
- la colère
- la honte
- la punition
- la confiance
- la dépendance
- le besoin de contrôle
- la peur de perdre
- la tendresse
- le secret
- le sacrifice
- le rapport au corps
- le rapport à la violence
- la capacité à supporter la proximité ou l’imprévu

## E. Sa continuité
Qu’est-ce qui doit continuer à exister une fois le module activé en RP ?
Qu’est-ce qui ne doit pas disparaître entre deux scènes ?

---

# 10. Un module spécialisé n’est presque jamais autosuffisant

C’est un point essentiel.

Ajouter un module spécialisé ne consiste pas juste à écrire un bloc de plus dans le script et à passer à autre chose.

Un module isolé, laissé seul dans son coin, est souvent peu efficace.

Si le module est réellement important, il doit être **relié aux autres blocs qu’il influence**.
Sinon, il risque :
- de ne pas ressortir en scène
- d’être écrasé par les blocs relationnels
- d’être oublié par le modèle
- de rester purement décoratif

Quand j’ajoute un module spécialisé, je vérifie donc toujours quels autres blocs doivent être ajustés.

Par exemple :
- un module de combat peut devoir rejaillir sur `[CONFLICT]`, `[MOMENTUM]`, `[ANTI-LOOP]`, `[PLAYER PROTECTION]` et parfois `[INTIMACY]`
- un module de politique peut devoir rejaillir sur `[SCENE ENGINE]`, `[WORLD ANCHORS]`, `[CONFLICT]`, `[CONTINUITY ANCHORS]` et `[ANTI-GENERIC]`
- un module de religion peut devoir rejaillir sur `[CORE IDENTITY]`, `[RELATIONAL MODEL]`, `[CONFLICT]`, `[INTIMACY]`, `[PREGNANCY]` ou `[PLAYER PROTECTION]`
- un module de capacité dangereuse peut devoir rejaillir sur `[CONFLICT]`, `[MOMENTUM]`, `[CONTINUITY ANCHORS]`, `[ANTI-LOOP]`, `[FAILSAFE]` et parfois sur la dynamique physique avec l’utilisateur

L’existence d’un module peut donc impliquer :
- de modifier la formulation d’autres blocs
- de rappeler certaines conséquences dans plusieurs endroits du script
- de créer une redondance volontaire entre le module et les blocs qu’il influence

---

# 11. La redondance peut être nécessaire

Je n’essaie pas forcément de faire exister un module spécialisé dans un seul bloc parfaitement isolé.

Au contraire, si un module est réellement structurant, il peut être utile que certaines de ses conséquences soient rappelées ailleurs dans le script.

Cette redondance n’est pas là pour remplir.
Elle sert à empêcher le module de rester théorique ou d’être écrasé par des comportements plus génériques.

Exemple :
- un module “combat / violence” peut exister comme bloc autonome
- mais son effet sur la retenue, la brutalité, la protection, la lecture du danger ou la proximité physique peut aussi apparaître dans `[CONFLICT]`, `[MOMENTUM]`, `[RELATIONAL MODEL]` ou `[INTIMACY]`

Exemple :
- un module “politique / pouvoir” peut exister comme bloc autonome
- mais ses conséquences sur la confiance, le secret, la négociation, le contrôle de l’image ou le sacrifice peuvent aussi réapparaître dans `[SCENE ENGINE]`, `[CONFLICT]`, `[CONTINUITY ANCHORS]` ou `[FAILSAFE]`

Exemple :
- un module “capacité dangereuse” peut exister comme bloc autonome
- mais ses conséquences sur la fatigue, la peur du contact, la destruction, le contrôle, la honte ou les accidents peuvent aussi apparaître dans `[CORE IDENTITY]`, `[CONFLICT]`, `[MOMENTUM]`, `[ANTI-LOOP]` ou `[PLAYER PROTECTION]`

Le but n’est donc pas seulement :
> “ouvrir un module”

Le but est aussi :
> “faire circuler ses conséquences dans les autres parties du script quand c’est nécessaire.”

---

# 12. Les erreurs fréquentes dans l’écriture d’un module spécialisé

## Erreur 1 — écrire un mini résumé de lore
Un module n’est pas une fiche wiki.
Le problème n’est pas de rappeler tout l’historique d’un sujet.
Le problème est d’expliquer **comment il agit sur le bot en jeu**.

## Erreur 2 — écrire quelque chose de trop abstrait
“Il a un rapport compliqué au pouvoir” n’aide pas assez.

Il faut expliquer :
- comment cela se voit
- ce que cela change
- ce que cela produit en scène
- ce que cela bloque ou accélère

## Erreur 3 — ouvrir un module alors que le contenu rentre déjà dans un bloc existant
Si l’élément peut être traité proprement dans `[FOUNDATION]`, `[CORE IDENTITY]`, `[SETTING]` ou `[CONFLICT]`, il n’a pas forcément besoin d’un module autonome.

## Erreur 4 — créer un module sans continuité
Si le module n’a aucune conséquence après son introduction, il risque de devenir décoratif.

## Erreur 5 — ne pas relier le module au reste du script
Un module spécialisé ne doit pas flotter seul.
Il doit rester cohérent avec :
- le moteur de scène
- le conflit
- la relation à l’utilisateur
- la continuité
- l’anti-loop
- les risques de dérive générique

## Erreur 6 — figer trop tôt sa hiérarchie
La place d’un module dans le script n’est pas forcément définitive au moment où tu l’écris.

Il peut arriver qu’après test, tu constates que :
- le module ne ressort pas assez
- il ressort trop tard
- il est écrasé par un autre bloc
- il monopolise trop le bot
- il devrait être fusionné avec un autre module
- il devrait être scindé
- ou il devrait simplement être déplacé plus haut ou plus bas

---

# 13. Exemples de familles de modules spécialisés

Cette liste n’est pas une taxonomie obligatoire.
Elle sert simplement à montrer les types de structures qui peuvent mériter un module autonome.

## Combat / violence / mission
- style de combat
- discipline martiale
- rapport à la violence
- commandement en mission
- survie en terrain hostile
- rapport au corps blessé
- logique de protection armée
- technique de combat
- usage d’armes ou d’équipement spécialisé
- capacité tactique ou destructive
- doctrine de retenue, de neutralisation ou de mise à mort

## Politique / pouvoir / hiérarchie
- gouvernance
- diplomatie
- négociation
- stratégie de cour
- réputation institutionnelle
- pression de succession
- commandement
- autorité publique

## Religion / idéologie / rituel
- pratique religieuse
- tabous
- culpabilité religieuse
- rituels quotidiens
- mission sacrée
- vision morale du monde
- obéissance idéologique

## Criminalité / clandestinité / coercition
- réseau criminel
- dette
- chantage
- dissimulation
- hiérarchie mafieuse
- logique de fuite
- gestion de la menace

## Profession / devoir / institution
- médecine
- recherche
- enseignement
- police
- armée
- administration
- service public
- travail artisanal ou commercial si cela structure fortement la vie du bot

## Famille / domesticité / autorité privée
- parentalité
- tutelle
- autorité domestique
- rôle d’aîné
- famille recomposée
- charge mentale
- devoir filial

## Corps / santé / vulnérabilité
- maladie chronique
- handicap
- douleur
- fertilité
- grossesse
- dépendance physique
- rapport au soin
- rapport à l’épuisement

## Surnaturel / espèce / magie / capacité
- instincts non humains
- transformations
- magie liée au corps
- lien surnaturel
- malédiction
- dette magique
- logique de faim ou de pulsion
- contraintes rituelles ou métaphysiques
- pouvoir instable
- technique héréditaire
- système de possession, de soin, de perception, de destruction ou de contrôle
- coût d’usage d’une capacité
- logique de corruption, surcharge ou perte de contrôle

---

# 14. Comment utiliser ChatGPT, Claude ou Gemini pour construire un module

L’IA peut être utile ici, mais pas comme autorité aveugle.

Je l’utilise plutôt comme **agent de travail** et comme **outil d’audit structurel**.

Je peux m’appuyer sur elle à plusieurs moments.

## A. Avant d’ouvrir le module
Pour demander :
- si le module est réellement nécessaire
- s’il mérite d’être autonome
- quels blocs il risque d’influencer
- s’il est central ou secondaire
- s’il est plus structurant que le relationnel

## B. Pour décider où le placer
Je peux lui demander :
- si le module doit apparaître avant ou après les blocs relationnels
- s’il devrait être rapproché de `[CORE IDENTITY]`, `[FOUNDATION]`, `[SCENE ENGINE]` ou `[WORLD ANCHORS]`
- s’il devrait être fusionné avec un autre module
- s’il devrait être scindé en deux modules distincts
- si sa hiérarchie actuelle correspond réellement aux moteurs du bot

## C. Pour le rédiger
Une fois la logique validée, je peux demander à l’IA de rédiger le module :
- à partir de mes instructions
- à partir du concept ou du canon
- à partir des autres blocs déjà écrits
- à partir des priorités comportementales déjà définies

L’important est que la rédaction vienne **après audit** et **selon validation**, pas comme un remplissage automatique de cases.

## D. Pour l’intégrer au reste du script
Je peux lui demander :
- quels blocs doivent être réécrits si ce module existe
- quelles conséquences doivent être répétées dans `[CONFLICT]`, `[MOMENTUM]`, `[CONTINUITY ANCHORS]`, `[ANTI-LOOP]`, etc.
- si le module est encore trop isolé
- si certaines redondances seraient utiles

## E. Après test et debug
Je peux revenir vers l’IA avec les résultats de test pour lui demander :
- si le module est mal placé
- s’il ne ressort pas assez
- s’il prend trop de place
- s’il faudrait le remonter, le descendre, le fusionner ou le scinder
- si son articulation avec les autres blocs est trop faible

---

# 15. Comment tester si un module spécialisé est bien construit

Un module spécialisé est utile s’il produit un effet visible dans le comportement du bot.

Après l’écriture, je le teste donc comme le reste du script.

Je vérifie notamment :

## A. Est-ce que le module influence vraiment les réponses du bot ?
Ou bien est-ce qu’il disparaît dès qu’on entre en scène ?

## B. Est-ce que le module produit des conséquences visibles sur :
- la prise de décision
- les scènes
- le conflit
- la continuité
- la manière de parler, d’éviter, de céder, de protéger, de mentir, de punir ou de demander

## C. Est-ce que le module reste actif sur la durée ?
Ou bien est-ce qu’il s’effondre après une ou deux scènes ?

## D. Est-ce que le module résiste au retour des archétypes génériques ?
Par exemple :
- la politique disparaît et le bot redevient juste “amant possessif”
- la logique de mission disparaît et le bot redevient juste “slow burn boudeur”
- la structure criminelle disparaît et le bot redevient juste “bad boy protecteur”
- la religion disparaît et le bot redevient juste “personnage torturé”
- la capacité ou la logique de combat disparaît et le bot redevient juste “guerrier froid” ou “protecteur dangereux” sans vraie structure

## E. Est-ce que le module interfère correctement avec les autres blocs ?
Par exemple :
- la logique de commandement influence-t-elle vraiment le conflit ?
- la survie influence-t-elle vraiment le momentum ?
- la structure de dette influence-t-elle vraiment la dépendance, la peur ou la négociation ?
- la douleur chronique influence-t-elle vraiment le rythme, l’irritabilité, la vulnérabilité ou l’intimité ?
- la capacité ou le système de combat influence-t-il vraiment le risque, la retenue, la violence, la fatigue, la stratégie ou la proximité physique ?

Si la réponse est non, le problème n’est pas forcément “il faut plus de lore”.
Le problème est souvent que le module n’a pas été écrit comme une structure comportementale active, ou qu’il est mal relié au reste du script.

---

# 16. Le testing / debugging peut obliger à changer l’ordre ou la hiérarchie du module

C’est un point important.

La hiérarchie d’un module spécialisé n’est pas forcément figée au moment où tu le crées.

Après test, tu peux découvrir que :
- le module n’est pas assez visible
- il arrive trop tard dans la logique du script
- il est écrasé par les blocs relationnels
- il n’influence pas assez le conflit ou le momentum
- il est trop isolé
- il est trop large ou trop flou
- il devrait être fusionné avec un autre module
- il devrait être scindé
- il devrait être déplacé plus haut ou plus bas

Dans ce cas, je n’essaie pas forcément de “forcer” la première version.
Je ré-audite la structure avec un agent IA.

Je peux lui demander :
- si la hiérarchie actuelle est mauvaise
- si le module devrait remonter avant le relationnel
- si le module devrait descendre
- si le problème vient du placement, du contenu, ou du manque de liens avec les autres blocs
- quels blocs doivent être réécrits pour mieux le soutenir

Autrement dit, le testing / debugging ne sert pas seulement à corriger la rédaction d’un module.
Il peut aussi servir à corriger :
- son niveau de priorité
- sa place dans le script
- son degré d’autonomie
- son articulation avec les autres blocs

---

# 17. En pratique : comment je décide

Quand j’hésite, je reviens à une question simple :

## “Si j’enlève ce module, est-ce que le bot perd une partie de sa vraie structure ?”

Si la réponse est non, le module n’est peut-être pas nécessaire.

Si la réponse est oui, la question suivante devient :

## “Est-ce que cette structure mérite d’être autonome, et si oui, à quel niveau de priorité ?”

À partir de là, je regarde :
- si elle gouverne les décisions
- si elle génère les scènes
- si elle transforme le conflit ou la relation
- si elle a besoin de continuité
- si elle résiste mal quand elle reste dispersée dans plusieurs blocs
- si elle doit être auditée, hiérarchisée puis rédigée avec l’aide d’un agent IA
- si elle doit ensuite être reliée explicitement aux autres blocs du script

Si plusieurs réponses sont oui, il y a de bonnes chances qu’un module spécialisé soit utile.

---

# 18. Résumé

Un module spécialisé n’existe pas pour enrichir artificiellement un script.

Il existe pour isoler une structure qui :
- gouverne réellement le bot
- mérite une continuité propre
- génère des scènes ou transforme fortement leur logique
- modifie le conflit, la relation, la vulnérabilité, le corps, la pression ou la progression
- serait mal gérée si elle restait implicite ou dispersée

Je ne recommande pas de construire ce type de module à l’aveugle.

En pratique, je m’appuie sur un agent IA comme ChatGPT, Claude ou Gemini pour :
- auditer si le module doit exister
- déterminer s’il doit être autonome ou non
- proposer sa hiérarchie dans le script
- rédiger le module après validation et selon mes instructions
- identifier les autres blocs qu’il faut modifier
- réviser sa place, sa forme ou sa priorité après test et debug si nécessaire

Le point important n’est donc pas :
> “Qu’est-ce que je pourrais ajouter au script ?”

Le point important est plutôt :
> “Quelles structures gouvernent réellement ce bot, lesquelles ont besoin d’un espace propre pour rester actives en RP, et comment les intégrer au reste du script sans les laisser flotter seules ?”