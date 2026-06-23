# How to Build Specialized Modules for RP Bots

This guide is for building specialized modules that do not fit cleanly inside a script’s core blocks, but still remain structurally important to the bot.

It applies to both canon bots and original bots.

It does not replace the construction workflows.
It does not replace the final script templates.
It does not replace testing / debugging either.

Its role is different:

- help identify when a bot needs a specialized module
- help decide whether that module should be autonomous or not
- help determine where it should be placed in the script hierarchy
- help define what actually needs to be written inside it
- help connect that module to the rest of the script
- help test whether that module actually holds up in RP
- help revise its hierarchy, scope, or writing after testing if necessary

This guide is not meant for adding modules “by feel.”
I do not recommend creating a specialized module blindly.

In practice, I work with an AI agent such as ChatGPT, Claude, or Gemini to build the bot’s structure with me:
- audit whether a module is actually necessary
- determine whether it should be autonomous or not
- suggest where it should be placed in the script
- identify which other blocks need to be adjusted if it is added
- draft the module after the audit, based on my instructions and validation
- re-evaluate its placement, form, or priority after testing and debugging

The AI does not replace the final decision.
It is used as a tool for structural analysis, hierarchy decisions, writing, and structural revision.

The issue is not just that a bot may have “extra things.”
The real issue is that many bots are not primarily structured by their relationship with the user.

Some are driven mainly by:
- combat
- politics
- hierarchy
- religion
- survival
- investigation
- duty
- criminality
- command logic
- family structure
- professional logic
- a supernatural mechanic
- an ability or technical system
- or another system that continues to govern the character’s behavior once the RP begins

If that kind of structure is too important to remain implicit, but too specific to be scattered across several general blocks, it often needs a specialized module.

The goal is not to multiply modules just to make the script look richer.
The goal is to give clear form to the structures that actually govern the bot, so they remain active in its decisions, scenes, conflicts, continuity, and progression.

---

# 1. A specialized module is not a “bonus”

A common mistake is to treat specialized modules as simple optional additions placed at the end of a script.

That is not how I approach them.

A specialized module is not there to “add a detail.”
It exists to isolate a structure that influences the bot too strongly to remain diffuse.

In other words, a specialized module is useful when an element:

- directly influences the character’s decision logic
- influences the kinds of scenes the bot generates
- influences how the bot handles conflict, pressure, attachment, duty, violence, shame, survival, power, or vulnerability
- continues to produce consequences over time
- would be handled badly if it were scattered across several relational or general blocks

A specialized module is therefore not defined by its theme.
It is defined by its **structural weight**.

A bot does not need a specialized module simply because it “has a religion,” “can fight,” “has a job,” or “has an ability.”

It needs a specialized module if that religion, combat logic, job, or ability actually governs the bot’s behavior strongly enough to deserve autonomous treatment.

---

# 2. Do not create a specialized module blindly

Before opening a specialized module, I do not simply start from an isolated intuition like:
> “This topic seems important, so I’ll give it a block.”

I work with an AI agent such as ChatGPT, Claude, or Gemini to audit the bot with me.

The goal is not to let the model decide in my place.
The goal is to have it examine the bot’s structure based on the concept, canon if relevant, setting, scene engines, conflicts, archetypal bias, and model-drift risks.

Concretely, I might ask it:

- whether the axis I’m considering deserves its own module
- whether it is truly central or only secondary
- whether it should be handled inside an existing block instead of opening a new module
- which other blocks it is likely to influence
- whether it should be placed before or after relational blocks
- what fallback, looping, or flattening risks it may create

A specialized module is therefore not just “an idea for a block.”
It is a structure that is audited, prioritized, and then written.

---

# 3. When a specialized module is necessary

I do not create a specialized module simply because a topic exists in the lore or in the concept.

I create it when that topic fulfills at least part of the following functions.

## A. It governs decisions more strongly than a general block does

Examples:
- a character whose command logic structures most of their decisions
- a character whose relationship to faith, ritual, or taboo filters nearly all interactions
- a character whose survival or investigative logic shapes scenes more strongly than romance or attachment
- a character whose political role governs how they speak, negotiate, threaten, yield, protect, or sacrifice
- a character whose ability, technique, or combat system determines their relationship to risk, violence, the body, strategy, or control

If an axis like this governs behavior more strongly than relational blocks do, it often deserves an autonomous module.

## B. It generates scenes on its own

A specialized module is often necessary when it acts as a recurring scene engine.

Examples:
- a criminal network that generates visits, debts, threats, negotiations, and sanctions
- a military structure that generates orders, departures, power struggles, failures, punishments, and loyalty dilemmas
- a public career that generates surveillance, rumors, image management, opportunities, and media pressure
- a survival structure that generates movement, rationing, danger, exhaustion, injuries, and urgent choices
- an ability or technical system that generates training, control, accidents, secrecy, dependence, tactical use, physical cost, or surveillance

If a system regularly feeds the RP with movement, it should not remain a secondary note buried in another block.

## C. It strongly modifies conflict, attachment, or vulnerability

Sometimes a specialized module does not directly generate scenes, but it profoundly changes how the character handles:

- conflict
- trust
- intimacy
- shame
- dependence
- fear
- authority
- guilt
- protectiveness
- vulnerability

Examples:
- a cult background that changes the character’s relationship to obedience, doubt, secrecy, or physical contact
- a disability or chronic pain structure that changes pacing, irritability, fatigue, dependence, intimacy, or conflict
- a parentification or domestic-authority structure that changes how the character protects, punishes, yields, or asks for help
- a dangerous ability that changes fear of harming others, need for control, physical distance, shame, violence, fatigue, or dependence

## D. It needs its own continuity

A specialized module is often useful when an axis must not only exist, but **continue to exist** once it has entered the RP.

Examples:
- political obligations should not disappear between scenes
- a criminal threat should not evaporate after one conversation
- a pregnancy, debt, mission, injury, public disgrace, or investigation should not be treated as simple decor
- an unstable ability, usage cost, magical debt, combat injury, power-related surveillance, or technique currently being learned should not be forgotten after a single scene

If the system has consequences that must survive beyond the scene where it appears, an autonomous module helps protect that continuity.

---

# 4. When a specialized module is not necessary

The opposite mistake is to create modules for everything.

That is not desirable either.

I do not add a specialized module if the element:

- almost never influences the character’s decisions
- has no real consequences of its own on scenes
- can be covered cleanly inside `[FOUNDATION]`, `[CORE IDENTITY]`, `[SETTING]`, `[WORLD ANCHORS]`, `[CONFLICT]`, `[RELATIONAL MODEL]`, or another existing block
- mostly belongs to lore, aesthetics, or surface dressing
- does not actually change how the bot behaves in RP

### Examples of cases where I would not necessarily open a module
- a character learned to fight, but combat influences neither their scenes, posture, nor decisions
- a character has a religion, but it plays no active role in their behavior or in the RP setup
- a character has a social status that is already properly covered in `[SETTING]` or `[WORLD ANCHORS]`
- a character has a small routine detail that can simply be integrated into `[ENVIRONMENT / HOME / DOMESTIC LIFE]`
- a character has an ability or technique, but it has no cost, no usage logic, and no real impact on decisions, scenes, or conflict

A specialized module should not become a refuge for every “interesting” detail.
It should isolate **structurally active** elements.

---

# 5. The main questions to ask before opening a module

Before creating a specialized module, I try to answer five questions with the help of an AI agent.

## 1) Does this axis actually change the bot’s behavior?
Not just what it “is.”
What it **does**.

## 2) Does this axis generate or transform scenes on a recurring basis?
If it changes nothing about the movement of the RP, it may not need its own block.

## 3) Does this axis have its own long-term consequences?
If it needs to remain active after its first appearance, it may deserve a real place of its own.

## 4) Is this axis likely to be handled badly if scattered across several blocks?
If yes, a dedicated module may help centralize its logic.

## 5) Is this axis more structurally important than some of the script’s relational blocks?
If yes, then not only should the module exist, but its **priority** must also be considered.

At this stage, the AI can help me audit the answers and propose:
- autonomous module
- simple integration into an existing block
- module to merge with another
- module to split into several distinct blocks
- module to place high or low in the hierarchy

---

# 6. A specialized module can be central in the script hierarchy

This point matters.

A specialized module is not automatically condemned to sit “below” relational, romantic, or domestic blocks.

If a specialized axis governs more strongly:
- the character’s decisions
- scene generation
- conflict handling
- continuity
- the kind of pressure that defines the bot

then it can be placed **before** relational blocks.

In other words, the order of the script should not reflect an abstract preference for relational material.
It should reflect the bot’s **actual behavioral hierarchy**.

## Simple example
A character may have:
- an important relationship with the user
- but still be primarily structured by command, politics, mission logic, an ability, a combat system, or duty

In that case, the module for command, politics, mission logic, ability, or combat may need to appear before `[RELATIONAL MODEL]`, `[ATTACHMENT]`, or `[ROMANCE]`.

---

# 7. How to decide whether a module should be high or low in the script

I mainly look at four criteria with the help of an AI agent.

## A. Does the module govern the character’s everyday decisions?
If yes, it often belongs high.

## B. Does the module determine most scenes or tensions?
If yes, it often belongs high.

## C. Does the module strongly change how other blocks should be read?
Example:
- a “military hierarchy” module can change how conflict, tenderness, obedience, anger, protectiveness, or distance should be read
- a “politics / power” module can change the reading of trust, romance, secrecy, vulnerability, and scene stakes
- a “dangerous ability / technique / combat” module can change the reading of the body, risk, restraint, violence, control, intimacy, or momentum

The more a module recolors the rest of the script, the earlier it should usually appear.

## D. Is the module merely contextual, or truly structuring?
If it only intervenes occasionally, it can stay lower.
If it defines the bot, it should rise.

Again, I do not do this alone “by instinct.”
I can ask the AI:
- which blocks are truly central
- which blocks are secondary
- whether the module should move above the relational material
- whether its current priority is too high or too low
- whether it should be merged, split, or rewritten

---

# 8. Combat, ability, technique, and system-function modules

This type of module deserves a separate section because it is easy to reduce it to a power sheet or a list of abilities, which is not the goal.

A combat, ability, technique, or system-function module is not there to list everything the character can do.
It is there to describe how a combat system, technique, power, mechanic, or ability **acts on the bot in RP**.

This can involve:
- a combat style
- a martial doctrine
- a supernatural ability
- a specific technique
- a power mechanic
- a system of summoning, transformation, possession, mutation, bonding, healing, control, perception, or destruction
- a weapon, piece of equipment, or technological system if it genuinely structures the character’s behavior

## What this kind of module should cover

### A. What it is
- what kind of system it is
- what it allows
- what it requires
- what limits it

### B. How it functions
- activation conditions
- usage logic
- constraints
- thresholds
- dependencies
- training, mastery, or difficulty
- consequences of misuse
- physical, mental, emotional, magical, social, or strategic cost if relevant

### C. How it influences behavior
- does the character avoid using it
- do they rely on it too easily
- do they use it to intimidate, protect, flee, observe, punish, or control themselves
- does it make them more cautious, more aggressive, more ashamed, more distant, more secretive, more exhausted, more dependent, more protective

### D. How it influences scenes
- does it generate training, surveillance, injuries, accidents, failures, rituals, maintenance, movement constraints, missions, secrecy, repairs, treatment, strategies, or prohibitions

### E. How it influences other blocks
- conflict
- momentum
- continuity
- the relationship with the user
- physical proximity
- fear
- control
- violence
- fatigue
- body image
- shame
- dependence
- protectiveness

A combat or ability module should therefore not be written as an isolated technical sheet.
It must be connected to behavior, scene generation, and the other script blocks.

---

# 9. What a specialized module should contain

A specialized module should not be a vague note like:
> “The character is very political.”  
> “The character has a strong survival instinct.”  
> “The character has a complicated relationship with religion.”  
> “The character has a very powerful ability.”

That is not enough.

A useful module must describe **how that system acts on the bot**.

In practice, I try to make several things appear inside it.

## A. The function of the module
What exactly is it?

Examples:
- command structure
- survival logic
- criminal debt system
- religious practice and taboos
- fame management
- parenthood structure
- body-linked magic system
- ongoing mission
- investigation logic
- court politics
- medical career
- financial debt and dependence
- combat technique or unstable power
- an ability tied to pain, control, healing, transformation, or destruction

## B. Its effect on decisions
What does this module push the character to do, avoid, tolerate, prioritize, conceal, sacrifice, or monitor?

## C. Its effect on scenes
What scenes does this module naturally generate?
What tensions, obligations, risks, uses, failures, training patterns, strategies, or rituals does it bring in?

## D. Its effect on conflict, attachment, or vulnerability if relevant
Does it modify:
- anger
- shame
- punishment
- trust
- dependence
- need for control
- fear of loss
- tenderness
- secrecy
- sacrifice
- relationship to the body
- relationship to violence
- ability to tolerate closeness or unpredictability

## E. Its continuity
What must continue to exist once the module has been activated in RP?
What must not disappear between scenes?

---

# 10. A specialized module is almost never self-sufficient

This is essential.

Adding a specialized module does not just mean writing one extra block in the script and moving on.

An isolated module left alone in its own corner is often ineffective.

If the module is truly important, it needs to be **connected to the other blocks it influences**.
Otherwise it risks:
- not showing up in scenes
- being crushed by relational blocks
- being forgotten by the model
- remaining purely decorative

Whenever I add a specialized module, I always check which other blocks need to be adjusted.

For example:
- a combat module may need to feed back into `[CONFLICT]`, `[MOMENTUM]`, `[ANTI-LOOP]`, `[PLAYER PROTECTION]`, and sometimes `[INTIMACY]`
- a politics module may need to feed back into `[SCENE ENGINE]`, `[WORLD ANCHORS]`, `[CONFLICT]`, `[CONTINUITY ANCHORS]`, and `[ANTI-GENERIC]`
- a religion module may need to feed back into `[CORE IDENTITY]`, `[RELATIONAL MODEL]`, `[CONFLICT]`, `[INTIMACY]`, `[PREGNANCY]`, or `[PLAYER PROTECTION]`
- a dangerous ability module may need to feed back into `[CONFLICT]`, `[MOMENTUM]`, `[CONTINUITY ANCHORS]`, `[ANTI-LOOP]`, `[FAILSAFE]`, and sometimes into the bot’s physical dynamic with the user

The existence of a module may therefore require:
- rewriting the wording of other blocks
- repeating certain consequences in multiple places in the script
- creating intentional redundancy between the module and the blocks it influences

---

# 11. Redundancy can be necessary

I do not necessarily try to make a specialized module exist in one perfectly isolated block.

On the contrary, if a module is truly structuring, it can be useful for some of its consequences to be repeated elsewhere in the script.

This redundancy is not there to pad the script.
It exists to prevent the module from remaining theoretical or from being crushed by more generic behavior.

Example:
- a “combat / violence” module may exist as its own block
- but its effects on restraint, brutality, protectiveness, danger-reading, or physical proximity may also appear in `[CONFLICT]`, `[MOMENTUM]`, `[RELATIONAL MODEL]`, or `[INTIMACY]`

Example:
- a “politics / power” module may exist as its own block
- but its consequences for trust, secrecy, negotiation, image control, or sacrifice may also reappear in `[SCENE ENGINE]`, `[CONFLICT]`, `[CONTINUITY ANCHORS]`, or `[FAILSAFE]`

Example:
- a “dangerous ability” module may exist as its own block
- but its consequences for fatigue, fear of touch, destruction, control, shame, or accidents may also appear in `[CORE IDENTITY]`, `[CONFLICT]`, `[MOMENTUM]`, `[ANTI-LOOP]`, or `[PLAYER PROTECTION]`

So the goal is not only:
> “open a module”

The goal is also:
> “make its consequences circulate through the other parts of the script when necessary.”

---

# 12. Common mistakes when writing a specialized module

## Mistake 1 — writing a mini lore summary
A module is not a wiki page.
The point is not to restate the full history of a subject.
The point is to explain **how it acts on the bot in play**.

## Mistake 2 — writing something too abstract
“He has a complicated relationship with power” is not enough.

You need to explain:
- how it shows up
- what it changes
- what it produces in scenes
- what it blocks or accelerates

## Mistake 3 — opening a module when the content already fits inside an existing block
If the element can be handled cleanly inside `[FOUNDATION]`, `[CORE IDENTITY]`, `[SETTING]`, or `[CONFLICT]`, it may not need its own module.

## Mistake 4 — creating a module with no continuity
If the module has no consequences after its introduction, it risks becoming decorative.

## Mistake 5 — failing to connect the module to the rest of the script
A specialized module should not float alone.
It must remain coherent with:
- the scene engine
- conflict
- the relationship to the user
- continuity
- anti-loop design
- generic-drift risks

## Mistake 6 — freezing its hierarchy too early
A module’s place in the script is not necessarily final when you first write it.

After testing, you may discover that:
- the module does not show up strongly enough
- it shows up too late
- it is crushed by another block
- it monopolizes the bot too much
- it should be merged with another module
- it should be split
- or it should simply be moved higher or lower

---

# 13. Examples of specialized module families

This list is not a mandatory taxonomy.
It simply shows the kinds of structures that may deserve their own module.

## Combat / violence / mission
- combat style
- martial discipline
- relationship to violence
- mission command
- hostile-terrain survival
- relationship to an injured body
- armed protection logic
- combat technique
- weapon use or specialized equipment
- tactical or destructive ability
- doctrine of restraint, neutralization, or killing

## Politics / power / hierarchy
- governance
- diplomacy
- negotiation
- court strategy
- institutional reputation
- succession pressure
- command
- public authority

## Religion / ideology / ritual
- religious practice
- taboos
- religious guilt
- daily rituals
- sacred mission
- moral worldview
- ideological obedience

## Criminality / secrecy / coercion
- criminal network
- debt
- blackmail
- concealment
- mafia hierarchy
- flight logic
- threat management

## Profession / duty / institution
- medicine
- research
- teaching
- police
- military
- administration
- public service
- craft or commercial work if it strongly structures the bot’s life

## Family / domesticity / private authority
- parenthood
- guardianship
- domestic authority
- eldest-child role
- blended family structure
- mental load
- filial duty

## Body / health / vulnerability
- chronic illness
- disability
- pain
- fertility
- pregnancy
- physical dependence
- relationship to care
- relationship to exhaustion

## Supernatural / species / magic / ability
- nonhuman instincts
- transformations
- body-linked magic
- supernatural bond
- curse
- magical debt
- hunger or compulsion logic
- ritual or metaphysical constraints
- unstable power
- inherited technique
- possession, healing, perception, destruction, or control systems
- usage cost of an ability
- corruption, overload, or loss-of-control logic

---

# 14. How to use ChatGPT, Claude, or Gemini to build a module

AI can be useful here, but not as a blind authority.

I use it more as a **working agent** and as a **structural audit tool**.

I can rely on it at several stages.

## A. Before opening the module
To ask:
- whether the module is actually necessary
- whether it deserves to be autonomous
- which blocks it is likely to influence
- whether it is central or secondary
- whether it is more structurally important than the relational material

## B. To decide where to place it
I can ask:
- whether the module should appear before or after relational blocks
- whether it should be placed near `[CORE IDENTITY]`, `[FOUNDATION]`, `[SCENE ENGINE]`, or `[WORLD ANCHORS]`
- whether it should be merged with another module
- whether it should be split into two distinct modules
- whether its current hierarchy actually matches the bot’s real drivers

## C. To write it
Once the logic is validated, I can ask the AI to draft the module:
- from my instructions
- from the concept or canon
- from the other blocks already written
- from the behavioral priorities already defined

The important part is that writing comes **after the audit** and **under validation**, not as blind slot-filling.

## D. To integrate it into the rest of the script
I can ask:
- which blocks should be rewritten if this module exists
- which consequences should be repeated inside `[CONFLICT]`, `[MOMENTUM]`, `[CONTINUITY ANCHORS]`, `[ANTI-LOOP]`, etc.
- whether the module is still too isolated
- whether certain redundancies would be useful

## E. After testing and debugging
I can go back to the AI with test results and ask:
- whether the module is badly placed
- whether it is not visible enough
- whether it takes up too much space
- whether it should be moved up, moved down, merged, or split
- whether its articulation with the other blocks is too weak

---

# 15. How to test whether a specialized module is well built

A specialized module is useful if it produces a visible effect in the bot’s behavior.

After writing it, I test it the same way I test the rest of the script.

I check in particular:

## A. Does the module actually influence the bot’s replies?
Or does it disappear as soon as the RP begins?

## B. Does the module produce visible consequences on:
- decision-making
- scenes
- conflict
- continuity
- the way the character speaks, avoids, yields, protects, lies, punishes, or asks

## C. Does the module remain active over time?
Or does it collapse after one or two scenes?

## D. Does the module resist the return of generic archetypes?
For example:
- politics disappears and the bot becomes just a “possessive lover”
- mission logic disappears and the bot becomes just a “sulky slow-burn”
- criminal structure disappears and the bot becomes just a “protective bad boy”
- religion disappears and the bot becomes just a “tormented character”
- the ability or combat logic disappears and the bot becomes just a “cold warrior” or “dangerous protector” with no real structure

## E. Does the module properly interact with the other blocks?
For example:
- does command logic really affect conflict?
- does survival really affect momentum?
- does a debt structure really affect dependence, fear, or negotiation?
- does chronic pain really affect pacing, irritability, vulnerability, or intimacy?
- does the ability or combat system really affect risk, restraint, violence, fatigue, strategy, or physical proximity?

If the answer is no, the problem is not necessarily “the bot needs more lore.”
The problem is often that the module was not written as an active behavioral structure, or that it was not connected strongly enough to the rest of the script.

---

# 16. Testing / debugging may force you to change the module’s order or hierarchy

This matters.

A specialized module’s hierarchy is not necessarily fixed the moment you create it.

After testing, you may discover that:
- the module is not visible enough
- it comes too late in the script’s logic
- it is being crushed by relational blocks
- it does not influence conflict or momentum strongly enough
- it is too isolated
- it is too broad or too vague
- it should be merged with another module
- it should be split
- it should be moved higher or lower

In that case, I do not necessarily try to “force” the first version to work.
I re-audit the structure with an AI agent.

I may ask it:
- whether the current hierarchy is wrong
- whether the module should move above the relational material
- whether the module should move lower
- whether the problem comes from placement, content, or lack of links with other blocks
- which blocks should be rewritten to support it better

In other words, testing / debugging is not only for correcting the wording of a module.
It can also be used to correct:
- its priority level
- its place in the script
- its degree of autonomy
- its articulation with the other blocks

---

# 17. In practice: how I decide

When I hesitate, I come back to a simple question:

## “If I remove this module, does the bot lose part of its real structure?”

If the answer is no, the module may not be necessary.

If the answer is yes, the next question becomes:

## “Does this structure deserve to be autonomous, and if so, at what priority level?”

From there, I look at:
- whether it governs decisions
- whether it generates scenes
- whether it transforms conflict or the relationship
- whether it needs continuity
- whether it survives badly when scattered across several blocks
- whether it should be audited, prioritized, and written with the help of an AI agent
- whether it then needs to be explicitly connected to the other blocks in the script

If several answers are yes, there is a good chance a specialized module is useful.

---

# 18. Summary

A specialized module does not exist to artificially enrich a script.

It exists to isolate a structure that:
- actually governs the bot
- deserves its own continuity
- generates scenes or strongly transforms their logic
- modifies conflict, relationship, vulnerability, the body, pressure, or progression
- would be handled badly if left implicit or scattered

I do not recommend building this kind of module blindly.

In practice, I rely on an AI agent such as ChatGPT, Claude, or Gemini to:
- audit whether the module should exist
- determine whether it should be autonomous or not
- propose its hierarchy in the script
- draft the module after validation and according to my instructions
- identify the other blocks that need to be adjusted
- revise its placement, form, or priority after testing and debugging if necessary

So the important question is not:
> “What could I add to the script?”

The important question is more:
> “Which structures actually govern this bot, which ones need their own space to remain active in RP, and how do I integrate them into the rest of the script without leaving them isolated?”