# Documentation française

Bienvenue dans la documentation française de **Building RP Bots for Internet-Connected LLMs**.

Ce dépôt documente des méthodes pratiques pour concevoir des bots de roleplay destinés à des LLM connectés à Internet.

Il rassemble des workflows de production, des méthodes d'écriture, des principes de conception, des templates de scripts ainsi que des guides consacrés aux fonctionnalités propres à certaines plateformes, le tout basé sur des expérimentations et des tests réalisés en conditions réelles.

Plutôt que de proposer des règles universelles, ce dépôt documente les workflows, les méthodes d'écriture et les observations qui produisent actuellement les résultats les plus cohérents dans mes propres projets.

---

# 🧭 1. Nouveau sur le dépôt

Cette documentation est organisée en **deux parties complémentaires**.

La première documente une méthodologie complète pour concevoir des bots de roleplay stables et agréables à jouer, comprenant les principes de conception, les workflows de production et les templates de scripts.

La seconde documente des fonctionnalités propres à certaines plateformes pouvant améliorer considérablement les roleplays de longue durée lorsqu'elles sont correctement comprises et exploitées.

Si vous découvrez ce dépôt, je vous recommande l'ordre de lecture suivant.

### Méthodologie principale

1. Comment construire des personnages participatifs
2. Comment protéger l'agence du joueur dans les bots de roleplay
3. Comment construire des systèmes anti-loop pour les bots de roleplay
4. Comment construire des modules spécialisés pour les bots RP
5. Comment tester et debugger des bots de roleplay
6. Workflow canon ou original
7. Workflow des introductions et démarrages
8. Templates de production

### Guides des plateformes *(optionnel)*

Ces guides sont indépendants de la méthodologie principale et ne sont utiles que si vous utilisez la plateforme concernée.

Actuellement disponibles :

- Mémoire permanente de PolyBuzz
- Persona de PolyBuzz

---

# 🛡️ 2. Guides communs

Ces documents présentent les principes de conception utilisés dans l'ensemble du dépôt.

Ils s'appliquent aussi bien aux personnages canon qu'aux personnages originaux, quelle que soit la plateforme utilisée.

- [Comment construire des personnages participatifs](./shared/fr/comment-construire-des-personnages-participatifs.md)
- [Comment protéger l'agence du joueur dans les bots de roleplay](./shared/fr/comment-proteger-lagence-du-joueur-dans-les-bots-rp.md)
- [Comment construire des systèmes anti-loop pour les bots de roleplay](./shared/fr/comment-construire-des-systemes-anti-loop-pour-les-bots-rp.md)
- [Comment construire des modules spécialisés pour les bots RP](./shared/fr/comment-construire-des-modules-specialises-pour-les-bots-rp.md)
- [Comment tester et debugger des bots de roleplay](./shared/fr/comment-tester-et-debugger-des-bots-rp.md)

---

# 🎭 3. Personnages canon

Ces workflows sont consacrés à la création de personnages canon tout en préservant leur identité comportementale, leur cohérence à long terme et leur évolution naturelle au fil du roleplay.

Ils mettent l'accent sur l'analyse de l'œuvre d'origine, l'identification des déformations courantes des modèles et du fandom, puis leur traduction en scripts stables prêts à être utilisés.

- [Méthode de construction de personnages canon](./canon/fr/Core-Workflow-francais.md)
- [Méthode de création des introductions et démarrages pour bots canons](./canon/fr/creation-introduction-demarrage-bot-canon-connecte-internet.md)

---

# 🧩 4. Personnages originaux

Ces workflows expliquent comment concevoir des personnages originaux à partir de zéro tout en conservant une évolution cohérente, des comportements crédibles et une interaction durable avec le joueur.

Au lieu d'adapter un personnage existant, ils montrent comment transformer un concept original en un bot de roleplay complet.

- [Comment créer un bot original](./original/fr/comment-creer-un-bot-original.md)
- [Comment créer des ouvertures pour des bots originaux](./original/fr/comment-creer-des-ouvertures-pour-des-bots-originaux.md)

---

# 🧱 5. Templates de production

Une fois un workflow terminé, ces templates fournissent une structure standardisée permettant d'assembler le script final du bot.

Il ne s'agit **ni de tutoriels ni de workflows**, mais du format de production obtenu après avoir appliqué les méthodes documentées dans ce dépôt.

- [Template de script canon](./templates/fr/template-script-bot-canon.md)
- [Template de script original](./templates/fr/template-script-bot-original.md)

---

# 🖥️ 6. Guides des plateformes

Contrairement aux sections précédentes, ces guides sont consacrés aux fonctionnalités propres à certaines plateformes de roleplay.

Ils documentent les comportements observés, les fonctionnalités avancées, les méthodes de travail et les recommandations d'utilisation issues de nombreux tests.

Ces documents complètent la méthodologie du dépôt mais peuvent également être lus indépendamment.

### PolyBuzz

- [Comment comprendre et exploiter la mémoire permanente de PolyBuzz](./platforms/polybuzz/fr/comment-comprendre-et-exploiter-la-memoire-permanente-de-polybuzz.md)
- [Comment construire un Persona PolyBuzz efficace](./platforms/polybuzz/fr/comment-construire-un-persona-polybuzz-efficace.md)

---

# 📁 7. Structure du dépôt

Le dépôt est organisé en deux ensembles complémentaires.

### Méthodologie

Documentation consacrée à la conception de bots de roleplay, indépendamment de la plateforme utilisée.

- `shared/` — Les principes de conception communs à l'ensemble du dépôt.
- `canon/` — Les workflows dédiés aux personnages canon.
- `original/` — Les workflows dédiés aux personnages originaux.
- `templates/` — Les templates de production permettant de construire les scripts finaux.

### Documentation des plateformes

Documentation consacrée aux fonctionnalités et aux méthodes propres à certaines plateformes de roleplay.

- `platforms/`
  - `polybuzz/`
    - `en/`
    - `fr/`

Dans la mesure du possible, chaque document est proposé en français et en anglais.

---

# ℹ️ 8. À propos de ce dépôt

Ce dépôt poursuit **deux objectifs complémentaires**.

Le premier est de documenter des méthodes concrètes permettant de concevoir des bots de roleplay stables, cohérents et agréables à jouer pour des LLM connectés à Internet.

Le second est de documenter les fonctionnalités avancées propres à certaines plateformes pouvant améliorer considérablement les roleplays de longue durée lorsqu'elles sont correctement comprises et exploitées.

L'ensemble des documents publiés ici est basé sur mes propres recherches, expérimentations et retours d'expérience.

Les workflows, méthodes d'écriture, templates et guides de plateformes présentés dans ce dépôt **n'ont pas vocation à constituer des règles universelles**.

Ils documentent simplement les approches, les observations et les méthodes de production qui produisent actuellement les résultats les plus cohérents dans mes propres projets.

À mesure que les LLM et les plateformes de roleplay évolueront, ce dépôt évoluera avec eux.

---

# 🤖 9. Exemples de bots publics

Si vous souhaitez voir cette méthodologie appliquée en pratique, plusieurs bots publics construits à partir des workflows et des principes de conception présentés dans ce dépôt sont disponibles sur mon profil PolyBuzz.

**Profil PolyBuzz**

https://polybuzz.ai/su/XszqPReuNlR

---

# 🚀 10. Feuille de route

Ce dépôt est un projet en constante évolution.

De nouveaux documents viendront progressivement enrichir aussi bien la méthodologie générale que la documentation consacrée aux plateformes, au fur et à mesure des nouvelles expérimentations, des nouvelles méthodes de production et des nouvelles fonctionnalités explorées.

L'objectif est de construire une base de connaissances complète consacrée à la création de bots de roleplay stables, cohérents et agréables à jouer pour des LLM connectés à Internet.