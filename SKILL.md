---
name: the-payoff-script
description: Writes the long-form YouTube script in two passes, an outline the founder reviews first and then the full script, pouring a winning video's substance into the lesson cage (hook, credibility, outline, problem, solution, workflow, FAQ, close), recorded as one layer: the deck, the live screen, or the face. Use this whenever the founder wants a script or an outline, says the next video is ready to write, or calls for the Payoff Script, and right after the winner file and the locked package exist.
---

# The Payoff Script

Two passes with one stop between. The prep IS the outline (route, timings, beats,
key lines); the founder reviews it, then the full script inherits it word for word.

Identity resolves from `.claude/squad-roots.md`, read first (a repo carrying
the legacy `.claude/spine-roots.md` keeps working: read it as the fallback when
no squad-roots.md exists): the founder's name, the brand words (the product word
and its banned synonyms), the episodes root, the week folder, the credibility
bank path (`squad/credibility-bank.md`), the voice file, the wpm, and the data
sources. **The install lesson creates that file with every field at "(none yet)";
/the-winning-offer fills the ones its run answers** (the founder's name, the
product word, the accent color). This skill reads it, fills any field it learns during the run, and never asks
again for a field the file already answers. the-presentation's First run fills
whatever is still "(none yet)".

No roots file at all means the install never wrote one. Say so, take the
worked-example paths in this file as the defaults (episodes root
`squad/episodes/`, week folder `squad/week/`), and ask the founder once for
their name and their product word (the one noun you call your offer, plus the
synonyms you never want said). Write both answers into
`.claude/squad-roots.md` with every other field as "(none yet)", so the next
skill inherits them instead of interviewing again.

Input, three files. Two are the week's, both in the roots file's week folder:
the Winning Scrape's winner file `<date>-winner.md` (the transcript is the
substance source) and the Proven Package's locked `<date>-package.md` (the hook
echoes its MAIN title word for word). Take the latest package file, then read
ITS named winner file (the package file names its source winner next to the
episode-folder line); never infer the pair by date.

The third is the offer document, at the roots file's data-sources path (default
`squad/business.md`, beside `squad/offer-research.md`). The document's WHO sets who
the viewer is and gives the who-it-is-for line its words; its SENTENCE and
PROMISE give the mid CTA and the close ask theirs; and the magnet reality check
is graded against what the document says the founder actually delivers. Those
lines come from the document, never from the session. No document yet? Ask the
founder for the audience and the offer in one question, and say plainly in the
prep that no document exists.

**No winner file in the week folder.** Route to /the-winning-scrape when it is
installed in this repo. Otherwise the hand-built path: the founder names one
winning video in their niche, pull its transcript, write `<date>-winner.md`
into the roots file's week folder by hand, then proceed.

**No package file yet.** The founder's locked title IS the package. Ask for it,
then write a title-only `<date>-package.md` into the roots file's week folder,
marked title-only at the top and carrying the two join lines the whole chain
keys on: `episode: <episodes root>/epNN/` and `source winner:
<date>-winner.md`. Create that `epNN` folder by the-proven-package's counting
rule (the first run names `ep01`, every later run the next number after the
highest existing `epNN`), name the folder in the prep, and point the founder at
/the-proven-package for the thumbnail pairs before publish day, so title-only
stays the explicit exception, never a silent equal. A package file marked
title-only is ADOPTED, never competed with: the-proven-package's next run
overwrites that file in place, keeps its existing `episode:` and `source
winner:` lines, and creates no new `epNN`. One episode, one folder, one package
file.

Output: `00_PREP.md`, then `03_SCRIPT.md` (the six hook alt takes are its final
section, never a separate file), written into the episode folder the package
file's `episode:` line names. The file numbers are reserved slots from the full
system; `00_PREP.md`, `03_SCRIPT.md`, and `04_DECK.md` are the standard names.
Keep them; never renumber and never invent an 01 or 02.

<!-- Chris's Execution repo only (the source repo): there, /research writes
01_RESEARCH.md into the episode folder and stands in as the winner file, the
week files live at youtube/squad/week/ (the roots file's week field), and
02_OUTLINE.md is retired, which is why episode numbering runs 00, 03, 04.
Member repos have neither /research nor an 01 file; their input contract is
the week files above. -->

## The script cage (Chris, 2026-09-01: the lesson's eight beats, in the lesson's order)

The script runs on the same cage as the lesson page, under the same plain names, in
this order. The winners' devices below were mined from full beat-maps of six proven
videos (Metics 161.7x, zapiwala 22.1x, Kellan 16x, Hormozi 3.6M, Starter Story,
Kallaway 2.6M; evidence file `references/script-cage.md`, shipped with this skill).
They are how the beats get written, never sections of their own. The winner still
supplies the substance; the cage owns the order and the proportions.

| Beat | Job | Share |
|---|---|---|
| HOOK | One sentence that delivers the title's promise: the claim plus its number, echoing the locked package's MAIN title word for word. The finished result is on screen inside 15 seconds; hard cut | ~5s, one breath |
| CREDIBILITY | One line, one breath, from the credibility bank: why listen. Never a number the bank cannot receipt, never the same line as another episode | ~10s |
| OUTLINE | Three sentences painting the system doing it (what the viewer does, small; what the system reaches; what lands at the end). These ARE the roadmap, spoken, never a slide TOC. Then the free line when something ships free with this video ("The system is free. Link below." plus the one action), otherwise the single action line. No runway, no "in this video" | ~20s |
| PROBLEM | The ONE problem this video kills, in the viewer's own words, so they recognise themselves; the winner file's comments name it. Short, positive frame, never a mourning problem-agitate block; ends on a turn line into the solution | 5-10% |
| SOLUTION | The concept in the founder's own read: what the run is about to prove, and the short list it has to be true against by the end (the rubric; it becomes the progress bar and is re-graded at the close). Concept only, zero commands | 5-10% |
| WORKFLOW | The run, the main part: numbered beats, each ending in a VISIBLE result with its own mini-payoff every 60-90s. Inside it: a stakes-flag line before the key moment, ONE pattern-break (the system refuses or pushes back, planted then paid off), skip-ahead compression on every wait, a mid re-grade of the rubric, and the MID CTA immediately after the first marquee reveal, phrased as a resource. When the video demos a skill, the beats mirror that skill's run map one to one | 55-75% |
| FAQ | Three to five real questions, answered on camera in one to three sentences each: the questions the winner's audience asked in its comments (verbatim, with handles, from the winner file) or that real buyers asked the founder. No real questions, no FAQ; it is earned, never invented | 5-10% |
| CLOSE | The rubric re-graded and closed, a FRESH bookend proof (a new screenshot, the cost or time math), the payoff restated against the hook's promise, one soft ask maximum plus a curiosity gap into the next video. Abrupt; never signal the ending early | 5-10% |

CTA law: resource links tied to the exact on-screen step are unlimited and read as
service; channel asks are at most ONE, at the close (the two biggest winners have
zero or one): that is the one CTA.

**Pass 1, the prep (`00_PREP.md`). The prep IS the outline; the bar is
`references/standard-ep1-prep.md` (the Ep1 prep, 2026-08-27, shipped with this
skill).** Framing: the worked example shows the source episode's content on
purpose; your prep prints your business. Its `[SLOT]` markers flag the
source-founder-only elements (the receipts, the mid-CTA product, the tag
line, the mined comments, the dream paragraph, the magnet) as slots to fill
from the founder's own business, never content to imitate. It holds, at that level: the route in one line; every section with
its timing and its exact key lines drafted in the founder's spoken words; the opening as three beats (the hook with the number inside the first 15 seconds and
the on-screen proof named; the credibility line drafted from the credibility bank; the
three outline sentences sold as watchable moments, not process names); the problem with
the real quotes verbatim; the solution with the rubric stated; the workflow as numbered
beats, each ending with "See:" (what the viewer looks at), stakes-flag, pattern-
break, skip-ahead on every wait, mid re-grade, and the mid CTA at the first marquee
reveal; the FAQ with its real questions; the close with the dream, the bookend receipt, one ask; the magnet/CTA reality
(everything a CTA promises must exist on publish day; the description link a CTA
points to is the episode's Winrate tracked link, minted at publish, so the script
says "link below" and never bakes a raw URL); and the winner-vs-case call.
When the video demos one of our skills, the run's beats must mirror that skill's own
run map one to one, so the video is the skill's documentation.

Before showing the prep, verify it two ways: the section double-check against this cage, and an adversarial pass through four lenses (hook vs the winners' anatomies,
retention beat by beat, buyer trust in the audience's own distrust vocabulary,
publish-day logistics). Fix what dies, then show it.

The prep document itself is written in plain fourth-grade words with plain section
names, each demo step ending with what the viewer SEES. The prep's section names are the cage's eight names. The Ep1 references predate the cage
(2026-09-01) and read through this map: their HOOK is the hook; WHY ME is credibility;
ROADMAP is the outline; NOT JUST YOU is the problem, and its three comments move to the
FAQ; THE RUN opens with the solution (the checklist beat) and is otherwise the workflow;
THE END is the close.
Beat titles inside THE RUN are plain too ("The checklist goes up", never "Install
the rubric"). The jargon in the table above is for building, never for the document.
No changelogs, no his-idea-vs-mine tables, no defense of decisions: the prep states
what is true now, nothing about how it got there.

Prep mechanics that keep runs honest:

- **Set the target runtime from the winner's own runtime** plus the money
  chapter appended at the end, unless the founder names a number. The cage's percentage shares convert to minutes from it, so the timing table is real
  clock time, never bare percentages. 15-17 minutes is the source repo's
  typical result, never a floor: a quiet niche produces seven-minute winners
  and a seven-minute winner covered in full is a ten-minute video. The
  tiebreak: when full coverage of the winner plus the founder's margin lands
  short, the video is that length. Padding to a target is the over-caging
  failure.
- **The ending exists first.** The ending is drafted in the prep before any
  script prose exists; a prep without THE END written is not done.
- **No credibility bank? The founder's stated receipts ARE the bank.** List them,
  confirm each is sayable as written before the prep locks, and never reach past
  them. Then write them to the roots file's credibility-bank path in the six
  canonical sections the-proven-package uses, so one interview feeds every
  agent and no later skill asks again.
- **No voice file? Anchor one before the prep is written.**
  /the-winning-offer fills the roots file rows its own run answers and the
  credibility bank's VOICE NOTES section, so read both first and never re-ask
  for what they already hold. Both still empty, or the voice field reads "(none yet)": the default
  path is `squad/voice.md`, and this skill writes that path into the roots
  file the first time it fills it, so no later skill asks again. Three things
  count as the anchor, the same definition the-presentation runs on. A
  recording. A writing sample the founder already wrote (a client email, a
  post, a proposal). Or the founder typing four or five sentences about the
  last client problem they fixed, straight into `squad/voice.md`. A recording
  needs no install to become text: paste the transcript a phone voice memo
  already made, or dictate into this Claude Code session and let it type.
  Their real speech beats every language rule in this file. With no anchor of
  any kind, say so plainly in the prep: `references/standard-ep1-prep.md` is
  then STRUCTURE ONLY, and no sentence of its prose may be reused.
- **Real, and safe to show.** A demo screen carrying another party's data is
  either a demo account you own, a sanitised copy with names and account
  numbers changed, or shown with written permission. Say on screen which one
  it is. Sanitising is not faking; inventing a number is. Settle which one
  before any beat is drafted and write the choice into that beat's row.
- **Demoing the founder's own undocumented process?** Ask the founder for their
  real step list and mirror THAT, the same way a documented skill's run map gets
  mirrored. Never invent their workflow.
- **The pattern-break, generally:** the one real moment something pushes back,
  breaks, or surprises (a tool refuses, a number contradicts the plan, a step
  fails before it works). Ask the founder for a real one. If none exists, the beat
  is marked NOT YET A BEAT; a faked pattern-break is worse than none.
- **THE PROBLEM and THE FAQ, when the comments are thin:** read the winner file's
  comment section FIRST, before drafting either. A comment-poor flag on it, a
  COMMENTS UNREACHABLE flag, or fewer than three usable verbatim comments, and the
  FAQ is dropped (no real questions, no FAQ) while the problem is stated from the
  founder's own buyer conversations: no pull-quote cards, no `[COMMENT:]` marker
  anywhere in the script. A comment is quoted verbatim with its real handle or it
  does not appear; an invented comment is worse than no FAQ. The second-best source is the founder's own client
  emails and DMs, quoted the same way, attributed the same way, and labeled
  on screen as what they are.
- **The winner-vs-case call, defined:** one short paragraph stating whether the winner's own structure is poured in whole or only its ideas are extracted into the cage, and why. It exists so the choice is made once, on purpose.
- **ASK discipline:** an unresolved [ASK] on a load-bearing item (a hook number, a
  quote, a beat's content) means that section is headed NOT YET A BEAT, and the
  prep is not done. Open ASKs never sit formatted like finished work.
- **Numbers agree everywhere.** Every number appears once, or identically; a
  claim in one section never contradicts a stat in another. Illustrations about
  the audience's typical situation stay non-specific ("thousands of photos"),
  so they can never collide with the demo's real numbers.

## The method: our container, their substance

We do not invent a structure per video. **We have one package and we keep pouring winners into it.**

The winner earned its views on substance: the claims, the numbers, the objections it handled, the order it revealed things in. Our container is what makes it land better: the eight-beat cage, the one-layer recording, the hook patterns, the language rules.

So the job is: **inventory almost everything the winning video covers, then deliver it inside our package, plus what only the founder can add.** Same substance, better container, plus first-hand proof they do not have. That is how the remake beats the original instead of imitating it.

The failure is writing a summary of the winner. Covering 60% of its content in our structure produces a thinner video, not a better one.

## Feeding the prep: mine the winner first

These steps produce material that lands INSIDE `00_PREP.md`; there is no separate
outline file.

### 1. Outline THEIR video first

Before anything about ours. Write the winning video's own outline: section by section, what it says, in what order, with rough timings.

This is the step that gets skipped, and skipping it is why a remake ends up thinner. You cannot keep the structure that earned the views if you never wrote it down.

### 2. Inventory its substance

From that outline, list every claim, number, objection handled, and demo. That list is the coverage target.

Mark anything we deliberately drop, and why. Anything unmarked is expected to appear in ours.

### 3. Plan the packaging

Now decide how their video becomes ours. Keep as much of theirs as possible: their order, their beats, the questions they answer, the sequence they reveal in. Change only what has to change.

What has to change:
- their tool or example becomes ours where we have the real thing
- their claims get replaced by claims the founder can prove with a screen
- their beats each end with what the viewer sees (the `See:` line; on the screen
  layer, the `[DEMO]` line that heads each beat). On the deck layer those rows are
  the slide list the deck's beat map, `04_DECK.md`, starts from

What stays: the argument, the order, the objections, the density. The body keeps THEIR spine;
our money chapter is appended where they stopped (see the over-caging failure mode below).

### 4. Add what only the founder has

Real clients, real dollar amounts, screens of the thing working, the parts they got wrong. This is the margin over the winner and it cannot be researched.

### 5. Pick the one layer (Chris, 2026-09-01; replaces the three-layer screen base)

One recording per video, and it is ONE layer for the whole video: the deck full
screen, or the founder's live screen, or the founder's face. Ask the founder which
before the prep is written (unless they already said, or the roots file carries a
standing answer), write it once at the top of `00_PREP.md` as `Layer: deck`,
`Layer: screen`, or `Layer: face`, and never mix. No webcam bubble over a screen, no
cutting between a slide and a live screen.

- **screen**: the work itself is the picture. Every workflow beat opens with a
  `[DEMO: exact app, what is visible]` line, and those lines are the record-day
  screen list. No deck is built; /the-presentation does not run.
- **deck**: /the-presentation builds one slide per beat from the locked script, and
  anything real the video claims is a real capture embedded on a slide. The prep's
  beat rows are the slide list.
- **face**: the camera only. Nothing is staged; the words carry all of it.

The retention read behind the default (2026-08-19): the screen middle ran top-fifth
retention while the talking-head intro ran bottom-third. A video whose claim can be
shown picks the screen; the face is for a video that is about the founder.

### 6. Fold it into the prep and stop

Everything above lands in `00_PREP.md` at the bar the cage section describes.
**Then stop and bring it to the founder.** A prep is minutes to redirect; a
script is an afternoon.

## Pass 2: the full script

Only after the founder approves the prep. The bar is
`references/standard-ep1-script.md` (the Ep1 script, 2026-08-28, shipped with
this skill), read the same way the prep bar is read: its `[SLOT]` markers flag
the source founder's own content, and what transfers is the format, the
markers table, the demo density, and how fourth-grade words read out loud at
this length.

### The opening: hook, credibility, outline (~35 seconds)

Three beats, always, in this order, and the credibility line sits between the
promise and the roadmap (Chris, 2026-09-01):

1. **HOOK, one sentence that delivers the title's promise.** Four to five seconds. The
   claim plus its number, echoing the locked package's MAIN title word for word
   where it can. The finished result is on screen from the first frame.
2. **CREDIBILITY, one line.** Why listen, from the credibility bank, one breath.
3. **OUTLINE, three sentences that paint the system doing it.** What the viewer does
   (small), what the system reaches, what lands at the end. Then the third move,
   conditional: when something ships free with this video, the free line ("The
   system is free. Link below.") plus the one action ("open a second tab"), the
   free thing named HERE, always; otherwise the single action line, what to open
   and try, with the one resource named in the description. Every word understood
   on first hearing: no insider words ("graded"), no filler.

The number lands inside 15 seconds. No separate roadmap section after the
opening; the three sentences ARE the roadmap. No runway, no table of contents,
no "in this video".

**Vocabulary: the roots file's product word, never its banned synonyms.** In
the source repo that means "system", never "machine"; sweep any banned synonym
before handing over.

### Markers: the deck lives apart (LOCKED by Chris, 2026-08-28; one layer, 2026-09-01)

The script is what the founder SAYS. Slide choreography lives in the deck's beat map
(`04_DECK.md`), never woven into the script. Rules:

- A marker never sits inside a sentence. If a visual matters mid-paragraph,
  the beat map carries it; the script prose stays clean for reading aloud.
- The script's first line under its title is the layer line, verbatim from the
  prep: `Layer: deck`, `Layer: screen`, or `Layer: face`. One per script.
- On the deck layer the script carries ONE pace line, at the top of its first
  section, verbatim (the-presentation's cage owns it):
  `[DECK PACE: sentence-level; one arrow key per deck beat, a grouped slide holds through its sentences]`.
  No second pace line: nothing is screen-carried.
- Two marker definitions are the required FLOOR every script's Markers table
  carries: `[COMMENT: @handle]` (a real comment, captured per the-presentation
  cage's real-captures law; the FAQ's questions carry it) and
  `[DEMO: exact app, what is visible]` (the screen layer's beat opener, and on
  the deck layer the real capture a slide embeds). Episode-specific markers
  (`[CARD]`, `[BOARD]`, `[GITHUB]`, `[JUMP CUT]`, and their kind) are legal when
  the script's own Markers table defines them.
- Counts, per marker. `[DEMO:]` carries no cap: on the screen layer it heads
  every workflow beat, its own line, naming the screen exactly enough to stage
  before record, and those lines are the record-day screen list. `[COMMENT:]` is
  per comment.
- `[SCREEN ON:]` and `[FULL FACE]` are retired. A layer never switches mid-video.

### The script's laws (baked from Ep1, 2026-08-27)

1. **Beats are human moments.** A stop, a typed input, a decision = a beat. A
   stretch where the system runs alone is ONE beat, with lettered sub-headers
   (4a, 4b...) inside it for readability.
2. **Everything the viewer must copy is scripted verbatim,** whatever its form: a
   command, a chat answer, a text message, a checklist. When the video ships a
   repo or tool, every command matches its shipped README character for
   character. The demo format matches the demo:
   chat tools use the **I type / Claude asks / Claude outputs** triplet; GUI
   walkthroughs use `[DEMO: screen, action]` plus the spoken line; real-world
   artifacts (a message, an email) appear as blockquotes, word for word.
3. **System stretches teach the system.** While it runs, the narration names
   the devices the founder built inside (why each stop exists, what gets dropped,
   what gets admitted) plus one honesty line in the founder's own words, e.g.
   "I do not know what it will find either. If I did, this would be theater."
4. **Mechanism is said, receipt is shown.** A concept gets explained in words;
   evidence is the real file, the real line, the real number, on the layer the
   video runs on: a real capture on a slide, or the live screen itself. Never a
   made-up screen for evidence.
5. **No idioms.** If a word needed explaining once ("the bar"), it gets replaced
   with the plain word ("the test"). Fourth grade includes the metaphors.
6. **The bookend echo is self-aware.** The close calls back the hook's numbers as
   "the numbers you saw at the start," never as a verbatim repeat.
7. **The demo is real or it is dead.** When the video demos one of our skills,
   the beats mirror the skill's run map one to one, and the artifacts on screen
   are the actual run's outputs. When reality and script differ, fix the script
   or fix the skill; never fake the screen.
8. **CTA architecture.** Mid CTA: resource-framed, one breath, at the first
   marquee reveal. Close: ONE ask; when the magnet delivers by email, the ask is
   "leave your email, I will send it," matching the real automation.
9. **Real, and safe to show.** A demo screen carrying another party's data is
   either a demo account you own, a sanitised copy with names and account
   numbers changed, or shown with written permission. Say on screen which one
   it is. Sanitising is not faking; inventing a number is.

### Demos, inside the run

Every demo opens with the result, then shows how it was reached. Format:

```
**I type:** "..."
**Claude asks:** "..."
**Claude outputs:** "..."
```

Narration between each pair. Bullets for every step that moves the screen (scroll to X, open Y) so the demo has pacing breaks instead of reading as a wall.

### Language

Talking to one friend, not an audience. Fourth-grade reading level, 8 to 12 words a
sentence, nothing past 15. A setup line before each section, the *why* before each
prompt, first person.

The voice anchor is the roots file's voice file (default `squad/voice.md`).
When none exists, the prep's voice-anchor step made one: a recording, a writing
sample the founder already wrote, or four or five sentences they typed about
the last client problem they fixed. Anchor to that. Behind it sits the
credibility bank's VOICE NOTES section, written by /the-winning-offer. The winner file's
transcript comes last, a structure reference only, never a voice to imitate.
With no anchor of any kind, the shipped bar files are structure only and no
sentence of their prose may be reused.

No em dashes. Sweep against `references/humanizer.md` (shipped with this skill)
yourself. Say dollar amounts as spoken words, since the founder reads this aloud.

### Verify coverage before handing over

Walk the winner inventory from pass 1 and confirm each item is covered or consciously dropped. This is the check that makes it a better video rather than a shorter one.

### The six hook alt takes

Six alternate first lines, one or two sentences each, recorded as extra takes in
the same sitting (about two minutes of filming). Each anchors a different angle:
the number, the pain, the objection, the curiosity gap, the giveaway, the
transformation. They stand by for a hook swap if retention says the first one
missed.

### Format conventions

The script opens with a markers table (what each bracket tag means) and uses
inline performance cues: (pause), (slower), (tight, direct). The editor reads the
markers; the founder reads the cues. When only a summary of the winner exists (no
transcript), the prep says so plainly and the coverage claim shrinks to match;
pull the real transcript whenever one is reachable. The demo law's skill-mirror
rule has a twin: a founder demoing their OWN process mirrors their real step
list, gathered by asking, exactly as a documented skill's run map is mirrored.
The same resource CTA may appear at the mid and the close, but never in the same
words twice.

### The final check (mandatory, before the script reaches the founder)

Attack the finished script through four lenses, fix what dies, then hand over:

1. **The contrarian.** A smart founder with arms crossed: steelman every
   counterargument the script invites, catch every self-refuting claim (a dare
   the video's own runtime disproves), demand a hedge or a receipt for every
   equivalence claim. Named check: the "live" overclaim. One real session with
   the waits jumped is "one real session, waits jumped", never "live".
2. **The language cage.** Sentence-length scan (nothing past 15 words), banned
   words, dollar spelling, idioms, voice against the anchor.
3. **Claims and consistency.** Every number against the credibility bank (the
   roots file's credibility-bank field); every demo beat against the demoed
   skill's run map; every typed command against the shipped README (when the
   video ships one); every biographical claim against the credibility bank;
   and every demo screen against the safety law, real and safe to show (a demo
   account you own, a sanitised copy, or written permission, with the choice
   said on screen).
4. **Flow and timing.** Word counts at the roots file's wpm field (default
   110; measure the founder's real pace from their first recording onward)
   plus pauses against the stated timestamps; the mid CTA's position; dead
   stretches; whether the close actually fits its window.

## What makes this fail

**Writing the script before the outline is approved.** The expensive pass happens twice.

**Summarising the winner instead of covering it.** Thinner video, same length, no reason to watch ours.

**Over-caging the remake (2026-08-20).** The winner's structure earned the views. The cage owns
the title, thumbnail and hook; the winner owns the body's order; our money chapter is APPENDED
where they stopped, never woven through. Forcing the body into house frameworks is how a
10-minute video bloats to 20 and loses the original.

**Mixing layers.** A bubble over a screen, or a cut from a slide to a live screen and
back, is the three-layer format, retired 2026-09-01. One layer, start to finish.

## Hand over

The script is locked and nothing else here edits it. On the deck layer the deck is
/the-presentation's job: script to slides, never the reverse. It takes the prep's beat
rows as the slide list and writes `04_DECK.md` into the same episode folder; route to
it by name when it is installed in this repo, and when it is not, the beat map is
hand-written from the same rows with the pace line kept in the script. On the screen
layer the `[DEMO]` lines are the record-day screen list and no deck is built. On the
face layer nothing is staged. Then record, then the cut.

Close, word for word: "The script is locked. The deck, if you chose one, is the
Presentation's job; the recording is yours; the cut comes after. This skill stops here."
