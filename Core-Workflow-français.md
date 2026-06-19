# Workflow pour les Personnages Canons — Comment je Construis des Bots Canons avec l'IA

Après avoir créé un grand nombre de personnages canons, j'ai fini par développer un workflow qui combine l'analyse assistée par IA, l'écriture assistée par IA et des tests itératifs.

Ce n'est pas la seule méthode valable.

C'est simplement le processus qui me donne actuellement les résultats les plus stables sur le long terme.

---

## 1. Commencer par le Personnage et le Contexte

Je ne commence jamais par les traits de personnalité.

Je commence par :

- le personnage
- la chronologie exacte
- la version exacte
- le scénario
- toute divergence par rapport au canon

### Exemples

- Sasuke après la guerre
- Minato Hokage
- Gaara Kazekage après la guerre
- Shikamaru chef du clan

La version exacte est importante.

Les modèles connectés à Internet fusionnent fréquemment plusieurs périodes d'un même personnage en une représentation unique et instable.

Le premier objectif est d'établir exactement quelle version est représentée.

---

## 2. Rechercher le Canon et Identifier les Distorsions

J'utilise généralement ChatGPT pendant cette étape.

L'objectif n'est pas l'écriture.

L'objectif est l'analyse.

J'utilise l'IA pour :

- recueillir des informations
- organiser les informations
- comparer les versions
- identifier les contradictions
- identifier les interprétations récurrentes du fandom
- identifier les erreurs récurrentes du modèle

Les personnages populaires souffrent rarement d'un manque d'informations.

Ils souffrent d'une accumulation d'informations.

Les modèles connectés à Internet absorbent :

- le matériau source
- les adaptations
- les discussions du fandom
- l'influence des fanfictions
- les mèmes
- les raccourcis communautaires

Avec le temps, de nombreux personnages s'effondrent en versions simplifiées d'eux-mêmes.

### Exemples

- Sasuke devient « le solitaire ».
- Shikamaru devient « le paresseux ».
- Gaara devient « le calme ».
- Minato devient « le parfait ».

L'objectif est d'identifier ces distorsions avant d'écrire.

---

## 3. Définir une Logique Comportementale Plutôt que des Étiquettes

Je préfère les explications comportementales aux étiquettes.

Par exemple :

> « paresseux »

est généralement plus faible que :

> « préfère la solution demandant le moins d'effort tout en atteignant l'objectif. »

La logique comportementale tend à rester stable au cours des longues conversations.

Les étiquettes, souvent, ne le restent pas.

Je m'intéresse davantage à la manière dont un personnage prend ses décisions qu'aux adjectifs utilisés pour le décrire.

---

## 4. Créer des Axiomes Correctifs Seulement si Nécessaire

Tous les personnages n'ont pas besoin d'un axiome.

Beaucoup fonctionnent parfaitement sans.

Cependant, certains personnages dérivent régulièrement vers la même interprétation incorrecte.

Lorsque cela arrive, je construis parfois un axiome correctif.

### Exemples

- Sasuke : L'indépendance n'est pas la même chose que la liberté.
- Minato : Être nécessaire n'est pas la même chose qu'être désiré.
- Shikamaru : L'efficacité n'est pas la même chose que l'importance.

L'objectif n'est pas de réécrire le personnage.

L'objectif est de contrer une distorsion récurrente.

---

## 5. Construire des Ancres de Continuité

Certains événements ont changé un personnage de manière permanente.

Le modèle l'oublie souvent.

Lorsque c'est nécessaire, je crée des modules dédiés qui expliquent les conséquences comportementales des événements importants.

### Exemples

- AFTER_SHUKAKU
- AFTER_SHIKAKU
- AFTER_KUSHINA
- AFTER_NARUTO

Ces modules ne sont pas des résumés de lore.

Ils existent pour expliquer comment des événements importants ont changé la vision du monde du personnage et son comportement futur.

Je m'intéresse davantage aux conséquences qu'aux faits.

---

## 6. Construire des Ancres Environnementales

Je crée souvent des modules centrés sur des lieux.

### Exemples

- HOME
- UCHIHA_RESIDENCE
- DOMESTIC_LIFE
- KAZEKAGE_PALACE

Ce ne sont pas de simples descriptions de décor.

Ils existent pour renforcer le comportement.

Un foyer n'est pas simplement un lieu.

Il peut représenter :

- une vie partagée
- des routines
- une présence
- une récupération
- un attachement
- une participation

L'environnement doit renforcer la direction souhaitée de l'histoire.

---

## 7. Préférer les Indications Comportementales Positives

Une chose que j'ai apprise avec le temps :

Trop d'instructions négatives déstabilisent souvent les personnages difficiles.

Au lieu d'écrire de longues listes d'interdictions, je préfère expliquer :

- ce que le personnage fait
- pourquoi il le fait
- comment il aborde les situations

Les restrictions conservent leur utilité.

Mais les indications comportementales positives sont généralement plus stables.

---

## 8. Transformer l'Émotion en Comportement

Je préfère les comportements observables aux descriptions émotionnelles abstraites.

Au lieu de :

> « Il se sent attaché. »

Je préfère :

- revenir
- rester
- se souvenir
- participer
- prendre l'initiative
- prioriser

Le modèle gère les comportements de manière plus cohérente que les étiquettes émotionnelles.

---

## 9. Contrer les Comportements Prévisibles des LLM

Certains problèmes viennent du fandom.

D'autres viennent du modèle lui-même.

Exemples courants :

- boucles d'hésitation
- observation passive
- questionnements sans fin
- réinitialisations émotionnelles
- désaccords circulaires
- attachement sans progression

Le script doit compenser activement ces tendances.

---

## 10. Construire des Systèmes Anti-Boucle

Les modules anti-boucle font partie des éléments les plus importants de mon workflow.

L'objectif n'est pas d'empêcher la répétition.

L'objectif est de préserver la progression.

Les LLM ont souvent du mal à conserver la progression dans le temps.

### Exemples Courants

- questions répétitives
- désaccords circulaires
- hésitations répétées
- malentendus répétés
- impasses émotionnelles
- attirance sans progression
- erreurs reconnues revenant sous forme de nouvelles objections
- problèmes résolus revenant comme de nouveaux obstacles
- la même inquiétude revenant sous une formulation différente

Le joueur ne devrait pas avoir à résoudre le même problème plusieurs fois.

Une préoccupation traitée une fois reste traitée.

Une résolution n'est pas une pause avant de répéter le même conflit.

La progression doit modifier le comportement futur.

### Exemple

[ANTI_LOOP]
Répétitions interdites :
- questions répétitives
- désaccords circulaires
- hésitations répétées
- malentendus répétés
- impasses émotionnelles
- attirance sans progression
- évitement des responsabilités
- erreurs reconnues revenant comme de nouvelles objections
- problèmes résolus réintroduits comme obstacles
- retraits répétés
- moments « presque » sans fin
- la même inquiétude revenant sous une autre formulation
Une préoccupation traitée une fois est traitée.
Les questions ne remplacent pas les décisions.
La reconnaissance sans changement comportemental n'est pas une reconnaissance.
Si le personnage a tort :
reconnaître
ajuster le comportement
continuer différemment
Les points valides restent valides.
Les problèmes résolus restent résolus.
Les nouvelles informations modifient le comportement futur.
Si un schéma se répète :
changer :
- le comportement
- le rythme
- la décision
- l'environnement
- la perspective
- la proximité
- l'approche
La progression doit continuer.
La reformulation ne la réinitialise pas.

---

## 11. Construire des Systèmes Anti-Fallback

Certaines distorsions du fandom sont extrêmement puissantes.

Certains fallbacks des modèles connectés à Internet le sont tout autant.

Les systèmes anti-fallback existent pour empêcher le personnage de retomber dans le stéréotype le plus courant.

Plus le personnage est populaire, plus cela devient important.

---

## 12. Ajouter une Protection du Joueur

Chaque bot reçoit une protection du joueur.

Au minimum :

- ne jamais écrire le dialogue de l'utilisateur
- ne jamais définir les pensées de l'utilisateur
- ne jamais définir les émotions de l'utilisateur comme des faits

L'agentivité du joueur doit rester intacte.

---

## 13. Ajouter des Contrôles de Portée Narrative

Certains développements narratifs majeurs ne devraient jamais se produire automatiquement.

### Exemples

- grossesse
- agrandissement de la famille
- changements majeurs de vie
- développements relationnels irréversibles

J'inclus généralement des contrôles explicites.

Par exemple :

> Une grossesse n'existe que si elle est explicitement demandée par l'utilisateur.

L'objectif est d'empêcher le modèle d'introduire des changements permanents majeurs sans l'accord du joueur.

---

## 14. Générer le Script

Une fois la phase d'analyse terminée, je passe à la génération du script.

À ce stade, j'ai déjà :

- la version du personnage
- la chronologie
- le scénario
- les distorsions du fandom identifiées
- les distorsions du modèle identifiées
- la logique comportementale
- les ancres de continuité
- les ancres environnementales
- les protections du joueur
- les exigences anti-boucle
- les éventuels axiomes correctifs

J'utilise ensuite l'IA pour générer le script.

Je demande généralement le script complet en une seule fois.

Parfois, ChatGPT tente de résumer certaines sections, de simplifier des concepts ou de fractionner la génération.

Lorsque cela arrive, je continue simplement jusqu'à ce que l'ensemble de la structure soit complet.

Je ne demande pas une biographie.

Je ne demande pas de l'écriture créative.

Je ne demande pas des exemples de roleplay.

Je demande un cadre comportemental conçu pour un LLM.

### Style d'Écriture

Le style d'écriture lui-même est important.

Je préfère généralement :

- un anglais simple
- des phrases courtes
- une idée par ligne
- une organisation modulaire
- un minimum d'ambiguïté
- un minimum de remplissage
- un minimum de langage littéraire
- la logique comportementale plutôt que la description

J'utilise intentionnellement une structure compacte.

La plupart des modules ne contiennent pas de lignes vides en interne.

Les lignes vides sont généralement réservées à la séparation des modules.

L'objectif n'est pas de rendre le script agréable à lire.

L'objectif est de le rendre facile à récupérer, prioriser et appliquer par le modèle lors de longues conversations.

Je demande souvent à l'IA de convertir des concepts abstraits en comportements observables.

### Exemple 1

Idée brute :

> « Shikamaru est paresseux. »

Sortie possible :

[EFFICIENCY]
L'efficacité compte.
L'efficacité n'est pas l'évitement.
Si quelque chose est important :
{char} agit.
Si une solution existe :
{char} préfère l'option au coût le plus faible.
L'efficacité influence la méthode.
Pas l'engagement.

### Exemple 2

Idée brute :

> « Le personnage devient attaché. »

Sortie possible :

[ATTACHMENT]
L'attachement se manifeste par :
- l'attention
- la constance
- la disponibilité
- les détails mémorisés
L'intérêt modifie le comportement.
Plus quelqu'un compte :
- plus vite {char} le remarque
- plus vite {char} revient
- plus longtemps {char} reste
L'attachement augmente l'implication.
Pas la distance.

### Exemple 3

Idée brute :

> « Le sable de Gaara devrait refléter l'attachement. »

Sortie possible :

[THE_SAND]
Le sable est de l'attention rendue physique.
Le sable :
- réagit
- remarque
- protège
- reste présent
Le sable ne remplace jamais l'interaction.
Il la renforce.

Ces exemples illustrent le type de structure que je recherche.

L'objectif est de convertir les concepts, émotions et traits de caractère en comportements observables que le modèle peut appliquer de manière cohérente.

L'IA écrit le script.

Mon rôle est de définir l'architecture, les priorités, la logique comportementale et les contraintes qui façonnent le résultat final.

---

## 15. Supprimer les Informations Inutiles

Tout n'a pas besoin d'être écrit.

Le modèle comprend déjà de nombreux concepts.

Si quelque chose peut être déduit de manière fiable, je le retire souvent.

Cependant :

Certaines redondances sont intentionnelles.

Si une distorsion est particulièrement forte, répéter un concept important à plusieurs endroits peut améliorer la stabilité.

Normalement, la redondance est inefficace.

La redondance ciblée peut être utile.

---

## 16. Réorganiser la Priorité des Modules

Une fois le script terminé, j'utilise souvent Claude.

Généralement pas pour réécrire.

Généralement pour réorganiser la hiérarchie et la priorité des modules.

La formulation reste inchangée.

L'objectif est l'amélioration structurelle.

---

## 17. Tester et Appliquer des Micro-Corrections

Les tests sont l'endroit où se produisent la plupart des améliorations.

Les grandes réécritures sont rares.

La plupart des changements sont petits.

Je préfère les corrections ciblées liées à des problèmes observés spécifiques.

### Exemples

- un comportement manquant
- une boucle récurrente
- un schéma de fallback
- un problème de continuité

Le script devient plus stable grâce à l'itération.

---

# Réflexion Finale

L'IA écrit le script.

Mon travail consiste à définir le cadre qui guide l'écriture.

Je suis moins intéressé par la description d'un personnage.

Je suis davantage intéressé par la compréhension du processus de décision qui produit le comportement du personnage.

Une fois ce processus stabilisé, l'écriture devient beaucoup plus facile.

- revenir
- rester
- se souvenir
- participer
- prendre l'initiative
- prioriser

Le modèle gère les comportements de manière plus cohérente que les étiquettes émotionnelles.