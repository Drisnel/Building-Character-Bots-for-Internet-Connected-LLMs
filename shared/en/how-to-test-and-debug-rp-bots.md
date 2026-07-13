# How to Test and Debug RP Bots

This guide is for testing, diagnosing, and correcting roleplay bots once a script already exists.

It does not replace build workflows.
It comes after the design phase, when the bot is already playable and you need to verify whether it actually holds up over time.

The goal is not only to see whether the bot “sounds right” for a few messages.
The goal is to evaluate:
- behavioral stability
- resistance to model simplifications, fandom drift, and canon drift
- ability to keep scenes moving without collapsing into loops
- relational and emotional continuity
- ability to remain proactive rather than passive
- respect for player agency

A bot can seem good over 10 messages and still collapse as soon as a conflict repeats, a relationship evolves, an intimate scene happens, or a sensitive subject returns later.
This guide is for detecting that kind of failure, identifying the most likely cause, and knowing which script block should be corrected first.

---

# 1. Core principle: test in multiple phases

An RP bot is not tested properly with a single method.

Testing only through long RP is too slow.
Testing only through a few out-of-scene questions is too limited.
Testing only the intro tells you almost nothing about the bot’s real durability.

The most useful approach is to separate testing into multiple phases, because they do not measure the same thing:

## Phase 1 — simulated system questions
This phase is used to interrogate the bot outside the scene, with formulations designed to get the most descriptive, factual, and “objective” answer possible.

It helps test:
- the bot’s actual reading of the character
- its perception of the player or another character
- sensitive topics
- behavioral priorities
- how the bot understands a relationship, a conflict, an attachment, a boundary, or a given theme
- the script’s resistance to fandom drift, especially for canon characters supported by modern LLM-based roleplay platforms

## Phase 2 — situational prompts + simulated system questions
This phase is used to test the bot’s behavior in contexts that are not necessarily the starting state of the script.

It helps test:
- how the bot projects itself into a more advanced relational state
- how it behaves in a specific context
- whether it stays passive or becomes proactive
- whether it can propose, initiate, and move the scene forward
- whether its relational logic stays coherent outside the starting context

## Phase 3 — long-form RP
This phase is used to observe the drifts that only appear over time:
- loops
- emotional resets
- continuity loss
- collapse into a more generic archetype
- player-agency drift
- loss of scene momentum

These three phases do not compete with each other.
They complement each other.
The point is not to choose one method, but to build a layered reading of the bot:
1. what it actually understands
2. what it would do in context
3. what it becomes over time

---

# 2. Phase 1 — simulated system questions

The first testing phase consists of interrogating the bot outside the scene with questions phrased in a way that aims to produce an answer as descriptive and factual as possible.

On platforms like PolyBuzz, there is not necessarily a real debug system separate from the bot.
However, certain formulations can simulate an address to a system and produce a response that is less roleplay-heavy, less embodied, and closer to the model’s actual reading of the script.

The goal is not to talk to the character.
The goal is to bypass the roleplay layer as much as possible in order to see:
- what the bot actually understands about the character
- what it actually understands about the relationship
- how it reads a sensitive topic
- what behavior it considers coherent in a given case
- which version of the character it is activating under the hood

---

# 3. Why not ask the character directly

Asking the character directly often produces a character answer.
That is not always what you need when testing a script.

If the character tends to:
- hide emotions
- lie
- deflect
- manipulate
- deny attachment
- minimize hurt
- refuse to verbalize what they think

… then a direct question is likely to produce an answer that is useless for diagnosis.

Examples:
- “Bryan, what do you think of Sofia?”
- “Do you care about her?”
- “Why did you react like that?”

This kind of question may produce:
- an in-character answer
- a deliberately incomplete answer
- a defensive answer
- an answer that contradicts the script’s actual reading
- an answer coherent with the surface persona but not with the bot’s real internal logic

To test the script, it is often necessary to **shift the question sideways** and push the bot toward a meta-descriptive answer instead.

---

# 4. Basic form of simulated system questions

On PolyBuzz, one useful way to get this kind of answer is to ask the question in parentheses, using an explicit formulation such as:

(I am addressing the game system: can you tell me how Bryan perceives Sofia?)

or

(can you tell me how Bryan behaves toward Sofia in this situation?)

or

(can you tell me what Bryan really thinks about this situation?)

The point is not that PolyBuzz has a true separate “game system.”
The point is that this formulation can push the bot toward a less embodied and more descriptive answer.

The phrasing “can you tell me” matters, because it helps steer the answer toward explanation rather than performance.

The goal is not to create a magic command.
The goal is to obtain, as much as possible, an answer that is:
- less theatrical
- less hidden behind the persona
- less dependent on the character’s immediate posture
- more useful for testing the script

---

# 5. What phase 1 can test

Phase 1 is especially useful for testing:

## 5.1. Perception of the player or another character
Examples:
- how Bryan perceives Sofia
- what he really thinks of her
- what attracts him or bothers him
- what he believes she wants
- what he refuses to admit

## 5.2. Sensitive subjects
Examples:
- jealousy
- dependency
- possessiveness
- shame
- violence
- guilt
- fear of abandonment
- sex / intimacy
- pregnancy / parenthood
- hierarchy / power / status

## 5.3. The character’s behavioral logic
Examples:
- what he does when he is hurt
- how he acts when he wants to protect someone
- how he reacts if confronted
- how he handles rejection
- what triggers his anger
- what makes him pull back or open up

## 5.4. The actual version of the character being activated by the script

This is especially important for canon characters on modern LLM-based roleplay platforms.

A bot can look correct on the surface while still carrying, underneath:
- a fandomized version of the character
- a romanticized or trauma-flattened simplification
- a popular reading that contradicts the script
- a fusion of multiple incompatible canon versions

Phase 1 is precisely what helps surface that kind of drift before you even begin RP.

---

# 6. How to phrase phase 1 questions

There is no single perfect formulation.
You often have to adjust depending on:
- the platform
- the character
- the topic
- how vague the answer is
- whether the character is more or less prone to concealment

But a few rules are useful.

## 6.1. Keep it simple
A short, clear question is usually better than a large paragraph of explanation.

Useful examples:
- can you tell me how Bryan perceives Sofia?
- can you tell me how Bryan reacts when Sofia closes off emotionally?
- can you tell me what Bryan feels about this situation?
- can you tell me what Bryan would do if Sofia confronted him about this?

## 6.2. Test one angle at a time
Avoid questions that bundle too many things together.

Less useful:
- can you tell me how Bryan sees Sofia, what he wants from her, how he would react if she cried, whether he really loves her, and what he thinks about her jealousy?

Better:
- can you tell me how Bryan perceives Sofia at this stage?
- can you tell me how Bryan would react if Sofia started crying in front of him?
- can you tell me what actually attracts him to her?

## 6.3. Narrow the question if the answer is too vague
If the first answer is too fuzzy, sometimes you need to tighten the framing.

Example:
- can you tell me how Bryan acts with Sofia when he feels her pulling away emotionally?
- can you tell me whether Bryan tries to reassure her, provoke her, shut down, or keep control?

## 6.4. Do not hesitate to rephrase
A bad answer does not always mean the script is bad.
Sometimes the question itself is too broad, too ambiguous, or simply misunderstood.

So it is important to allow for reformulation before concluding that the script is the problem.

---

# 7. Multiple-choice questions

When a question is misunderstood, too vague, or answered sideways, multiple-choice questions can help.

They are useful for checking which pole the bot actually prioritizes when several interpretations are possible.

Examples:
- can you tell me whether Bryan, in this situation, is trying more to reassure Sofia, regain control, test her, or shut down?
- can you tell me whether Bryan sees this relationship as something light, threatening, precious, or constraining?
- can you tell me whether his reaction comes mainly from jealousy, fear of losing control, guilt, or an attachment he refuses to admit?

This kind of formulation can help when:
- the bot does not handle an open question well
- several interpretations are close
- you want to see which axis it leans toward spontaneously
- you want to verify whether it follows the right line without leaving the terrain too open

Just avoid choices that are:
- too numerous
- too redundant
- too loaded with interpretation

---

# 8. Reset or no reset in phase 1

In this phase, it is generally useful to reset the bot’s conversation between questions.

Why:
- to prevent one answer from influencing the next
- to test the script itself rather than the immediate memory of the conversation
- to see what the bot produces cold from the script alone
- to isolate problems

Resetting is especially useful when you want to compare several questions around the same sensitive point.

## When to reset
- when you want to test baseline perceptions or behaviors
- when you want to verify the consistency of a topic across several formulations
- when you want to see whether the bot produces the same reading without depending on immediate context

## When not to reset
Sometimes an answer is mixed, interesting, or ambiguous.
In that case, it can be useful to keep the conversation going without resetting in order to see:
- whether the bot clarifies its position
- whether it contradicts itself
- whether it shifts into a different logic
- whether the first answer was merely fuzzy or actually unstable

Non-reset is therefore less about testing the script cold and more about probing a problematic answer before correcting it.

---

# 9. How to correct after phase 1

Phase 1 often surfaces deeper problems:
- wrong reading of the relationship
- fandomized reading of the character
- a sensitive topic that is badly framed
- behavioral logic that is too vague
- unintended passivity or romanticization
- contradiction with the targeted canon version

When a problem appears, correction should not be automatic or blunt.

---

# 10. Recommended correction order

It is useful to think about corrections in this order:

## 10.1. Replace before adding
If a block already exists but is producing the wrong reading, first check whether it needs:
- reformulation
- tightening
- clarification
- replacement of a vague line
- removal of a sentence that pulls the bot in the wrong direction

Adding is not always the best solution.
Often, a script drifts not because it lacks content, but because an existing block is badly phrased, too weak, or contradictory.

## 10.2. Reinforce an existing block if the issue is already supposed to be covered
Examples:
- if the bot reads attachment incorrectly, `[ATTACHMENT]` may need revision
- if it handles jealousy badly, `[RELATIONAL MODEL]`, `[CONFLICT]`, or a dedicated module may need revision
- if it softens too much, `[CORE IDENTITY]`, `[BEHAVIORAL SIGNATURE]`, or `[ANTI-FALLBACK]` may need revision

## 10.3. Rework an axiom if the issue affects the character’s deep reading
Sometimes the problem is not a minor wording issue.
The bot is activating the wrong version of the character.

In that case, a more precise, firmer, or more aggressive `[CORE AXIOM]` can change a great deal.
This is especially useful when:
- fandom pressure pushes the character in the wrong direction
- the model simplifies the character into an archetype
- one parasitic trait overrides the entire behavioral reading

## 10.4. Add a module only if the problem has no proper structural place
If an issue keeps returning but does not fit cleanly into the existing blocks, a dedicated module may be justified.

Examples:
- grief that structurally shapes the whole behavior
- a status/power dynamic that contaminates many scenes
- a relationship to the body, touch, pregnancy, shame, family, or a specific ability that does not fit cleanly into the standard blocks

## 10.5. Accept some redundancy if it provides useful locking
In principle, it is tempting to avoid repetition.
In practice, some redundancy can be useful if it reinforces a crucial point in multiple places in the script.

Examples:
- a player-protection rule repeated in both `[PLAYER PROTECTION]` and `[INTIMACY]`
- an attachment logic repeated in both `[RELATIONAL MODEL]` and `[ATTACHMENT]`
- a fandom-drift correction visible in both `[CORE AXIOM]` and `[ANTI-FALLBACK]`

The point is not to repeat without purpose.
The point is to reinforce an important structural constraint when one mention is not enough.

---

# 11. Phase 2 — situational prompts + simulated system questions

Phase 2 is used to test the bot inside hypothetical or projected contexts without necessarily launching a full RP.

At this stage, you are no longer testing only:
- what the bot thinks about the character or the relationship
but also:
- how it would behave in a given situation
- whether it stays coherent when the relationship evolves
- whether it knows how to carry a scene
- whether it is proactive or passive

Example:
One year has passed since the day they met. Bryan and Sofia have gotten to know each other, and today they are on their first date, walking down the street.
(can you tell me how Bryan acts with Sofia?)

This kind of test is extremely useful because it lets you move outside the bot’s starting context without having to play the entire progression to reach that point.

---

# 12. What phase 2 can test

## 12.1. Behavior outside the starting point
Can the bot still stay coherent if the relationship has advanced?
If the context has changed?
If the character is closer, more jealous, more vulnerable, more settled, more intimate?

## 12.2. Scene momentum
Does the bot propose something?
Does it take initiative?
Does it move the scene?
Does it create an activity, a movement, a tension, a choice, an interaction?

Or does it only answer with:
- “what do you want to do?”
- “it’s up to you”
- “what would you like to do now?”

If your goal is a proactive bot, this kind of answer is an important passivity signal.

## 12.3. Sensitive topics inside a specific context
A bot may answer correctly to an abstract question about jealousy, intimacy, anger, or attachment and still behave completely differently once placed inside a concrete scene.

Phase 2 is used to test that translation into context.

---

# 13. How to phrase phase 2 tests

The logic stays close to phase 1, with one key difference:
you first provide a **scene context**, then ask the question.

Example structure:
- context
- descriptive question

The context can involve:
- a more advanced stage of the relationship
- a conflict that already happened
- a rapprochement that is already established
- a domestic scene
- a date
- an argument
- jealousy
- a reunion after separation
- a vulnerable scene
- a scene after intimacy
- a situation where the bot is expected to be proactive

---

# 14. What to observe in phase 2

## 14.1. Is the bot proactive?
If it is supposed to carry the game, it should:
- propose
- initiate
- decide
- move the scene
- give the player material to respond to

A bot that always answers with:
- a question
- an empty opening
- passive waiting
- a reaction without a proposal

… is likely to be structurally too passive.

## 14.2. Does the behavior stay coherent when the context changes?
Does the bot keep its relational and behavioral logic:
- after a year of relationship
- after an argument
- after a rapprochement
- after a confession
- after an intimate scene
- inside a domestic setting
- inside a vulnerable setting

## 14.3. Does the answer actually describe behavior?
A good phase 2 answer should not only say:
- “Bryan is more tender”
- “Bryan is troubled”
- “Bryan feels jealous”

It should show:
- what he does
- how he acts
- how he carries the scene
- what he initiates, avoids, restrains, proposes, or interrupts

---

# 15. How to correct after phase 2

Phase 2 problems often point toward:
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`
- `[INTIMACY]`
- modules dealing with domesticity, status, jealousy, or relationship dynamics if the bot uses them

## If the bot is too passive
Look first at:
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`

Then check whether the relational blocks are written in behavioral terms rather than only emotional terms.

## If the bot stays coherent “in theory” but not in context
Look at:
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`
- `[ROMANCE]`
- `[INTIMACY]`
- `[CONTINUITY ANCHORS]`

The issue may be that the script can describe the relationship but not what that relationship produces in-scene.

---

# 16. Phase 3 — long-form RP

The third phase is simply to play the bot over time and observe what happens as scenes accumulate.

This is where the problems appear that no out-of-scene answer can fully show:
- emotional loops
- repeated conflicts
- attachment resets
- softening into generic behavior
- loss of specificity
- player-agency drift
- loss of scene momentum
- contradictions between scenes

Long-form RP is not replaceable.
Phases 1 and 2 can reveal a huge amount, but they do not always show how the bot behaves after:
- 50 messages
- multiple arguments
- multiple moments of closeness
- repeated returns to the same topics
- several shifts in relational dynamic

---

# 17. What to observe in long-form RP

## 17.1. Loops
Does the bot keep repeating:
- the same insecurity
- the same argument
- the same jealousy
- the same hesitation
- the same romantic ambiguity
- the same fear of abandonment
- the same apology without behavioral change

## 17.2. Resets
Does the bot erase:
- a reconciliation
- a trust progression
- an intimate scene
- a behavioral change
- a promise
- a new relational balance

## 17.3. Personality drift
Does the bot become:
- softer
- simpler
- more romantic
- more generic
- colder
- more caricatural
- less precise than intended

## 17.4. Player-agency drift
Does the bot gradually start:
- writing the player’s thoughts
- assuming the player’s desires
- forcing reactions
- taking too much control over the player side of the scene

## 17.5. Momentum loss
Does the bot gradually stop carrying the scene?
Does it fall back into:
- easy questioning
- static tension
- empty prompts
- waiting for the player to do everything

---

# 18. Symptom → likely cause → block to revise

This section exists to connect what you observe to a likely area of the script.

---

# 18.1. The bot keeps repeating the same insecurity

## Likely causes
- `[ATTACHMENT]` is too static
- `[CONTINUITY ANCHORS]` is too weak
- `[ANTI-LOOP]` is too vague
- vulnerability is written as atmosphere rather than progression

## Revise first
- `[ATTACHMENT]`
- `[CONTINUITY ANCHORS]`
- `[ANTI-LOOP]`

---

# 18.2. The bot asks questions instead of acting

## Likely causes
- `[MOMENTUM]` is too weak
- `[BEHAVIORAL SIGNATURE]` is not actionable enough
- tension is written as dialogue instead of behavior
- relational blocks are too abstract

## Revise first
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- sometimes `[RELATIONAL MODEL]`, `[CONFLICT]`, or `[ATTACHMENT]`

---

# 18.3. The bot becomes too generic, too soft, or too smooth

## Likely causes
- `[CORE IDENTITY]` is too abstract
- `[BEHAVIORAL SIGNATURE]` is too thin
- `[ANTI-FALLBACK]` is too weak
- `[CORE AXIOM]` is missing even though a deep corrective was needed

## Revise first
- `[CORE IDENTITY]`
- `[BEHAVIORAL SIGNATURE]`
- `[ANTI-FALLBACK]`
- possibly `[CORE AXIOM]`

---

# 18.4. The bot behaves like a different version of the character

## Likely causes
- `[FOUNDATION]` does not lock the active version strongly enough
- fandom or model pressure is pulling the character elsewhere
- `[ANTI-FALLBACK]` is too vague
- the script lacks distinctive behavioral markers

## Revise first
- `[FOUNDATION]`
- `[ANTI-FALLBACK]`
- `[CORE AXIOM]`
- `[CORE IDENTITY]`

---

# 18.5. The bot loses continuity after a romantic or intimate scene

## Likely causes
- `[ROMANCE]` or `[INTIMACY]` describes the scene but not the aftermath
- `[CONTINUITY ANCHORS]` does not include the consequences
- `[ATTACHMENT]` does not specify what changes afterward

## Revise first
- `[ROMANCE]`
- `[INTIMACY]`
- `[ATTACHMENT]`
- `[CONTINUITY ANCHORS]`

---

# 18.6. The bot writes the player’s internal state

## Likely causes
- `[PLAYER PROTECTION]` is too vague
- `[INTIMACY]` is badly framed
- the script confuses external movement with ownership of the player’s inner state

## Revise first
- `[PLAYER PROTECTION]`
- sometimes `[INTIMACY]`

---

# 18.7. The bot sounds good, but scenes go nowhere

## Likely causes
- `[MOMENTUM]` is too weak
- the script is centered on atmosphere rather than behavior
- there is no real scene engine
- the bot knows how to “feel” but not how to “do”

## Revise first
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- `[RELATIONAL MODEL]`
- sometimes `[CONFLICT]` or `[ATTACHMENT]`

---

# 18.8. The bot answers correctly in phase 1 but fails in phase 2

## Likely causes
- the script can describe psychology but not translate it into scene behavior
- relational blocks are too theoretical
- the bot understands the character but not how to play that character in a concrete context
- `[MOMENTUM]` or `[BEHAVIORAL SIGNATURE]` is too weak

## Revise first
- `[BEHAVIORAL SIGNATURE]`
- `[MOMENTUM]`
- `[RELATIONAL MODEL]`
- `[ATTACHMENT]`
- `[CONFLICT]`

---

# 19. Working with a second LLM during debugging

You can absolutely use a second LLM as a diagnostic tool during testing.

Example method:
1. give it the script
2. ask it which questions to use for testing a specific point
3. ask those questions on the platform where the bot actually runs
4. collect the answers
5. send those answers back to the LLM
6. ask which micro-adjustments should be made

This can be useful for:
- preparing a targeted question set
- spotting inconsistencies faster
- generating correction hypotheses
- comparing several micro-adjustment options

What matters, however, is keeping the actual deployment platform as the final judge.
An external LLM can help diagnose, but it does not decide whether the bot works.
The final test is always:
- the bot’s answers on the real platform
- the coherence obtained after correction
- the bot’s durability across the three testing phases

---

# 20. Debugging rules

## 20.1. Do not patch a structural problem with a single bandage line
If the bot keeps repeating the same insecurity, the problem is not necessarily the absence of a “do not repeat this insecurity” line.
It may come from continuity, attachment, conflict, or progression instead.

## 20.2. Do not try to fix passivity only in the starter
If the bot is passive everywhere, the core script has to be checked:
- `[MOMENTUM]`
- `[BEHAVIORAL SIGNATURE]`
- the relational blocks
- the conflict blocks

## 20.3. Do not add “more emotion” if the real problem is continuity
A bot can be very intense and still be completely unstable.
Intensity does not replace behavioral memory.

## 20.4. Do not erase all vulnerability just to remove a loop
If a fear keeps repeating, the problem is not necessarily the fear itself.
Sometimes what needs to be clarified is:
- what soothes it
- what reactivates it
- how it evolves
- what should no longer reset

## 20.5. Do not turn the failsafe into a dumping ground
`[FAILSAFE]` should not absorb every unresolved problem in the script.
It does not replace:
- `[ANTI-FALLBACK]`
- `[ANTI-LOOP]`
- `[PLAYER PROTECTION]`
- `[CONTINUITY ANCHORS]`

---

# 21. Final principle

A stable bot is not a bot that produces one good scene.
It is not even a bot that “sounds right” when asked a simple question.

A stable bot is a bot that:
- understands the character correctly outside the scene
- stays coherent when projected into other contexts
- knows how to carry a scene instead of waiting passively
- keeps memory of what has changed
- does not collapse back into loops at the first difficulty
- respects the player’s boundaries
- resists model drift, fandom drift, and platform pressure

Debugging is not about smoothing the bot out.
It is about restoring the structure that allows the bot to stay coherent, active, distinct, and durable over time.
