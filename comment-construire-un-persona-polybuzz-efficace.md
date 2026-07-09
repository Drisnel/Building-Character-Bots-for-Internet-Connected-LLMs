# Comment construire un Persona PolyBuzz efficace

Le Persona est la mémoire du bot sur votre personnage joueur.

Il ne s'agit pas d'une fiche personnage destinée au joueur, mais d'un ensemble d'informations persistantes que le bot utilisera pour comprendre qui est votre personnage, comment il fonctionne et comment il se situe dans le monde.

La manière de construire un Persona dépend toutefois d'un élément essentiel : disposez-vous de la mémoire permanente de PolyBuzz ?

Sans mémoire permanente, le Persona doit contenir l'ensemble des informations importantes concernant votre personnage. Les 1500 caractères deviennent alors une ressource extrêmement limitée qu'il faut apprendre à optimiser.

Avec la mémoire permanente, la stratégie change complètement. Une grande partie des informations stables est déjà stockée ailleurs, ce qui permet d'utiliser le Persona comme un complément spécialisé plutôt que comme une fiche complète.

Ce guide présente les deux méthodes de travail.

---

# 💡 Quel est votre cas ?

### 🚫 Vous n'avez **pas** la mémoire permanente ?

Commencez directement par la **Partie 1**.

### 💾 Vous disposez de la mémoire permanente ?

Commencez directement par la **Partie 2**.

### 🧠 Les bonnes pratiques de la **Partie 3** concernent tous les utilisateurs.

---

# 🚫 Partie 1 — Sans mémoire permanente

## Pourquoi cette situation est la plus contraignante

Sans mémoire permanente, le Persona devient la seule mémoire persistante dont dispose le bot concernant votre personnage.

Toutes les informations importantes doivent donc tenir dans une limite de **1500 caractères**.

Cette contrainte oblige à faire des choix. Il est impossible d'écrire une biographie complète, une personnalité détaillée, l'ensemble des relations du personnage ou encore l'intégralité de son histoire.

L'objectif n'est donc pas d'être exhaustif.

L'objectif est de conserver les informations les plus importantes afin que le bot puisse comprendre rapidement qui est votre personnage et jouer correctement avec lui sur le long terme.

Il faut donc apprendre à hiérarchiser les informations et accepter que certains détails devront être sacrifiés.

Le Persona doit être considéré comme une mémoire optimisée, pas comme une fiche descriptive.

---

## Que doit contenir le Persona ?

Sans mémoire permanente, le Persona doit regrouper toutes les informations indispensables au bot.

Selon la place disponible, on cherchera généralement à inclure :

- l'identité du personnage ;
- son apparence ;
- sa personnalité ;
- son histoire condensée ;
- ses capacités importantes ;
- ses relations principales ;
- son fonctionnement ;
- sa résidence si elle joue un rôle important.

En pratique, il est rare de pouvoir développer chacune de ces catégories.

Il faut donc condenser fortement les informations et ne conserver que ce qui apporte une réelle valeur au roleplay.

Par exemple, quelques mots décrivant une capacité emblématique seront souvent plus utiles qu'un long historique racontant son apprentissage.

De la même manière, quelques éléments clés concernant les relations importantes auront davantage d'impact qu'une liste exhaustive de personnages secondaires.

L'objectif est toujours le même :

**offrir au bot le maximum d'informations utiles avec le minimum de caractères.**

## Organiser les 1500 caractères

Lorsque l'on ne dispose pas de la mémoire permanente, le véritable défi n'est pas de savoir quoi écrire, mais de décider quelles informations méritent réellement d'occuper l'espace disponible.

Les 1500 caractères partent très vite.

Il est donc préférable de raisonner par ordre de priorité plutôt que de chercher à remplir chaque catégorie de manière équilibrée.

Les informations qui définissent durablement votre personnage doivent toujours passer avant les détails.

Par exemple, si vous manquez de place, il sera généralement plus pertinent de conserver une capacité emblématique, une relation importante ou un élément central de son histoire que plusieurs descriptions secondaires.

Cherchez toujours à répondre à une question simple :

> **Quelles informations le bot doit-il absolument connaître pour comprendre immédiatement mon personnage ?**

Tout le reste devient secondaire.

N'hésitez pas à condenser fortement les formulations.

Le Persona n'est pas un texte destiné à être agréable à lire. C'est une mémoire optimisée pour un LLM.

Chaque caractère économisé permet d'ajouter une information utile.

---

## Garder de la place pour les événements importants

Lorsque c'est possible, évitez d'utiliser immédiatement les 1500 caractères disponibles.

Essayez de conserver une petite réserve afin de pouvoir ajouter ultérieurement quelques événements majeurs ayant réellement modifié votre personnage ou ses relations.

Par exemple :

- un changement durable dans une relation importante ;
- un événement ayant profondément marqué votre personnage ;
- une évolution qui influence désormais son comportement ;
- une décision importante qui continuera d'avoir des conséquences.

L'objectif n'est pas de transformer le Persona en journal de bord.

Il ne doit contenir que les événements dont le bot devra encore tenir compte plusieurs scènes ou plusieurs conversations plus tard.

Cette réserve est évidemment très limitée.

Au fil d'un long roleplay, vous devrez parfois supprimer ou condenser d'anciens éléments afin de faire de la place pour les nouveaux.

---

## Les limites de cette méthode

Même correctement construit, un Persona ne remplacera jamais la mémoire permanente.

Avec seulement 1500 caractères, il est impossible de conserver durablement une histoire riche, de nombreuses relations ou un grand nombre d'évolutions importantes.

Cette méthode permet surtout de ralentir la perte d'informations en donnant au bot les éléments les plus utiles pour continuer à jouer correctement votre personnage.

Plus un roleplay devient long, plus il faudra faire des choix concernant les informations à conserver.

Si vous utilisez régulièrement PolyBuzz pour des scénarios de longue durée, la mémoire permanente apportera une amélioration significative en prenant en charge les informations d'identité les plus stables.

Le Persona pourra alors être utilisé différemment, ce que nous allons voir dans la partie suivante.

# 💾 Partie 2 — Avec mémoire permanente

## Ce qui change

La mémoire permanente modifie complètement la manière de construire un Persona.

Sans mémoire permanente, le Persona devait contenir l'ensemble des informations importantes concernant votre personnage.

Avec la mémoire permanente, ce n'est plus le cas.

Une grande partie des informations stables est désormais stockée automatiquement dans la mémoire permanente et injectée au bot à chaque génération de réponse.

Le Persona n'a donc plus vocation à être une fiche complète.

Il devient un complément destiné à fournir au bot les informations qui ne trouvent pas naturellement leur place dans la mémoire permanente.

Cette nouvelle répartition permet d'utiliser les 1500 caractères beaucoup plus intelligemment.

Au lieu de répéter des informations déjà présentes, vous pouvez consacrer cet espace à enrichir le comportement du bot en jeu.

---

## Ce qui n'a plus besoin d'être écrit

La mémoire permanente permet déjà de renseigner plusieurs catégories importantes.

Il devient donc inutile de les recopier dans le Persona.

Selon votre utilisation, cela concerne notamment :

- l'identité du personnage ;
- son âge ;
- son apparence ;
- sa personnalité condensée ;
- sa résidence ;
- son orientation sexuelle.

En répétant ces informations dans le Persona, vous gaspillez une partie des 1500 caractères disponibles sans réellement apporter d'informations supplémentaires au bot.

L'objectif est justement d'éviter les doublons.

Chaque caractère économisé pourra être utilisé pour des informations que la mémoire permanente ne peut pas stocker aussi facilement.

---

## Ce que le Persona doit maintenant contenir

Une fois les informations d'identité prises en charge par la mémoire permanente, le Persona peut se concentrer sur des éléments beaucoup plus utiles au roleplay.

On y retrouvera par exemple :

- les relations importantes ;
- les capacités ;
- le fonctionnement du personnage ;
- son histoire condensée ;
- tout contexte utile que le bot doit connaître en permanence.

Le Persona devient ainsi une extension de la mémoire permanente plutôt qu'un remplacement.

Cette répartition permet généralement d'obtenir un personnage beaucoup plus cohérent sur la durée.

---

## Le fonctionnement n'est pas la personnalité

C'est une distinction importante.

La personnalité décrit **qui est** votre personnage.

Le fonctionnement décrit **comment il réfléchit, analyse les situations et prend ses décisions**.

Par exemple, une personnalité pourra être résumée par quelques traits dans la mémoire permanente.

En revanche, le Persona pourra préciser son fonctionnement de manière beaucoup plus concrète :

> analyse vite ; lit bien les gens ; identifie rapidement l'essentiel ; décide puis agit ; s'adapte rapidement ; corrige vite ses erreurs ; très efficace sous pression.

Ce type d'information est particulièrement utile au bot.

Il ne s'agit plus d'une simple description du personnage, mais d'une manière d'expliquer sa logique de fonctionnement.

Le bot comprend alors plus facilement pourquoi votre personnage réagit d'une certaine façon dans une scène et adapte naturellement son propre comportement en conséquence.

Le fonctionnement vient donc compléter la personnalité.

Il ne la remplace pas.

## Écrire correctement les relations

Les relations sont probablement l'une des parties les plus importantes du Persona.

Elles permettent au bot de comprendre immédiatement la place qu'occupent les différents personnages dans la vie du vôtre, sans avoir à reconstruire progressivement ces liens au fil de la conversation.

En revanche, toutes les relations ne s'écrivent pas de la même manière.

---

### La relation avec le bot

La relation avec le bot doit toujours être écrite **uniquement du point de vue du personnage joueur**.

Autrement dit, vous décrivez ce que **votre personnage ressent, pense ou considère** à propos du bot.

Par exemple :

> Relation à Kawaki : Drisnel reste réellement attirée par lui ; leur relation a été abîmée par la manière dont Kawaki a géré les événements ; malgré cela, elle ne considère pas ce qu'ils ont vécu comme quelque chose de léger ou d'effaçable.

Cette formulation informe le bot sur votre personnage.

Elle ne lui impose jamais ce que **lui** ressent.

Il est important d'éviter d'écrire des phrases comme :

- Kawaki est toujours amoureux de Drisnel.
- Kawaki lui fait totalement confiance.
- Kawaki regrette profondément leur séparation.

Ces informations appartiennent au personnage du bot.

Elles doivent être définies dans son propre script et évoluer naturellement au cours du roleplay.

Les imposer depuis le Persona risque de perturber son fonctionnement ou de contourner la progression prévue par son script.

---

### Les relations avec les autres personnages

Les autres personnages ne sont pas le bot.

Vous pouvez donc décrire ces relations de manière beaucoup plus libre.

Il est tout à fait possible d'écrire des relations bilatérales lorsque celles-ci sont déjà établies.

Par exemple :

> Boruto : entente vive et naturelle ; franchise ; loyauté ; goût du mouvement.

> Sarada : respect mutuel solide ; relation franche et stable.

> Mitsuki : relation calme ; compréhension fine.

Ces informations servent simplement à fournir un contexte relationnel cohérent.

Elles ne modifient pas directement le comportement du bot principal.

---

## Exemple complet

Voici un exemple de Persona utilisé avec la mémoire permanente.

L'identité, l'apparence, la personnalité et les autres informations stables étant déjà enregistrées dans la mémoire permanente, le Persona peut se concentrer sur les éléments qui enrichissent directement le roleplay.

```text
Relation à Kawaki : Drisnel reste réellement attirée par lui ; leur relation a été abîmée par la manière dont Kawaki a géré les événements ; malgré cela, elle ne considère pas ce qu'ils ont vécu comme quelque chose de léger ou d'effaçable.

Autres relations : Boruto, entente vive et naturelle, franchise, loyauté, goût du mouvement. Sarada, respect mutuel solide, relation franche et stable. Mitsuki, relation calme, compréhension fine. Naruto, respect sincère sans idéalisation ; apprécie sa fiabilité et son indépendance. Sasuke, respect net et mesuré ; reconnaissance mutuelle de leurs capacités.

Capacités : prodige du Fūinjutsu offensif ; spécialiste du contrôle du terrain ; maîtrise également le Doton et le Bōjutsu. Créatrice et seule utilisatrice de Kagi, bâton contenant plus de cent sceaux, matrices et systèmes complexes préchargés, déployés instantanément par contact. Insei : sceau médical sur la langue ; activé par bouche contre bouche ; permet l'auto-soin ou le soin direct d'un allié.

Histoire : prodige du clan Aoyama sans en être l'héritière ; devient Jōnin très tôt ; refuse l'ANBU ; développe un Fūinjutsu offensif atypique pensé pour le terrain, l'imprévu et les brèches tactiques ; sert Konoha sans renoncer à son autonomie.

Fonctionnement : analyse vite ; lit bien les gens ; identifie rapidement l'essentiel ; décide puis agit ; s'adapte rapidement ; supporte mal la stagnation ; corrige vite ses erreurs ; très efficace sous pression.
```

Ce type de Persona n'est pas écrit comme un texte narratif.

Chaque catégorie constitue un bloc d'informations immédiatement exploitable par le LLM.

L'objectif n'est pas d'écrire une belle présentation du personnage, mais de transmettre le maximum d'informations utiles avec le minimum de caractères.

# 🧠 Partie 3 — Bonnes pratiques communes

Les conseils présentés dans cette partie s'appliquent aussi bien aux utilisateurs disposant de la mémoire permanente qu'à ceux qui utilisent uniquement le Persona.

Ils ne concernent pas le contenu du Persona, mais la manière de l'écrire afin qu'il soit le plus facilement exploitable possible par le LLM.

---

## Écrire pour un LLM

Le Persona n'est pas destiné à être lu par un humain.

Il est destiné à être interprété par un LLM.

Il ne faut donc pas chercher à écrire un texte littéraire, une biographie ou une fiche personnage agréable à lire.

Au contraire, privilégiez une écriture dense, directe et immédiatement exploitable.

Chaque catégorie doit transmettre un maximum d'informations utiles avec un minimum de caractères.

Par exemple, préférez :

> analyse vite ; lit bien les gens ; identifie rapidement l'essentiel ; décide puis agit.

plutôt que :

> Drisnel analyse rapidement les situations. Elle comprend facilement les autres et prend rapidement ses décisions.

La seconde formulation est plus naturelle pour un lecteur humain.

La première est plus dense, plus concise et laisse davantage de place aux informations réellement utiles.

---

## Utiliser efficacement la ponctuation

Dans un Persona, la ponctuation ne sert pas uniquement à respecter les règles du français.

Elle permet également de structurer l'information.

Une convention simple fonctionne particulièrement bien :

- **:** introduit une catégorie.
- **,** relie des informations très proches.
- **;** sépare plusieurs idées au sein d'une même catégorie.
- **.** termine uniquement la catégorie.

Évitez de multiplier les points à l'intérieur d'un même paragraphe.

Le point clôt une idée.

Lorsque plusieurs phrases courtes se succèdent, le bloc d'information devient plus fragmenté.

Les virgules et les points-virgules permettent au contraire d'organiser plusieurs informations tout en conservant une seule unité logique.

---

## Optimiser les 1500 caractères

L'espace disponible est extrêmement limité.

Chaque caractère économisé peut être utilisé pour ajouter une information utile.

Quelques habitudes permettent de gagner facilement de la place :

- supprimer les espaces inutiles lorsque la limite est atteinte ;
- éviter les mots de liaison lorsqu'ils n'apportent rien ;
- condenser les formulations ;
- supprimer les répétitions ;
- privilégier des informations utiles plutôt que des formulations élégantes.

Le but n'est pas d'obtenir un texte agréable à lire.

Le but est de transmettre le plus d'informations pertinentes possible.

---

## Erreurs fréquentes

Voici quelques erreurs souvent rencontrées lors de la création d'un Persona :

- écrire comme un roman ou une biographie ;
- gaspiller des caractères avec des formulations inutilement longues ;
- confondre personnalité et fonctionnement ;
- définir les pensées ou les sentiments du bot dans la relation avec le personnage joueur ;
- recopier dans le Persona des informations déjà présentes dans la mémoire permanente ;
- vouloir tout faire tenir sans hiérarchiser les informations.

Le Persona est une mémoire condensée.

Il doit aller à l'essentiel.

---

## Observations issues des tests

Les remarques suivantes proviennent d'observations réalisées au cours de nombreux tests sur PolyBuzz.

Elles ne constituent pas une documentation officielle de la plateforme.

Le Persona semble parfois être moins systématiquement exploité que la mémoire permanente.

Il peut arriver que certaines informations présentes dans le Persona soient momentanément moins prises en compte par le bot.

Dans ce cas, une simple modification du Persona, même minime (par exemple l'ajout ou la suppression d'un espace ou d'un caractère), suivie d'un nouvel enregistrement, semble parfois permettre à PolyBuzz de recharger correctement son contenu.

Ce comportement n'est pas systématique, mais il peut être utile à connaître lorsqu'un bot semble soudainement moins tenir compte du Persona.

---

# Conclusion

Le Persona est l'un des outils les plus importants mis à disposition par PolyBuzz.

Bien construit, il permet au bot de comprendre rapidement votre personnage, de mieux interpréter ses réactions et de conserver une cohérence bien supérieure au fil des conversations.

La stratégie à adopter dépend toutefois de votre situation.

Sans mémoire permanente, le Persona devient la mémoire principale du bot et doit contenir l'essentiel de votre personnage malgré la limite des 1500 caractères.

Avec la mémoire permanente, il devient un complément spécialisé permettant d'enrichir le comportement du bot avec des informations que la mémoire permanente ne stocke pas naturellement.

Dans les deux cas, gardez toujours le même objectif :

**écrire pour le LLM, pas pour un lecteur humain.**

Plus votre Persona est clair, dense et structuré, plus le bot sera capable de comprendre rapidement votre personnage et de produire un roleplay cohérent sur la durée.