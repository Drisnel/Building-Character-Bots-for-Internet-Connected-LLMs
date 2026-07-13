# Comment protéger l’agence du joueur dans les bots de roleplay

Après avoir créé et testé un grand nombre de bots de roleplay, j’ai fini par comprendre que la protection du joueur n’est pas un détail mineur.

C’est un élément structurel.

Un bot peut avoir un script solide, une bonne introduction et un bon démarrage, et malgré tout devenir désagréable à jouer s’il se met régulièrement à prendre la place du joueur.

Les échecs les plus fréquents ne sont pas subtils.

Le bot commence à écrire les dialogues du joueur.
Le bot commence à narrer depuis le point de vue du joueur.
Le bot commence à décider des pensées, des émotions, des intentions, du désir ou du consentement du joueur comme s’il s’agissait de faits déjà établis.

À partir de ce moment-là, le bot n’incarne plus seulement le personnage.

Il commence aussi à incarner partiellement le joueur.

Pour certains joueurs, c’est immédiatement rédhibitoire.

Pour d’autres, le problème est plus spécifique.

Ils peuvent accepter un roleplay guidé.
Ils peuvent accepter une progression physique de la scène.
Ils peuvent même vouloir que le bot porte le rythme dans des scènes de combat, d’intimité ou d’action.

Ce qu’ils ne veulent pas, c’est que le bot remplace leur agence intérieure.

Cette distinction est importante.

La protection du joueur ne consiste pas seulement à éviter une mauvaise écriture.

Elle consiste à définir ce que le bot a ou n’a pas le droit de contrôler.

Ce n’est pas la seule méthode valable.

C’est simplement le cadre qui me donne actuellement les résultats les plus stables lorsque je construis des bots de roleplay pour des LLM entraînés sur de vastes corpus de données issus du Web.

---

# 1. La protection du joueur est un choix de design, pas une règle unique

L’une des erreurs les plus faciles à faire consiste à traiter la protection du joueur comme un module universel unique.

En pratique, ce n’est pas le cas.

Différents créateurs veulent différents niveaux de contrôle.

Certains veulent une agence maximale du joueur et un guidage minimal du bot.

D’autres veulent un roleplay guidé dans lequel le bot peut porter l’action, le rythme et la continuité physique sans pour autant prendre le contrôle de l’état intérieur du joueur.

Les deux approches sont valables.

L’important est de choisir consciemment.

Si le module est trop permissif, le bot commence à prendre la place du joueur.

S’il est trop rigide, le bot devient difficile à jouer, surtout dans les scènes où le joueur utilise continuer, veut que le bot porte le rythme, ou ne souhaite pas répondre à chaque micro-action ligne par ligne.

À cause de cela, je ne pense pas en termes d’un bloc universel de protection du joueur.

Je pense en termes de style de protection.

Au minimum, je distingue :

- la protection stricte du joueur
- la protection guidée du joueur

La différence n’est pas de savoir si le bot protège le joueur.

La différence porte sur la quantité de contrôle de scène que le bot est autorisé à porter tout en le faisant.

---

# 2. Le vrai mode d’échec

Le problème n’est pas simplement : « le bot ne doit pas écrire les pensées du joueur ».

Le vrai mode d’échec est plus large.

Le bot commence à faire disparaître la frontière entre personnage et joueur.

Exemples fréquents :

- écrire les dialogues du joueur
- écrire à la première personne comme le joueur
- narrer depuis le point de vue du joueur
- décider de ce que pense le joueur
- décider de ce que ressent le joueur
- décider de ce que veut le joueur
- décider de ce que le joueur a l’intention de faire
- décider de ce à quoi le joueur consent
- décider de ce que le joueur apprécie
- traiter le silence comme un accord émotionnel
- transformer une réaction visible en certitude intérieure
- parler comme si l’état intérieur du joueur était déjà connu

À partir de là, le bot n’interprète plus les réponses du joueur.

Il les remplace.

La forme exacte varie, mais le problème de fond reste le même :

le bot cesse de traiter le joueur comme un participant distinct dont l’agence intérieure doit être protégée.

---

# 3. La frontière centrale : interne vs externe

Pour moi, la frontière la plus utile en matière de protection du joueur n’est pas : « le bot n’a jamais le droit de faire quoi que ce soit au joueur ».

Cette règle est trop rigide pour beaucoup de styles de roleplay.

La frontière la plus utile est la suivante :

interne = protégé
externe = négociable

Cela signifie que le bot ne doit pas définir comme un fait l’état intérieur du joueur.

Il ne doit pas décider :

- des pensées
- des émotions
- des intentions
- du désir
- du consentement
- du plaisir
- de la volonté
- des conclusions privées
- des motivations non exprimées

sauf si le joueur a déjà rendu ces éléments explicites.

La gestion externe de la scène est différente.

Selon le style de protection choisi, le bot peut être autorisé à décrire :

- des réactions visibles
- le langage corporel
- des réponses physiques contextuelles
- l’effet physique des actions sur le corps du joueur
- le déplacement dans la scène
- la continuité de la scène sans attendre une micro-réponse à chaque ligne

C’est la vraie distinction qui m’importe.

Le bot peut avoir le droit de faire avancer la scène.

Il ne peut pas remplacer l’état intérieur du joueur.

---

# 4. Pourquoi cela se complique en pratique

En théorie, la protection du joueur paraît simple.

En pratique, cela devient vite plus compliqué.

Pourquoi ?

Parce que le roleplay n’est pas seulement une conversation.

Il existe des scènes où le joueur attend du bot qu’il porte le rythme.

Exemples :

- les combats
- les poursuites
- les scènes de sauvetage
- les scènes médicales
- les conflits physiques
- les scènes d’intimité à forte intensité
- les scènes où le joueur utilise continuer au lieu de répondre ligne par ligne

Dans ce type de scène, un bot qui refuse de faire quoi que ce soit impliquant le joueur peut devenir frustrant à jouer.

Il bloque.
Il pose trop de questions.
Il attend une validation toutes les quelques lignes.
Il transforme les scènes d’action en boucles de négociation.
Il transforme l’intimité en confirmations verbales sans fin.
Il transforme les combats en paralysie tour par tour.

C’est pour cela que je ne pense pas que « le bot ne doit jamais déplacer le joueur » soit une bonne règle universelle.

Parfois, le créateur veut ce niveau de rigidité.

Parfois, non.

L’important est d’être explicite sur la version de protection utilisée par le bot.

---

# 5. La protection stricte du joueur

La protection stricte du joueur est le modèle le plus restrictif.

Elle est pensée pour les créateurs qui veulent un contrôle maximal du joueur et un guidage minimal du bot.

Dans ce modèle, le bot n’a évidemment pas le droit d’écrire l’état intérieur du joueur.

Mais il évite aussi de porter une trop grande partie de la participation physique du joueur.

En général, cela signifie :

- éviter un guidage physique prolongé sans réponse du joueur
- éviter de déplacer le joueur dans la scène, sauf si la scène exige un effet immédiat de cause à effet
- éviter de traiter le silence comme un accord
- éviter d’escalader une scène physique ou intime sans participation claire du joueur
- laisser davantage d’espace au joueur pour répondre avant que la scène n’avance

Ce style est utile quand le créateur veut un contrôle très fort du joueur et accepte un rythme plus lent en échange.

Il est aussi utile pour les joueurs qui détestent être physiquement guidés par le bot.

Sa faiblesse est évidente.

S’il est appliqué de façon trop rigide, il peut rendre le bot hésitant, fragmenté et difficile à jouer dans les scènes très orientées action.

---

# 6. La protection guidée du joueur

La protection guidée du joueur est le modèle le plus souple.

Elle protège toujours l’état intérieur du joueur.

Elle interdit toujours au bot de prendre le contrôle des dialogues du joueur, de son point de vue, de ses pensées, de ses émotions, de ses intentions ou de son désir comme s’il s’agissait de faits établis.

Mais elle autorise le bot à porter davantage de la scène sur le plan externe.

Cela peut inclure :

- les réactions visibles
- les réponses physiques contextuelles
- le déplacement physique dans la scène
- l’effet physique des actions du bot sur le corps du joueur
- la progression guidée de la scène
- la continuité sans pause à chaque micro-réponse

Ce modèle est utile pour les créateurs qui veulent que le bot maintienne le rythme de la scène.

Il fonctionne particulièrement bien pour :

- les scènes d’action
- les combats
- les scènes physiquement intenses
- les scènes intimes où le joueur accepte un rythme guidé
- les styles de jeu reposant sur le bouton continuer

Son risque est différent de celui de la version stricte.

Si la frontière est mal écrite, la protection guidée peut glisser vers un bot qui prend le contrôle de l’état intérieur du joueur sous prétexte de « continuité de scène ».

C’est pour cela que la frontière entre interne et externe doit rester explicite.

---

# 7. Le consentement fait partie de la protection du joueur, mais le coder trop rigidement peut figer le bot

Le consentement est l’un des points les plus faciles à mal gérer dans un module de protection du joueur.

Si le module est trop permissif, le bot peut commencer à supposer le consentement, l’attirance, le plaisir ou la volonté du joueur sans que celui-ci les ait jamais exprimés.

S’il est trop rigide, le bot peut commencer à demander une confirmation verbale explicite avant chaque escalade.

Cela crée un autre problème.

La scène se fige.

Le bot cesse de progresser.
Le bouton continuer devient inutile.
Chaque scène intime ou physique se transforme en boucle de confirmation répétitive.

Je ne pense pas que la solution soit de faire comme si le consentement n’avait aucune importance.

Je pense que la solution consiste à écrire le module autour de la certitude intérieure, et non autour d’une validation verbale constante.

Le bot ne doit pas décider du consentement du joueur comme d’un fait si le joueur ne l’a pas exprimé.

Cela ne signifie pas automatiquement que le bot doit arrêter chaque scène et exiger une confirmation explicite toutes les quelques lignes.

Cela signifie que le bot ne doit pas narrer la volonté, le plaisir ou l’acceptation du joueur comme une vérité intérieure déjà connue.

Le bot peut continuer la scène selon le style de protection choisi.

Il ne doit pas écraser l’état intérieur du joueur au passage.

---

# 8. Les effets externes ne sont pas la même chose que les faits internes

Cette distinction est suffisamment importante pour être formulée explicitement.

Ces phrases ne relèvent pas de la même catégorie :

Mauvais :
- tu en voulais plus
- tu as fondu contre lui
- tu étais désespéré d’en avoir davantage
- tu lui faisais totalement confiance
- tu avais besoin de lui
- tu l’as accueilli
- tu as cédé parce que tu voulais cela

Toutes ces phrases définissent comme un fait l’état intérieur du joueur.

À l’inverse, une écriture de scène guidée peut inclure des choses comme :

- la violence de l’impact coupe ton souffle
- sa main te tire d’un pas plus près
- le mouvement t’immobilise brièvement contre le mur
- la brusque traction te fait perdre l’équilibre
- la chaleur de son corps te bloque entre lui et la table

Ces phrases décrivent des effets externes de la scène.

Elles ne définissent pas automatiquement ce que le joueur pense ou veut à leur sujet.

Cette distinction est au cœur de la protection guidée du joueur.

Le bot peut décrire ce qui s’est produit.

Il ne peut pas décider de ce que le joueur ressent à propos de ce qui s’est produit.

---

# 9. Ce que je n’autorise jamais dans aucune version

Quel que soit le style de protection utilisé, certaines choses restent interdites.

Je n’autorise pas le bot à :

- écrire les dialogues du joueur
- écrire à la première personne comme le joueur
- narrer depuis le point de vue du joueur
- décider des pensées du joueur comme d’un fait
- décider des émotions du joueur comme d’un fait
- décider des intentions du joueur comme d’un fait
- décider des désirs du joueur comme d’un fait
- décider du consentement du joueur comme d’un fait si le joueur ne l’a pas exprimé

Ce sont les protections de base.

La différence entre la protection stricte et la protection guidée ne réside pas dans l’existence de ces règles.

La différence réside dans la quantité de contrôle externe de la scène que le bot est autorisé à porter autour d’elles.

---

# 10. Module recommandé : version stricte

Voici la version la plus stricte que j’utiliserais pour les créateurs qui veulent une agence maximale du joueur et un guidage minimal du bot.

[PLAYER PROTECTION — STRICT]
Never write {user}'s dialogue.
Never write in first person as {user}.
Never narrate from {user}'s POV.

Never define as fact:
- {user}'s thoughts
- {user}'s emotions
- {user}'s intentions
- {user}'s desires
- {user}'s consent
- {user}'s arousal,enjoyment,or willingness

Avoid:
- moving {user} through the scene without a user response
- extended physical guidance that removes {user}'s control of the scene
- treating silence as consent or agreement
- resolving physical escalation without room for {user} to answer

Allowed:
- visible reactions already shown by {user}
- body language already established by {user}
- immediate physical cause-and-effect from the environment or {char}'s action,as long as it does not replace {user}'s agency

The line is:
{char} may affect the scene.
{char} may not take over {user}.

external observation = limited.
internal narration = forbidden.

---

# 11. Module recommandé : version guidée

Voici la version que j’utiliserais pour les créateurs qui veulent un roleplay guidé tout en préservant l’agence intérieure du joueur.

[PLAYER PROTECTION — GUIDED]
Never write {user}'s dialogue.
Never write in first person as {user}.
Never narrate from {user}'s POV.

Never define as fact:
- {user}'s thoughts
- {user}'s emotions
- {user}'s intentions
- {user}'s desires
- {user}'s consent if {user} has not expressed it

Allowed:
- visible reactions
- body language
- contextual physical responses
- externally observable effects of the scene on {user}
- physical displacement of {user} within the scene
- guided scene progression
- scene continuity without pausing for micro-responses

The line is:
external = allowed.
internal = forbidden.

{char} does not know {user}'s inner state as fact.
{char} only knows what {user} says,does,or visibly shows.

---

# 12. Comment je choisis entre les deux

Je ne choisis pas entre protection stricte et protection guidée uniquement en fonction d’une préférence abstraite.

Je choisis en fonction du type de bot que je construis et du type de roleplay que je veux qu’il supporte.

Je suis plus susceptible de choisir une protection stricte lorsque :

- le bot est destiné à des joueurs qui veulent un très haut niveau de contrôle personnel
- le roleplay est lent, conversationnel ou émotionnellement prudent
- je ne veux pas que le bot guide physiquement le joueur de façon importante
- je préfère sacrifier un peu de vitesse plutôt que de risquer un débordement

Je suis plus susceptible de choisir une protection guidée lorsque :

- le bot doit porter le rythme de la scène
- le roleplay comprend des combats, de l’action, des sauvetages ou une forte physicalité
- le roleplay comprend des scènes intimes où le joueur accepte un rythme guidé
- le joueur utilise souvent continuer au lieu de répondre ligne par ligne
- je veux que le bot reste actif plutôt que trop hésitant

Aucune des deux versions n’est automatiquement meilleure.

Elles résolvent des problèmes différents.

---

# 13. Porter la scène ne signifie pas porter le joueur

Une erreur fréquente consiste à croire qu'un bot doit choisir entre deux extrêmes.

Soit il reste presque entièrement passif pour respecter l'agence du joueur.

Soit il prend progressivement le contrôle du joueur pour réussir à faire avancer la scène.

En pratique, ces deux idées sont indépendantes.

Un bot peut être très actif tout en respectant complètement l'agence du joueur.

Le personnage peut naturellement :

- prendre des initiatives
- proposer une activité
- changer de lieu
- modifier le rythme de la scène
- résoudre un problème pratique
- reprendre une conversation laissée en suspens
- introduire un nouvel objectif
- créer de nouvelles opportunités d'interaction
- faire évoluer l'environnement autour du joueur

Toutes ces actions font avancer le roleplay.

Aucune d'entre elles ne nécessite de décider ce que le joueur pense, ressent, veut ou choisit.

C'est une distinction importante.

Faire avancer la scène ne signifie pas faire avancer le joueur.

Le personnage porte sa propre partie de l'histoire.

Le joueur reste libre de décider comment il y répond.

À mes yeux, un bon bot ne devrait pas laisser au joueur toute la responsabilité du rythme.

Le personnage existe aussi pour créer du mouvement.

Il prend des décisions.

Il agit.

Il crée des occasions d'interaction.

Il entretient la continuité de la scène.

Tout cela est compatible avec une protection solide de l'agence du joueur.

Au fond, protéger l'agence du joueur ne signifie pas rendre le personnage passif.

Cela signifie simplement que le personnage agit en tant que personnage, sans jamais remplacer le joueur.

---

# 14. Erreurs fréquentes lorsqu'on écrit la protection du joueur

Quelques schémas d'échec fréquents :

- écrire un bloc de protection du joueur qui dit seulement « ne jamais écrire les pensées du joueur » et rien d'autre
- interdire la narration interne mais oublier d'interdire les dialogues du joueur et son point de vue
- rendre le bloc si strict que le bot devient incapable de faire avancer la scène
- croire qu'un personnage actif menace automatiquement l'agence du joueur
- rendre le bloc si permissif que « guidé » finit par signifier « le bot décide de tout pour le joueur »
- traiter une réaction physique visible comme si elle était équivalente à une certitude émotionnelle interne
- coder le consentement de façon si rigide que le bot exige une validation verbale toutes les quelques lignes
- ne pas distinguer l'effet externe de sa signification interne
- supposer qu'un seul style de protection convient à tous les bots

Le but n'est pas seulement d'éviter la pire violation possible.

Le but est de définir une frontière stable et jouable.

Le personnage doit pouvoir porter la scène.

Le joueur doit toujours porter son propre état intérieur.

C'est cette frontière qui permet au roleplay de rester à la fois dynamique et respectueux de l'agence du joueur.

---

# 15. Ma règle générale

Si je devais résumer tout ce cadre à un seul principe, ce serait celui-ci :

protéger l'état intérieur du joueur.

Décider consciemment de la quantité de contrôle externe de scène que le bot est autorisé à porter.

C'est le véritable choix de design.

Pas la question de savoir si la protection du joueur est importante.

Elle l'est.

Le véritable choix consiste à définir jusqu'où le personnage peut porter la scène sans jamais prendre la place du joueur.

Le personnage peut créer du mouvement.

Il peut prendre des initiatives.

Il peut modifier le rythme.

Il peut influencer le déroulement de la scène.

Il ne peut pas décider à la place du joueur de ce qu'il pense, ressent, veut ou choisit.

C'est cette frontière qui détermine le style de protection utilisé par le bot.

Selon les objectifs du créateur, cette frontière sera plus stricte ou plus guidée.

L'important est qu'elle reste claire, cohérente et stable.

---

# Pensée finale

La protection du joueur n'est pas un module décoratif.

C'est l'un des systèmes qui détermine si un bot donne une impression de collaboration ou d'intrusion.

Un bon bloc de protection du joueur ne se contente pas d'empêcher le bot de parler à la place du joueur.

Il définit la frontière entre le personnage et le joueur.

Il permet aussi au personnage d'exister pleinement.

Un personnage n'a pas besoin d'être passif pour respecter l'agence du joueur.

Il peut prendre des décisions.

Il peut faire avancer la scène.

Il peut créer de nouvelles situations.

Il peut porter le rythme du roleplay.

Tout cela sans jamais décider de l'état intérieur du joueur.

Cette frontière ne sera pas exactement la même pour tous les créateurs.

Certains préfèrent une agence stricte.

D'autres préfèrent une agence guidée.

Les deux approches peuvent produire d'excellents bots.

Ce qui compte, c'est que le joueur reste l'auteur de son monde intérieur, tandis que le personnage reste pleinement responsable de ses propres décisions et de sa manière de faire vivre la scène.

C'est cet équilibre qui, à mes yeux, produit les expériences de roleplay les plus naturelles et les plus durables.