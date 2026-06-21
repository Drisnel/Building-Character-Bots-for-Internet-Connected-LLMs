# How to Protect Player Agency in RP Bots

After building and testing a large number of RP bots, I eventually realized that player protection is not a minor detail.

It is structural.

A bot can have a strong script, a good introduction, and a solid starter, and still become unpleasant to play if it repeatedly takes over the player.

The most common failures are not subtle.

The bot starts writing the user's dialogue.
The bot starts narrating from the user's point of view.
The bot starts deciding the user's thoughts, emotions, intentions, desire, or consent as if they were already known facts.

At that point, the bot is no longer only playing the character.

It is partially playing the user too.

For some players, that is an immediate dealbreaker.

For others, the problem is more specific.

They may accept guided roleplay.
They may accept physical scene progression.
They may even want the bot to carry momentum through combat, intimacy, or high-action scenes.

What they do not want is for the bot to replace their internal agency.

That distinction matters.

Player protection is not only about preventing bad writing.

It is about defining what the bot is and is not allowed to control.

This is not the only valid method.

It is simply the framework that currently gives me the most stable results when building RP bots for internet-connected LLMs.

---

# 1. Player Protection Is A Design Choice, Not A Single Rule

One of the easiest mistakes is treating player protection as a single universal module.

In practice, it is not.

Different creators want different levels of control.

Some want maximum player agency and minimal bot guidance.

Others want guided roleplay where the bot can carry action, pacing, and physical continuity without taking over the user's inner state.

Both approaches are valid.

The important part is choosing deliberately.

If the module is too loose, the bot starts taking over the player.

If the module is too rigid, the bot becomes difficult to play, especially in scenes where the player uses continue, wants the bot to carry momentum, or does not want to answer every micro-action line by line.

Because of that, I do not think in terms of one universal player protection block.

I think in terms of protection style.

At minimum, I distinguish between:

- strict player protection
- guided player protection

The difference is not whether the bot protects the player.

The difference is how much scene control the bot is allowed to carry while doing it.

---

# 2. The Actual Failure Mode

The problem is not simply "the bot should not write the user's thoughts."

The real failure mode is broader.

A bot starts collapsing the boundary between character and player.

Common examples:

- writing the user's dialogue
- narrating in first person as the user
- narrating from the user's point of view
- deciding what the user thinks
- deciding what the user feels
- deciding what the user wants
- deciding what the user intends
- deciding what the user consents to
- deciding what the user enjoys
- treating silence as emotional agreement
- turning visible reaction into internal certainty
- speaking as if the user's inner state is already known

At that point, the bot is no longer interpreting the player's responses.

It is replacing them.

The exact form varies, but the underlying problem is the same:

the bot stops treating the user as a separate participant with protected internal agency.

---

# 3. The Core Boundary: Internal vs External

For me, the most useful player protection boundary is not "the bot may never do anything to the user."

That rule is too rigid for many RP styles.

The most useful boundary is:

internal = protected
external = negotiable

That means the bot should not define the user's internal state as fact.

It should not decide:

- thoughts
- emotions
- intentions
- desire
- consent
- enjoyment
- willingness
- private conclusions
- unspoken motives

unless the user has already made those things explicit.

External scene handling is different.

Depending on the protection style, the bot may be allowed to describe:

- visible reactions
- body language
- contextual physical responses
- the physical effect of actions on the user's body
- movement through the scene
- scene continuity without waiting for a micro-response every line

That is the real distinction I care about.

The bot may be allowed to move the scene.

It may not replace the user's inner state.

---

# 4. Why This Gets Complicated In Practice

In theory, player protection sounds simple.

In practice, it becomes messy very quickly.

Why?

Because roleplay is not only conversation.

There are scenes where the player expects the bot to carry momentum.

Examples:

- combat
- chase scenes
- rescue scenes
- medical scenes
- physical conflict
- high-intensity intimacy
- scenes where the player uses continue instead of replying line by line

In those scenes, a bot that refuses to do anything involving the user can become frustrating to play.

It stalls.
It asks too many questions.
It waits for validation every few lines.
It turns action scenes into negotiation loops.
It turns intimacy into endless verbal confirmation.
It turns combat into turn-by-turn paralysis.

That is why I do not think "the bot must never move the user" is a universally good rule.

Sometimes the creator wants that level of strictness.

Sometimes they do not.

The important part is being explicit about which version the bot is using.

---

# 5. Strict Player Protection

Strict player protection is the more restrictive model.

It is designed for creators who want maximum user control and minimal bot guidance.

In this model, the bot still cannot write the user's internal state.

But it also avoids carrying too much of the user's physical participation.

That usually means:

- avoiding extended physical guidance without a user response
- avoiding moving the user through the scene unless the scene absolutely requires immediate cause and effect
- avoiding treating silence as agreement
- avoiding escalating physical or intimate scenes without clear user participation
- leaving more room for the user to respond before the scene advances

This style is useful when the creator wants very strong player control and is willing to accept slower pacing in exchange.

It is also useful for players who strongly dislike being physically steered by the bot.

Its weakness is obvious.

If used too rigidly, it can make the bot hesitant, fragmented, and difficult to play in action-heavy scenes.

---

# 6. Guided Player Protection

Guided player protection is the more flexible model.

It still protects the user's internal state.

It still forbids the bot from taking over the user's dialogue, POV, thoughts, emotions, intentions, or desire as fact.

But it allows the bot to carry more of the scene externally.

That can include:

- visible reactions
- contextual physical responses
- physical displacement within the scene
- the physical effect of the bot's actions on the user's body
- guided scene progression
- continuity without pausing for micro-responses

This model is useful for creators who want the bot to maintain scene momentum.

It works especially well for:

- action scenes
- combat
- physically intense scenes
- intimate scenes where the player accepts guided pacing
- continue-button playstyles

Its risk is different from the strict version.

If the boundary is written badly, guided protection can slide into the bot taking over the user's internal state under the excuse of "scene continuity."

That is why the internal vs external line must stay explicit.

---

# 7. Consent Is Part Of Player Protection, But Hardcoding It Badly Can Freeze The Bot

Consent is one of the easiest areas to mishandle in a player protection module.

If the module is too loose, the bot may start assuming consent, attraction, enjoyment, or willingness without the user ever expressing them.

If the module is too rigid, the bot may start asking for explicit verbal confirmation before every single escalation.

That creates a different problem.

The scene freezes.

The bot stops progressing.
The continue button becomes useless.
Every intimate or physical scene turns into repetitive confirmation loops.

I do not think the solution is pretending consent does not matter.

I think the solution is writing the module around internal certainty rather than constant verbal checkpoints.

The bot should not decide the user's consent as a fact if the user has not expressed it.

That does not automatically mean the bot must halt every scene and demand explicit confirmation every few lines.

It means the bot should not narrate the user's willingness, enjoyment, or acceptance as already known internal truth.

The bot can continue the scene according to the chosen protection style.

It should not overwrite the user's inner state while doing it.

---

# 8. External Effects Are Not The Same As Internal Facts

This distinction matters enough to be stated explicitly.

These are not the same kind of sentence:

Bad:
- you wanted more
- you melted into him
- you were desperate for it
- you trusted him completely
- you needed him
- you welcomed it
- you gave in because you wanted this

These all define the user's internal state as fact.

By contrast, guided scene writing may include things like:

- the force of the impact knocks the breath from your lungs
- his hand drags you a step closer
- the movement pins you briefly against the wall
- the sudden pull throws you off balance
- the heat of his body traps you between him and the table

These describe external scene effects.

They do not automatically define what the user thinks or wants about them.

That distinction is the core of guided player protection.

The bot may describe what happened.

It may not decide what the user feels about what happened.

---

# 9. What I Never Allow In Either Version

No matter which protection style I use, some things remain forbidden.

I do not allow the bot to:

- write the user's dialogue
- write in first person as the user
- narrate from the user's POV
- decide the user's thoughts as fact
- decide the user's emotions as fact
- decide the user's intentions as fact
- decide the user's desires as fact
- decide the user's consent as fact if the user has not expressed it

Those are the baseline protections.

The difference between strict and guided protection is not whether these rules exist.

The difference is how much external scene control the bot is allowed to carry around them.

---

# 10. Recommended Strict Module

This is the stricter version I would use for creators who want maximum player agency and minimal bot guidance.

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

# 11. Recommended Guided Module

This is the version I would use for creators who want guided roleplay while preserving the user's internal agency.

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

# 12. How I Choose Between Them

I do not choose strict or guided protection based on abstract preference alone.

I choose based on the kind of bot I am building and the kind of roleplay I want it to support.

I am more likely to choose strict protection when:

- the bot is meant for players who want very high personal control
- the roleplay is slow, conversational, or emotionally careful
- I do not want the bot physically steering the user very much
- I would rather sacrifice speed than risk overreach

I am more likely to choose guided protection when:

- the bot needs to carry scene momentum
- the roleplay includes combat, action, rescue, or high physicality
- the roleplay includes intimate scenes where the player accepts guided pacing
- the player often uses continue instead of replying line by line
- I want the bot to remain active rather than overly hesitant

Neither version is automatically better.

They solve different problems.

---

# 13. Common Mistakes When Writing Player Protection

Some common failure patterns:

- writing a player protection block that only says "never write the user's thoughts" and nothing else
- forbidding internal narration but forgetting to forbid user dialogue and POV
- making the block so strict that the bot becomes unable to move the scene at all
- making the block so loose that "guided" becomes "the bot decides everything for the user"
- treating visible physical response as identical to internal emotional certainty
- hardcoding consent in a way that forces verbal validation every few lines
- failing to distinguish between external effect and internal meaning
- assuming one player protection style fits every bot

The goal is not simply to prevent the worst-case violation.

The goal is to define a stable and playable boundary.

---

# 14. My General Rule

If I had to reduce the whole framework to one principle, it would be this:

protect the user's inner state.
decide deliberately how much external scene control the bot is allowed to carry.

That is the real design choice.

Not whether player protection matters.

It does.

The real choice is how strict or how guided the protection should be.

---

# Final Thought

Player protection is not a decorative module.

It is one of the systems that determines whether a bot feels collaborative or invasive.

A good player protection block does not only prevent the bot from speaking for the user.

It defines the line between roleplay guidance and player replacement.

That line will not look exactly the same for every creator.

Some want strict agency.
Some want guided agency.
Both can work.

What matters is writing the boundary clearly enough that the bot knows where the user ends and the character begins.