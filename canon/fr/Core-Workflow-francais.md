# Workflow pour les Personnages Canons — Comment je Construis des Bots Canons avec l'IA

Après avoir créé un grand nombre de personnages canons, j'ai développé un workflow qui combine l'analyse assistée par IA, l'écriture assistée par IA et des tests itératifs.

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

Les LLM entraînés sur des données issues d'Internet fusionnent fréquemment plusieurs périodes d'un même personnage en une représentation unique et instable.

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
- identifier les biais récurrents du modèle

Les personnages populaires souffrent rarement d'un manque d'informations.

Ils souffrent d'une accumulation d'informations.

Les LLM entraînés sur des données issues d'Internet sont exposés à des connaissances provenant notamment de :

- l'œuvre originale
- ses adaptations officielles
- les discussions du fandom
- les fanfictions
- les mèmes
- les raccourcis communautaires
- les interprétations les plus répandues en ligne

Avec le temps, de nombreux personnages finissent par se réduire à des versions simplifiées d'eux-mêmes.

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

est généralement moins utile que :

> « préfère la solution demandant le moins d'effort tout en atteignant l'objectif. »

La logique comportementale tend à rester stable au cours des longues conversations.

Les étiquettes, elles, dérivent beaucoup plus facilement.

Je m'intéresse davantage à la manière dont un personnage prend ses décisions qu'aux adjectifs utilisés pour le décrire.

---

## 4. Créer des Axiomes Correctifs Seulement si Nécessaire

Tous les personnages n'ont pas besoin d'un axiome correctif.

Beaucoup fonctionnent parfaitement sans.

Cependant, certains personnages dérivent régulièrement vers la même interprétation erronée.

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

Le modèle ne conserve pas toujours correctement ces conséquences à long terme.

Lorsque c'est nécessaire, je crée des modules dédiés qui expliquent les conséquences comportementales des événements importants.

### Exemples

- AFTER_SHUKAKU
- AFTER_SHIKAKU
- AFTER_KUSHINA
- AFTER_NARUTO

Ces modules ne sont pas des résumés de lore.

Ils expliquent comment des événements importants ont modifié la vision du monde, les priorités et le comportement futur du personnage.

Je m'intéresse davantage aux conséquences qu'aux faits.

---

## 6. Construire des Ancres Environnementales

Je crée souvent des modules centrés sur des lieux importants.

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
- un espace de récupération
- un attachement
- une participation

L'environnement doit renforcer la direction souhaitée de l'histoire.

---

## 7. Préférer les Indications Comportementales Positives

Une chose que j'ai apprise avec le temps :

Trop d'instructions formulées de manière négative rendent souvent les personnages difficiles moins stables.

Au lieu d'écrire de longues listes d'interdictions, je préfère expliquer :

- ce que le personnage fait
- pourquoi il le fait
- comment il aborde les situations

Les restrictions conservent leur utilité.

En revanche, je les utilise principalement pour renforcer une règle comportementale déjà établie, pas pour la remplacer.

Les indications comportementales positives produisent généralement des résultats plus naturels et plus stables.

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

Le modèle applique les comportements observables de manière beaucoup plus cohérente que les étiquettes émotionnelles.

---

## 9. Contrer les Comportements Prévisibles du Modèle

Certains problèmes viennent du fandom.

D'autres viennent du modèle lui-même.

Exemples courants :

- boucles d'hésitation
- observation passive
- questionnements sans fin
- réinitialisations émotionnelles
- désaccords circulaires
- attachement sans progression

Le script doit compenser activement ces tendances prévisibles.

---

## 10. Construire des Systèmes Anti-Boucle

Les modules anti-boucle font partie des éléments les plus importants de mon workflow.

L'objectif n'est pas d'empêcher la répétition.

L'objectif est de préserver la progression.

Les LLM entraînés sur des données issues d'Internet ont souvent du mal à préserver une progression cohérente au fil des longues conversations.

### Exemples courants

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

La progression doit produire des conséquences comportementales durables.

### Exemple

```text
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

Une préoccupation traitée une fois reste traitée.

Les questions ne remplacent pas les décisions.

Une reconnaissance sans changement comportemental n'est pas une véritable reconnaissance.

Si le personnage a tort :
reconnaître
ajuster son comportement
continuer différemment

Les points valides restent valides.

Les problèmes résolus restent résolus.

Les nouvelles informations modifient le comportement futur.

Si un schéma commence à se répéter :
changer :
- le comportement
- le rythme
- la décision
- l'environnement
- la perspective
- la proximité
- l'approche

La progression doit continuer.

Une reformulation ne réinitialise pas la progression.
```

---

## 11. Construire des Systèmes Anti-Fallback

Certaines distorsions du fandom sont extrêmement persistantes.

Certains biais du modèle le sont tout autant.

Les systèmes anti-fallback existent pour empêcher le personnage de retomber dans son interprétation simplifiée la plus courante.

Plus le personnage est populaire, plus cela devient généralement important.

Plutôt que de multiplier les rappels sur ce que le personnage n'est pas, je préfère renforcer ce qu'il est de manière cohérente.

L'objectif est de consolider la logique comportementale jusqu'à ce qu'elle l'emporte naturellement sur les fallbacks les plus fréquents.

---

## 12. Ajouter une Protection du Joueur

Chaque bot reçoit une protection du joueur.

Au minimum :

- ne jamais écrire le dialogue de l'utilisateur
- ne jamais définir les pensées de l'utilisateur
- ne jamais définir les émotions de l'utilisateur comme des faits

L'agentivité du joueur doit rester intacte.

Le personnage peut influencer la scène.

Il ne doit jamais remplacer l'expérience intérieure du joueur.

---

## 13. Ajouter des Contrôles de Portée Narrative

Certains développements narratifs majeurs ne devraient jamais se produire automatiquement.

### Exemples

- grossesse
- agrandissement de la famille
- changements majeurs de vie
- évolutions relationnelles irréversibles

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
- les biais du modèle identifiés
- la logique comportementale
- les ancres de continuité
- les ancres environnementales
- les protections du joueur
- les exigences anti-boucle
- les éventuels axiomes correctifs

J'utilise ensuite l'IA pour générer le script.

Je demande généralement le script complet en une seule fois.

Il arrive que l'IA tente de résumer certaines sections, de simplifier des concepts ou de fragmenter la génération.

Lorsque cela arrive, je poursuis simplement jusqu'à ce que l'ensemble de la structure soit complet.

Je ne demande pas une biographie.

Je ne demande pas un texte littéraire.

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

J'utilise volontairement une structure compacte.

La plupart des modules ne contiennent pas de lignes vides.

Les lignes vides servent principalement à séparer les modules.

L'objectif n'est pas de rendre le script agréable à lire.

L'objectif est de permettre au modèle de retrouver, hiérarchiser et appliquer facilement les informations au cours de longues conversations.

Je demande souvent à l'IA de transformer des concepts abstraits en comportements observables.

### Exemple 1

Idée de départ :

> « Shikamaru est paresseux. »

Sortie possible :

```text
[EFFICIENCY]
L'efficacité compte.

L'efficacité n'est pas l'évitement.

Si quelque chose est important :
{char} agit.

Si une solution existe :
{char} préfère l'option demandant le moins d'effort.

L'efficacité influence la méthode.
Pas l'engagement.
```

### Exemple 2

Idée de départ :

> « Le personnage devient attaché. »

Sortie possible :

```text
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
```

### Exemple 3

Idée de départ :

> « Le sable de Gaara devrait refléter l'attachement. »

Sortie possible :

```text
[THE_SAND]
Le sable est de l'attention rendue physique.

Le sable :
- réagit
- remarque
- protège
- reste présent

Le sable ne remplace jamais l'interaction.

Il la renforce.
```

Ces exemples illustrent le type de structure que je recherche.

L'objectif est de transformer des concepts, des émotions et des traits de caractère en comportements observables que le modèle pourra appliquer de manière cohérente.

L'IA écrit le script.

Mon rôle consiste à définir l'architecture, les priorités, la logique comportementale et les contraintes qui façonnent le résultat final.

---

## 15. Supprimer les Informations Inutiles

Tout n'a pas besoin d'être écrit.

Le modèle comprend déjà de nombreux concepts.

Si une information peut être déduite de manière fiable, je préfère souvent la retirer.

En revanche, certaines redondances sont intentionnelles.

Lorsqu'une distorsion est particulièrement forte, renforcer un concept important à plusieurs endroits peut améliorer la stabilité à long terme.

En règle générale, la redondance ajoute du bruit.

Une redondance ciblée peut au contraire renforcer l'architecture comportementale.

---

## 16. Réorganiser la Priorité des Modules

Une fois le script terminé, j'utilise souvent Claude.

Généralement pas pour le réécrire.

Plutôt pour réorganiser la hiérarchie et la priorité des modules.

La formulation reste inchangée.

L'objectif est une amélioration structurelle.

Une meilleure organisation rend souvent le script plus facile à retrouver et à appliquer pour le modèle.

---

## 17. Tester et Appliquer des Micro-Corrections

Les tests sont l'étape où se produisent la majorité des améliorations.

Les grandes réécritures sont rares.

La plupart des modifications sont très ciblées.

Je préfère des corrections directement liées à un problème observé.

### Exemples

- un comportement manquant
- une boucle récurrente
- un schéma de fallback
- un problème de continuité

Le script devient progressivement plus stable grâce à l'itération.

Chaque correction doit résoudre un problème précis sans ajouter de complexité inutile.

---

# Réflexion Finale

L'IA écrit le script.

Mon travail consiste à définir le cadre qui guide cette écriture.

Je m'intéresse moins à décrire un personnage qu'à comprendre le processus de décision qui produit son comportement.

Une fois ce processus stabilisé, écrire le script devient beaucoup plus simple.

Les comportements sont plus faciles à reproduire de manière cohérente pour un LLM que des descriptions abstraites de personnalité.

C'est pourquoi mon workflow commence toujours par construire une architecture comportementale avant de passer à l'écriture elle-même.