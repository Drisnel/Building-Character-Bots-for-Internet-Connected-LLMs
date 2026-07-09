# Building RP Bots for Internet-Connected LLMs

## 🇬🇧 English

Documentation, practical workflows, production templates, and platform-specific guides for building roleplay bots for internet-connected LLMs.

This repository focuses on long-term behavioral stability, practical script architecture, player experience, and advanced platform features that help create roleplay bots capable of remaining engaging over extended interactions.

Rather than presenting universal rules, this repository documents the workflows, scripting methods, and observations that currently produce the most consistent results throughout my own projects.

## 🇫🇷 Français

Documentation, méthodes de travail, templates de production et guides dédiés à certaines plateformes pour créer des bots de roleplay destinés à des LLM connectés à Internet.

Ce dépôt met l'accent sur la stabilité comportementale à long terme, l'architecture pratique des scripts, l'expérience du joueur et les fonctionnalités avancées de certaines plateformes permettant de créer des bots capables de rester cohérents et agréables à jouer sur de longues interactions.

Plutôt que de proposer des règles universelles, ce dépôt documente les workflows, les méthodes d'écriture et les observations qui produisent actuellement les résultats les plus cohérents dans mes propres projets.

---

# 🧭 New to the Repository

## 🇬🇧 English

This repository is organized into **two complementary parts**.

The first documents a complete methodology for designing stable and engaging roleplay bots, including design principles, production workflows, and script templates.

The second documents platform-specific features that can significantly improve long-term roleplay when properly understood and used.

If this is your first time reading the repository, I recommend following the order below.

### Core Methodology

1. How to Build Participating Characters
2. How to Protect Player Agency in RP Bots
3. How to Build Anti-Loop Systems for RP Bots
4. How to Build Specialized Modules for RP Bots
5. How to Test and Debug RP Bots
6. Canon or Original Workflow
7. Introduction and Starter Workflow
8. Production Templates

### Platform Guides *(Optional)*

These guides are independent from the main methodology and should only be read if you use the corresponding platform.

Currently available:

- PolyBuzz Permanent Memory
- PolyBuzz Persona

## 🇫🇷 Français

Ce dépôt est organisé en **deux parties complémentaires**.

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

### Guides des plateformes *(Optionnel)*

Ces guides sont indépendants de la méthodologie principale et ne sont utiles que si vous utilisez la plateforme concernée.

Actuellement disponibles :

- Mémoire permanente de PolyBuzz
- Persona de PolyBuzz

---

# 🛡️ Shared Guides

## 🇬🇧 English

These documents introduce the core design principles used throughout the repository.

They apply equally to canon and original characters, regardless of the platform on which the bot will be used.

- [How to Build Participating Characters](./shared/en/how-to-build-participating-characters.md)
- [How to Protect Player Agency in RP Bots](./shared/en/how-to-protect-player-agency-in-rp-bots.md)
- [How to Build Anti-Loop Systems for RP Bots](./shared/en/how-to-build-anti-loop-systems-for-rp-bots.md)
- [How to Build Specialized Modules for RP Bots](./shared/en/how-to-build-specialized-modules-for-rp-bots.md)
- [How to Test and Debug RP Bots](./shared/en/how-to-test-and-debug-rp-bots.md)

## 🇫🇷 Français

Ces documents présentent les principes de conception utilisés dans l'ensemble du dépôt.

Ils s'appliquent aussi bien aux personnages canon qu'aux personnages originaux, quelle que soit la plateforme utilisée.

- [Comment construire des personnages participatifs](./shared/fr/comment-construire-des-personnages-participatifs.md)
- [Comment protéger l'agence du joueur dans les bots de roleplay](./shared/fr/comment-proteger-lagence-du-joueur-dans-les-bots-rp.md)
- [Comment construire des systèmes anti-loop pour les bots de roleplay](./shared/fr/comment-construire-des-systemes-anti-loop-pour-les-bots-rp.md)
- [Comment construire des modules spécialisés pour les bots RP](./shared/fr/comment-construire-des-modules-specialises-pour-les-bots-rp.md)
- [Comment tester et debugger des bots de roleplay](./shared/fr/comment-tester-et-debugger-des-bots-rp.md)

---

# 🎭 Canon Bots

## 🇬🇧 English

These workflows are dedicated to building canon characters while preserving their behavioral identity, long-term consistency, and natural progression throughout extended roleplay.

They focus on analyzing the original source material, identifying common model and fandom distortions, and translating that analysis into stable production-ready scripts.

- [Canon Character Workflow](./canon/en/Core-Workflow.md)
- [Canon Introduction and Starter Workflow](./canon/en/canon-introduction-and-starter-workflow.md)

## 🇫🇷 Français

Ces workflows sont consacrés à la création de personnages canon tout en préservant leur identité comportementale, leur cohérence à long terme et leur évolution naturelle au fil du roleplay.

Ils mettent l'accent sur l'analyse de l'œuvre d'origine, l'identification des déformations courantes des modèles et du fandom, puis leur traduction en scripts stables prêts à être utilisés.

- [Méthode de construction de personnages canon](./canon/fr/Core-Workflow-francais.md)
- [Méthode de création des introductions et démarrages pour bots canons](./canon/fr/creation-introduction-demarrage-bot-canon-connecte-internet.md)

---

# 🧩 Original Bots

## 🇬🇧 English

These workflows explain how to design original characters from the ground up while maintaining coherent behavior, believable progression, and strong player interaction over long conversations.

Rather than adapting an existing character, they focus on transforming an original concept into a complete RP bot.

- [How to Build Original Bots](./original/en/how-to-build-original-bots.md)
- [How to Build Openings for Original Bots](./original/en/how-to-build-openings-for-original-bots.md)

## 🇫🇷 Français

Ces workflows expliquent comment concevoir des personnages originaux à partir de zéro tout en conservant une évolution cohérente, des comportements crédibles et une interaction durable avec le joueur.

Au lieu d'adapter un personnage existant, ils montrent comment transformer un concept original en un bot de roleplay complet.

- [Comment créer un bot original](./original/fr/comment-creer-un-bot-original.md)
- [Comment créer des ouvertures pour des bots originaux](./original/fr/comment-creer-des-ouvertures-pour-des-bots-originaux.md)

---

# 🧱 Production Templates

## 🇬🇧 English

Once a workflow has been completed, these templates provide a standardized structure for assembling the final bot script.

They are **not** tutorials or workflows themselves. Instead, they represent the final production format generated by the methods documented throughout this repository.

- [Canon Script Template](./templates/en/canon-script-template.md)
- [Original Script Template](./templates/en/original-script-template.md)

## 🇫🇷 Français

Une fois un workflow terminé, ces templates fournissent une structure standardisée permettant d'assembler le script final du bot.

Il ne s'agit **ni de tutoriels ni de workflows**, mais du format de production obtenu après avoir appliqué les méthodes documentées dans ce dépôt.

- [Template de script canon](./templates/fr/template-script-bot-canon.md)
- [Template de script original](./templates/fr/template-script-bot-original.md)

---

# 🖥️ Platform Guides

## 🇬🇧 English

Unlike the previous sections, these guides focus on features that are specific to individual roleplay platforms.

They document observed behaviors, advanced features, practical workflows, and usage recommendations based on extensive testing.

These documents complement the repository's methodology but can also be read independently.

### PolyBuzz

- [How to Understand and Use PolyBuzz Permanent Memory](./platforms/polybuzz/en/how-to-understand-and-use-polybuzz-permanent-memory.md)
- [How to Build an Effective PolyBuzz Persona](./platforms/polybuzz/en/how-to-build-an-effective-polybuzz-persona.md)

## 🇫🇷 Français

Contrairement aux sections précédentes, ces guides sont consacrés aux fonctionnalités propres à certaines plateformes de roleplay.

Ils documentent les comportements observés, les fonctionnalités avancées, les méthodes de travail et les recommandations d'utilisation issues de nombreux tests.

Ces documents complètent la méthodologie du dépôt mais peuvent également être lus indépendamment.

### PolyBuzz

- [Comment comprendre et exploiter la mémoire permanente de PolyBuzz](./platforms/polybuzz/fr/comment-comprendre-et-exploiter-la-memoire-permanente-de-polybuzz.md)
- [Comment construire un Persona PolyBuzz efficace](./platforms/polybuzz/fr/comment-construire-un-persona-polybuzz-efficace.md)

---

# 📁 Repository Structure

## 🇬🇧 English

The repository is divided into two complementary areas.

### Core Methodology

Documentation dedicated to designing stable and engaging RP bots, regardless of the platform.

- `shared/` — Core design principles used throughout the repository.
- `canon/` — Workflows dedicated to canon characters.
- `original/` — Workflows dedicated to original characters.
- `templates/` — Production-ready script templates.

### Platform Documentation

Documentation dedicated to features and workflows specific to individual roleplay platforms.

- `platforms/`
  - `polybuzz/`
    - `en/`
    - `fr/`

Whenever possible, every document is available in both English and French.

## 🇫🇷 Français

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

# ℹ️ About This Repository

## 🇬🇧 English

This repository combines **two complementary objectives**.

The first is to document practical methods for designing stable, engaging, and long-lasting roleplay bots for internet-connected LLMs.

The second is to document advanced platform-specific features that can significantly improve long-term roleplay when properly understood and used.

Everything published here is based on my own research, experimentation, and practical experience.

The workflows, scripting methods, templates, and platform guides presented throughout this repository are **not intended to be universal rules**.

Instead, they document the approaches, observations, and production methods that currently produce the most consistent results throughout my own projects.

As both LLMs and RP platforms continue to evolve, this repository will continue evolving alongside them.

## 🇫🇷 Français

Ce dépôt poursuit **deux objectifs complémentaires**.

Le premier est de documenter des méthodes concrètes permettant de concevoir des bots de roleplay stables, cohérents et agréables à jouer pour des LLM connectés à Internet.

Le second est de documenter les fonctionnalités avancées propres à certaines plateformes pouvant améliorer considérablement les roleplays de longue durée lorsqu'elles sont correctement comprises et exploitées.

L'ensemble des documents publiés ici est basé sur mes propres recherches, expérimentations et retours d'expérience.

Les workflows, méthodes d'écriture, templates et guides de plateformes présentés dans ce dépôt **n'ont pas vocation à constituer des règles universelles**.

Ils documentent simplement les approches, les observations et les méthodes de production qui produisent actuellement les résultats les plus cohérents dans mes propres projets.

À mesure que les LLM et les plateformes de roleplay évolueront, ce dépôt évoluera avec eux.

---

# 🤖 Public Bot Examples

## 🇬🇧 English

If you'd like to see these methods applied in practice, several public bots built using the workflows and design principles documented throughout this repository are available on my PolyBuzz profile.

**PolyBuzz Profile**

https://polybuzz.ai/su/XszqPReuNlR

## 🇫🇷 Français

Si vous souhaitez voir cette méthodologie appliquée en pratique, plusieurs bots publics construits à partir des workflows et des principes de conception présentés dans ce dépôt sont disponibles sur mon profil PolyBuzz.

**Profil PolyBuzz**

https://polybuzz.ai/su/XszqPReuNlR

---

# 🚀 Repository Roadmap

## 🇬🇧 English

This repository is an ongoing project.

New documentation will continue to expand both the core methodology and the platform-specific documentation as new workflows, production methods, and platform features are explored.

The goal is to build a comprehensive knowledge base for creating stable, engaging, and long-lasting roleplay bots for internet-connected LLMs.

## 🇫🇷 Français

Ce dépôt est un projet en constante évolution.

De nouveaux documents viendront progressivement enrichir aussi bien la méthodologie générale que la documentation consacrée aux plateformes, au fur et à mesure des nouvelles expérimentations, des nouvelles méthodes de production et des nouvelles fonctionnalités explorées.

L'objectif est de construire une base de connaissances complète consacrée à la création de bots de roleplay stables, cohérents et agréables à jouer pour des LLM connectés à Internet.