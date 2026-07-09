# How to Understand and Use PolyBuzz Permanent Memory

# 📖 1. Introduction

After spending hundreds of hours roleplaying and testing PolyBuzz, I gradually developed my own way of working with Permanent Memory.

This document is **not** official PolyBuzz documentation.

I obviously do not have access to PolyBuzz's internal systems. Everything presented in this guide is based on my own observations, repeated testing, and the workflow that has consistently produced the best results for me.

Some of these behaviors may change as PolyBuzz evolves, and other users may have reached different conclusions or developed different methods.

The goal of this guide is therefore **not** to explain how Permanent Memory works internally, but to share the observations and practical methods that have allowed me to make much better use of it during long-term roleplays.

I hope these observations will also help you improve your own experience.

---

# 🏗️ 2. Permanent Memory Architecture

At the time of writing, Permanent Memory is organized as follows:

```text
Permanent Memory
│
├── 📌 Pinned
│
├── 🔗 Link
│   ├── Important Events
│   ├── Agreements & Tasks
│   ├── Important Elements
│   └── Relationships
│
├── 👤 Character
│   ├── Main Character
│   ├── Secondary Characters
│   └── One profile for every character encountered
│
├── 🙋 User
│   ├── Name
│   ├── Nickname
│   ├── Age
│   ├── Gender
│   ├── Sexual Orientation
│   ├── Preferences
│   ├── Other Important Information
│   ├── Appearance
│   ├── Personality
│   ├── Identity
│   └── Residence
│
└── 📅 Memories
```

Each section appears to serve a different purpose.

From my observations, not every field behaves the same way.

Some fields can be edited manually.

Others appear to be entirely managed by PolyBuzz.

Some information also seems to evolve automatically as the roleplay progresses.

Understanding these differences is, in my opinion, one of the most important steps toward using Permanent Memory effectively.

The following chapters will examine each section in detail.

---

# ⚙️ 3. How Permanent Memory Appears to Be Built

From my observations, Permanent Memory is not created once and then left unchanged.

Instead, it seems to evolve continuously throughout the entire roleplay.

Personally, I think of this process as four different stages.

## 3.1 Initial Generation

When Permanent Memory is enabled while creating a character, PolyBuzz appears to extract information from the script, the opening message, and the introduction.

This first extraction seems to create the initial character profiles as well as several entries inside Permanent Memory.

However, I have also observed that this extraction is not always perfect.

Some information may be ignored.

Some details may be interpreted differently than intended.

Other information may simply never be stored, even if it is clearly present in the script.

Later chapters will discuss which types of information seem to be prioritized.

## 3.2 Growth During Roleplay

Once the roleplay begins, Permanent Memory appears to continue updating itself automatically.

Throughout the story, I have observed that PolyBuzz may:

- create new important events;
- generate profiles for newly introduced characters;
- enrich information about the user;
- update relationships between characters;
- register new objects, abilities, or other important elements.

In other words, Permanent Memory does not appear to be static.

Instead, it seems to keep evolving as the roleplay progresses.

## 3.3 User-Provided Information

Not every field inside Permanent Memory is fully automatic.

Some fields can be edited directly by the player.

Others appear to remain entirely under PolyBuzz's control.

Understanding which fields belong to each category is extremely important, and the following chapters dedicated to the **User** and **Character** sections will cover this in detail.

## 3.4 A Memory That Requires Monitoring

One of the main conclusions I reached during my testing is that Permanent Memory should not be treated as infallible.

Instead, I recommend checking it regularly.

Over time, I have observed entries that were:

- incomplete;
- simplified;
- misinterpreted;
- or occasionally completely incorrect.

Finding these issues early usually makes them much easier to deal with before they begin affecting the roleplay over hundreds or even thousands of messages.

Later in this guide, I'll explain which sections I personally consider the most important to monitor.

# 👤 4. The User Section

The **User** section contains the information PolyBuzz knows about the player.

At first glance, it looks like a simple character profile.

However, from my observations, not every field behaves the same way.

Some fields can be edited manually.

Others are generated automatically and cannot be edited directly.

Understanding this distinction is essential if you want to make good use of Permanent Memory.

---

## ✏️ Editable Fields

At the time of writing, the following fields can be edited manually:

- Nickname
- Age
- Gender
- Sexual Orientation
- Appearance
- Personality
- Identity
- Residence

Most editable fields allow approximately 200 characters.

Some shorter fields, such as nickname, age, gender, and sexual orientation, have a much lower character limit.

Personally, I recommend writing these fields the same way you would write an LLM script.

Avoid long literary descriptions.

Instead, write concise, structured information that is easy for the model to interpret.

For example, rather than writing a paragraph describing your personality, I recommend listing the behavioral traits that actually influence how your character behaves.

I also strongly recommend writing every editable field in the same language as your roleplay.

Otherwise, PolyBuzz may occasionally reuse words from another language during conversations, producing awkward multilingual responses.

---

## 🤖 Automatically Generated Fields

Two fields behave differently:

- Preferences
- Other Important Information

As far as I have been able to determine, these fields cannot be edited manually.

During the initial generation, PolyBuzz appears to extract information from the opening message or introduction whenever it considers that information important enough.

Afterward, these fields also seem to continue evolving automatically during the roleplay.

For example, if the player repeatedly mentions liking certain things, those preferences may eventually be added automatically.

However, I have also observed that this process is not entirely predictable.

Some information that I personally consider important is never recorded.

Meanwhile, other details sometimes appear even though I would not have expected PolyBuzz to store them.

In other words, these fields appear to depend entirely on PolyBuzz's own interpretation of what is worth remembering.

---

## ⚠️ The Special Case of "Other Important Information"

This field deserves special attention.

Throughout all of my testing, I have never found a reliable way to edit information once it has been written into this field.

If PolyBuzz stores an incorrect piece of information here, that mistake may remain for the rest of the roleplay.

The error might concern:

- a factual detail;
- an interpretation;
- an intention attributed to the player;
- a personality trait;
- or any other piece of information PolyBuzz considers important.

For this reason, I strongly recommend checking this field regularly.

If an incorrect interpretation appears here, detecting it early is usually much easier than trying to deal with its consequences hundreds of messages later.

We'll discuss possible correction methods later in this guide.

---

## 💡 About the PolyBuzz Persona

PolyBuzz also includes a separate Persona system.

I deliberately won't cover it in detail here.

In my opinion, it deserves its own dedicated guide.

For now, I'll simply mention one observation.

From my testing, the Persona can interact with Permanent Memory.

For example, some Persona information appears to populate certain Permanent Memory fields automatically, especially the Personality field.

Because of this, I personally prefer to think of the Persona and Permanent Memory as complementary systems rather than completely independent features.

A future guide will explain how I personally use the Persona alongside Permanent Memory.

---

# 👥 5. The Character Section

The **Character** section works very similarly to the **User** section.

It contains nearly the same categories:

- identity;
- appearance;
- personality;
- preferences;
- residence;
- and more.

The major difference is that these profiles cannot be edited manually.

From my observations, PolyBuzz automatically creates a profile for the main character and then gradually generates profiles for new characters introduced throughout the roleplay.

These profiles also appear to evolve over time.

---

## 📌 Profiles Continue to Evolve

As the roleplay progresses, I have observed PolyBuzz adding information to character profiles.

For example, it may:

- add new preferences;
- expand personality descriptions;
- refine identity information;
- enrich character descriptions.

These changes appear to be based on what happens during the roleplay itself.

---

## ⚠️ The Biggest Risk: Incorrect Interpretations

In my opinion, this is where Permanent Memory becomes the most sensitive.

If PolyBuzz misinterprets a character's behavior, that interpretation may eventually become part of the character's profile.

Examples might include:

- assigning jealousy to the wrong person;
- oversimplifying an emotional response;
- exaggerating a recurring behavior;
- creating an overly broad generalization.

Once stored, these interpretations may continue influencing the character's future behavior.

The longer the roleplay becomes, the more noticeable their effects may be.

---

## 🎭 Extra Attention for Canon Characters

I pay particularly close attention to canon characters.

Much of my work focuses on reducing fandom fallbacks and behavioral simplifications produced by language models.

If Permanent Memory records one of those simplifications, it may gradually reinforce it over time.

For that reason, I recommend checking the profiles of important characters regularly.

Correcting a mistaken interpretation early is usually much easier than trying to fix it after hundreds of additional messages.

# 🔗 6. The Link Section

In my opinion, the **Link** section is the most interesting part of Permanent Memory.

It is also the section that took me the longest to understand through testing.

Everything presented in this chapter is based on my own observations after many long-term roleplays.

I do not claim to understand how PolyBuzz works internally.

This is simply the workflow that has consistently produced the best results for me.

The **Link** section is divided into four categories:

- Important Events
- Agreements & Tasks
- Important Elements
- Relationships

Each category appears to serve a different purpose.

---

# 📅 Important Events

Important Events are, in my opinion, the core of Permanent Memory.

During my testing, I observed that PolyBuzz gradually creates event summaries as the roleplay progresses.

Each event generally contains:

- the participants;
- a summary of what happened;
- a time reference;
- a location.

Most of my own writing methodology for openings and time skips actually comes from trying to understand how this part of Permanent Memory behaves.

---

## 📍 Why I Always Use Precise Time References

If you've read my other guides, you've probably noticed that I always recommend using:

- a complete date;
- a precise time;
- a precise location.

Originally, I adopted this method simply because it made roleplays more coherent.

However, after many tests, I began noticing something else.

Using precise temporal and spatial anchors also seemed to improve the way Permanent Memory organized events.

For example, whenever I only wrote things like:

> The next day...

or

> Later that afternoon...

I often had the impression that multiple scenes were merged into the same event.

On the other hand, when I consistently used precise dates, hours and locations, Permanent Memory appeared to generate more distinct events.

I obviously cannot confirm that this is how PolyBuzz actually works internally.

This is simply the behavior I repeatedly observed during my own testing.

---

## 🕒 Time Alone Doesn't Always Seem Enough

Another observation surprised me.

Changing only the date didn't always seem to generate a new event.

Likewise, changing only the location didn't always appear sufficient either.

However, combining both precise time and location consistently gave me much better results.

This is precisely why nearly all of my openings follow the same structure.

---

# 🔄 Why I Always Write a Transition

Before every time skip, I almost always write a transition.

For example:

> *The following days pass between missions, daily routines and ongoing research...*

The purpose of this sentence is not simply to advance time.

Its primary role is to close the current scene.

Only after that transition do I begin the next scene.

Personally, I think this also produces a much smoother reading experience.

My workflow usually looks like this:

```text
Current scene

↓

Transition
(closes the current scene)

↓

Opening narrative sentence

↓

New scene
```

---

# ✍️ One Narrative Sentence

Another thing I gradually started doing was keeping the date, time, location and beginning of the new scene inside a single narrative sentence.

For example:

> *On October 22nd, Year 106 of the Shinobi Calendar, at 7:10 PM, I return home after a long day.*

Personally, I avoid writing something like:

> *October 22nd, Year 106.*

> *I return home.*

From my own observations, keeping everything inside one narrative sentence appears to produce more stable results.

Once again, this is only an observation based on my own testing.

---

# ⏭️ Why I Regularly Use Time Skips

Over time, I also noticed that very long scenes often caused Permanent Memory to gradually rewrite the corresponding event.

Older information sometimes disappeared while newer information replaced it.

In other words, the longer a scene lasted, the greater the chance that earlier details would eventually disappear from that event summary.

Because of this, I personally prefer ending a scene once it has fulfilled its narrative purpose.

I then create a new event through a time skip.

For long-term roleplays, this workflow has consistently produced better results for me.

---

# 🧠 Recalling Previous Events

One of the biggest advantages of building events this way appears later during the roleplay.

If events have clear temporal and spatial anchors, I have found that it becomes much easier to refer back to them naturally.

For example, instead of saying:

> Do you remember that day?

I can say something much more specific, such as:

> Remember October 22nd, Year 106, when we were at my house...

In many of my tests, the bot was able to reconnect much more accurately with the event I was referring to.

This is one of the reasons why I insist so much on precise dates and locations.

For me, they are not only narrative tools.

They also become useful reference points later in the roleplay.

---

# 📋 Agreements & Tasks

This category appears to store commitments made during the roleplay.

Examples include:

- promises;
- upcoming meetings;
- contracts;
- planned missions;
- important tasks.

Unlike Important Events, these entries seem to evolve much more slowly.

When something changes, PolyBuzz generally appears to update the existing entry instead of creating a completely new one.

---

# 📦 Important Elements

This category appears to contain objects or concepts that PolyBuzz considers important enough to preserve.

Most commonly, I have found:

- objects;
- weapons;
- techniques;
- abilities;
- important narrative elements.

Some of these elements are already present immediately after the character is generated, especially when they are strongly emphasized in the script, opening message or introduction.

However, this is not always consistent.

Two very similar bots may produce different results.

At least so far, I have not been able to identify a completely reliable rule explaining these differences.

---

# 🤝 Relationships

The **Relationships** category appears to summarize how characters relate to the player.

This doesn't only concern the main character.

Secondary characters also receive their own relationship entries.

From my observations, these entries generally evolve gradually over time.

When a major relationship changes, PolyBuzz often seems to rewrite the summary instead of simply adding contradictory information.

For example, an enemy who later becomes a romantic partner may eventually be summarized as a former enemy who became a lover.

However, during extremely long roleplays, I have occasionally observed inconsistencies.

Older relationship information sometimes remains alongside newer information instead of being fully replaced.

For that reason, I personally recommend checking this category regularly as well.

# 🛠️ 7. Correcting and Maintaining Permanent Memory

Despite its strengths, Permanent Memory is not perfect.

Throughout my testing, I have observed that some information can occasionally be misunderstood, oversimplified or simply recorded incorrectly.

Because of this, I personally consider Permanent Memory to be something that requires occasional maintenance rather than something that can safely be ignored once a roleplay begins.

I don't check it after every message, but I do recommend reviewing it regularly, especially after important story developments.

---

# 👀 Regularly Review Your Permanent Memory

One habit that has helped me a great deal is simply opening Permanent Memory from time to time to verify that everything still makes sense.

In particular, I usually check:

- character profiles;
- relationships;
- recent events;
- important elements;
- information about the player.

Doing this regularly allows me to catch mistakes before they begin affecting the roleplay over hundreds or even thousands of messages.

The longer an incorrect piece of information remains inside Permanent Memory, the more likely it is to influence the bot's future behavior.

---

# ⚠️ The Most Sensitive Fields

Not every field inside Permanent Memory carries the same level of risk.

In my experience, the **Other Important Information** field deserves the most attention.

Across all of my testing, I have never found a reliable way to manually modify information once it has been written into this field.

This applies to:

- the player;
- the main character;
- secondary characters.

If an incorrect interpretation ends up here, it may remain for the rest of the roleplay.

The mistake may concern:

- a factual detail;
- an intention attributed to the player;
- a personality trait;
- an emotional interpretation;
- or a simplified behavioral pattern.

These kinds of mistakes can significantly affect future interactions.

For that reason, I strongly recommend checking these fields regularly.

---

# 💬 Communicating with the Game System

Over time, I developed a method that sometimes allows me to correct information stored inside Permanent Memory.

I intentionally say **sometimes**, because this method is not guaranteed to work.

It is simply the approach that has produced the best results during my own testing.

The idea is to temporarily step outside the roleplay and address what I call the **game system**.

To do this, I send a message written between parentheses.

For example:

> *(I'm addressing the game system. I have a question regarding Permanent Memory.)*

At this point, I do **not** ask for any correction yet.

The purpose of this first message is simply to initiate the interaction.

In most of my tests, the system then replies, indicating that it is ready to answer questions about Permanent Memory.

Only then do I make my request.

---

# ✍️ How I Phrase Correction Requests

Over time, I noticed that the wording of the request seems to matter.

Personally, I try to keep every request:

- focused on a single correction;
- short;
- factual.

For example:

> Could you correct Shikamaru's eye color? His eyes are black, not brown.

I avoid making multiple requests in the same message.

Likewise, I avoid long explanations whenever possible.

If the correction succeeds, Permanent Memory is usually updated shortly afterward.

I always verify the result immediately.

---

# ❓ Why I Ask Instead of Giving Orders

One interesting pattern I repeatedly observed concerns the way requests are phrased.

Personally, I obtain much better results by asking questions, for example:

> Could you tell me...

or

> I have a question regarding Permanent Memory...

than by writing commands such as:

> Correct...

> Change...

I cannot explain why this seems to work better.

I can only say that, based on my own testing, approaching the interaction as a question has consistently produced more reliable results.

---

# 💡 Explaining Why the Correction Matters

Sometimes a correction doesn't work on the first attempt.

When that happens, I occasionally add a very brief explanation.

For example, I might explain that the incorrect information prevents the roleplay from continuing properly or negatively affects the overall roleplay experience.

Again, I cannot guarantee that this makes a difference.

I simply observed that this kind of justification sometimes seems to increase the likelihood that the correction will be accepted.

---

# 🚫 One Correction at a Time

Another habit I strongly recommend is limiting each interaction to a single correction.

From my observations, extending the conversation with the game system for too long tends to make the interaction less reliable.

My usual workflow is therefore very simple:

- initiate the interaction;
- request one correction;
- verify the result;
- immediately return to the roleplay.

If another correction is needed, I usually prefer opening a new interaction later instead of chaining multiple requests together.

---

# ↩️ When Rollback Becomes the Best Option

Unfortunately, some mistakes simply refuse to be corrected.

When that happens, I personally consider rollback to be the safest solution.

I would rather lose a few recent messages than allow an incorrect piece of Permanent Memory to influence the following hundreds of messages.

This is especially true when the mistake concerns:

- the **Other Important Information** field;
- an important character behavior;
- a major relationship;
- or any interpretation likely to influence the long-term direction of the roleplay.

In those situations, performing a rollback is often much less costly than keeping an incorrect memory permanently attached to the roleplay.


# ✅ 8. Best Practices

To conclude this guide, here are the main principles I personally follow when using Permanent Memory in PolyBuzz.

These are **not** universal rules.

They are simply the practices that have consistently produced the best results during my own testing.

---

## 📝 Write in the Same Language as Your Roleplay

Whenever I manually edit Permanent Memory, I always use the same language as the roleplay itself.

For example, if my RP is written in French, I also write every editable field in French.

During my testing, I noticed that mixing languages sometimes causes PolyBuzz to reuse foreign words or expressions directly during conversations.

Although this doesn't prevent Permanent Memory from working, the result often feels much less natural.

---

## 🤖 Write for an LLM, Not for a Human Reader

Whenever a field can be edited manually, I recommend treating it like part of an LLM script rather than a piece of prose.

In practice, this means:

- writing concise information;
- avoiding unnecessary wording;
- avoiding long literary descriptions;
- focusing on information that is easy for the model to interpret.

The goal is not to write something beautiful.

The goal is to write something the model can understand consistently.

---

## 👀 Check Permanent Memory Regularly

One of the habits that has helped me the most is checking Permanent Memory on a regular basis.

Not after every message.

Not after every scene.

But often enough to catch mistakes before they become part of a very long roleplay.

In my experience, correcting an incorrect entry early is almost always easier than trying to fix the consequences hundreds of messages later.

---

## 📅 Structure Your Scenes

One of the biggest improvements I have made to my own workflow concerns scene structure.

Whenever possible, I prefer to:

- properly conclude the current scene;
- write a transition;
- begin the next scene with a precise date, time, location and the opening action contained within the same narrative sentence.

Based on my own observations, this approach seems to produce a much more stable event history inside Permanent Memory.

---

## ⏭️ Don't Let Scenes Last Forever

Very long scenes often appear to evolve continuously inside Permanent Memory.

As new information is added, older details may gradually disappear or be summarized.

Because of this, I generally prefer ending a scene once it has accomplished its narrative purpose.

A well-placed time skip often creates a much cleaner separation between events.

---

## 🎭 Pay Extra Attention to Important Characters

I recommend paying particular attention to the profiles of important characters.

An incorrect interpretation stored there can sometimes influence the character's behavior for a very long time.

This is especially true for canon characters.

If Permanent Memory reinforces an incorrect interpretation or a fandom-driven simplification, it may gradually strengthen exactly the kind of fallback your script was designed to avoid.

---

## 🔄 Correct Mistakes as Soon as Possible

Whenever I notice an incorrect entry, I try to deal with it as soon as possible.

The longer it remains inside Permanent Memory, the more opportunities PolyBuzz has to reuse it.

If I cannot correct it, I generally prefer performing a rollback rather than continuing with incorrect information.

---

# 📚 Conclusion

Permanent Memory is, in my opinion, one of the most powerful features currently available in PolyBuzz for long-term roleplay.

At the same time, it is also one of the least understood.

Over time, I realized that getting the most out of it is not simply a matter of enabling the feature.

It requires understanding how it appears to evolve, learning how to work with it, checking it regularly and correcting mistakes before they become long-term problems.

Everything presented in this guide is based on my own observations.

I do not claim that these are the only possible methods, nor do I claim to know exactly how PolyBuzz works internally.

Other users may have reached different conclusions or developed different workflows.

My hope is simply that sharing my own experience will help others better understand Permanent Memory, avoid some common pitfalls and build more stable long-term roleplays.

Like the rest of this repository, this guide will continue to evolve.

As I continue testing PolyBuzz and as the platform itself evolves, some of these observations may be refined, corrected or expanded in future updates.
