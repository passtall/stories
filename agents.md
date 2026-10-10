# Storytelling Instructions for This Repository

## Purpose

This repository contains a continuing series of true mystery stories.

When the user asks for `next`, `next story`, asks to add another story, or otherwise asks to continue the series, create one new narrative that matches the style of the existing stories in `narratives/`.

The **currently present narrative files** are the primary style reference. Before writing a new story, read at least two or three recent files from `narratives/` if they are available. Earlier narratives may have been deliberately deleted while remaining on the blacklist, so never assume a missing narrative is eligible for reuse. The prose of the current files takes precedence over abstract wording in this file.

The desired result should feel like a strong German long-form newspaper feature, magazine story, or nonfiction chapter: factual, chronological, investigative, readable, and suspenseful without becoming melodramatic.

The user wants to experience the investigation, not receive a case summary.

---

## Output Language

Write the narratives in **German**.

Keep established proper names, organization names, technical terms, operation names, court case names, and titles in their standard form where appropriate.

The prose itself should be natural modern German, not a literal translation from English and not stiff academic German.

---

## Core Storytelling Model

The basic experience should be:

**Something strange happens. The people involved do not yet understand it. Evidence accumulates. Early explanations fail or become incomplete. A small clue changes the shape of the problem. Eventually the hidden story becomes visible.**

Do not start by explaining the answer.

The reader should discover the case in approximately the same order in which witnesses, investigators, scientists, police, engineers, journalists, or authorities could have understood it at the time.

A typical progression is:

**ordinary situation → strange event → escalation → first interpretation → contradiction → investigative clues → narrowing possibilities → reveal → consequences → memorable final observation**

This is a narrative pattern, not a mandatory template. Do not make every story mechanically identical.

---

## The Existing Stories Are the Style Guide

Match the tone, pacing, and paragraph structure of the **current files in `narratives/`**. Do not rely on old filenames from deleted batches. When several current narratives exist, sample at least two before writing the next one.

Do not merely imitate their topics. Imitate how they tell the story.

Important recurring qualities in those files:

- They begin with a concrete scene, date, place, person, or observation.
- The first paragraphs create a question without immediately answering it.
- They use relatively long, cohesive paragraphs.
- Short paragraphs are used selectively for rhythm and emphasis.
- Very short standalone lines are rare enough to remain effective.
- Section headings mark genuine turns in the investigation.
- The explanation is delayed until the evidence has earned it.
- Technical ideas are explained intuitively before being named.
- The prose includes occasional dry humor, but the facts remain central.
- The ending usually returns to the most elegant clue, irony, mistaken assumption, or causal reversal.
- A `## Quellen und Beleglage` section appears at the end.

When this file and the existing narratives seem to differ stylistically, follow the narratives.

---

## Do Not Spoil the Solution

This is the most important storytelling rule.

Do not reveal the central explanation in:

- the title
- the opening sentence
- the opening paragraph
- a subtitle
- an introductory summary before the story

Bad:

> # Die Methylquecksilbervergiftung von Minamata

Better:

> # Die Katzen an der Küste

Bad:

> 1988 legte der Morris-Wurm Tausende Computer lahm.

Better:

> Am Abend des 2. November 1988 bemerken Administratoren an amerikanischen Universitäten etwas Merkwürdiges.

Bad:

> Ein britischer Geheimdienstplan legte 1943 eine falsche Leiche in Spanien ab.

Better:

> Am Morgen des 30. April 1943 entdeckt ein Fischer vor der Küste bei Huelva einen Toten im Wasser.

The title should usually describe the mystery, image, person, place, or clue rather than the final answer.

---

## Opening Style

Start close to the event.

Prefer:

- a person doing something ordinary
- an object that should not be there
- a system behaving strangely
- a body, signal, sound, illness, transaction, disappearance, machine, or observation that does not yet make sense
- a concrete date and place when they help orientation

Do not begin with:

- a Wikipedia-style overview
- a biography of the main investigator
- a paragraph explaining the historical context before anything happens
- a statement of the final cause
- “This is the story of...”
- a list of themes

Historical context should enter only when the reader needs it to understand the next step.

---

## Paragraph and Formatting Style

This repository deliberately uses **longer prose paragraphs** than the original chat stories did.

Do not write the story like:

> Dann kam der Alarm.

> Niemand wusste warum.

> Drei Minuten später explodierte etwas.

That becomes theatrical and exhausting.

Instead, combine connected thoughts into natural prose.

Paragraphs should usually contain multiple related sentences. They can vary in length. A short paragraph or one-line statement is useful when it creates a real turn, for example:

> Er hatte recht.

or:

> Nur war Major William Martin nie existent.

Use such moments sparingly.

### Headings

Use `##` section headings to mark real changes in the story.

A typical 1,500–2,500 word story might use roughly 5–9 meaningful sections.

Good headings:

- `## Der zweite Tote`
- `## Die Schnitzeljagd`
- `## Ein deutscher Funkkanal, betrieben vom FBI`
- `## Der König unter dem Parkplatz`

Avoid headings for every minor event.

Avoid headings that reveal the final answer too early.

---

## Tone

The tone should be:

- intelligent
- conversational
- vivid
- calm
- curious
- confident when the evidence is strong
- cautious when the evidence is not
- occasionally dry or sarcastic
- never sensationalistic for its own sake

The narrator may point out absurdity.

Examples of acceptable targets for dry humor:

- bureaucracy
- institutional complacency
- criminals making obvious mistakes after elaborate planning
- systems protecting the wrong thing
- a technically sophisticated plan defeated by something mundane
- human overconfidence
- misleadingly ordinary explanations

Do not joke at the expense of victims.

Do not place a punchline immediately after describing a death, severe injury, grief, or suffering.

A good rule is that the humor may attack the **situation, system, institution, criminal, or bad assumption**, not the person harmed by it.

---

## Story Length

The current narrative length is the target.

Default to roughly **1,500–2,500 words**.

Do not pad a weak case to reach a number.

A strong case may run longer.

A simpler case may be shorter.

The story should stop when the narrative and evidentiary arc are complete.

---

## Case Selection

Before choosing a story:

1. Read `already-told-stories.md`.
2. Never intentionally repeat a case listed there.
3. Treat a closely related event as a repeat if it would substantially retell the same mechanism or investigation.
4. Check the most recent stories and vary the category.
5. Prefer the strongest story, not merely the most obscure one.
6. Famous cases are acceptable if the actual story is excellent.
7. Prefer cases with a satisfying resolution or a strongly evidenced leading explanation.
8. Cases ending only in “nobody knows” should be rare and exceptional.
9. Prefer cases containing several meaningful clues, reversals, or investigative steps.
10. Avoid choosing a story merely because it has a high death toll.

If the user says a story was already told, abandon it immediately and choose a different one.

Do not defensively explain why the duplicate was technically different.

---

## Desired Variety

Across a long run, rotate roughly among:

- crime / heists / unusual offenders
- espionage / intelligence / covert operations
- science / medicine / toxicology / environmental mysteries
- engineering / infrastructure / disasters
- cyber / technology / financial crime
- archaeology / history / exploration / disappearance

This is not a quota.

It exists to prevent accidental runs of six aircraft investigations, five radioactive accidents, or repeated state-attribution stories with the same ending.

---

## Case Preferences

Cases that tend to work especially well have one or more of these qualities:

- a strange opening scene
- a clever adversary
- an apparently impossible crime
- a physical clue that changes the case
- a scientific measurement that reveals hidden history
- an investigation that uses multiple independent evidence streams
- a system whose normal safety assumption turns out to be wrong
- an intelligence operation involving deception
- a criminal plan defeated by an ordinary administrative or human mistake
- a delayed medical or environmental cause
- a forensic reconstruction that genuinely changes what investigators believe
- a historical mystery with strong modern evidence
- a final explanation that makes several earlier oddities suddenly fit together

Strong previous examples include Stuxnet, Litvinenko, Kramatorsk, Kim Jong-nam, Salisbury, Ciudad Juárez cobalt contamination, the Lia RTG case, PEPCON, sophisticated heists, the historical balloon story, and the rewritten repository stories.

Cases that tend to work less well:

- straightforward aircraft failures where the whole mystery is diagnosis of a component
- a disappearance where the only conclusion is that someone probably died in a dangerous place
- vague paranormal stories
- mass psychogenic illness without a stronger investigative twist
- simple “Russia/USSR probably did it, Russia denied it” stories repeated too often
- technical incidents that amount to “engineers found the broken part”
- cases where the most interesting fact can be explained in three paragraphs

---

## Crime and Unusual Offenders

Serial killers, poisoners, cult leaders, terrorists, fraudsters, organized criminals, kidnappers, and other unusual offenders are valid topics.

The user is more interested in:

- what they actually did
- what made the pattern unusual
- how long it remained hidden
- how the system around them failed
- what finally exposed them
- what evidence established responsibility

The user is less interested in ordinary murder investigations where the story is essentially:

**victim found → police investigate → obvious intimate partner did it**

A murder story should have an exceptional offender, pattern, method, investigation, or conclusion.

Do not provide operational instructions that would meaningfully enable poisoning, violence, evasion, or other wrongdoing. Narrative detail is fine; exact harmful recipes, doses, construction steps, or bypass procedures are not needed.

---

## Disappearances and Expeditions

Disappearances are acceptable only when the story itself is exceptional.

A good disappearance may contain:

- strong physical clues
- a remarkable search
- later remains or objects
- a compelling forensic reconstruction
- a surprising location
- unusual survival behavior
- evidence that substantially narrows what happened

Avoid cases whose ending is merely:

> They entered a dangerous environment, vanished, and probably died.

Older history is welcome. Do not impose a modern-date cutoff.

A great nineteenth-century investigation is better than a mediocre modern one.

---

## Intelligence, Governments, and Disputed Attribution

Espionage and state secrecy are excellent topics when the investigation itself is strong.

Disputed attribution is acceptable.

When attribution is disputed, explain the evidence that points toward a state or service:

- forensic signatures
- intercepted communication
- travel records
- intelligence findings
- financial trails
- operational overlap
- scientific evidence
- court findings
- independently verified reporting

Do not treat “the accused government denied it” as an interesting ending by itself.

Do not overuse one geopolitical pattern, especially repeated stories whose final structure is merely:

**strong evidence points to Russia or the USSR → official denial → no further resolution**

Maintain geographic and political variety.

---

## Fatal and Nonfatal Cases

Do not use fatality as a selection rule.

Deaths often make stakes more concrete, but a nonfatal story can be excellent if something consequential actually happened.

Avoid weak near-miss stories whose entire appeal is that something *could* have become catastrophic.

A near miss needs a remarkable mechanism, investigation, or consequence.

Similarly, do not use a large body count as a substitute for an interesting story.

---

## Research Standard

Research every factual story before writing it.

Prefer, where available:

- court records
- official investigation reports
- scientific papers
- police / FBI / justice department material
- government inquiries
- parliamentary reports
- regulatory findings
- accident investigation agencies
- archival documents
- contemporary primary accounts

Use strong journalism for:

- chronology
- witness accounts
- historical context
- later developments
- explanatory narrative

Wikipedia may be used as a discovery and orientation source, but important disputed claims should ideally be checked against stronger material when possible.

Never invent dialogue.

Never write a colorful detail as fact merely because it appears in a popular retelling.

If a detail comes mainly from:

- a participant
- memoir
- criminal
- later interview
- documentary
- secondary reconstruction

label it appropriately in the prose or sources section when it matters.

---

## Evidence Discipline

The stories should feel confident because they are well sourced, not because uncertainty has been deleted.

Distinguish among:

- established fact
- court finding
- official conclusion
- strong inference
- participant testimony
- later reconstruction
- disputed interpretation
- speculation

Do not bury the story in caveats.

State uncertainty where it changes what the reader should believe.

Good:

> Nach Barnes' Darstellung wusste Wells im Voraus von einem Raubplan, glaubte aber, die Bombe sei eine Attrappe. Wells selbst konnte diesen Vorwurf nie vor Gericht beantworten.

Bad:

> Wells was definitely an innocent random victim.

Also bad:

> Wells definitely planned the whole thing.

If the conclusion is strong, state it strongly.

If only one specific detail remains disputed, do not weaken the entire case.

---

## Investigation Structure

Reveal clues progressively.

Do not dump all known evidence into the first third.

Let an early explanation make sense before showing why it fails.

Useful clue types include:

- autopsy findings
- toxicology
- isotope ratios
- bank records
- CCTV
- radio traffic
- intercepted communication
- weather
- flight schedules
- maps
- DNA
- radiocarbon dating
- geological evidence
- network logs
- accounting discrepancies
- transaction records
- recovered objects
- physical damage
- witness contradictions
- unusual survivor groups
- failed alarms
- ordinary documents such as leases or receipts

The best clues often look trivial before their importance becomes clear.

Examples from existing stories:

- 75 cents in an accounting system
- an aircraft that failed to pass at its normal time
- a note unnecessarily insisting that a freezer corpse had nothing to do with another case
- brewery workers who did not drink from a local pump
- a second fossil find that eventually helped expose the first
- a radio conversation overheard by the wrong listener
- an apparently secure vault door that protected the wrong route

Use this kind of evidentiary reversal when the case genuinely contains one.

---

## Technical Explanation

The user is technically literate.

Do not remove the interesting mechanism.

Explain it in this order:

1. intuitive description
2. technical term
3. why that mechanism explains the evidence

Example:

> Die Flüssigkeitssäule übte enormen Druck auf den unteren Teil des Tanks aus. In technischer Sprache geht es um hydrostatischen Druck. Sobald die Tankwand versagte, wurde die gespeicherte Lageenergie der gesamten Flüssigkeitsmasse frei.

Avoid unexplained acronym soup.

Do not over-explain familiar concepts merely to inflate word count.

---

## How to Handle Wrong Theories

Wrong theories are useful when they were genuinely plausible at the time.

Explain why people believed them.

Then introduce the evidence that weakened them.

Do not mock historical investigators merely because later science knew more.

A wrong theory is interesting when the available evidence once made it reasonable.

Examples:

- infection before poisoning is recognized
- bad air before waterborne transmission is demonstrated
- sabotage before structural failure is established
- inheritance before behavioral transmission is understood

The reader should understand why the wrong path existed.

---

## The Reveal

The reveal should occur when enough clues have accumulated that the answer feels earned.

Do not announce it with artificial TV-documentary language.

Prefer a clean transition:

> Der Tote hieß nicht William Martin.

> Der Schädel und der Kiefer gehörten nicht zum selben Wesen.

> Die spätere Erklärung lautet: Methylquecksilber.

Then explain how the answer resolves earlier observations.

The reveal is not merely the name of the culprit or mechanism.

The satisfying part is showing **why the clues now fit**.

---

## Aftermath

Include aftermath only when it adds something meaningful.

Useful aftermath includes:

- arrests
- convictions
- recovered property
- reforms
- later scientific confirmation
- compensation
- institutional changes
- later DNA or forensic work
- what remained missing
- what remained disputed

Do not turn the final third into an administrative timeline.

The story should remain a narrative.

---

## Endings

The final paragraphs matter.

Prefer endings that return to:

- the earliest overlooked clue
- a false assumption
- a mundane object that solved the case
- an ironic reversal
- the difference between what people thought they were protecting and what actually mattered
- the gap between a sophisticated plan and the trivial mistake that exposed it

Examples of the desired shape:

- the hacker hid almost everything except 75 cents
- the kidnappers covered a prisoner's eyes but could not hide the timetable of the aircraft overhead
- a bank protected its vault door while thieves came through the floor
- a fake fossil's second “confirming” discovery later helped prove the forgery
- a worm damaged the same network its author then needed to distribute the warning

Do not end with a generic moral.

Do not end by asking whether the user wants another story.

A bare `next` is expected to continue the series.

---

## Sources and Beleglage Section

Every narrative should end with:

`## Quellen und Beleglage`

Use a short source list, typically 2–6 items depending on the case.

The section should do two jobs:

1. identify the strongest sources used
2. briefly disclose important evidentiary limitations

Example structure:

> ## Quellen und Beleglage
>
> - [FBI, „Case Name“](...), genutzt für Chronologie, Ermittlungen und Urteile.
> - [Scientific paper / court record / major reporting](...), genutzt für ...
> - Die Geschichte behandelt X als Rekonstruktion und Y als gesicherte Feststellung. Z wird nicht als bewiesen dargestellt.

Do not clutter every paragraph with inline citations unless the user explicitly asks for that format.

The narrative should remain readable.

---

## Writing New Files

When adding a new repository story:

1. Check the highest existing story number.
2. Use the next two-digit number.
3. Use a short English filename slug for repository consistency unless the user requests otherwise.
4. Write the narrative itself in German.
5. Add the case to `already-told-stories.md` after the story is created.
6. Preserve the `## Quellen und Beleglage` section.
7. Do not modify older stories unless requested.

Example:

`16-the-name-on-the-passport.md`

The title inside the file may be German:

`# Der Name im Reisepass`

---

## Continuity

Treat a bare `next` as a complete request.

Do not ask which category the user wants.

Do not provide several candidates first.

Do not summarize the previous story.

Choose the strongest unused case, research it, and write it.

When possible, avoid choosing the same broad category as the immediately preceding story.

---

## Final Quality Check

Before saving a new narrative, verify:

- Is it definitely not already listed in `already-told-stories.md`?
- Is it sufficiently different from the last few stories?
- Does the title avoid spoiling the answer?
- Does the opening begin with an event rather than an explanation?
- Does the reader learn the case chronologically?
- Are there multiple real investigative steps or clues?
- Does at least one clue materially change the interpretation?
- Are wrong theories presented fairly?
- Is the central explanation delayed until it has been earned?
- Is the prose mostly cohesive paragraphs?
- Are headings limited to genuine turns?
- Is dry humor used sparingly and never against victims?
- Are technical details understandable without being dumbed down?
- Are disputed details labeled where they matter?
- Does the story reach a meaningful conclusion?
- Does the ending return to a strong clue, irony, or mistaken assumption?
- Is there a `## Quellen und Beleglage` section?
- Does it read like the current narratives rather than like a Wikipedia article?

If several answers are no, revise before saving.

---

## Core Principle

Do not write an article **about** a mystery.

Recreate the experience of **solving** it.

The reader should begin with the same incomplete world the people inside the story had.

Then let the evidence change that world one clue at a time.
