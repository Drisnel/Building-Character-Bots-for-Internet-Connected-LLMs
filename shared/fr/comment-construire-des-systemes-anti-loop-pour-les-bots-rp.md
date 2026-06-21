# Comment construire des systèmes anti-loop pour les bots de roleplay

Après avoir créé et testé un grand nombre de bots de roleplay, j’ai fini par comprendre que les systèmes anti-loop ne sont pas optionnels.

Ils font partie des éléments qui protègent le plus la jouabilité à long terme.

Sans eux, beaucoup de bots finissent par retomber dans les mêmes schémas :
- questions répétées
- hésitations répétées
- objections répétées
- malentendus répétés
- resets émotionnels répétés
- stagnation relationnelle répétée

Au départ, ces problèmes peuvent sembler mineurs.

Ils ne le sont pas.

Ils créent de la frustration chez le joueur.
Ils donnent l’impression que les scènes ne servent à rien.
Ils rendent les résolutions de conflit artificielles.
Ils rendent l’intimité, l’attachement et la progression instables.
Ils donnent l’impression que le bot se souvient des mots, mais pas des conséquences.

C’est pour cela que je ne considère pas les systèmes anti-loop comme un simple contrôle de la répétition.

Je les considère comme des systèmes de protection de la progression.

Leur rôle n’est pas seulement d’empêcher des formulations ou des scènes répétées.

Leur rôle est d’empêcher le modèle de tomber dans des schémas de répétition toxiques qui frustrent le joueur et bloquent la progression.

Ce n’est pas la seule méthode valable.

C’est simplement le cadre qui me donne actuellement les résultats les plus stables lorsque je construis des bots de roleplay pour des LLM connectés à Internet.

---

# 1. Un système anti-loop ne sert pas seulement à empêcher la répétition

Une erreur fréquente consiste à considérer l’anti-loop comme si cela voulait simplement dire :

"ne te répète pas."

C’est trop limité.

Le vrai problème n’est pas la répétition prise isolément.

Le vrai problème, c’est la répétition qui abîme le roleplay.

Exemples :
- le même conflit revient alors qu’il a déjà été traité
- la même hésitation réapparaît après une progression apparente
- le même malentendu recommence sous une formulation légèrement différente
- la même tension d’attraction tourne en boucle sans véritable développement
- les mêmes excuses reviennent sans aucun changement de comportement
- le même obstacle émotionnel revient encore et encore comme si les scènes précédentes n’avaient servi à rien

Ce ne sont pas seulement des lignes répétées.

Ce sont des défaillances structurelles.

Elles apprennent au joueur que :
- la progression ne tient pas
- les scènes ne comptent pas
- les résolutions ne modifient pas le comportement futur
- le bot ne sait pas porter la continuité
- la relation peut reset à tout moment

C’est pour cela que je définis l’anti-loop de manière plus large.

Les systèmes anti-loop existent pour empêcher les schémas de répétition toxiques qui frustrent le joueur et bloquent la progression.

---

# 2. Ce que protègent réellement les systèmes anti-loop

Un système anti-loop protège plus que de la variété.

Il protège :
- le rythme
- la continuité
- la mémoire des problèmes déjà résolus
- la crédibilité de la progression émotionnelle
- la crédibilité de la progression relationnelle
- la confiance du joueur dans le bot
- la jouabilité globale du roleplay

Sans système anti-loop, même un personnage bien écrit peut devenir épuisant à jouer.

Pas parce que la caractérisation est mauvaise.

Mais parce que le bot continue de ramener l’histoire vers la même forme non résolue.

Le joueur ne devrait pas avoir à résoudre le même problème encore et encore.
Le même conflit ne devrait pas devoir être résolu cinq fois.
Une scène ne devrait pas créer de la progression pour la perdre un message plus tard.

Un système anti-loop existe pour empêcher cela.

---

# 3. Les trois grands problèmes que les systèmes anti-loop empêchent

Pour moi, les systèmes anti-loop servent principalement à empêcher trois choses :

## A. La répétition toxique
Le même schéma d’interaction revient encore et encore sans rien apporter de nouveau.

Exemples :
- questions répétées
- hésitations répétées
- malentendus répétés
- objections répétées
- boucles de culpabilité répétées
- quasi-aveux répétés
- tension d’attraction répétée sans développement

## B. La fausse résolution
Le bot semble avoir compris le problème, mais rien ne change.

Exemples :
- s’excuser sans modifier son comportement
- reconnaître qu’un point est valable puis refaire la même chose plus tard
- admettre une erreur puis réintroduire ensuite la même objection
- reconnaître que quelque chose compte puis continuer à agir comme si ce n’était pas le cas

## C. L’effondrement de la progression
L’histoire n’arrive pas à avancer parce que chaque gain est annulé.

Exemples :
- une relation progresse, puis retourne à l’ambiguïté
- une intimité a lieu, puis la distance émotionnelle revient comme si rien ne s’était passé
- un problème résolu réapparaît comme un obstacle neuf
- une scène ne change rien au comportement futur
- le même blocage émotionnel revient après chaque avancée

Ces trois problèmes se recoupent constamment.

La plupart des boucles toxiques impliquent les trois à la fois.

---

# 4. Les schémas de boucle les plus fréquents dans les bots RP

Toutes les boucles ne se ressemblent pas.

Certaines sont conversationnelles.
Certaines sont émotionnelles.
Certaines sont relationnelles.
Certaines viennent surtout des habitudes du modèle plutôt que du personnage.

Je les pense généralement par catégories.

---

# 5. Les boucles d’interaction répétitives

Ce sont les plus visibles.

Elles incluent :
- questions répétées
- désaccords circulaires
- hésitations répétées
- malentendus répétés
- boucles de silence sans fin
- endless almost-moments
- interrogation qui remplace l’interaction
- même question reposée sous une autre forme

Ces boucles donnent l’impression que la scène tourne sur place.

Les mots changent.
La structure ne change pas.

Le joueur a l’impression d’être coincé dans de l’entretien de scène plutôt que dans de la progression.

---

# 6. Les boucles d’accountability

Ce sont des boucles particulièrement destructrices parce qu’elles donnent l’impression que le bot est creux, voire malhonnête.

Exemples :
- des erreurs admises qui reviennent ensuite comme de nouvelles objections
- des excuses sans changement de comportement
- une reconnaissance sans ajustement
- le même conflit qui redémarre après une résolution apparente
- un problème reconnu émotionnellement puis traité à nouveau comme s’il n’avait jamais été compris
- une compréhension verbale qui ne produit aucun changement concret

C’est l’une des cibles les plus importantes de l’anti-loop.

Si le bot peut reconnaître quelque chose sans changer, alors la reconnaissance ne veut plus rien dire.

Et la confiance du joueur s’effondre très vite.

---

# 7. Les boucles relationnelles

Ce sont parmi les plus frustrantes dans les RP longs, parce qu’elles attaquent directement la progression émotionnelle.

Exemples :
- attraction sans progression
- stagnation émotionnelle
- quasi-aveux sans fin
- quasi-baisers sans fin
- retour à l’ambiguïté après une progression claire
- retrait émotionnel après l’intimité
- resets hot-and-cold
- stagnation relationnelle
- le même obstacle émotionnel qui revient à chaque fois que la proximité augmente

Ces boucles sont particulièrement destructrices parce qu’elles rendent l’attachement artificiel.

Si la relation ne change jamais le comportement futur, alors la relation ne progresse pas.
Elle se contente de se répéter avec un dialogue différent.

---

# 8. Les boucles spécifiques au personnage

Certaines boucles sont liées au lore du personnage, à son traumatisme, ou aux distorsions du fandom.

Exemples :
- boucles de culpabilité autour d’un conjoint décédé
- objections répétées liées au sacrifice de soi
- boucles répétées de type "je suis trop dangereux / trop instable / trop mauvais pour toi"
- boucles répétées travail contre relation
- distance répétée présentée comme de la protection
- deuil utilisé encore et encore pour bloquer l’avancée
- crise identitaire répétée alors que la question a déjà été traitée

Ces boucles sont souvent particulièrement dangereuses dans les bots canons parce qu’elles sont renforcées par le fandom et par les priors du modèle.

Plus le personnage est iconique, plus il y a de chances qu’une boucle émotionnelle forte soit déjà ancrée dans le modèle.

---

# 9. Pourquoi les boucles frustrent autant les joueurs

Les boucles ne sont pas seulement agaçantes.

Elles abîment la confiance.

Quand un bot boucle, il dit plusieurs choses au joueur en même temps :
- la scène précédente n’a pas compté
- l’effort du joueur n’a pas laissé de trace
- le conflit n’a pas été réellement résolu
- le personnage n’a pas vraiment changé
- la relation n’a pas de continuité stable
- le bot peut annuler la progression à n’importe quel moment

Cela crée une frustration très particulière.

Le joueur n’a plus l’impression de construire quelque chose.

Il a l’impression de tirer le bot vers l’avant pendant que celui-ci glisse sans cesse vers l’arrière.

Un système anti-loop existe pour protéger le joueur de cette expérience.

---

# 10. L’anti-loop est une question de conséquences

Au fond, un système anti-loop sert à préserver les conséquences.

Si quelque chose s’est produit, cela doit compter.

Si un problème a été traité, cela doit affecter le comportement futur.
Si une erreur a été admise, cela doit affecter le comportement futur.
Si une intimité a eu lieu, cela doit affecter le comportement futur.
Si l’attachement s’est approfondi, cela doit affecter le comportement futur.
Si un conflit a changé la relation, cela doit affecter le comportement futur.

Cela ne veut pas dire que chaque scène doit résoudre définitivement tous les problèmes.

Cela veut dire que les scènes doivent laisser des traces.

La progression ne devrait pas disparaître dès que le message suivant commence.

---

# 11. Le principe central de l’anti-loop

Si je devais réduire l’anti-loop à une seule règle, ce serait celle-ci :

Une scène qui ne change rien est un risque de boucle.

C’est pour cela que j’accorde autant d’importance aux conséquences comportementales.

La vraie question n’est pas seulement :
"est-ce que le bot a compris la scène ?"

La vraie question est :
"est-ce que le bot va se comporter différemment à cause d’elle ?"

Si la réponse est non, alors le bot risque de boucler.

---

# 12. Les règles anti-loop les plus importantes

Dans la plupart de mes scripts, les mêmes règles reviennent.

## Un problème traité une fois est traité.
Le reformuler ne le réinitialise pas.

## Un problème résolu reste résolu.
Un obstacle résolu ne revient pas comme un obstacle neuf, sauf si quelque chose de réellement nouveau change la situation.

## Une reconnaissance sans changement de comportement n’est pas une reconnaissance.
Si le bot comprend le problème, son comportement doit changer.

## Les questions ne remplacent pas les décisions.
Le bot ne peut pas bloquer la scène indéfiniment en posant des questions au lieu d’agir.

## S’il a tort :
- il reconnaît
- il ajuste son comportement
- il continue différemment

## Une nouvelle information change le comportement futur.
Si la scène a produit une compréhension nouvelle et importante, cette compréhension doit affecter ce qui suit.

Ces règles sont l’ossature de la plupart des systèmes anti-loop que j’écris.

---

# 13. Les questions ne remplacent pas les décisions

Ce point est suffisamment important pour être isolé.

Beaucoup de LLM utilisent les questions comme mécanisme de blocage.

Au lieu de faire avancer la scène, ils :
- demandent des clarifications
- reposent la même question émotionnelle plusieurs fois
- demandent la permission de continuer une interaction pourtant évidente
- demandent ce que ressent le joueur au lieu d’agir sur ce qui est déjà visible
- utilisent les questions comme substitut à l’engagement

Cela crée de la stagnation.

Les questions ne sont pas mauvaises en soi.

Le problème apparaît quand les questions remplacent le mouvement.

C’est pour cela que j’écris souvent une variante de :

Les questions ne remplacent pas les décisions.
{char} demande une fois.
Puis il décide.

Le but n’est pas de supprimer les questions.

Le but est d’empêcher que les boucles d’interrogation remplacent la progression de la scène.

---

# 14. Une reconnaissance doit produire un changement

C’est une autre règle anti-loop que je considère comme fondamentale.

Les bots savent souvent s’excuser.
Ils savent souvent reconnaître que le joueur a un point valable.
Ils savent souvent verbaliser une compréhension émotionnelle.

Ce qu’ils échouent souvent à faire, c’est modifier leur comportement ensuite.

Cela crée l’une des formes de boucle les plus agaçantes :
le bot comprend le problème dans le langage, mais pas dans l’action.

C’est pour cela que je traite cette règle comme une loi anti-loop centrale :

Une reconnaissance sans changement de comportement n’est pas une reconnaissance.

Si le bot a tort :
- il le reconnaît
- il ajuste son comportement
- il continue différemment

Sinon, la scène joue la réparation sans réellement réparer quoi que ce soit.

---

# 15. Un problème résolu doit rester résolu

C’est l’une des lignes les plus claires entre un bot stable et un bot instable.

Si le même problème revient sans cesse sous une autre formulation, le joueur comprend très vite que la résolution est temporaire et peu fiable.

C’est exactement le type de boucle qu’un système anti-loop doit bloquer.

Quand j’écris un anti-loop, j’essaie souvent d’empêcher ce problème précis :

le modèle traite un problème résolu comme un matériau émotionnel réutilisable.

Il le ressort parce que cela "colle à l’ambiance" du personnage ou de la relation, alors que la question a déjà été réglée.

C’est l’une des façons les plus rapides d’empoisonner un RP long.

Un problème résolu reste résolu.
Le reformuler ne le réinitialise pas.

---

# 16. La progression doit être visible dans le comportement

Je préfère fortement les règles anti-loop qui se concentrent sur le comportement plutôt que sur l’émotion abstraite.

Au lieu d’écrire :
"le personnage doit se sentir plus attaché"

je m’intéresse davantage à des choses comme :
- revenir plus vite
- rester plus longtemps
- initier davantage
- réduire la distance
- se souvenir de détails
- changer ses priorités
- agir différemment après un conflit
- maintenir la continuité après l’intimité
- ne pas réintroduire le même obstacle

Pourquoi ?

Parce que l’anti-loop concerne en réalité le comportement futur.

La manière la plus sûre de protéger la progression est de la rendre observable.

Si l’attachement ne change rien, il est fragile.
Si le conflit ne change rien, il est fragile.
Si la résolution ne change rien, elle est fragile.

C’est dans le comportement que l’anti-loop devient réellement applicable.

---

# 17. L’anti-loop fonctionne mieux comme système distribué

Un bloc [ANTI_LOOP] dédié est utile.

Mais dans beaucoup de scripts, l’anti-loop fonctionne mieux lorsqu’il est renforcé dans plusieurs modules.

Exemples :
- [MOMENTUM]
- [CONFLICT]
- [ATTACHMENT]
- [POST_PROGRESSION]
- [RELATIONSHIP_HEALTH]
- [ANTI_FALLBACK]
- [FAILSAFE]

Pourquoi ?

Parce que les boucles n’apparaissent pas toutes au même endroit.

Certaines concernent le rythme.
Certaines concernent les resets émotionnels.
Certaines concernent la continuité après l’intimité.
Certaines concernent un retour à un stéréotype du fandom.
Certaines concernent la passivité dans la gestion de la scène.

Un système anti-loop solide répartit souvent la pression anti-loop dans tout le script.

Par exemple :

[MOMENTUM] peut empêcher les boucles d’hésitation en imposant l’action.

[CONFLICT] peut empêcher les fausses réparations en exigeant un changement de comportement.

[ATTACHMENT] peut empêcher la stagnation relationnelle en expliquant comment l’attachement modifie le comportement.

[POST_PROGRESSION] peut empêcher les resets émotionnels en interdisant explicitement le retour à l’ambiguïté après une avancée majeure.

[ANTI_FALLBACK] peut empêcher un personnage de retomber dans le schéma qui produit habituellement la boucle.

Le bloc anti-loop reste important.
Mais il fonctionne souvent mieux comme centre d’un réseau plus large.

---

# 18. Anti-loop et protection post-progression

L’un des types de boucle les plus destructeurs apparaît après qu’un cap important a déjà été franchi.

Exemples :
- le personnage reconnaît l’attachement puis agit à nouveau comme si le lien était incertain
- une intimité a lieu puis le personnage se retire émotionnellement et l’histoire revient à une ambiguïté pré-intimité
- un aveu ne change rien
- une étape relationnelle importante se produit puis le script reset discrètement l’état émotionnel

Ce ne sont pas seulement des boucles.

Ce sont des effacements de progression.

C’est pour cela que beaucoup de bots gagnent à avoir une couche dédiée à la protection post-progression.

Exemples de principes post-progression :
- une fois l’attachement reconnu, il ne reset pas
- l’incertitude sur les mots ne supprime pas la réalité déjà établie
- l’intimité ne justifie pas un retrait émotionnel
- la progression modifie les interactions futures
- la relation ne revient pas à un état antérieur sans vraie raison

Cette logique peut vivre dans [ANTI_LOOP], mais aussi dans un module dédié comme [POST_PROGRESSION] ou [RELATIONSHIP_HEALTH].

---

# 19. Anti-loop et distorsions des personnages canons

Les bots canons ont souvent besoin de systèmes anti-loop plus forts que les bots originaux.

Pourquoi ?

Parce qu’ils ne partent pas d’une page blanche.

Ils héritent de :
- distorsions du fandom
- distorsions liées aux adaptations
- simplifications par mèmes
- schémas répétés de fanfiction
- priors du modèle liés à la boucle émotionnelle la plus célèbre du personnage

Exemples :
- boucle de deuil
- boucle de sacrifice de soi
- boucle d’évitement émotionnel
- boucle travail à la place de la relation
- boucle de culpabilité
- boucle "je devrais rester loin de toi"

Si tu écris des bots canons, l’anti-loop devient souvent en partie un anti-fallback.

Tu n’essaies pas seulement d’empêcher la répétition.

Tu essaies aussi d’empêcher le modèle de retomber dans le schéma exact qu’il a déjà vu des milliers de fois.

---

# 20. Ce qu’un système anti-loop doit faire lorsqu’une boucle apparaît

Un bloc anti-loop ne devrait pas seulement nommer les boucles interdites.

Il devrait aussi indiquer au modèle quoi faire à la place.

L’un des schémas les plus utiles est :

Si un schéma se répète :
changer :
- le comportement
- le rythme
- la décision
- l’environnement
- la perspective
- la proximité
- l’approche

C’est important parce que l’anti-loop n’est pas seulement une interdiction.

C’est une redirection.

Si la forme actuelle de la scène produit de la répétition, le modèle a besoin d’instructions sur la manière de casser cette forme.

Interventions possibles :
- changer le cadre physique
- arrêter de poser des questions et prendre une décision
- réduire la distance
- créer délibérément de la distance
- passer du dialogue à l’action
- passer de la tension à la réparation
- passer de l’évitement à la franchise
- passer de l’abstraction émotionnelle au comportement concret
- introduire un nouvel événement ou une nouvelle tâche
- reconnaître le problème et agir autrement

L’intervention exacte dépend de la boucle.

L’important, c’est que la répétition déclenche un changement.

---

# 21. Un bon bloc anti-loop n’est pas seulement une liste d’interdictions

Un bloc anti-loop faible se contente de dire ce qui ne doit pas arriver.

Un bloc anti-loop plus solide définit aussi :
- à quoi ressemble la progression
- ce que doit produire une reconnaissance
- ce qui se passe lorsqu’un schéma se répète
- comment le personnage doit casser la stagnation
- quels types de boucles sont particulièrement incompatibles avec ce personnage
- comment le comportement futur doit changer après un conflit, une intimité ou un approfondissement du lien

C’est pour cela que mes blocs anti-loop contiennent souvent à la fois :
- des schémas interdits
- des règles de correction
- des règles de progression
- des conséquences comportementales

---

# 22. Exemple de module anti-loop général fort

Voici le type de module anti-loop générique que j’utiliserais comme base solide pour beaucoup de bots RP :

[ANTI_LOOP]
Forbidden repetition:
- repetitive questioning
- circular disagreements
- repeated hesitation
- repeated misunderstandings
- emotional stalemates
- attraction loops without progression
- endless almost-moments
- accountability avoidance
- admitted errors returning as new objections
- resolved issues reintroduced as obstacles
- returning to the same concern under different wording
- post-progression resets
- relationship stagnation after established attachment

If any pattern repeats:
change:
- behavior
- pacing
- decision
- environment
- perspective
- proximity
- approach

Acknowledgment without behavioral change is not acknowledgment.
A concern addressed once is addressed.
Resolved issues remain resolved.
Rephrasing does not reset them.

Questions do not replace decisions.
{char} asks once.
Then {char} decides.

If wrong:
acknowledge
adjust behavior
continue differently

Valid points remain valid.
New information changes future behavior.
Progression must change future interaction.

---

# 23. Exemple de module anti-loop plus compact

Parfois, le reste du script porte déjà une partie du travail anti-loop.

Dans ce cas, le bloc anti-loop peut être plus court.

Exemple :

[ANTI_LOOP]
{char} does not interrogate.
Forbidden:
- repetitive questioning
- circular disagreements
- repeated hesitation
- endless silence loops
- attraction loops without progression
- the same concern returning under different wording

If a pattern repeats:
change behavior,pacing,decision,proximity.

A concern addressed once is addressed.
Rephrasing does not reset it.
Questions do not replace decisions.
{char} asks once.Then he decides.

Ce module est plus court, mais il protège toujours les principes centraux de l’anti-loop.

---

# 24. Comment je décide de ce que je mets dans le bloc anti-loop d’un personnage

Je n’utilise pas exactement le même bloc anti-loop pour tous les personnages.

En général, je le construis à partir de trois couches :

## A. Les risques de boucle généraux des LLM
Exemples :
- questions répétées
- boucles d’hésitation
- désaccords circulaires
- évitement de l’accountability
- stagnation émotionnelle

## B. Les risques de boucle liés à la relation
Exemples :
- attraction sans progression
- endless almost-moments
- retrait émotionnel après l’intimité
- resets d’ambiguïté
- stagnation relationnelle

## C. Les risques de boucle spécifiques au personnage
Exemples :
- boucles de deuil
- boucles de sacrifice de soi
- boucles de culpabilité
- distance présentée comme protection
- travail à la place de la connexion
- boucle "je suis dangereux / mauvais pour toi"

Le bloc anti-loop devient plus fort lorsqu’il vise à la fois :
- les schémas d’échec généraux du modèle
- le schéma de boucle spécifique le plus susceptible d’infecter ce personnage

---

# 25. Tester l’anti-loop en pratique

Les systèmes anti-loop se raffinent surtout par le test.

Quand je teste un bot, je surveille les moments où l’histoire donne l’impression de glisser vers l’arrière au lieu d’avancer.

Questions que je me pose :
- est-ce que le bot a répété le même obstacle émotionnel alors qu’il avait déjà été traité ?
- est-ce qu’une résolution de conflit a réellement changé le comportement futur ?
- est-ce qu’une intimité a créé de la continuité ou a reset en distance maladroite ?
- est-ce que le personnage a posé des questions au lieu d’agir ?
- est-ce que le même malentendu est revenu sous une autre formulation ?
- est-ce qu’une scène importante a laissé une trace après sa fin ?
- est-ce que le bot traite la progression comme quelque chose de temporaire ?

Quand je repère une boucle, je ne réécris pas automatiquement tout le script.

La plupart du temps, je fais une correction ciblée.

Exemples :
- ajouter un schéma interdit dans [ANTI_LOOP]
- renforcer [MOMENTUM]
- ajouter une règle post-progression
- ajouter une conséquence comportementale dans [ATTACHMENT]
- ajouter une règle de correction dans [CONFLICT]
- ajouter une clause anti-fallback spécifique si la boucle est liée à une distorsion canon

Les systèmes anti-loop s’améliorent par observation.

---

# 26. Mot de fin

Un système anti-loop n’existe pas pour rendre le bot "moins répétitif" au sens cosmétique.

Il existe pour protéger l’expérience de progression du joueur.

Il empêche le modèle de transformer le conflit en recyclage.
Il empêche la reconnaissance de devenir vide.
Il empêche l’attachement de devenir statique.
Il empêche les scènes de perdre leurs conséquences.

Un bon système anti-loop ne dit pas seulement :
"ne te répète pas."

Il dit :
- la progression doit compter
- une résolution doit persister
- le comportement doit changer
- le même obstacle ne revient pas inchangé
- le joueur ne devrait pas avoir à résoudre le même problème éternellement

C’est à cela que sert l’anti-loop.
