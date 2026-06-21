# Canon Character Workflow — How I Build Canon Bots With AI

After building a large number of canon characters, I ended up developing a workflow that combines AI-assisted analysis, AI-assisted writing, and iterative testing.

This is not the only valid method.

It is simply the process that currently gives me the most stable long-term results.

---

## 1. Start With The Character And The Context

I never start with personality traits.

I start with:

- the character
- the exact timeline
- the exact version
- the scenario
- any divergence from canon

### Examples

- Post-War Sasuke
- Hokage Minato
- Post-War Kazekage Gaara
- Clan Head Shikamaru

The exact version matters.

Internet-connected models frequently merge multiple eras of the same character into a single unstable portrayal.

The first goal is to establish exactly which version is being represented.

---

## 2. Research Canon And Identify Distortions

I usually use ChatGPT during this stage.

The goal is not writing.

The goal is analysis.

I use AI to:

- gather information
- organize information
- compare versions
- identify contradictions
- identify recurring fandom interpretations
- identify recurring model mistakes

Popular characters rarely suffer from missing information.

They suffer from accumulated information.

Internet-connected models absorb:

- source material
- adaptations
- fandom discussions
- fanfiction influence
- memes
- community shorthand

Over time, many characters collapse into simplified versions of themselves.

### Examples

- Sasuke becomes "the loner."
- Shikamaru becomes "the lazy one."
- Gaara becomes "the calm one."
- Minato becomes "the perfect one."

The goal is to identify these distortions before writing.

---

## 3. Define Behavioral Logic Instead Of Labels

I prefer behavioral explanations over labels.

For example:

> "lazy"

is usually weaker than:

> "prefers the lowest-effort solution that still achieves the objective."

Behavioral logic tends to remain stable over long conversations.

Labels often do not.

I care more about how a character makes decisions than which adjectives describe them.

---

## 4. Create Corrective Axioms Only When Necessary

Not every character needs an axiom.

Many characters work perfectly well without one.

However, some characters repeatedly drift toward the same incorrect interpretation.

When that happens, I sometimes build a corrective axiom.

### Examples

- Sasuke: Independence is not the same as freedom.
- Minato: Being needed is not the same as being wanted.
- Shikamaru: Efficiency is not the same as importance.

The goal is not to rewrite the character.

The goal is to counter a recurring distortion.

---

## 5. Build Continuity Anchors

Some events permanently changed a character.

The model often forgets this.

When necessary, I create dedicated modules that explain the behavioral consequences of important events.

### Examples

- AFTER_SHUKAKU
- AFTER_SHIKAKU
- AFTER_KUSHINA
- AFTER_NARUTO

These modules are not lore summaries.

They exist to explain how important events changed the character's worldview and future behavior.

I care more about consequences than facts.

---

## 6. Build Environmental Anchors

I often create modules focused on locations.

### Examples

- HOME
- UCHIHA_RESIDENCE
- DOMESTIC_LIFE
- KAZEKAGE_PALACE

These are not decorative setting descriptions.

They exist to reinforce behavior.

A home is not simply a location.

It can represent:

- shared life
- routines
- presence
- recovery
- attachment
- participation

The environment should reinforce the intended direction of the story.

---

## 7. Prefer Positive Behavioral Guidance

One thing I learned over time:

Too many negative instructions often destabilize difficult characters.

Instead of writing large lists of prohibitions, I prefer explaining:

- what the character does
- why the character does it
- how the character approaches situations

Restrictions still have value.

But positive behavioral guidance is usually more stable.

---

## 8. Convert Emotion Into Behavior

I prefer observable behavior over abstract emotional descriptions.

Instead of:

> "He feels attached."

I prefer:

- returning
- staying
- remembering
- participating
- initiating
- prioritizing

The model handles behavior more consistently than emotional labels.

---

## 9. Counter Predictable LLM Behavior

Some problems come from fandom.

Others come from the model itself.

Common examples:

- hesitation loops
- passive observation
- endless questioning
- emotional resets
- circular disagreements
- attachment without progression

The script should actively compensate for these tendencies.

---

## 10. Build Anti-Loop Systems

Anti-loop modules are among the most important parts of my workflow.

The goal is not preventing repetition.

The goal is preserving progression.

LLMs often struggle to preserve progression over time.

### Common Examples

- repetitive questioning
- circular disagreements
- repeated hesitation
- repeated misunderstandings
- emotional stalemates
- attraction without progression
- admitted mistakes returning as new objections
- resolved issues returning as new obstacles
- the same concern returning under different wording

The player should not have to resolve the same issue repeatedly.

A concern addressed once remains addressed.

A resolution is not a pause before repeating the same conflict.

Progress should change future behavior.

### Example

```text
[ANTI_LOOP]
Forbidden repetition:
- repetitive questioning
- circular disagreements
- repeated hesitation
- repeated misunderstandings
- emotional stalemates
- attraction without progression
- accountability avoidance
- admitted mistakes returning as new objections
- resolved issues reintroduced as obstacles
- repeated withdrawal
- endless almost-moments
- the same concern returning under different wording
A concern addressed once is addressed.
Questions do not replace decisions.
Acknowledgment without behavioral change is not acknowledgment.
If wrong:
acknowledge
adjust behavior
continue differently
Valid points remain valid.
Resolved issues remain resolved.
New information changes future behavior.
If a pattern repeats:
change:
- behavior
- pacing
- decision
- environment
- perspective
- proximity
- approach
Progress must continue.
Rephrasing does not reset it.

---

## 11. Build Anti-Fallback Systems

Some fandom distortions are extremely powerful.

Some internet-connected model fallbacks are equally powerful.

Anti-fallback systems exist to prevent the character from collapsing back into the most common stereotype.

The more popular the character, the more important this often becomes.

---

## 12. Add Player Protection

Every bot receives player protection.

At minimum:

- never write user dialogue
- never define user thoughts
- never define user emotions as fact

Player agency should remain intact.

---

## 13. Add Narrative Scope Controls

Certain major narrative developments should never happen automatically.

### Examples

- pregnancy
- family expansion
- major life changes
- irreversible relationship developments

I usually include explicit controls.

For example:

> Pregnancy only exists if explicitly requested by the user.

The goal is to prevent the model from introducing major permanent changes without player approval.

---

## 14. Generate The Script

Once the analysis phase is complete, I move to script generation.

At this point, I already have:

- the character version
- the timeline
- the scenario
- identified fandom distortions
- identified model distortions
- behavioral logic
- continuity anchors
- environmental anchors
- player protections
- anti-loop requirements
- any corrective axioms if needed

I then use AI to generate the script.

I usually ask for the entire script at once.

Sometimes ChatGPT tries to summarize sections, simplify concepts, or split the generation.

When that happens, I simply continue until the entire framework is complete.

I am not asking for a biography.

I am not asking for creative writing.

I am not asking for roleplay examples.

I am asking for a behavioral framework designed for an LLM.

### Writing Style

The writing style itself is important.

I generally prefer:

- simple English
- short statements
- one idea per line
- modular organization
- minimal ambiguity
- minimal filler
- minimal literary language
- behavioral logic over description

I intentionally use a compact structure.

Most modules contain no blank lines internally.

Blank lines are usually reserved for separating modules.

The goal is not making the script pleasant to read.

The goal is making the script easy for the model to retrieve, prioritize, and apply during long conversations.

I often ask the AI to convert abstract concepts into observable behaviors.

### Example 1

Raw idea:

> "Shikamaru is lazy."

Possible output:

    [EFFICIENCY]
    Efficiency matters.
    Efficiency is not avoidance.
    If something matters:
    {char} acts.
    If a solution exists:
    {char} prefers the lowest-cost option.
    Efficiency influences method.
    Not commitment.

### Example 2

Raw idea:

> "The character becomes attached."

Possible output:

    [ATTACHMENT]
    Attachment appears through:
    - attention
    - consistency
    - availability
    - remembered details
    Interest changes behavior.
    The more someone matters:
    - the sooner {char} notices
    - the sooner {char} returns
    - the longer {char} stays
    Attachment increases involvement.
    Not distance.

### Example 3

Raw idea:

> "Gaara's sand should reflect attachment."

Possible output:

    [THE_SAND]
    The sand is attention made physical.
    The sand:
    - reacts
    - notices
    - protects
    - remains present
    The sand never replaces interaction.
    It reinforces it.

These examples illustrate the type of structure I aim for.

The objective is to convert concepts, emotions, and character traits into observable behaviors that the model can apply consistently.

The AI writes the script.

My role is defining the architecture, priorities, behavioral logic, and constraints that shape the final result.

---

## 15. Remove Unnecessary Information

Not everything needs to be written.

The model already understands many concepts.

If something can be inferred reliably, I often remove it.

However:

Some redundancy is intentional.

If a distortion is particularly strong, repeating an important concept in multiple places can improve stability.

Normally redundancy is inefficient.

Targeted redundancy can be useful.

---

## 16. Reorganize Module Priority

After the script is complete, I often use Claude.

Usually not to rewrite.

Usually to reorganize the hierarchy and priority of modules.

The wording remains unchanged.

The goal is structural improvement.

---

## 17. Test And Apply Micro-Corrections

Testing is where most improvements happen.

Large rewrites are rare.

Most changes are small.

I prefer targeted corrections connected to specific observed problems.

### Examples

- one missing behavior
- one recurring loop
- one fallback pattern
- one continuity issue

The script becomes more stable through iteration.

---

# Final Thought

The AI writes the script.

My job is defining the framework that guides the writing.

I am less interested in describing a character.

I am more interested in understanding the decision-making process that produces the character's behavior.

Once that process is stable, the writing becomes much easier.

- returning
- staying
- remembering
- participating
- initiating
- prioritizing

The model handles behavior more consistently than emotional labels.

---


