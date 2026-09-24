# Decision log, capstone extract

This is the capstone-scope part of a longer working decision log. The full log also covers
work outside the capstone, which Part 1 of the Project Brief says is out of scope, so those
entries are not here.

Every entry was written on the day the decision was made, not reconstructed afterwards. A
decision that is later reversed is never deleted. It is marked superseded and the newer
entry links back to it, because a reversal with its reason attached is worth more to a
reader than a clean list of things that happened to be right.

The shape is fixed:

```
### YYYY-MM-DD  a short title
**Decision.** What was decided, in one sentence.
**Why.** The reason at the time, including the number or the observation that forced it.
**What changed.** Files, systems, or plans that moved.
**Evidence.** Where to look.
**Status.** live / superseded by <date> / abandoned
```

Newest first.

---

### 2026-09-24  the capstone is three things, and the rest of the repo is not one of them
**Decision.** Fix the capstone scope at the YouTube channel and Instagram account as the distribution half, the content engine behind them, and Nuuko. Everything else in my working repository is out, and the brief says so in writing rather than leaving it implied.
**Why.** My own instruction, and it was the right one. The repository carries several lanes of work that have nothing to do with this venture, and the brief had quietly reached into two of them. A capstone that spreads across every lane reads as several capstones, which is what #cp-curation punishes, and the handbook asks for one work product with a real-world audience.
**What changed.** The out-of-scope references came out of the brief. One custom LO, #voicefidelity, had been resting on a corpus that included out-of-scope writing, and it is rebuilt on 72,145 words of published pages instead. Part 2 now carries a scope statement naming what is in and what is out, which is a #cp-curation point as much as a scoping one.
**Thrown away.** The two-register argument inside #voicefidelity, which only held while the corpus mixed two kinds of writing. With one register the LO is narrower and it is true, which is the better trade.
**Status.** live.

### 2026-09-24  the handbook in the repo is the 2024-25 edition, and it had the brief wrong
**Decision.** Take the weight, the deadline and the scored LOs from the Forum assignment posting rather than from `Capstone Handbook 2026-2027.pdf`, and say so in the brief.
**Why.** The file is named 2026-2027 but every page footer inside it reads "Capstone Handbook 2024-2025, Last updated: August 13, 2024". It says the Project Brief is worth 10%, due Saturday of week 3, and scored on all four Capstone LOs. Forum says 25%, due Sunday 27 September at 1:00am with late submission closing Monday 28th at 1:00am, and scored on **#cp-outcomeanalysis and #cp-qualitydeliverables only**. I had already corrected my own header down to 10% on the handbook's authority, which was the wrong direction.
**What changed.** The brief header now carries the Forum figures and names the two scored LOs, and says Part 7 still lists all four because the cover sheet asks for the full set. Two of only two scored LOs are about measures and rubrics, which moves the weight of the document onto Part 2 and Part 7.
**Evidence.** Forum assignment page; page footers throughout the handbook PDF.
**Status.** live. The rest of the handbook's structure still matched the cover sheet, so it is trusted for everything except dates, weights and LO lists.

### 2026-09-24  the cover sheet is the assignment, and my ten sections were not its sections
**Decision.** Restructure the Project Brief into the order the official cover sheet template demands, and fill the template itself rather than submitting my own document.
**Why.** I had been writing the brief as ten sections of my own. The template asks for a specific table and then five named sections: a one-page summary, a short summary of completed work, general plans for #navigation, a specific plan for scheduling capstone time, and HC and LO plans. The scheduling section was missing from my version entirely, and the template is pointed about it: I am submitting in week 3, after two full weeks of work, so it wants what I have already done and what I would change. The honest answer is that the work happened and more than twelve hours of it, but nothing separated capstone hours from channel hours, so I cannot count them. That is a #navigation problem rather than a discipline one and it is now written down as one.
**What changed.** Eight parts in the template's order. New: the scheduling plan, backup plans with a trigger for each risk, a section on the people I work with and what happens to their feedback, and a scope statement naming what is out. The committee-faculty table, which was absent, now holds eight names with justifications.
**Evidence.** `Project Brief cover sheet - Maria Dumitrescu - FILLED.docx`, 16 pages.
**Status.** live.

### 2026-09-24  a third repository, public, so the private two stay private
**Decision.** Publish `github.com/riadumitrescu/capstone` with the capstone documents and a filtered decision log, and keep `riadms` and `nuuko-v1` private rather than adding my advisor as a collaborator.
**Why.** The cover sheet wants a GitHub row a reader can click. `riadms` holds credentials and `nuuko-v1` is a live app with other people's private journals in it, and neither should be opened to solve a paperwork problem.
**What changed.** 190 of 303 log entries dropped: writing and publishing work that the brief puts out of scope, and every entry naming a specific weakness in a live app. 113 kept. The log reads in first person now, because it was written in third person about me and that makes the author obvious. `LANES.md` states plainly that I use AI heavily, which model gets which job, and that the decisions are mine while much of the typing is not. That line is the point of the file.
**Evidence.** github.com/riadumitrescu/capstone, three commits.
**Status.** live.

### 2026-09-24  "put the text down": the line goes back under my chin, and the taller box above my head is superseded
**Decision.** On line cards the line sits under my chin at `--text-y 0.78 --allow-badge`, my face at the house size. The 22 September "taller box above my head" is superseded.
**Why.** My words, on the rebuilt batch: *"can you put the text down."* The box above my head was the pipeline's answer to "text bigger"; my answer to seeing it is the line down, which is where every card I have praised carries it. Under the chin a long line's last word runs into the runtime badge, which six of my seven biggest cards do.
**What changed.** All 17 line cards in `lab-0924` rebuilt; `PREFS.md`, `assets/thumb-templates.json`; `/thumb-lab` republished. The two note cards keep my 28 August recipe, line on top and the note low left.
**Evidence.** `/thumb-lab#lab-0924`.
**Status.** live. Supersedes the "taller box" part of the 2026-09-22 month audit; the "text bigger" ask stands and is met by the 0.19 cap and the shorter lines.

### 2026-09-24  three notes on the first rebuilt batch, and all three became rules
**Decision.** On line cards the room is sharp (`--bg-blur 2`, not 12), a line needs real air above it (the checker fails a block starting above 0.048 of the frame), and a mid-word grin frame is never chosen over a level one, even when sharper.
**Why.** My words on the first `lab-0924` pass: *"wayy too blurry the background and the text sometimes is cut by the thumbnail up and this pic is horrible."* The blur note is the second in three days. The 0.035 safe clamp had passed lines that my feed cut, so the clamp is a floor, not air. The frame was chosen because PREFS said it had replaced a flat one; I prefer the flat one.
**What changed.** `PREFS.md` (my words, dated), `assets/thumb-templates.json` (`top_min`, the line builder), `scripts/thumb-check.py` (`TOP`), all 21 cards rebuilt with my lower in the frame at 0.38 so the line clears my head, `/thumb-lab` republished.
**Evidence.** `/thumb-lab#lab-0924`, commit on origin/main.
**Status.** live.

### 2026-09-24  the third reel is held to 1 October rather than forced out
**Decision.** Stop the scheduled post of `mirror-06-edges` and leave it pending.
**Why.** It is cut out of the same clip as `mirror-05-marketing`, which went live at 16:24. `sameFootage` returns true, so the seven-day footage rest rule refuses it. Unlike the sitting guard, this one is about showing a viewer the same seconds twice, and there was no case for overriding it. Stopping the job before it fired was cheaper than letting it fail at post time.
**What changed.** Background poster stopped; item left pending, postable 1 October.
**Status.** live

### 2026-09-24  all three reels post today, the sitting guard overridden on my say-so
**Decision.** Post all three release-week reels today by hand, 45 minutes apart, overriding the same-sitting guard.
**Why.** I asked a second time, plainly: "can you post it today tho". A concern raised once and reaffirmed is my decision. Release week is the whole point of these and the guard costs two days of it. The override is narrow: `--post-next --id` is a supported route that still applies the footage rest rule and the already-said check, so only the sitting rule is set aside, and the 45 minute spacing is the gap my own queue configures between Instagram posts.
**What changed.** `mirror-04-covers` live at 15:37 Berlin (instagram.com/reel/DdrAjgojGH7); the other two follow at +45 and +90 minutes. Desk corrected, since it had already been published saying one a day.
**Supersedes.** The entry below, made earlier the same day.
**Status.** live

### 2026-09-24  one reel a day from a single sitting, even in release week
**Decision.** Let the same-sitting guard stand rather than override it, so one of the three new reels posts today and the others follow on the next days. I took the manual route for the other two instead.
**Why.** All three come from one sitting (one shirt, one room, one hour), and the queue refuses a second reel from a sitting Instagram has shown in the last twelve posts. That guard exists because I twice reported that my reels all looked the same, and there is no supported override for it at post time. Defeating a guard I asked for, silently, to hit a same-day count is the wrong trade.
**What changed.** New reels moved to the front of the reel lane; copies of all three plus captions in `~/Desktop/mirror-reels-today/`. I made the call within the hour.
**Status.** superseded by the 2026-09-24 entry above, on my instruction

### 2026-09-24  a short word is not a click, and the runner counts lanes by their own shell
**Decision.** The trim pass in the cutter treats any sound that overlaps a kept word as speech whatever its length, and its click limit is 0.10 s; the overnight runner counts lanes by an anchored match on the lane's own shell, never starts a take already rendering, gives the pre-render proof its own log, and re-reads its queue before every start.
**Why.** My question this morning: why are so many still broken, and why is it not reliable overnight yet. The first trim rule, written for a 40 ms lip click, stepped over "three" in "it's at least three" (a 0.15 s word said quietly), took 0.417 s off the edge, and the re-cut types-of-jealousy said "it's a list" at 0:02. Six joins on that take lost a third of a second the same way and 19 of its 38 trims were eating a word. deliver-gate held the file. Separately a watcher shell of mine matched the runner's lane count, so a two-lane run ran one lane for 14 minutes.
**What changed.** `scripts/perfect-joins.py` (word guard in the walk, BLIP 0.10), `scripts/overnight.sh` (busy, rendering, proof log, queue re-read), `scripts/cut-video.mjs` (the saved refinement is keyed by the cutter's code as well as the plan, because the first restart reused the bad-rule result and delivered the same fault twice), `tests/guards.sh` (guard 18), `assets/overnight-queue.txt`, `HANDOFF.md`.
**Thrown away.** The types-of-chemistry and alterous-attraction renders in flight at 10:23, cut with the bad rule, killed before delivery: about 25 minutes of work each, against an hour each of delivering a file the gate would hold.
**Evidence.** Re-run offline on the same jealousy plan: 19 trims instead of 38, "three" back at raw 35.30, my 1:46 join still at 0.15 s of air. Commit "perfect-joins: a short word is not a click" on origin/main. The held file: `WATCH-THESE/_FAILED - types-of-jealousy.mp4` at 10:00.
**Status.** live. The honest answer to my question is in this session's reply: the gates measured a narrower fault than I judge, fixes went into single takes instead of the cutter until 23 Sep, the picture was never checked, and the loop ran through my ear a day late.

### 2026-09-24  the re-cut batch gets its thumbnails built to the templates, two per video, before I pick
**Decision.** Every video in the re-cut batch has two candidate cards built to its template from a same-session still, gated by `thumb-check.py`, and put on `/thumb-lab` for me to pick from; nothing is set on YouTube until I pick.
**Why.** What I wanted: build the proposed improvements with full creative control, per kind of video. Nine of the eleven had no finished card or one that failed the gate, and two had nothing built at all. Full creative control still runs inside my settled rules: Times, lowercase, my face centred, the light room, the flag on ace videos, the note on long-forms. The lines were written in the four shapes the audit ranked and the label and the mood were not used.
**What changed.** `thumbnails/<slug>/lab-0924/` for eleven videos; `public/thumb-lab/lab-0924/`; a first section on `src/pages/thumb-lab.astro`; the checker's edge and size bands calibrated against Vision's box (the ascender and shadow run 0.015 past the clamp; a five-word full-width line tops out at 0.147) and cover print excluded from the block count.
**Thrown away.** The wrap card for the ace books: the display word ran behind my head and died at 210px. Replaced by the line template with Loveless propped and the flag on.
**Not acted on.** The picks, and the YouTube swaps that follow them. Two outfit calls are mine on am i anxious.
**Evidence.** `/thumb-lab#lab-0924`, the checker JSON under the session scratchpad, commit on origin/main.
**Status.** live, waiting on my picks.

### 2026-09-23  thumbnails get one template per kind of video and a gate that measures the finished card
**Decision.** Every thumbnail is built to one of seven named templates whose bands live in `assets/thumb-templates.json`, and `scripts/thumb-check.py --template <name>` measures the finished pixels and refuses a card before it is shown to my. The line is written in one of four shapes, all four drafted before one is chosen, and a line that repeats the title's words is struck.
**Why.** My ask, in my note at the time: audit how the thumbnails are done and make a system so "the size of the text on the thumbnail is big enough, it's centred enough, and we always have templates for each kind of thumbnail". The 90-day window to 11 September (39 long videos, 5,000+ impressions) says type height is the strongest lever I control (above-median 3.98% against 3.06%), every extra text block costs (r = -0.31), readable small print medians a point lower, and face size and grade move nothing. The Monday audit had already found 9 of 15 scheduled cards with the last word under the runtime badge, and nothing mechanical was catching it. 78 winning cards from ten other niches confirm the direction (tall stacked box, one accent word, the number as the object, a mid-expression face) and rule out copying their three-block caps-sans banners, because my own numbers say one block.
**What changed.** New `scripts/thumb-check.py` and `assets/thumb-templates.json`; `build-thumbnail` SKILL.md runs the gate in step 5 and its checklist; `/thumbnails` opens on the audit (the 39 measured, the 78 from other niches, the four line shapes ranked, the template table, the re-cut batch card by card); desk item on the youtube branch. Nothing in PREFS.md moved, because that file only records what I have said.
**Not acted on yet.** The eleven re-cut cards: nine fail the gate and two are unbuilt. Rebuilding needs the drive with the source stills plugged in, and my read of the proposed lines first.
**Honest limit.** The gate flagged 7 of my top 12 as well as 6 of my bottom 12. It is a floor for what I read as ugly, not a predictor of a click. The claim in the line still decides the rate.
**Evidence.** `src/pages/thumbnails.astro` section `audit-0923`, `public/thumbnails-guide/0923-*.jpg`, `youtube-mcp/ctr-snapshot.json`.
**Status.** live.

### 2026-09-23  the alterous re-cut: the QPR clip is gone, measured by the gate that found it
**Decision.** alterous-attraction's re-cut is right on the two faults it was re-cut for, and it goes round once more for four smaller ones rather than being called done.
**Why.** The GPU gate reports **0 faults across 169 joins** on the new plan. That is the same gate, on the same take, that found the QPR clip on the old cut when the CPU gate passed it, so a clean verdict from it means something a clean CPU verdict would not have. The word now starts at raw 708.3, exactly on the Q's onset, where the old blade cut at 707.79 and took the Q with the dead air. And the new plan carries four `mid-phrase-restore` spans, so the caption fix written earlier today returns **28 words** to the captions on the next render: "a lot of our friendships and romances have", "know what to do or you do", "had to i literally", "i want you to take from this video and". Those are the places I currently speaks with nothing on screen.
**What is left, and why it is worth another pass.** Two abandoned attempts (1.10 s at 2:14, 0.61 s at 1:52, which is the "fully" spot) and two gaps inside a word (1.00 s at 4:11, 0.69 s at 8:15). All four are the kind I hear. 4 cut ranges and 11 retimes are written, zero overlaps. The per-join cache was populated by this run, so the next pass re-proves only the joins that move.
**Evidence.** `~/Movies/riadms-work/proof/alt-NEW/alterous-attraction.proof.listen-cut.md`.
**Status.** live, one pass to go.

### 2026-09-23  I heard a pause I was not looking at the camera through, and that is a new class
**Decision.** `scripts/look-away.py` is the first check on the picture. A pause I hold the camera through is a beat and stays; the same pause with my eyes down is a hole.
**Why.** My report on types-of-jealousy: "1:46 there's a moment there of break and pause in which I'm not even looking at the camera." The pause is 0.56 s, under the 0.60 s the ear check flags at, and every audio check passed it. Its length was never what was wrong with it. Apple Vision and `vision/facekit.py` were already on the Mac, so the check is frames sampled out of each pause against the take's own baseline: my open eye measures 0.287, it reads 0.131 at 106.20, my eyes are down 0.20 s, and it flags 1:46.20 while clearing the two pauses either side. It runs on the raw take, so it answers before a render exists, at about a minute a take.
**And the fault underneath was the old one.** "read" is recorded running to 314.48 when my voice stops at 313.32, inflated by 1.12 s, and "into" starts 0.31 s before its record. Both retimed.
**Not done.** The threshold is now known to be too high and the right correction is to let the eyes decide for short pauses rather than simply lowering it. Not wired in.
**Status.** live.

### 2026-09-23  a fault class no gate can see: the refinement puts dropped speech back and the captions do not follow
**Decision.** Recorded and not fixed tonight. The proof reports it as SPEECH WITHOUT CAPTIONS and never cuts it automatically; the cutter-side fix is on the handoff and waits for a quiet machine.
**Why.** Found because a range `--fix` wrote on alterous overlapped words the cutter had dropped, and measuring the raw there gave speech at -21 dB peak, not silence. Tracing it: the plan input had the false start "had to i literally" removed and flagged dropped; the plan output had one keep across it. The refinement restored the audio and merged the pieces, the drop flags were never revisited, and the film says the words with no captions and then says "had to" again. The listening gate cannot see it because there is no join left to listen at. On the films I have: 5 such stretches on alterous, up to 2.03 s, and 3 on types-of-chemistry.
**What changed.** `dead-air.py` measures the audio inside every candidate gap instead of assuming it, which is what found the class; the two ranges that would have cut my speech were removed before any render; every range written today was rebuilt under the measured rule with zero overlaps against any word, dropped included.
**Evidence.** `HANDOFF.md` top item, with the raw seconds; `dead-air.py` on `_NOT-CHECKED - alterous-attraction.mp4`.
**Status.** live. The caption side is fixed in `cut-video.mjs` the same evening (restored words return to the captions); the measurement is the next alterous re-cut, which should report zero where today's film reports five.

### 2026-09-23  the first video through the fast loop, end to end
**Decision.** the-deadline-nobody-set is delivered as `_NOT-CHECKED` and ready for my CapCut pass. It is the first take to go from a fault I heard to a clean file with the sound proved before the render rather than after it.
**Why.** My report at 0:27, "two probably's and a small weird pause between them". The proof of the old plan reproduced it (1.38 s inside "you'll"); one retime and one cut were written; the proof of the re-cut's plan showed it gone, three seconds after the plan existed and an hour before the render finished. Then the render: drift-check in sync, cut-integrity 0 faults on 28 pieces, the listening gate 27 joins 0 faults, dead-air on the delivered film 0 silences of 0.6 s or more, and two frames at the spot show the caption "say i figured" with my mid-word. What I would hear and what I would see, both checked.
**What it cost, and why.** The gate took 61 minutes on the CPU for an 82 second video because four render lanes were competing; the same gate on the GPU does 189 joins in 28 under that load. And the file sat as `_FAILED` for an hour after its gate passed, because `deliver-gate.mjs` run by hand without `RIADMS_DRIVE` looked on the unmounted drive and exited 0 in silence. It says `NOTHING TO GATE` and exits 2 now.
**Evidence.** `~/Movies/riadms-work/WATCH-THESE/_NOT-CHECKED - the-deadline-nobody-set.mp4`; `review/the-deadline-nobody-set.listen-cut.md`; the desk.
**Status.** live. My CapCut pass is the next step, and the 16 September `the deadline.mov` on my Desktop is of the old cut.

### 2026-09-23  the listening gate on the GPU: measured, and the difference was the GPU being right
**Decision.** Not acted on. The gate stays on the CPU by default, because the standing instruction for the experiment was "any difference means it stays on the CPU and you write down what differed", and there was a difference. The call to move it is mine, with a recommendation to move it.
**Why.** Two takes, 359 joins, same files the CPU gate had already judged. types-of-chemistry: CPU 189 joins 0 faults, GPU 189 joins 0 faults, identical. alterous-attraction: CPU 170 joins 0 faults, GPU 170 joins **1 fault**, and the one fault is 5:22.03, "platonic relationship pr", missing "qpr": the real clipped word found by ear this morning, which the CPU gate had passed. So the engines agreed on 358 joins and on the one they differed the GPU caught a fault the CPU missed. No case of the reverse was seen. Wall clock under a saturated CPU: GPU 28 min for 189 joins; the CPU gate on the same day took 53 min for 34 joins. The gate is 30 per cent of every render.
**What changed.** Nothing in the default. `RIADMS_WHISPER=mlx` still puts it on the GPU per run; the proof loop's `--listen` was run that way on how-i-met-my-boyfriend, where the GPU reported 12 joins against the CPU film gate's 6 on the same keeps. Five are shared. Of the new ones, the timing-only `edge-check.py` independently confirms 16:53 ("like", 0.20 s of it thrown away at the blade), and for every new fault the missing word is present in both caption lists near the join, so they are audio verdicts and not a difference in the word lists. The evidence now points one way: the CPU gate misses clipped words the GPU finds.
**Evidence.** The two reports in this session's scratchpad, `mlx-gate/*.listen-cut.md`; `FAST-EDIT.md`.
**Status.** decided and not acted on, waiting for my.

### 2026-09-23  a pixel match is not a repeat unless the sentences agree
**Decision.** The on-screen-words check (`textprint`) only calls two cards the same when the picture hash matches AND the first lines of their captions share words. Reversed nowhere: two identical sentences still fail.
**Why.** `--verify-text` was red on three pairs, and every one was two different sentences: a Jacks reel against a Garber quote card, a love-journal prompt against the novella announcement, the love-triangle reel against the red-flag one. The hash reads the lower half of one frame at 32 by 16 and cannot tell sentences apart when the layout is the same shape. The prescribed fix for a red audit, `dedupe --apply`, would have killed three good cards. The caption is the sentence I typed, so it is the tie-breaker.
**What changed.** `scripts/ig-queue.mjs`: `sharesWords()` next to `lineOf`, applied at fill time and in the audit; the audit now prints layout matches separately and passes.
**Evidence.** `node --env-file=.env scripts/ig-queue.mjs --verify-text` today: 3 layout matches, 0 repeats.
**Status.** live.

### 2026-09-23  "waiting four hours for a video is not at all okay": check the sound in seconds, render once
**Decision.** The cut is proved on audio alone, as many times as it takes, and the picture is rendered once at the end. `scripts/proof-cut.py` splices the raw take's samples in the order the plan says (under a second), lays the word list into cut time, and runs the ear checks on it. `FAST-EDIT.md` is the loop.
**Why.** Measured on just-tell-me-what-to-do, a 115 second video that took three hours: cut refinement 111.6 minutes, the listening gate 53.2, everything I see on screen together under a minute. 93 per cent of making a video is transcribing the same audio over and over, and nearly everything I have ever heard wrong (the QPR, "fully", 0:29, the two probablys) is in the sound of the cut. The fix for the pause I heard on the-deadline-nobody-set was verified in three seconds from the re-cut's plan, before any render existed.
**What changed.** Three tools, each corrected by a labelled fault the same day. `dead-air.py` went through three rewrites: a fixed -45 dB floor found nothing under my music bed, so the floor is each film's median minus 12; gaps between words missed the 0:27 hole because it sat inside "you'll", so gaps are measured from the last sound of one word to the first sound of the next; and 0:29 turned out not to be dead air at all but "the... the... the" collapsed into one word by the transcriber, which is a stutter the tightener cannot touch, so a swallowed stutter is its own class and the report names the loudest attempt to retime to. `joinlisten.py` now caches every listen per join, on disk, with the model and its own code hash in the key, so a one-word retime re-proves only the joins it moved instead of the whole take. `listen-cut.py` takes an exclusive lock and times out after 15 minutes, because three of three gates deadlocked under memory pressure and held two finished videos for 21 hours with no log line.
**Evidence.** Guards 12 to 15, 22 passed. The threshold table in `dead-air.py`: the take I complained about returns exactly my fault at 0.60s and the take delivered clean returns nothing.
**Not done, and why.** Skipping joins that sit in silence: measured at 1 to 2 per cent of joins, because the cutter hugs the words, so not built. The gate on the GPU: the verdict comparison is running; nothing moves without it. Batched transcription in the chooser: not started. And the honest cost of the cache: joinlisten.py is in the cut fingerprint, so every take re-cuts once at full price before the cache pays.
**Status.** live.

### 2026-09-23  the vertical vlog Short is the fifth format, and it is 100 seconds not 40
**Decision.** Build a vertical vlog Short pipeline as a `--short` mode on the existing vlog draft rather than a new format of its own, and target 100 seconds, which is over twice the length the reference pool medians.
**Why.** I asked for fast vertical vlogs with text, sound effects and a viral sound, and nothing here made one: the `vlog` skill is landscape long-form, `vertical-short` is talking-head, `edit-video-dense` is talking-head. The length was the only real decision. The 15 vertical vlog Shorts measured for this median 38.9s, and building to that would have rebuilt the lane my own numbers retired on 2026-09-15: 233 of my videos at 60s or under produced 37 net subscribers between them, 0.10 per 1k. Ranked by punch (views over subscribers, so channel size is not doing the work) the pool says the same thing: 61-120s medians 0.35 against 0.20 for 30s and under, and the two best vlog Shorts in it are 94.9s and 108.4s. 100 seconds sits inside the 75-150s mini band CLAUDE.md rule 17 already asks for, so the format agrees with my strategy instead of arguing with it.
**What changed.** `vlog-draft.mjs --short` (1080x1920, 1.8s hold, static holds capped at 3s not 7s, no teaser, a viral sound picked from the 99-track bank and started at its `hookAt`, and a trim that drops whole clips because a Short is not a shorter day). `vlog-render.mjs` gained `fit: "cover"` so landscape footage fills a vertical frame instead of being letterboxed into a blurred strip, and `music.from` so a track can start at its hook. New skill `vlog-short`. Research in `creator-research/VLOG-SHORTS.md` and `anatomy-shorts-vlog.md`.
**Evidence.** `creator-research/VLOG-SHORTS.md`; `creator-research/anatomy-shorts-vlog.md` (15 Shorts, Apple Vision, 2 frames a second); `creator-research/shorts-vlog/TOP.md` (348 Shorts from 15 channels). The cover-vs-contain frame comparison was rendered and looked at. **The end-to-end render on my real footage is UNVERIFIED: the Toshiba holds the DJI scenes and it is unplugged.**
**Status.** live, unproven end to end.

### 2026-09-23  the Shorts detector had been answering no to everything
**Decision.** Fix the Shorts check with a consent cookie, and make a sweep that confirms nothing throw rather than write an empty pool over a good one.
**Why.** `shorts-refs.mjs` asks YouTube whether a video is a Short with a HEAD request, 200 for yes and 303 for no. From an unconsented IP YouTube 302s every request to its consent page before it looks at the video, so the answer was no for real Shorts and long-form alike. A vlog sweep found 231 candidates and confirmed 0, with no error anywhere. Checked against my own published Shorts, which are known-good: they returned 302 as well. This is the always-green failure LEARNINGS.md keeps recording, and left alone the next `--refresh` on the essay pool would have replaced 242 confirmed Shorts with an empty list.
**What changed.** `shorts-refs.mjs` sends a consent cookie and counts checks that answer neither 200 nor 303; an empty sweep now throws. Two additions beside it rather than on top of it: `--set <name>` namespaces a sweep so the vlog question could not overwrite the essay pool, and `--queries <file>` supplies a different query set. New `scripts/shorts-sweep.mjs` asks the same question with yt-dlp and no API quota at all, after 18 queries exhausted the day's 10,000 units, which is the same quota my uploads spend at 1,600 each.
**Evidence.** `scripts/shorts-refs.mjs`, `scripts/shorts-sweep.mjs`, `creator-research/VLOG-SHORTS.md` final section.
**Status.** live.

### 2026-09-23  "0:29 for the types of chemisty has a little pause there that s actuallly kinda bad"
**Decision.** Three faults that shipped on 22 and 23 September are one root cause, not three bugs, and the fix (`scripts/tighten-words.py`) does not go on any other take until one re-cut proves it. types-of-chemistry is the measurement and it is queued first.
**Why.** The transcriber stretches a word's recorded span across the silence beside it, and the cutter trusts that span when it decides where to put the blade. The span starts early and the blade eats the front of a sound: alterous 5:22 says "a queer platonic relationship PR is" because "qpr" is timed from 707.70 while the Q is voiced at 708.32. The span starts early and the caption outlives the sound: alterous 1:52 burns "fully" over "without. And here's what amatonormativity is." The span runs long and the piece opens in silence: types-of-chemistry 0:29 has 1.3 seconds of nothing because "the" is timed from 54.54 and I say it at 55.92. Every word-level check passed all three, because the word is in the list and only a sound inside it is wrong. Counted before the fix existed: 26 pieces in types-of-chemistry open more than 0.4s before my first word, 20 in alterous, 26 in a-little-life, worst 1.79s. **I found 0:29 myself after I had dismissed all seven dead-air notes on that take as my pause style.**
**What changed.** `tighten-words.py` shrinks each span to the sound measured inside it, never grows one, leaves anything under 0.15s of silence alone, and keeps 0.04s of margin so a soft consonant is never clipped. 145 of 2155 spans on types-of-chemistry. Word count and order never change, so the decisions files' word indices stay valid. The queue was rebuilt shortest-raw-first with types-of-chemistry at the front.
**Evidence.** Commit `1a1bf6c3`; `assets/overnight-queue.txt`; the first comparison I ran showed 26 gaps becoming 17 and that number is meaningless, because it measured new word times against the old cut plan. Only a re-cut can answer it.
**Second take, independent, and it needed no audio.** how-i-met-my-boyfriend failed its listening gate on 6 joins. Every one of the five I could place lands INSIDE a word, and the word it lands inside is near the top of its own distribution in that same take: "like" 1.08s against a median of 0.20s over 289 instances, longer than 99% of them; "are" 0.84s against 0.17s over 12, longer than all of them; "in" 0.70s against 0.20s over 105, 96%; "after" 1.30s against 0.82s over 10, 90%. The two where the blade landed in a normally-timed word ("that" at the 53rd percentile, "me" at the 31st) are the two mild faults, a leftover "and" and a dropped "i". So the blade lands inside an inflated span, the inflation is the transcriber stretching the word across the silence beside it, and **a word whose duration sits above its own p90 in its own take is a cheap predictor of a bad join, computable before anything renders and with no transcription at all.**
**Status.** live, unproven. If the re-cut comes back without the hole at 0:29 the fix goes on every take; if not, `types-of-chemistry.words.json` is reverted from `.bak-tighten` and the fix was wrong.

### 2026-09-23  a hand retime is a word time, and mine was wrong twice over
**Decision.** No span may end at or before it starts, it is checked across every take by `scripts/span-check.py`, and a broken one is never repaired by arithmetic.
**Why.** My own hand retime of "the" on types-of-chemistry moved the start from 54.54 to 55.90 and left the end at 55.58, so the word carried a negative duration into the cut planner and nothing complained. 55.90 is also not where I say it: the audio puts "the" at 55.46 to 55.65 and "first" at 55.92 to 56.21, so the retime had walked the word forward onto the next one's sound, which is the same fault class the tightener exists to remove. `tighten-words` was blind to it too, because `int(55.90/0.01)` is past `int(55.58/0.01)`, the audio slice came out empty and the loop skipped it silently. A sweep of all 45 takes found exactly one more, `facetime-how-i-use-ai` "AI" at 856.10 to 855.58, the same signature.
**What changed.** `span-check.py` over every take, guard case 12, and a refusal printed by `tighten-words` before it does anything else. "the" measured and put back at 55.42 to 55.69. Zero-length spans turned out to be the transcriber's, one or two a take, mid-phrase inside continuous speech, so they are reported and not called errors. Nothing anywhere starts before the word before it, which matters because decisions files address words by index. **The facetime-how-i-use-ai span is NOT fixed**, because its audio is not offline and guessing a word time is the fault itself.
**Evidence.** `.venv-transcribe/bin/python scripts/span-check.py`; `tests/guards.sh` 19 passed 0 failed.
**Status.** live.

### 2026-09-23  the overnight system delivered one video against a target of ten, and the cap was the reason
**Decision.** The render queue is ordered shortest raw first and the slot cap came off two. Recorded as a failure, not a tuning change.
**Why.** I asked for at least ten videos fully edited in eight hours with something always running. The runner capped at two heavy stages, on a 1h27m measurement taken from a SHORT take, and the three renders already in flight when it started were the three longest in the set (43.4, 40.9 and 23.0 minutes of raw). The work scales with the number of joins, so a 43-minute take is not 2.5x the cost of a short one, it is many times it. Not one of the twelve queued takes ever started all night while more than half the machine sat idle. One video was delivered. Stopping the competing lane drivers more than doubled the CPU reaching real work, 102% to 223%.
**What changed.** `assets/overnight-queue.txt` rebuilt shortest first with the reason written into the file; `scripts/overnight.sh --slots 5`. Two runner faults were found only by running it: `busy()` counted 4 renders as 12, and DRIVE resolved to the unmounted Toshiba so every take would have logged "drive not mounted, nothing to do".
**Also.** The runner reads its queue once at startup, so the 09:59 reorder never reached the instance that started at 09:35 and types-of-chemistry had to be launched by hand. And `FP_CUT` does not include `words.json`, so the forced re-cut came back "delivered but stale: cards" and would have re-delivered the identical cut under a fresh timestamp with a green log. Both are in `HANDOFF.md`, the second blocked on rule 8.
**Evidence.** `~/Movies/riadms-work/logs/overnight.log`; commit `1a1bf6c3`; `HANDOFF.md` items 5.
**Status.** live.

### 2026-09-23  two reels in the Berlin day, and the daily YouTube lane is minis and not Shorts
**Decision.** Two extra Instagram reels a day at **09:00 and 15:00 Berlin**, as a
separate lane called `holdcard` with its own lines, and a daily YouTube job that
cuts **3 to 4 minis of 75 to 150 seconds** out of an already published essay
rather than 3 to 4 sub-minute Shorts. Both were asked for in the same morning.
**Why.** The account posts nothing into the European daytime: every one of its ten
slots lands between 18:30 and 07:45 Berlin. On the YouTube side my own numbers
decide the size, not taste: 219 videos of 45 seconds or under have produced 32 net
subscribers between them (0.09 per 1k), 10 videos of 61 to 90 seconds produced
2,061 (5.57 per 1k), and the break is a cliff at one minute rather than a slope.
Building 3-4 sub-minute Shorts a day would be building the thing that made 32
subscribers out of 219 videos, so the volume I asked for is built at the length
that converts. I can overrule it and the job takes a flag.
**What changed.** `ig-queue.mjs` slots can now name their own timezone, so a
Berlin slot stays a Berlin hour through the two weeks a year the offset is eight
and not nine. `instagram/queue.json` has the two slots; `lines-24-hold.md` is the
first batch, 11 of 14 queued and 3 refused as already posted. `face-card.mjs`
grew `--min-source` and now loops a clip up to the card length instead of
shipping a card shorter than the one asked for and saying nothing. `scripts/minis-daily.sh`
and its plist are the YouTube lane; `EMPLOYEES.md` and `instagram/lanes/README.md`
carry both.
**Evidence.** `youtube-mcp/shorts-snapshot.json` for the bands,
`creator-research/tt-theelliebarker.json` for what the reference account is doing
now, `node --env-file=.env scripts/ig-queue.mjs --status` for the slots.
**Status.** live

### 2026-09-23  the 29-second card is blocked on footage, not on code
**Decision.** The Berlin lane ships at **6 seconds**, the measured format, and
goes to 15 only when I films longer clips. Not decided by preference: it was
attempted and the batch came back with two cards in it.
**Why.** @theelliebarker's last week medians 29 seconds against ria's 6, so the
straight copy is a long card. Of my 277 face clips, 21 run 15 seconds or more,
and once the ones filmed wide, filmed too far back or with no face are dropped,
**two usable sittings are left**. Looping a 6-second clip three times to fake the
length is visible and cheap. Length is also not the reference account's engine:
split its week at the median and the short half medians 33,700 views against
22,000 for the long half.
**What changed.** Nothing shipped at 15 seconds. `--seconds 15 --min-source 15` is
the single switch, and the ask is four or five sittings of 30 to 60 seconds, close
up, which is one afternoon.
**Evidence.** `node scripts/face-card.mjs --lines instagram/face-cards/lines-24-hold.md --n 14 --seconds 15 --min-source 15 --dry-run`
**Status.** live

### 2026-09-23  the `done-` prefix is not evidence, and Batch D has been sitting since August
**Decision.** `176` comes off the filming plan and onto the render queue with
`done-184` and `done-186`; the scripts index and script 176 both carry a warning
that the filename prefix is not the source of truth.
**Why.** I read `/filming` and said I was fairly sure *five more types of
attraction* was already filmed. I was right. It was shot 24 August, 23:03 raw,
cut to 10:10, spec and decisions written 25 August. The earlier check read the
`done-` prefix in `NEW-SCRIPTS-TO-FILM/`, which is applied by hand and was never
applied to 176, so a page correcting `LONGFORMS-TO-FILM.md` for being stale made
the same class of error one step further along. The proper check against
`TRACKER.json` and the drive also found that **all three** Batch D takes are
filmed, cut and unrendered, a month after they stopped at the render for the
`only one lane may render` rule and were never picked back up.
**What changed.** `FILMING-PLAN.md` correction section rewritten and a Day 0
added; Day 1 loses 176 and gains `22`; the slot table gives 176 the next
available date rather than 11 November and holds `done-184` six weeks clear of
it, per 184's own header. `_READ-ME-FIRST.md` and `176-*.md` carry the prefix
warning. The other nine scripts in the plan were re-checked and have no footage.
**Evidence.** `TRACKER.md` rows at 75% delivered; `assets/decisions/` and
`out/specs/` files dated 25 August; `five-more-types-of-attraction.MP4`, 5.8 GB,
on the LaCie; no match in the YouTube uploads at any privacy setting.
**Status.** live. Two questions are open and only I can answer them: the
missing seventh dimension on 176, and "gender envy" or "gender and" on 184.

### 2026-09-23  the plan becomes a calendar, and the proverb test gets its script
**Decision.** `FILMING-PLAN.md` now opens on three dated filming days and a
proposed slot for every video against the live schedule; the one proverb-titled
test is written as script 224, *you don't want them, you want to be wanted*; a
Berlin b-roll list is script 225; twelve correction face cards are drafted and
not queued.
**Why.** I asked for the strategy step by step and for scripts. The schedule
snapshot in the repo was nineteen days old, so the calendar was laid against
`list-scheduled.mjs` live: long-form slots are full to 18 November, which is why
two swaps are proposed rather than assumed. 224 was chosen because
`LONGFORMS-TO-FILM.md` had called it "the best unwritten one" since August and
it fits the sahar shape without borrowing my note at the time: the image is ria's own
August face card. The Meana "being desired" claim was kept out because it could
only be traced to interviews, not a citation, and I say sources out loud as
fact. The face cards are built from strangers' real comments under
`face-cards-07-26` because five of my six top Instagram posts are that shape.
**What changed.** `NEW-SCRIPTS-TO-FILM/224-*.md`, `225-*.md`, `_READ-ME-FIRST.md`
rows, `script-pdfs/224-*.pdf`, `text-shorts/batches/corrections-2026-09/lines-draft.md`,
`FILMING-PLAN.md` (new top section), `src/data/threads.ts`.
**Evidence.** `/filming` on the studio host. `my-voice.mjs --diff` on 224 in the
essay register, contractions brought up from 5,990 per million after the first
draft measured thirteen times under my.
**Status.** live. The two slot swaps and the five `(fight)` cards are decisions
made and not acted on, waiting on my.

### 2026-09-23  the filming plan is measured against other channels, not against our own notes
**Decision.** The next filming batches are set from a live measurement of eleven
adjacent channels plus my own last 90 days, published as `FILMING-PLAN.md` and
served at `/filming` on the studio deploy. Landscape stays the universal feeling
with asexuality as the credential; portrait becomes asexuality and the
correction shape. One proverb-titled essay is authorised as a single test, not
as a change of policy.
**Why.** I asked what the wider love and personal development essay lane is
making right now. Three things came back that our own documents had wrong.
First, `LONGFORMS-TO-FILM.md` still ranks four videos to film next and three of
them are already filmed (`done-186`, `done-184`, `done-177`), and `done-90`
makes script 35 a duplicate. Second, `@funkyfreshsahar` has 9,610 subscribers,
almost exactly mine, and my last fourteen long-forms median 10,571 views, or
1.10x my subscriber count, against 0.40x for the next best channel measured;
my titles are proverbs, which contradicts the search-shaped title rule in our
own strategy doc. That contradiction is resolved by traffic mix rather than by
picking a side: this channel is 66% subscriber and 1.4% search, so a
search-shaped title was never the engine. Third, my reach and my conversion
have come apart: the 2am test took 147,070 views and returned 132 subscribers
while *7 types of attraction* took fewer and returned 895.
**What changed.** `FILMING-PLAN.md` added. `src/pages/filming.astro` added,
gated by `IS_STUDIO` and the desk password. `.vercelignore` allowlists the new
top-level markdown file, which is the trap that ships an empty page.
`src/data/threads.ts` carries the youtube branch entry and `asOf` 2026-09-23.
**Evidence.** `/filming` on the studio host. `FILMING-PLAN.md` names every
source and states the one limitation: the YouTube search quota ran out partway
through, so the competitor set is eleven channels chosen from my own research
corpus rather than an exhaustive sweep.
**Status.** live

### 2026-09-22  the last two promised pages were written, and one number was left out rather than guessed
**Decision.** Write `/guide/how-to-know-if-someone-likes-you` and `/guide/gender-envy`, which closes every promise the unpublished long-forms make to riadms.com, and leave two figures off the economist page because they need full texts nobody here has.
**Why.** My standing rule, 2026-09-22: *"write the article always"*. Reading the cut of every long-form that is not already public found 25 places where I sends a viewer to the site, and three had nothing behind them. A promise with no page is not a line to cut from the video, it is a page to write, and it has to exist before that video gets a date.
**What each page adds that the video did not.** The likes-you page splits the 28 per cent back into 36 per cent for men and 18 for women, which every write-up averages away, and adds Montoya, Kershaw and Prosser's meta-analysis of 286 studies finding that the signs really are correlates of attraction. That makes my argument sharper rather than softer: the list is true about a population and unreadable at one table. It also adds the 2022 replication where third-party observers judging speed daters landed at chance. The gender envy page adds the benign-against-malicious envy distinction, which reframes the sting I describes as the kind of envy that points at becoming, and says out loud that gender envy is community vocabulary with no paper defining it while the nearest measured thing is gender euphoria.
**What was refused.** The first DOI written for the Samara paper resolved to a paper about rheumatic disease. Every DOI on both pages is now checked against crossref rather than typed from memory, and the two economist numbers stay out until somebody reads the full texts.
**Evidence.** commits `2bfda152` and the gender envy commit, `PROMISED-PAGES.md`, both pages loaded on the deployed host. ai-tells 2/100 and 1/100, both HUMAN_ONLY.
**Status.** live

### 2026-09-22  a drift check that judged the worst point was failing good videos
**Decision.** `drift-check.py` now judges sound-to-picture drift on the median of its measurements plus a second point in the same direction, instead of on the worst single point.
**Why.** It held `types-of-chemistry` with "DRIFT: -3583ms at worst" while seven of its eight measurements read +4ms, including two taken after the bad one. Sound and picture cannot come back into sync on their own, so one outlier was never drift. Checked against the cut plan, the picture at 4:23 comes from raw 532.653s and the tool's own picture matcher found 532.650, right to 3 milliseconds. The file was correct and the check was wrong. A window that straddles a join matches the raw before the cut on one side and after it on the other, which is what produced the number.
**What was thrown away.** A first fix assumed the sound occurred twice in the raw and added an ambiguity test. Its numbers disagreed with the tool's own matcher, 0.858 against -0.161 at the same index, so it was deleted rather than tuned. A measurement that cannot be trusted is not a foundation for a gate.
**What changed.** `scripts/drift-check.py`, and `types-of-chemistry` came off hold.
**Evidence.** commit `a16e0e2f`. The guard that refuses a genuinely half-second-shifted file still passes, so the gate did not go soft.
**Status.** live

### 2026-09-22  resolve the file, never trust the path something wrote down
**Decision.** Where a recorded path no longer resolves, look the file up by its name inside the library it names, and refuse rather than guess when the lookup is ambiguous.
**Why.** Two separate faults in one evening, both of which turn a correct decision into nothing on screen. Three of the eight hand-picked b-roll clips on `types-of-chemistry` were written as `scenes/` and had since been re-filed under `with-people/`, so they came back unreadable and the video was minutes from shipping with five clips instead of eight. Separately, `relocate-beats.mjs` looked for a take's cut in lanes a to d, and `how-i-met-my-boyfriend` was rendered in lane E, so the file it needed was on disk and reported missing.
**Why this is the same fault twice.** A path is a fact about one day. The name of a clip and the identity of a cut are not. Every resolver in this repo already works that way for the two drives, and these two places had not caught up.
**What changed.** `scripts/place-overlays.mjs` follows a re-filed clip and says so in the log. `scripts/relocate-beats.mjs` reads the lanes off the disk, and where more than one holds a cut of the same take they have to agree word for word, because a beat is a time in one cut and the wrong one plays the wrong half-second of my talking.
**Evidence.** commit `6670da52`, guard case 9, 16 passed and 0 failed.
**Status.** live

### 2026-09-22  the advisor, the track, and a main folder that exists rather than a recommendation
**Decision.** Record Prof Gloria Tam as capstone advisor and the track as independent and self-designed rather than a declared dual major, rebalance the College LOs to four Computational Sciences and two Arts and Humanities, state the one-capstone framing as agreed rather than proposed, and build the Drive main folder.
**Why.** I said three things this session that the documents had wrong. The advisor was not named anywhere. The plan of 11 September asserted a dual major in Design Across the Humanities and Data Science and Statistics, which I have never had, and the whole two-LOs-per-major arithmetic was built on it. And Prof Tam has already agreed to the one-venture framing, which the brief was still arguing as a proposal and hedging around.
**What changed.** `PROJECT-BRIEF.md`: advisor and track named in the header, section 1 states the framing as agreed, section 7 opens with the track question and carries six College LOs (`#cs130-decisiondesign`, `#IL181003-FoundationalDeepLearning`, `#cs110-ComputationalCritique`, `#cs114-ParameterEstimation`, `#ah113-designforwhom`, `#ah113-designlogics`) with three more named as reserve, and section 10 now describes a folder that exists. `CAPSTONE-PLAN.md` and `README.md` follow. The PDF is 12 pages now.
**The LO rule, which is genuinely ambiguous and is question two for Prof Tam.** The handbook says two LOs from each major. An independent track is not a pair of declared majors, so it reads either as two from the college the track sits in or two from each college it draws on. The six satisfy both readings, which is why the reserve exists: a different answer costs an edit rather than a rebuild.
**What was built.** `Capstone 2026-2027 - ria dumitrescu` in Google Drive, folder id 1fQhyDn6kJDIhd5omx9aUDyShoMoACJvg, holding `00 START HERE` as a Google Doc plus the brief as PDF and as editable source, the plan, the decision log, the research synthesis, the strategy and the handbook, numbered so they sort in reading order. The files went in through the Drive for desktop mount rather than through an upload.
**The fault caught by reading rather than by a check.** The first `00 START HERE` was written with em dashes in it, which is a standing ban. It was trashed and rewritten, and the replacement was read back from Drive rather than assumed.
**Evidence.** The folder, read back through the Drive API after writing. `capstone/Project-Brief-CP193-ria-dumitrescu.pdf`, 12 pages.
**Status.** live

### 2026-09-22  the engine is capstone work, and the git history is what says so
**Decision.** Rebuild the Project Brief for the Week 3 submission (due Sunday 27 September, 1:00am, weight 25%), and rewrite section 2 so the content engine is counted as capstone-year work rather than as prior work.
**Why.** I said the video-editing software, the automated Instagram and YouTube publishing and the employee agents were built in the first weeks of September. The 12 September draft had described all of it as prior work, which gave away a large part of the year's output before anyone assessed it. The history agrees with my and not with the draft: the repository's first commit is 12 July 2026, and 1,414 of its 3,324 commits were made on or after 1 September, 1,102 of them in the first fifteen days. `EMPLOYEES.md` is dated 7 September and `employees-doctor.mjs` 8 September, both inside capstone week 1.
**What changed.** `capstone/PROJECT-BRIEF.md` rebuilt: a dated per-subsystem ledger in section 2, a new section 3.2 of written-in-advance rubrics for the three deliverables, every HC and LO rewritten into the handbook's "I will apply #X by doing Y" shape, and the reach figure corrected from 840,000 a quarter to the measured 1,715,696 views and 1,306,099 minutes watched in the 90 days to 21 September. `capstone/README.md` written, which closes the main-folder item the 12 September draft left open. `scripts/capstone-pdf.mjs` added so the PDF can be re-rendered after I edits.
**The weighting that changed the document.** The assignment page attaches only `#cp-outcomeanalysis` and `#cp-qualitydeliverables`, not the four the handbook implies. `#cp-outcomeanalysis` is defined as identifying and using appropriate measures and rubrics, so the rubrics section was written rather than the navigation section being extended.
**Counts corrected against the machine rather than remembered.** 81 skills not 79, 186 memory files not 100, 30 scheduled job definitions not 14, 3,324 commits not 2,597.
**What is still blocked and on my.** The Project Brief Cover Sheet is behind a Minerva login and returns 401 from here, so the table rows cannot be filled in. I copies it, pastes sections 1 to 9, and exports the one PDF.
**What was left in rather than fixed.** `ai-tells.mjs` flags two words: `utilize`, which is Minerva's own wording for the LO and would be a misquote if changed, and `learnings`, which is the filename `LEARNINGS.md`.
**Evidence.** `capstone/Project-Brief-CP193-ria-dumitrescu.pdf`, 11 pages, rendered and read page by page. `capstone/PROJECT-BRIEF.md`, `capstone/README.md`.
**Status.** live

### 2026-09-22  a local mirror counts as a volume, so a render survives the drive leaving
**Decision.** `onEitherDrive` in `scripts/lib/paths.mjs` now resolves against `~/Movies/riadms-work/offline` as well as the two drives, last in the list, and the raws for the takes in flight were copied there before I unplugged the LaCie.
**Why.** I asked how long until I could take the drive, and the honest answer was hours. The cut stage works off audio already cached on the laptop, so nothing had the drive open at that moment, but the render step reads the raw video back, and those two raws are 4.1 GB and 9.6 GB and existed only on the drive. Unplugging would have failed both renders and everything after them.
**What changed.** The resolver, the 13.7 GB copy (about two and a half minutes at 100 MB/s, taken in the window where the lanes were not touching the drive), and the lane C and D watchers, which were stopped because their takes' raws are not mirrored and they would have started later and failed. Verified with the drive physically out: all three mirrored raws resolve to the laptop copy, and the b-roll, music and image libraries were already local.
**The limit, stated rather than hidden.** With the drive out, `edit-queue.sh` still copies the finished video, the overlays and the keep directory back to `$LF/<take>/` on the drive, and those copies now fail. There is no `set -e`, so the run continues and the video still lands in `WATCH-THESE`, which is the folder I opens. The cost is the reusable cache: a later re-render of those two takes would redo the whole 90-minute cut. The fix is one line in the delivery step and it waits, because zsh reads a running script incrementally and editing it would corrupt the run.
**Evidence.** Commit 88404cc3, and the resolver tested against a file present only in the mirror.
**Status.** live

### 2026-09-22  the already-public gate now reads privacy, and refuses to answer blind
**Decision.** `edit-preflight.mjs` fails a render only when the matched video is **public**, and warns when it is private, scheduled or unlisted. `published-check.mjs` exits 2 rather than printing a clean sheet when it can see no takes at all, and `assets/published-overrides.json` is new: the cases a person settled by hand, with the reason and the date.
**Why.** Two faults, found while the re-edit lanes were already running. The gate carried my August rule, *"the ones that are scheduled are fine, you don't have to redo them"*, which I reversed today; left as it was it would have refused nine takes in lane A that I have asked for. And the gate was blind: it reads the takes off the Toshiba, the Toshiba is not plugged in, so it found zero takes and reported that no video anywhere was public. Against the LaCie the same pull named **six public videos inside lanes B and C** (in-love-or-just-comfortable, aromantic-vs-asexual, how-to-turn-your-relationship-rom-com, five-types-of-intimacy, seven-types-of-love-sternberg, why-bridgerton-is-addictive), four of them only weak matches, which warn and never block, so four would have rendered.
**What changed.** The two scripts, the new overrides file, guard case 7 in `tests/guards.sh` which makes both halves fail on purpose (13 passed, 0 failed), and `RE-EDIT-PLAN.md`, where the six are struck and the four dates they were filling are marked empty. Two re-edit sanctions written while their videos were still scheduled are retired rather than deleted, because both videos have since gone public.
**Five takes were freed rather than locked**, each by reading the take's own first sentence against the video it was accused of being. `just-tell-me-what-to-do` is the clearest: its strong match is 34 seconds long, the Short cut out of the take, while the mini itself is private with a slot on 12 October.
**Supersedes** the 2026-08-12 rule that anything on YouTube at all is locked. That entry stands; the reason it was right then was that nothing was being re-cut on purpose.
**Evidence.** Commits b5758486 and ba0c64ea, `assets/published-overrides.json`, `RE-EDIT-PLAN.md`.
**Status.** live

### 2026-09-22  re-edit everything that is not public, in three lanes
**Decision.** Re-cut every video on the new editor except the ones already public on YouTube, in three lanes running at once: A the 19 that hold a publish date, in slot order; B the 28 delivered but never scheduled, longest first; C the 10 filmed and never edited that already carry a spec. What I wanted: *"just re-edit every video that we have ... if you need some lanes that would work at the same time you can do that too"*, then, as a constraint on it, *"dont do the already public ones only the ones that arent public"*.
**Why.** Everything cut before 16 September carries at least one of the faults found between 19 and 22 September: half a frame lost at every join, so the lips ran 3.5 s ahead by the end; cuts through the middle of a phrase; my own lists and parallels cut as if they were retakes; clipped words at the edges; a checker that rebuilt 70 per cent of joins one frame off the film; spec b-roll that stayed on screen after being removed. The public exclusion is arithmetic rather than caution: YouTube cannot swap the file of a live video, so a re-edit means a new upload that starts at zero views and loses its comments.
**What changed.** `RE-EDIT-PLAN.md` holds the plan, the three lanes and the 41 filled slots through February 2027. `guilty-for-not-wanting-sex` was removed from lane C and from the schedule table after my constraint. The lanes run out of separate work directories so they do not share a lock, all delivering into one `WATCH-THESE`. A memory, `never-re-edit-a-public-video`, was written so a later session cannot undo it.
**What this does NOT cover.** The 37 never-edited takes that have no spec and no decisions file, including six unnamed DJI files. They need a writing pass before a cut can start, and none of it is scheduled yet.
**Evidence.** `RE-EDIT-PLAN.md`, commits f70409a8 and 472904fe, the lane logs in `~/Movies/riadms-work/logs/`.
**Status.** live

### 2026-09-21  the join fixer went onto the GPU once I said yes, and back off three hours later
**Decision.** The fixer (perfect-joins) ran on the GPU from 19:50 and was put back on the CPU at 21:30. The gate never moved.
**Why.** I said yes to the split proposed below (fixer on the GPU, gate on the CPU). On its first real run it cut a little life in 20 minutes instead of 2 hours, and the CPU gate then held it for 5 joins, three of them exactly where the GPU had chosen a different edge from the CPU in the afternoon comparison (1:06, 1:27, 2:09). The CPU-fixed cut of the same take had none left once the checker was corrected. A held video costs a full extra round, so a fixer that is six times faster and wrong more often is slower end to end. The proposal assumed the gate catching misses made them free; it does not.
**What changed.** scripts/lib/whisper_engine.py defaults to the CPU for both roles; RIADMS_WHISPER=mlx-fix keeps the GPU fixer for experiments. a little life and alterous re-cut overnight on the CPU.
**Evidence.** Commits 31f1b8e3 (on), d887b856 (off); ~/Movies/riadms-work/logs/q-a-little-life-tonight.log.
**Status.** live. Supersedes the proposal in "the join listeners can run on the GPU, and are not switched yet" below.

### 2026-09-21  the join listeners can run on the GPU, and are not switched yet
**Decision.** Built an opt-in GPU transcriber (`RIADMS_WHISPER=mlx`) for perfect-joins and listen-cut, and left the default on the CPU. Proposed split, awaiting my go-ahead: the fixer on the GPU, the final gate on the CPU.
**Why.** The two listening passes are most of the time a video takes (about 2 hours and 70 minutes on a little life) and the GPU sat idle. Same model, medium.en: the 13 hand-judged joins run in 67 s on the GPU against 425 s on the CPU, but score 12 of 13 against 13 of 13 (greedy decoding heard "he takes" as clean where I said "it takes"). On a whole take, a little life's fixer took 22 minutes against about 2 hours, and 427 of 436 cut edges came out identical. large-v3-turbo was tried and scored 9 of 13: it hears what I meant, which is the one thing this check cannot do. Thrown away.
**What changed.** `scripts/lib/whisper_engine.py`, `scripts/lib/mlx_whisper_worker.py`, `.venv-mlx-whisper` (own venv, so it cannot move a package under the editor's). Nothing renders differently until it is switched on.
**Evidence.** Commit 9cd3f925.
**Status.** live, default off

### 2026-09-21  nuuko: the channel's framework moves inside the app, and the funnel it depends on was broken
**Decision.** Build the half of `build-order.md` that makes Nuuko an app rather than a
site, and connect it to the channel: the seven kinds run inside the app, `nuuko.app/kinds`
is the link a video carries, arrivals are counted per video, and the filing moment,
the feather's noticing line, Wrapped per person, the keepsake and share-in are built.
On branch `capstone/app-2026-09-21` in nuuko-v1, 16 commits, not merged; a preview deploy only (nuuko.app untouched).
**Why.** What I wanted: audit it against the business and the channel and make it "an actual
app". The audit found the gap that matters most for the business: the channel is about
the seven kinds, and the app could only fill a person's seven-kinds profile by sending
them out to riadms.com and back through a URL (out to Chrome, inside the Android app).
And no video could be credited with a single install, which `how-people-arrive.md`
names as the one number nobody has.
**What changed.**
- **Found and fixed: the diagnostic handoff never worked for a new person.** The
  onboarding redirect on `people.html` ran first and sent anyone with no pages to
  `welcome.html`, so a stranger who finished riadms.com/which-one-is-this and tapped
  "open their page in nuuko" lost the result. Seen in a clean browser: welcome.html,
  nothing saved. Only people who had already written ever got through. The existing
  test could not see it because it ran after pages existed.
- **Found and fixed: every .js and .css was served `immutable` for a year** under
  filenames with no hash, so returning web visitors could keep old code indefinitely.
- **Found and fixed: the weekly backup modal opened three seconds into the write page**,
  over the first sentence, and over the new filing moment.
- The fourteen questions, lifted verbatim from the site with the site's scoring
  (checked by hand: all-first-answers gives romantic 23, alterous 10, sexual 8), run
  on a person's page. Every run is kept on the device so the page can say what moved.
- `?src=yt-<video>` is kept as first touch and rides on every later milestone. The tag
  is the same for everyone who taps a link, so it names a video, never a person.
  Migration 008 adds the column; **written, not applied**.
- Fonts moved off Google onto the app's own files: right offline and in the Android
  app, and no third party is told who opened a private journal.
**Evidence.** `nuuko-v1/about-nuuko/PLAN-2026-09-21.md` (the plan written before, and
what was built after); ten browser suites, `npm run smoke:all`, all passing;
screenshots read for every new surface. Two of the features (Wrapped, the keepsake)
were built in parallel by agents on their own branches and merged after review.
**Not acted on.** The letter and the friend layer (`the-law.md`); the paid tier (DSO);
a brooding screen at onboarding, which should be designed with my rather than written
overnight; `summary.js` still carries a Gemini client with no key, dead surface; the
one-line change on riadms.com that would tag the site's own handoff, left because it is
my site's main branch.
**Thrown away.** A handoff test that could not fail for the one visitor that matters.
Two test waits that measured the harness instead of the app: chrome-headless-shell stops
producing frames after a cross-document view transition, which looked like a frozen
page until the same flow ran clean in Google Chrome.
**Status.** built on a branch, waiting on my phone and my word to merge.

### 2026-09-20  the drift gate had been firing into a log nobody read
**Decision.** `edit-queue.sh` reads the cut's exit status inside the branch that
runs it, not after the `if ... fi`.
**Why.** `pipestatus` describes the last pipeline and closing an `if` counts, so
`cut_rc=${pipestatus[1]}` read after `fi` returned 0 no matter what node did. The
guard, written 2026-09-06 after a drifted video shipped, has therefore never
worked. On alterous the cutter printed "AUDIO AND PICTURE HAVE DRIFTED APART ...
Do not ship this", the pop stage printed "NOT trusting this", and the run
delivered the file anyway. I watched it and called it weird for two days while
the diagnosis sat at line 57 of the log.
**What changed.** `scripts/edit-queue.sh`; verified in isolation both ways before
applying.
**The reusable part.** A guard is not installed until it has been seen to fail a
real run - the test here is three lines and ten seconds. And when something ships
broken, read the log of the run that produced it before building anything new: two
days went into checks for a fault an existing check was already reporting by name.
**Status.** live

### 2026-09-19  the picture was running ahead of my voice on every video
**Decision.** The frame-selection start boundary gets the same 1e-4 tolerance the
end already had, and the delivered-file check now compares the picture stream
against the sound stream instead of against the container.
**Why.** I called the alterous re-cut "weird" for two days while every audio
measurement said it was clean. The picture was 3.5 s shorter than the sound, and
because `setpts` renumbers the surviving frames, a short picture does not stutter
- it plays early and the gap grows with every cut. Measured: 1.97 s ahead at the
halfway point against 2.00 predicted, 3.37 s at 94 per cent against 3.34, 3.53 s
at the end. My lips were out of sync the whole video and worsening, and my
sign-off had no picture on it at all. The cause is one missing epsilon: the span
end carried a 0.1 ms margin and the start carried none, so about half the time
`between` dropped the span's first frame. Half a frame per cut, 86 frames over
172, and 88 over 176 in the previous build.
**What changed.** `scripts/cut-video.mjs` select expression; `scripts/edit-queue.sh`
gains a picture-versus-sound length guard with a 0.25 s tolerance.
**Evidence.** Verified on my own footage before applying: five real spans, 353
frames expected, 351 selected as it was, 353 with the margin. The drift itself was
measured by matching delivered frames against the raw take over a scanned range.
**What I got wrong, recorded because it is the reusable part.** I first checked
the burned captions and reported no drift. Captions are burned onto the picture
after the cut, so they move with it and can never reveal this - a reference that
travels with the thing being measured is not a reference. I then scored the
picture against four candidate offsets and took the best; the true answer was not
among them, so it returned the closest wrong one and looked like a result.
**Status.** live

### 2026-09-19  "still not good it s werid"
**Decision.** Two new rules go into the editor - a cut may not run through the
middle of one continuous phrase, and a kept piece may not begin or end on debris -
and `cut-integrity.py` becomes the gate for both, replacing a check that could not
see either fault.
**Why.** I listened to the 11:53 alterous re-cut and said it was still weird. The
night's work had measurably fixed what I thought I meant: the cut at 0:57 moved
from -36.3 dB to -53.9 dB and truncated word-decays went from 136 to 7. I was
right and the instruments were wrong. What I was actually hearing at 0:56-0:57
was one two-second piece made of three separate faults: the dying tail of a word
whose beginning had been cut away, 1.43 seconds of silence at -80 dB, and my
"and" chopped off mid-word - and beyond it, a cut that had removed "a lot of our
friendships and romances have", the subject and verb of my sentence. I had
described all three in my own words days earlier ("weird sounds happening before
I say the word", "little cuts of the words from before", "a weird pause at 00:57")
and each had been read as a separate small problem.
**The root cause, and it is a measurement failure, not an editing one.**
`listen-cut` judges a join by transcribing it twice - once as cut, once with both
edges loosened by 0.25 s - and calls a fault only when the two disagree. A removal
of one to two seconds is far outside that budget, so the loosened take says the
same broken thing, the two agree, and the fault cancels. **The gate is
structurally blind to any fault larger than the amount it loosens by.** It
reported three faults on a file that had four mid-phrase cuts in it, and it took
344 minutes to do it - 77 per cent of the whole pipeline. `cut-integrity.py`
finds all four in about ten seconds, because it reads energy and never
transcribes anything.
**What changed.** `scripts/perfect-joins.py` gains passes 6 (mid-phrase restore)
and 7 (strand); `scripts/cut-integrity.py` is new; `scripts/join-tests.py` now
runs with no drive attached, off a 16 kHz wav, which is what let all of this be
verified on a plane. On alterous the rules restore my words at four places and
remove 14.2 s of debris and dead air, 176 pieces to 172, 8:50 to 8:42.
**Evidence.** `scripts/cut-integrity.py` on the 11:53 build reports 32 faults and
names the words each cut took. The 13 hand-judged joins in
`tests/joins/fixtures.json` still pass 13 of 13.
`~/Movies/riadms-work/WATCH-THESE/LISTEN-alterous-before-after.mp3` is the six
worst spots, each as it was and as it is now, for me to judge by ear.
**Status.** live

### 2026-09-19  "always you have to have like a viral sound on the video"
**Decision.** Every Instagram post must be able to say where its sound came from,
checked at fill time for every kind rather than for face cards only. Provenance is
recorded by whoever puts the sound on, and a post that cannot answer is refused.
**Why.** Two lane cards posted back to back carrying only the room they were filmed
in. Nothing failed: the renderer levels the clip's own audio to -14 LUFS, so a pen
on paper went out at exactly the volume a song would have. The loudness guard added
on 16 September for this same complaint could not catch it, because a room and a
track measure the same. A measurement cannot answer a provenance question.
**What changed.** New `scripts/lib/hastrack.mjs`; `ig-queue.mjs` asks it of every
kind; `lane-card.mjs` runs the sound pass as a step in making a batch rather than as
an option on one; `reel.mjs` stamps renders that keep a sound baked into their
source. `instagram/viral-sounds.md` was 12.5 days stale and was researched and
refreshed, which is what `--viral-only` refusing was telling us. The nine pending
love-journal cards were scored and re-pointed at the sounded files.
**Evidence.** `LEARNINGS.md`, section of the same date; `instagram/lanes/README.md`,
19 September; every pending lane card verified by measured loudness and by stamp,
not by the pass reporting success.
**Status.** live

### 2026-09-19  a path-keyed record is not a record about a file
**Decision.** A sound stamp carries the size and modification time of the bytes it
was made about, and the legacy path-keyed face-card log is believed only when the
file is older than its entry. `face-card-sound.mjs` consults one authority.
**Why.** Found by the fix above failing the same way, within the hour. A batch was
re-rendered into the same folder after two lines were reworded; the sound pass
reported "7 already had a track" and skipped every card, because the log held
entries for three files that no longer existed. Three cards carrying my room were
vouched for by a record about their predecessors, and the run was green.
**What changed.** `scripts/lib/hastrack.mjs` binds identity; `face-card-sound.mjs`
drops `log.used[path] || trackOf(file)` for `trackOf(file)` alone, because two
sources of truth where one is known to be weaker is the same as having the weaker.
**Evidence.** The batch measured card by card after the change: three scored, four
already carrying a sound I chose, all seven at posting level.
**Status.** live

### 2026-09-19  the Instagram storage guard counts `ig/`, not the whole bucket
**Decision.** `assertStorageHeadroom` measures the Instagram prefix and prints the
whole-bucket total when it is large, instead of refusing on it.
**Why.** It refused every fill at "68255 MB of 10000". It summed the whole R2
bucket, which was right when the bucket was only Instagram's and a 1 GB Vercel Hobby
quota was the thing being protected. The bucket now also holds the rain ambience
renders: 67.1 GB across 25 objects against Instagram's 1.1 GB across 138. It refused
on somebody else's files and named three levers that all act on the 1.1 GB. A guard
that cannot be satisfied by anything it tells you to do is a guard nobody can act on.
**What changed.** `scripts/ig-queue.mjs`. Found while queueing the new lane, not
looked for.
**Evidence.** The queue run prints `ig/ is 1151 MB, but the bucket holds 68.3 GB in
total` and proceeds.
**Status.** live. **Open for my:** rain sharing the Instagram bucket is still
unresolved and is a decision about buckets, not about this guard.

### 2026-09-18  the footage was never the constraint, it was where I looked
**Decision.** Rebuild the word reel on my Escapism clip at 6 words, ingest the whole 15 September sitting into `reels-content/dance/`, and make the overlay band a per-sitting spec option. Supersedes the footage-constraint finding in the entry below, which was wrong.
**Why.** I said: *"but I gave you like more dancing videos of me, like maybe 10 of them."* I was right. The scan behind the earlier claim only covered `reels-content/`, the **ingested** library. The sitting I airdropped on 15 September had never been ingested, so it sat in `~/Downloads/video/` under hex names where no catalogue could see it. **Six of those clips are 11 to 19 seconds**: Escapism 18.9, bloodstream stripped 15.1, UNDER THE STARS 15.1, Love The Way You Lie 15.1, Mercy 15.0, Training Season 11.1. The desk had already recorded that this sitting existed and had never recorded how long the clips were, which is why a note about framing got read as a note about length.
**What changed.** All six copied into `reels-content/dance/`, identified by Shazam and named through `reel-scan.mjs --rename`, so they are findable from now on. The reel is re-rendered on Escapism at **6 words, 2.68 seconds each**, against 5 words on a third use of Great Expectation. `word-reel.mjs` takes an optional `band`, defaulting to the old values so the black top sitting is untouched. The queued item and its blob were replaced rather than left pointing at the old render.
**The band was set by looking, and the measurement would have got it wrong.** The blue satin sitting frames my head at about 21 per cent down rather than 45, so the block moved to y 64-294. A row-variance scan of the source claimed my hands crossed the text in 12 per cent of frames; pulling the worst frame showed my hands nowhere near it, because the detector was reading the static ceiling line and the smoke alarm as content. Rule 1 again: the automatic check was confidently wrong and the frame was right.
**What this leaves.** Five more long clips unused, which is four or five more of these without filming anything. The standing ask for a new take is withdrawn.
**Evidence.** `reels-content/dance/_scan/catalog.json`, `text-shorts/WORD-FOR-IT.md`, `instagram/words/should-know.json`.
**Status.** live

### 2026-09-18  measure my CapCut filter instead of guessing it, and find half of it cannot be automated
**Decision.** Rebuild the colour half of my CapCut filter inside the pipeline, measured off a matched pair of files rather than translated from the sliders, and keep the makeup half in CapCut because ffmpeg cannot do it. What I wanted: *"find a wy for ht efilter to work perfectly, every long orm efore it s edited should have the filter."*
**Why.** I wanted pre-filtered raw files so Shorts cut out of a long-form would already carry my look. Two things came out of testing it. First, a second filtered copy of every raw is a large write to a 84 MB/s spinning disk, a lossy re-encode before editing, and a look that cannot be changed later without rebuilding the library. Second, and the one that actually decides it: **the makeup is most of what I see, and it is face-tracked AR.** Blush, lipstick, eyelashes and face highlights are painted onto a per-frame facial mesh. Nothing in ffmpeg does that, so a pre-filtered raw would carry the 5% and miss the 95%.
**How it was measured, because the sliders are not ffmpeg's scales.** `the-lie-of-the-spark` exists as both the pipeline render (108.859s) and my CapCut export (108.867s), same timeline, so frames line up. Six frame pairs at 8/20/35/50/70/90s, sampled over four **background** boxes only — curtain, wall, window, desk — because my face carries the makeup and would have poisoned the colour measurement. 3.79M pixels. My filter is R +8.15, G +2.37, B +0.27, luma +3.60, saturation x1.157: a warm-highlight lift that rolls off before the whites.
**The result is exact.** Per-channel curves plus `eq=saturation=1.015` reproduce it to under 1% on every channel (R 0.25/255, G 0.43/255, B 2.04/255, saturation 0.51/255). Saturation was swept at 1.000/1.015/1.025/1.035 and 1.015 minimised total error; higher overshoots AND drags blue down, because CapCut's saturation is not ffmpeg's operation.
**One setting was rendered and rejected by looking.** `bilateral=sigmaS=10:sigmaR=0.14` for Smooth 54 erases my eyebrows and turns my hair to plastic. The light setting, sigmaS=6:sigmaR=0.08, evens my skin and keeps my. The strong one would have passed any numeric check.
**Not acted on, pending my verdict.** The look is NOT wired into the render path yet. I asked to see a 30 second test first and that is what exists.
**What changed.** `scripts/lib/capcut-look.mjs` holds the look and the provenance. Nothing else moved.
**My verdict, and both halves of it were right.** *"the beautify is no where near stong enoghg and it s way too pink the entire video."*
**The beautify was weak because the wrong knob was turned.** `bilateral` has two: sigmaR is how DIFFERENT two pixels may be and still be averaged, sigmaS is how FAR APART. The first pass reached for sigmaR, which is intuitively "smooth harder" and is literally an instruction to smooth across edges - which is why it ate my eyebrows, and why it had to be run weak to be usable at all. Holding sigmaR low and raising sigmaS instead smooths hard inside flat skin and leaves every strong edge alone. sigmaS=60:sigmaR=0.05 is far stronger than the rejected setting and my brows, lashes, lip line and hair all survive. It does not flicker: frame-to-frame delta on a forehead patch is 4.89 filtered against 6.39 unfiltered, steadier than the source because it suppresses sensor noise. Costs 2.4x realtime, about 36 minutes on a 15 minute long-form.
**The pink is real and the measurement explains why I am right rather than wrong.** On my forehead my own export runs R-G of 34 against the pipeline's 25, so the warmth genuinely is mine and the match was accurate. But in CapCut that warmth sits UNDER blush, lipstick and lashes, which give the face colour variety. With the makeup absent the identical cast lands flat on an unpainted face and reads as pink skin instead of glow. **So the number that matches the measurement is not the number to ship** - the measurement was never wrong, it was answering a question with the makeup still in it.
**AND THEN THE DIAL WAS THE WRONG ANSWER, which is the part worth keeping.** I put the warmth-0.25 frame beside mine: it had gone grey and flat, measured 5.8 red and 3 luma short of my export. Turning warmth DOWN was treating the symptom. **The warmth was never the fault - the missing thing was GLOW.** My export runs 19.45% near-white against the pipeline's 17.89%: highlights that spread and bloom. Bloom is what turns warmth into glow instead of into pink skin, so WITH it the full measured warmth reads correctly, and WITHOUT it no warmth setting is right - too pink at 1.0, grey at 0.25. Warmth went back to the measured 1.0 and v3 matches my export to R -1.1, G -0.8, B +0.5, luma -0.48.
**A latent bug in the live renderer, found on the way.** `finish-video.mjs`'s own bloom block screens a blurred copy over the picture while the graph is in yuva420p, and `screen` is per-plane - so it screens the CHROMA planes, which is not a brightening at all. Measured on one frame: blue 149 -> 178 while green went DOWN. Bloom is off by default so nothing shipped with it, but anything passing `--bloom` would have got a colour cast dressed up as glow. Fixed with `format=gbrp`.
**Bloom was rejected once before and this is not a reopening of that.** The note in `finish-video.mjs` says it was tried stacked with vignette and grain and that "each was subtle on its own; stacked, they turned a clean image muddy". This is bloom alone at 0.09. If I call it hazy, that is settled and it comes out.
**Warmth is now a dial, not a constant.** 1.0 is the measured truth, 0 keeps the identical tone curve with no colour separation at all, brightness unchanged at every setting. One direction at several strengths. My pick is pending against `FILTER-TEST-warmth-ladder.png`.
**Evidence.** `~/Movies/riadms-work/WATCH-THESE/FILTER-TEST-v2.mp4` (corrected) and `FILTER-TEST-warmth-ladder.png` — 30s, my CapCut export on the right, the pipeline plus the measured filter on the left. Colour is indistinguishable; the missing makeup is plainly visible in my lips and cheeks.
**Status.** live

### 2026-09-18  put the word series inside the reel that works, and find the limit is footage
**Decision.** Build **words you should know but don't**, the he10 structure carrying the "there's a word for it" idea: my dancing, a title card, then a word, what it means and a small picture on the same 2.73 second beat. Queue it second in the reel lane, directly between the books version and the text-short version of the same idea. What I wanted: *"kind of like how we started the red flags. And then we put a word and what it means and then a little image that would make sense."*
**Why.** The two engines had been tested separately and never crossed. This is the cross, and putting it at position two makes the lane a real experiment rather than a pile: position 1 against 2 changes the idea and holds the structure (books against words, same he10 frame), position 2 against 3 changes the container and holds the idea (he10 frame against a text-short, same words).
**What changed.** `scripts/word-reel.mjs`, `instagram/words/should-know.json`, five stills cropped out of my own b-roll into `instagram/words/images/`, and a section in `text-shorts/WORD-FOR-IT.md`. The five words are limerence, demisexual, fawning, sonder and the spotlight effect, all real and checkable, none of them anywhere in the queue.
**A sibling script and not a mode.** `he10-reel.mjs` is the one measured winner on this channel. Folding a second layout into it means editing the winner to add something that is not it, so the new one is beside it and the cutting engine is the only thing duplicated.
**Two faults caught by looking, neither of which any check would have raised.** The first pass ran meanings to twelve words, which forced the type down to 37px and turned the definition into fine print nobody can read in 2.73 seconds; meanings are capped at about eight words now and set at 41px. And the first crop was the whole frame, so Radio Silence was an unreadable dark rectangle at 430px wide. Every picture is now cropped to its subject.
**Pictures come from my own footage on purpose.** `broll-mine/` is tier 0 and rights clean. `out/vibe/` was the obvious source and has concept-matched sets sitting right there, including one literally called alterous-more-than-friends, but those are Pinterest film stills: fine as a half second pop inside a long form essay, a different thing held as the point of the frame for three seconds in a post.
**THE REAL LIMIT, AND IT IS NOT WRITING.** This format needs one continuous vertical clip of 15 to 25 seconds with a single sound on it, and I owns exactly three. Two are the dance clips already carrying the he10 reels and the third is a reading clip. All 95 lip syncs in `with-viral-sound/` are 5 to 8 seconds, and splicing three together fails because each has a different song baked in. So this one is 5 words rather than 7, on the Great Expectation clip at its third use. **One new take, 20 to 25 seconds, head starting about 45 per cent down, unlocks the format.** This is the fourth week running where the answer is an afternoon of filming rather than more lines.
**Evidence.** `text-shorts/out/words/words-you-should-know.mp4`, `text-shorts/WORD-FOR-IT.md`, `instagram/queue.json`.
**Status.** superseded by 2026-09-18 (the footage was there, in Downloads)

### 2026-09-18  the cap on how far a cut edge may move was doing no safety work
**Decision.** In the editor's proving pass, let an edge be LOOSENED as far as the gap
between the two pieces allows (up to 60 frames), instead of a fixed 8 frames, and add
the exact dissolve as a candidate. Tightening stays at 8 frames.
**Why.** Every delivered video still carried clipped words, and the editor could hear
them. Its own log at the alterous QPR join records that it listened, heard "a queer
platonic relationship, PR, is", found no candidate that fixed it, and kept the join.
The "Q" starts 0.67 s before the edge and the search could only reach 0.34 s. The cap
was protecting nothing: everything inside the gap is my own continuous take, so
loosening can only restore sound I actually made, and every candidate already has to
pass `confirmed(strict=True)`, which reports a restored stumble as scrap and refuses it.
The test was the safety net all along. Tightening REMOVES my sound and has no
equivalent net, so it was left alone.
**What changed.** `scripts/perfect-joins.py`. Measured on the two takes due next:
a-little-life 19 faulty joins of 220 to 3, alterous 19 of 175 to 10 to 8, QPR gone.
Two runs of different versions produced identical output on a-little-life (221 keeps,
11:48.9, 101 changes), so the editor is deterministic.
**Evidence.** Commit `5b561325`. Reports in the session scratchpad under
`perfect/<take>.reach/listen-new.md`.
**Status.** live

### 2026-09-18  Friday and Sunday filled from exports I had already made
**Decision.** Move `a little life` (11:35) from Wed 23 Sep to Fri 18 Sep, and give the
Sunday 20 Sep slot to my 8:36 alterous export instead of the 8:06 cut that held it.
**Why.** I asked for a video on Friday and Sunday. Friday was empty, and Sunday held
the OLD 8:06 alterous, which still says "not as much as romance card" - the fault I
caught myself and which later renders fixed. Re-cutting either one for this weekend was
not possible, because a re-cut needs my CapCut pass and Friday was under twelve hours
away. Both slots were therefore filled with files I had already exported, which cost
my nothing.
**What changed.** The 8:36 export inherited the old one's title, description, tags and
thumbnail and took the slot; the 8:06 is renamed `SUPERSEDED 2026-09-17` with its
publish date removed. 23 Sep is now free and is pencilled for `eight kinds of closeness`.
**Evidence.** `<scratchpad>/friday-sunday.mjs` and its log, ending `BOTH SLOTS CORRECT`;
verified again live, off YouTube rather than off the log, at 03:12.
**Status.** live

### 2026-09-18  three finished long-forms that had never been uploaded
**Decision.** Write titles, descriptions and chapters for `eight-kinds-of-closeness`
(12:53), `saving-things-for-a-better-day` (12:52) and `my-thoughts-on-marriage` (15:04),
and schedule them for 23 Sep, 21 Oct and 25 Oct.
**Why.** All three had a finished CapCut export on my Desktop, a render on disk, and
nothing on the channel pointing at them. All three are in the 12-18 minute band, which
delivers 4.64 watched minutes per view against 3.61 for 8-12, and which only five of my
videos have ever been in. `closeness` takes the nearest slot because it is a numbered
list of eight with research behind each, and lists out-perform single concepts here.
**What changed.** `out/publish/three-new-longforms.json`,
`out/publish/three-new-descriptions.md` (ai-tells 3/100, HUMAN_ONLY), and
`scripts/yt-upload-three-longforms.mjs`.
**Evidence.** The jobs file and the descriptions file.
**Status.** NOT ACTED ON. The uploader was refused by the permission classifier, twice,
including its dry run, so nothing has been uploaded and nothing is scheduled. None of the
three has a thumbnail either. Both need my.
### 2026-09-18  stop researching a route into Them
**Decision.** Three sessions is enough. Either message Sarah Burke on LinkedIn at `/in/sarahlubyburke`, or reassign the fish-and-water essay to AZE or Xtra. Do not spend a fourth session looking for a masthead.
**Why.** 24 August, 30 August and 18 September all failed to find a named editor for Them's first-person essays. Today's attempt could not read the masthead at all: the cloud session's network policy blocked every outlet domain, and them.us blocks the fetcher anyway. Search surfaced one name alongside Burke, Alyza Enriquez, which checked out as a VICE person and not a Them editor, which is the kind of near miss that becomes a bad guess. Equalpride bought Them in February so any convention inherited from Condé Nast is stale, and a guessed address spends the one arrival on a bounce. The Cut already spent one arrival on a wrong inbox and that is why the rule exists.
**What changed.** `out/press/PUBLICATION-STRATEGY.md` §4, the `press` branch of `threads.ts`. The Gmail draft keeps its `[ADD EDITOR ADDRESS]` subject so it cannot go out by accident.
**Decided and deliberately NOT acted on.** Guessing at `equalpride.com` or at a `firstname.lastname@` convention. It was considered and rejected for the reason above.
**Evidence.** `out/press/NEXT-MOVES.md` §2 for the first two attempts; `PUBLICATION-STRATEGY.md` §4 for the third.
**Status.** live, and it is a decision waiting on my

### 2026-09-18  three live pieces stand on the six Greek words, and one of them has to give
**Decision.** Record the collision and put the choice in front of my rather than resolving it unilaterally. The proposal is that the Greek-words section comes out of the Autostraddle essay before its form is filled in.
**Why.** The Autostraddle essay carries a whole section on the six words, the Guardian pitch sent on 25 August carries the same argument, and the NYT Opinion piece written today carries both. **This predates today and had never been recorded anywhere.** It is not fatal, because none of the three has run, but if two land the second reads as a rewrite of the first. Autostraddle is the one to cut because that essay's strength is the personal material and the *just friends* argument, not the etymology, and losing the section costs it about 150 words and no ideas.
**What changed.** Flagged in `out/press/nyt-opinion-six-words.md`, `PUBLICATION-STRATEGY.md` §3, `SEND-PLAN.md` and the desk.
**Evidence.** `out/press/autostraddle-essay.md` ("six words, and we kept one"), `guardian-pitch.md`, `nyt-opinion-six-words.md`.
**Status.** live, waiting on my before Autostraddle is submitted

### 2026-09-17  journaling posts credit @nuukoapp as a collaborator
**Decision.** Every Instagram post about journaling goes up with **@nuukoapp** invited as a collaborator, automatically, rather than as a mention in the caption.
**Why.** My instruction: *"when you're posting about journaling, can you add as a contributor Nuuko app, my journaling app, @nuukoapp"*. A collaborator is not a mention: the post appears on BOTH grids with both names on it, so the love-journal lane feeds the app's account as well as mine, at no cost per post. Nuuko is the capstone product and has no distribution of its own; the journaling lane already posts daily at 22:45.
**What changed.** `scripts/ig-lib.mjs`: `collaboratorsFor({ kind, caption })` is the decision (the `lovejournal` kind always, anything else when the caption's own words are about journaling), and the three container calls take `collaborators`. `scripts/ig-queue.mjs` writes it onto the item at fill time so it is visible in `queue.json`, and falls back to deciding at publish time, which is how the **10 journaling cards already queued** get it. `scripts/ig-post.mjs` gained `--collab` / `--no-collab`. If Instagram refuses the invite the post still goes up without it, loudly: a journaling card that never posts because of a credit line is the worse outcome.
**Evidence.** `instagram/lanes/README.md`, `node -e` over `instagram/queue.json` on 17 Sep: 10 of 143 pending items credit it, none of them false positives. The first 22:45 post confirms the API accepts the parameter.
**Status.** live

### 2026-09-16  "it doesn't matter the length as long as they are perfectly edited"
**Decision.** Re-cuts of already-filmed long-forms are not held for being under the 8:30 floor. They are held for any edit fault at all, including the ones earlier waved through as "does not block".
**Why.** My words, on being told types-of-jealousy (5:11) and am-i-anxious (6:10) could not reach 8:30 honestly: *"it's fine it doesn't matter the length as long as they are perfectly edited"*. The floor decides what to film; a take already filmed short has nothing true to put back.
**What changed.** The 2026-09-16 verdicts that those two "cannot be long-forms" are reversed. Every fault in all eight re-cuts is now fixed, including five deferred as cosmetic. CLAUDE.md rule 17 carries the exception.
**Evidence.** RECUT-BROKEN-JOINS.md status block of 2026-09-16; the decisions files' `_2026_09_16_*` notes.
**Status.** live. Narrows, does not supersede, the 2026-09-03 8:30 rule.

### 2026-09-16  a fix is read back from the rebuilt audio, not from the transcript
**Decision.** Every edit fix is verified by stitching the kept raw audio around the join back together from a cutter dry run and transcribing it cold, with loudness measured at each edge.
**Why.** Checking kept word times against stored word times said 21 of 31 fixes were clean and ten were not. The truth was different in both directions, because the stored times were exactly what was wrong: "patterns" sat 0.85s early in silence, "However," was twelve seconds from where the read put it, jealousy's "or" was at 392.06 not 391.60. The rebuilt-audio listen then found seven faults no read had listed, one of which turned my contrast into a list ("the fear of abandonment AND understanding each other's pain").
**What changed.** Scratch tools only for now (listen.py, splice.py, rms.py in the session scratchpad); the method is what is recorded.
**Evidence.** commit e8ec4655.
**Status.** live

### 2026-09-16  the cutter can cut in seconds
**Decision.** `cutSeconds` in a decisions file places a cut at measured times, and the silence pass leaves that air alone.
**Why.** Some joins have no word boundary where they need to be. "the loop" was heard "the look" with the pause cut at 561.01 and "loop" at 561.18. The only existing lever, the per-take noise floor, would have had to drop to about -60 dB and stopped every breath in the video being trimmed.
**What changed.** scripts/cut-video.mjs; opt-in, and a take without the key produces a byte-identical cut plan (checked on types-of-jealousy). New scripts/retime-words.mjs for measured retimes that asserts each word, refuses out-of-order times, and proves every cut and keep still covers the same words after a merge.
**Evidence.** commit e8ec4655.
**Status.** live

### 2026-09-15  the quality re-cuts get dressed into the slots they already own
**Decision.** My 33 CapCut re-exports of tonight replace the scheduled cuts in place: each new
upload inherits the old video's title, description, tags and thumbnail, takes over its publishAt,
and the old cut is retired private and retitled SUPERSEDED rather than deleted. The first twelve
are uploaded; the rest follow as I finishes.
**Why.** My note at the time: *"these are like the videos that we recut for quality"*, and *"tomorrow morning
9am whatever video comes make sure that it's like the most updated version of it"*. YouTube cannot
swap the file on an existing video, so a re-cut is always a new URL; for a video that has never been
public that costs nothing, but only if the new upload takes the old one's identity AND the old one
comes off the calendar, or both publish that morning.
**What changed.** New `scripts/yt-dress-recuts.mjs`, which is `yt-dress-desktop-uploads.mjs` with
its job table moved out to JSON, because I now re-cuts in batches and a new batch should not mean
editing a script. Two things it adds: a duration assert against what YouTube actually received
(CLAUDE.md rule 12), and a thumbnail fallback that pulls the old video's own custom thumbnail across
when there is no approved file on disk, so a slot can never inherit a YouTube-chosen frame.
`yt-dress-desktop-uploads.mjs` is untouched; it is the record of what was done on 2026-08-21, and an
addition is not a replacement.
**Evidence.** `scripts/yt-dress-recuts.mjs`, `out/publish/`, and the per-video scan record in
`youtube-mcp/repeat-scans.json`.
**Status.** live

### 2026-09-15  a-little-life ships on the new export, with one known over-cut left in
**Decision.** My new export (`a little fl.mov`, 11:34) is cleared for its slot. The one genuine
over-cut found in it, at 9:56, is documented and deferred rather than fixed.
**Why.** All four breaks recorded in `RECUT-BROKEN-JOINS.md` are fixed in this export, verified by
transcribing the export itself at each join. Of 33 SEAMs, 30 are the transcriber mishearing the
export ("Judy" for Jude, "possible" for possibility, "further" for "far away", which is mine
verbatim) and two are real but harmless clips. The 33rd is real: the stutter rule took all three
"that"s out of "recommendations of books that, that, that do exactly this", leaving a clause with no
relative pronoun. That is one missing function word in a fast aside, and asking my to redo a CapCut
export the night before publication costs more than it buys.
**What changed.** 33 rulings written into `youtube-mcp/repeat-scans.json`, each quoting its line and
saying why it stays; `_2026_09_15_read_as_paragraph` added to
`assets/decisions/a-little-life.decisions.json` carrying the deferred fix (`keep [2337, 2337]`) so
the next re-cut picks it up rather than rediscovering it. The publish gate now reports CLEAR.
**Evidence.** `assets/decisions/a-little-life.decisions.json`, `youtube-mcp/repeat-scans.json`,
`RECUT-BROKEN-JOINS.md` lines 100-104 for the four breaks this is compared against.
**Status.** live

### 2026-09-15  the preflight gate caught a doubling that MY OWN fix had created
**Decision.** The Bridgerton "underneath every single argument" repair was rewritten from a keep into a cut plus a narrower keep, after the render gate refused the take.
**Why.** `keep [1075,1096]` was written to stop a weld that read "underneath every single ARGUMENTS is". It did stop it, but I say the sentence TWICE, and the keep protected both attempts, so the cut shipped 04:45 "underneath every single argument is the thing that none of them want to say right" and 04:49 "then underneath all of these arguments is the thing that none of them wants to actually say". A fix that introduced a fault, caught only because the gate reads the film rather than the intent.
**What changed.** `cut [1075,1091]` removes attempt one, `keep [1091,1107]` protects attempt two, which is the complete one. Left edge 2.11s of silence, right edge 0.96s. Two other flags on the same take were read and NAMED as staying rather than cut: "to get into a relationship with someone" twice is my own "or like" self-clarification with no silence anywhere in it, and the 80 per cent flag at 05:02 is two different sentences building one point.
**Evidence.** Re-cut reports "every caption word has audio behind it" and 12:27.00. The gate no longer reports either restart.
**Status.** live.

### 2026-09-15  a paragraph-read finding is not applied verbatim, because keep and cut ranges must be disjoint
**Decision.** The overlapping `cut`+`keep` pairs proposed for `why-bridgerton-is-addictive` were **rewritten as disjoint ranges** before being written to the decisions file, and a disjointness assertion now runs before the file is saved.
**Why.** `keep [a,b]` is inclusive and `cut [from,to)` is half-open, and `isVetoed` (`cut-video.mjs:1032`) treats any overlap as a veto. Applied as proposed, the veto put the caption back while the hand cut still took the audio: the dry run went from **3 phantom caption words to 20**, including "Richard and cool job so" — the exact words the cut existed to remove, left on screen with silence behind them. That is rule 3, a wrong thing on screen, introduced by a fix.
**What changed.** All four overlapping pairs re-derived from the word table and the audio. The end card was settled by measurement rather than by reading: volumedetect gives 2801 "if" -28.6 dB mean / -10.2 max and 2802 "you" -16.4/-7.6, against 2803 "if" at -36.0 over 0.98s. So 2801-2802 are the real words and 2803-2804 are the dead one and a duplicate.
**Evidence.** Re-run reports **"every caption word has audio behind it"**, better than the 3 the take started with. `assets/decisions/why-bridgerton-is-addictive.decisions.json` carries the rule in `_ranges_note`.
**Status.** live.

### 2026-09-15  the mini target is 80-90 seconds, and batch one is written
**Decision.** Minis are written and filmed at **80 to 90 seconds**, about 300 words, wide, with a premise card and a seconds-count title. The first batch of five is `NEW-SCRIPTS-TO-FILM/minis-01-the-vocabulary-batch.md`: squish, alterous attraction, queerplatonic relationships, demisexual, demiromantic against demisexual. Narrows the 75-150s range proposed earlier today.
**Why.** Splitting the over-60s videos by length: 61-75s converts at 3.08 subs per 1k, **76-90s at 5.64 and holds 56% viewed**, 91-120s at 3.94, 121-180s collapses to 0.92 and 49%. The subs column is thin, five and six videos a band, and 1,922 of the 2,030 in the best band is one video, so the load is carried by **% viewed**, which does not depend on the outlier and orders the bands the same way. The five terms were chosen off my own comments rather than off a keyword tool: 3,502 likes on an aroace viewer wanting to share a life with their best friend, 416 on someone who could know their crush for years and still not know, 381 on someone who thought it was a crush and did not want a relationship.
**What changed.** The scripts file. `CLAUDE.md` rule 17 and `RPM-AND-REVENUE.md` already re-worded earlier today.
**What was verified.** Checked against my own voice, not only the AI list: burstiness 1.26 against the 0.60 floor, specificity 67.2 against my corpus 25.3, em dashes 0, `ai-tells` 2/100 HUMAN_ONLY. Limerence was checked against the live schedule and dropped from the batch because "how to know it's limerence, not love, in 141 seconds" already publishes on 27 October.
**What was caught in review.** The first draft used em dashes in five section headings, which is my absolute ban, and carried a claim that a 416-like comment was the most liked thing on my channel. It is not; a 3,502 comment is in the same file. The claim was cut rather than softened.
**Status.** live

### 2026-09-15  a mini cannot be lifted out of an essay, and my question caught it before anything shipped
**Decision.** The three lifted minis are not published and the lift approach is abandoned for the mini lane. Minis stay what they already are on this channel: written and filmed for the length. `scripts/mini-cut.mjs` is kept as a passage **finder**, not a renderer. Supersedes the decision earlier the same day that proposed shipping lifts into a new Thursday slot.
**Why.** I asked, *"minis are not shorts they need thumbnails and everythign r u sure they are good enogh to make them a single video?"* and `repeat-scan.mjs` answered it. All three BLOCKED on real faults: mini 1 says "want to be in a relationship with" twice 4.5s apart; mini 3 says "like a lot of people" twice 5.2s apart and "it doesn't have to be" twice 1.1s apart; mini 2 restates its own point at 76s. The cause is structural. Inside an 11 minute essay a phrase recurring five seconds later is invisible; inside a 107 second lift it is the whole video, so **a lift inherits the parent's repetition at a length where it cannot hide.** A second gate can never clear at all: joins are verified against the raw take, and a lift cut from the published file has no take, so NO-TAKE blocks it permanently. And my packaging point stands on its own: a mini is a video on the channel and needs a thumbnail and a title, and none of the three had one because I was treating them as feeders.
**What was already written down and read past.** `scripts/shorts-cut.mjs` says in its own header that a 60-120s standalone explainer is "a different job: written for the length, filmed for it, not cut out of something else". That was correct when it was written and it is the conclusion arrived at again the expensive way.
**What survives.** The length finding is untouched: 233 videos at or under 60s gave 37 net subs, 22 over 60s gave 2,188. Rule 17 and `RPM-AND-REVENUE.md` stay re-worded. `mini-cut.mjs` reads the published captions and picks the strongest self-contained 75-150s arguments; 30 are in `out/minis/*.picks.json` across nine essays and they are briefs to film from, not files to post.
**What was thrown away.** Three rendered minis, about 130MB, and the Thursday slot plan.
**Evidence.** The three scan reports in `~/Movies/riadms-work/repeat-scans/`, `out/minis/`.
**Status.** live

### 2026-09-15  the mini is built, and rule 17 no longer defends short form with the minis' number
**Decision.** The sub-minute lane is retired and the **mini** replaces it: 75 to 150 seconds, wide, lifted out of a published essay. `CLAUDE.md` rule 17 and `RPM-AND-REVENUE.md` are re-worded to say so, on my instruction to do it myself. Three minis are cut and none is scheduled.
**Why.** My correction, *"any short above 1 minute is actually a long form pls undertand that"*, re-cut the measurement at the minute: 233 videos at or under 60 seconds gave **37 net subscribers** between them, 22 over 60 seconds gave **2,188**. A cliff, not a slope, since 46-60s converts at 0.58 with the six second cards while 61-90s converts at 5.57. The 4.3-5.5 subs per 1k that rule 17 used to defend Shorts, reels and updates was always a measurement of the 61-180 second wide videos; the sub-minute ones convert at 0.10.
**What changed.** `scripts/mini-cut.mjs`: lifts a passage out of the file YouTube actually serves, using the published captions' word timings, wide, no vertical crop. It has a hard floor at 70 seconds and refuses a window that crosses one of my own section openers, which is what stops a mini being two arguments. `CLAUDE.md` rule 17 and `RPM-AND-REVENUE.md` §4 re-worded. `out/minis/*.picks.json` holds 30 selected passages across 9 essays.
**What was verified rather than assumed.** That my biggest one is wide was read off its own frame sheet, not taken from the research note. The download was checked against the published duration (660.4s against 661s) before anything was cut from it, because neither the pipeline render (1224s) nor anything on the Desktop matches these essays. All three renders were looked at as contact sheets rather than trusted from the log.
**What is blocked and was not worked around.** `repeat-scan.mjs` is refused by this session's permission classifier, and rule 4 says nothing gets a publish date until repeat-scan has read the file. So the three minis are rendered and **unscheduled**. The gate did its job; it is mine to run or to permit.
**What was thrown away.** A first VTT parser read every word twice, because YouTube's rolling caption format repeats the previous line above the new one and taking the whole cue body glues the repeat onto the first new word. A first section detector caught "the fourth type" and missed "the first one" and "the type two is", so the first mini it produced ran through two of my list items.
**Evidence.** `scripts/mini-cut.mjs`, `out/minis/`, `SHORTFORM-GROWTH.md`, `/shortform`.
**Status.** superseded by 2026-09-15, the entry above: the lifts failed repeat-scan and are not shipping.

### 2026-09-15  a breath is not silence, and the cutter was built on the belief that it is
**Decision.** The cut engine stops trusting whisper's word boundaries for anything about air, and every long-form and mini is re-cut and re-delivered into `WATCH-THESE/finished needs capcut`. My prompt: *"there's like still a moment around 0:50 where it's like just me breathing in the mic"*, and then *"make sure these never happen again"*.
**Why.** I had reported the same thing once before, on 30 August, and it was answered by lowering `beatKeep` to 0.25, which reduced the symptom and never touched the mechanism. Measured on the raw take this time: I finishes "the magnitude of the threat" at 172.96, the room is silent to 173.7, I draws breath from 173.8 to 175.0, silent again to 175.9, and says "If your partner" at 176.0. A breath averages well under the -30dB line but peaks around -14, and `silencedetect` needs the level to stay under for the whole span, so it reports the two silences and not the breath between them. Four separate rules then did the right thing with that wrong input: the island weld gave the pause back because it asked what CLASS of cut made the gap rather than what was in it; whisper had put "if" three seconds early and a second long, so the silence and the breath sat inside a word span that the pause rules may not trim and that `touchesAWord` correctly held; the gap was trimmed as two silences rather than one piece of air, so a short one failed `--mid-min-save` and was left alone; and a word-removal cut started at whisper's start for the word it removes, leaving the front of it on the kept side of the join, which is the second fault I reported the same morning on four-conversations.
**What changed.** `scripts/cut-video.mjs`: the weld measures the audio; a word that cannot have been said across a silence is stood against the word that follows it; the silences between two kept words are one span; a cut that removes a word goes back to where that sound starts. `soundParts`/`soundEnd`/`soundStart` at the top of `plan()` are the shared measurement, because whisper snaps one word's end to the next word's start and 91% of real gaps come back as exactly 0.000. New check `breath-check.mjs`, which costs one silence pass and no transcription, because every render already writes the delivered-timeline word timings into `NAME.cut-words.json`. `WATCH-THESE/finished needs capcut` created; a file enters it only after the delivered file itself passes, never on a log saying ok.
**What was verified rather than assumed.** Two dry runs of the same take differing only in `--min-island` proved the weld was the cause: with the weld off there is a 0.73s cut at 02:53.08 that is gone with it on. Every change was read back from a fresh dry run before any render: identical text on both takes, 1119 and 1882 words diffed word for word, and no new caption word without audio behind it. The sweep over all 57 deliveries found 15 breath moments in 10 takes and 46 files clear.
**What was thrown away.** A first fragment detector reported 27 leftover word-fronts on four-conversations. Checking one showed the "leftover sound" was my kept word "country", with the 0.06s plosive stops inside continuous speech resetting its reference; the real count was 3. The number was discarded rather than reported. A first version of the cut-front guard took the ends off "fun,", "country", "partner" and six more words while the captions still showed them, and was replaced before anything rendered.
**What is still mine.** The three decisions from the overnight round are untouched: Sunday's alterous upload, the five long-forms under 8:30, and the ending of `not-their-only-support`.
**Evidence.** Commits `aa7f5c76` and `c87aee5d`, `LEARNINGS.md` under "A breath is not silence", `scratchpad/breath-sweep.txt`.
**Status.** live

### 2026-09-14  the drive is not full of junk, it is full of bitrate
**Decision.** The Toshiba is reclaimed in two moves: the design channel's raw footage is deleted outright, and the 54 already-edited raw takes are re-encoded from 31 Mbps to 14 Mbps in place rather than deleted. The Google Photos archive and every unedited take are left alone.
**Why.** I asked why the drive holds 1.8 TB and assumed duplicates. It does not: a full inventory of all 9,791 files over 10 MB found only **0.5 GB** of genuine duplicate files. The drive is large because I films 30-60 minutes of 2.7K HEVC at 31 Mbps per video and keeps all of it, 439 takes. The ugly-b-roll cleanup I asked for is real editorial work but the entire b-roll folder is 4.1 GB of 1,800, so it could never have been the answer. Re-encoding beats deleting because the footage stays re-cuttable: measured SSIM against source is 0.9932 at 14 Mbps, and a frame-exact comparison of my hair edge against the pale wall is indistinguishable.
**What changed.** Deleted `video-files/design-videos/` raw footage and renders, 35 GB, after confirming all nine design videos are published with live YouTube IDs. **Kept `design-videos/work-state`** (5.3 GB) against the instruction, because CLAUDE.md names it the only backup of unregenerable decisions files and `/tmp/riadms-ux` is confirmed gone. Free space went 38 GB to 73 GB. Wrote `~/Movies/riadms-work/reencode-takes.sh` for the 219 GB re-encode, expected to return ~120 GB.
**Evidence.** `~/Movies/riadms-work/reencode/reencode.log`. Two faults the script catches and a naive re-encode would not: `creation_time` is dropped by the encoder, which rule 18 reads for the FaceTime menu-bar clock, and a parallel session's render was actively reading a target file mid-batch. The script therefore verifies frame count, audio stream, duration and creation_time per file before replacing an original, waits for a quiet drive, and re-checks for a render immediately before the swap.
**Status.** live. Deletion done; re-encode written and verified on settings, running as the drive allows.

### 2026-09-14  the face-card ceiling is footage, and the register count moves to after queueing
**Decision.** Finish Monday's half-dead build by hand rather than wait for next Monday, and take the register count on what actually reached the queue rather than on what was written. Add `--skip` to `face-card.mjs` so a build that dies partway can be resumed without re-rendering or splitting the lines file.
**Why.** The 09:00 job wrote all seventy lines, cleared cold-read and the freshness gate, then died mid-render: twenty-five half-made files, nothing queued, no report, and the log truncated by the 10:00 guard opening it, so the cause is unrecoverable. This is the second identical failure in nine days (the 6 September build died on card 26). Instagram was at 1.2 days against a 2-day floor. The finding that matters more than the fix: the batch was written 44 per cent warm and the first 28 cards through the guards came out 36 per cent warm and 25 per cent sad, because the duplicate refusals fell on seven warm lines against one sad one. Warm clips get consumed fastest, so the footage guard silently reshapes the register and nothing measures it. Underneath both: 52 queued cards sit on two days of unrepeated footage, and sixteen of today's eighteen refusals were footage rather than words.
**What changed.** 40 cards queued to Instagram and 40 to TikTok off `lines-23.md` (`face-cards-23`, `-23b`, `-23c`). `scripts/face-card.mjs` gained `--skip N`; default behaviour unchanged. Three items removed from the queue and their R2 blobs deleted after a caption-check bypass let them through, one of them a hard duplicate of a card posted 16 August. `src/data/threads.ts` and the desk snapshot updated. A split lines file (`lines-23b.md`) was written and thrown away: the repeat gate excludes only the file it is handed, so a split of `lines-23.md` scores 100 per cent against its own parent and every line drops as a repeat of itself.
**Evidence.** `scripts/.face-card-weekly-report.md`, `out/freshness/lines-23.md`, `instagram/queue.json`.
**Status.** live. Two things were found and deliberately not acted on: the *same words* refusal is a background hash rather than OCR and misfired eight times today, already written up and left alone; and `face-cards-20b-04` is blocked for a third week because the card correcting a deleted post is held as a duplicate of the post it corrects, which is mine to clear because it releases a post.

### 2026-09-14  the restart-rule list guard is measured and not adopted
**Decision.** Keep the cutter's restart rule as it is; do not merge the list guard that was built and measured today. My lists keep being protected by the paragraph read and hand keeps.
**Why.** Against 16 hand-reviewed long-forms with keeps removed, the best guard stopped 20 of 64 wrong list cuts with no new cuts, but it also undid two real restarts ("your social mind, your social time, your social life", where I am searching for the word with long pauses between tries), and no signal separated two-item lists from restarts: every attempt at pairs took 34-40 real restarts with it.
**What changed.** Nothing in the shipping cutter. The experiment, labels and diff are kept in `out/experiments/restart-list-guard/` and `scripts/cut-video.anaphora-exp.mjs`. The publish gate now also reads a take's drive decisions copy when the repo has none, the same order edit-queue uses, and every mini carries its read note.
**Evidence.** LEARNINGS.md 2026-09-14; out/experiments/restart-list-guard/compare.json.
**Status.** abandoned for now (guard); live (gate fallback)

### 2026-09-14  the paragraph read becomes a gate, an agent and a cutter experiment, not a habit
**Decision.** After I asked that these mistakes not happen again, the read is enforced in code and carried in files rather than remembered: no take-bound long-form gets a publish date without a dated `_read_as_paragraph` note in its decisions file; a `paragraph-read` agent carries the method; CLAUDE.md rule 4, SHIP-CHECKLIST section 6 and the edit-video skill require it; and the cutter's restart rule is being tested for a guard against cutting my lists.
**Why.** The same read over 16 long-forms found about 110 faults that every scan and a full listen had passed, in two directions: stumbles left in, and my own lists and parallels cut as retakes. A note in LEARNINGS does not stop the next video; a refusal at the publish date does, because every video passes through it.
**What changed.** `scripts/repeat-scan.mjs` `assertParagraphRead`, called from `assertRepeatClear` (the publish gate only, not the CLI scan the render queue runs); `.claude/agents/paragraph-read.md`; CLAUDE.md rule 4; SHIP-CHECKLIST.md section 6; `.claude/skills/edit-video/SKILL.md` step 3; the memory note. The restart-rule guard is tested in `scripts/cut-video.anaphora-exp.mjs`, a copy nothing renders with, against the 16 hand-reviewed takes; it is adopted only if it stops the list cuts without losing real restarts. Also found and fixed on the way: a `while read` render loop that lost its list to a child reading stdin and skipped eleven takes.
**Evidence.** Commits 72c38242 and this one; LEARNINGS.md 2026-09-14 morning; scratchpad stumbles-group1-4.md and guard-exp/.
**Status.** live (gate, agent, docs); experiment in progress (restart guard)

### 2026-09-14  nothing is ready until its cut has been read as a paragraph against the raw
**Decision.** A video is called ready only after a person-style read of the whole cut text against the raw transcript finds no abandoned starts, unmeant 1-3 word repeats, or clipped words; the audio listens alone are no longer enough, and the eight files already called ready were pulled back.
**Why.** I heard "both can be true at once. trauma does not. there is no study that shows that trauma causes asexuality" in asexual or repressed. Nothing in that is said twice, so every repeat check and the full cold listen passed it. A pattern scanner over the same text flagged 41 spots, almost all my own rhetoric, so a scanner is not the answer either. Reading four long-forms as paragraphs found 30 fixes, including socializing at 9:18, where a cut dropped "when I do them" and reversed my meaning.
**What changed.** Four readers, one per group of takes, write proposals only; each proposal is checked for text and overlaps before it is written to both decisions copies, and every cut edge must sit in a measured silence. The render queue was stopped by hand so no take renders twice before its fixes land. Decisions for asexual-or-repressed, four-conversations-every-couple, how-much-socializing-you-actually-need, a-little-life and types-of-chemistry.
**Evidence.** Commit 8f45a3ca; scratchpad stumbles-group2.md; WATCH-THESE/_DONT-CAPCUT-YET.txt 09:15; the desk.
**Status.** live

### 2026-09-14  a stumble with every word whole beats a cut that clips one
**Decision.** Where two tries run together with no pause, keep both whole rather than cut between them; and a doubling report that is only "2" against "two" is named in the decisions file, not repaired.
**Why.** Full listens of the morning renders found friendship saying "to understand what of it" where I said "what love is", because a hand cut from the day before started mid-word, and underrated keeping my sung "la la la la la", which the transcript had hidden inside "because". types-of-jealousy was refused by the doubling gate over a digit.
**What changed.** Decisions for friendship-is-not-second-class (hand cut 1919-1924 replaced by keep 1914-1924), underrated-romantic-things (cut 104-117 for "because my", la repaired out of raw 766 and cut 753-767 with both earlier tries, keep moved to 1142-1150), types-of-jealousy (03:23 named). Friendship, enemies to lovers, am I anxious, types of jealousy and underrated render again before the Monday minis.
**Evidence.** Commits 181466b3, 3d98f856, d7edc9ec, 20361b94; LEARNINGS.md 2026-09-14 morning; WATCH-THESE/_DONT-CAPCUT-YET.txt.
**Status.** live

### 2026-09-13  the face cards take the first step off asexuality, and next Sunday holds
**Decision.** The week of 14 September ships 3 blocks asexuality, 2 crushes, 2 love in general, which is the first step of my shift. Next Sunday does **not** move another block: it holds at 3/2/2 and says why. Two tag decisions were deliberately **not** taken: no hashtag was promoted and none retired.
**Why.** Growth halved for the second week running, +96, then +73, then +39, a fall of 47 per cent, and the step rule in `instagram/lanes/README.md` holds the mix whenever it falls by more than a third. The step itself still happens because the README fixes the week of 14 September by name, and it is my direction. The honest part is that nothing in this week's numbers argues for cutting asexuality from 50 lines to 30: it still medians 100 likes against 20 to 31 for every other topic and carries a 9.1 per cent comment rate against 0.7 to 2.3. The tag moves were skipped because promotion needs a tag seen in two scout reads and this was the first read ever, so acting would have been acting on one Saturday.
**What changed.** `instagram/BRIEF.md` rewritten for 2026-09-13 (gate passes, exit 0); both lane playbooks gained a "from the scout" section and an explicit "too early, no findings" note; four dated lines in `instagram/scout/watch.json` `_log` recording the non-moves and what to check on 20 September.
**Evidence.** `instagram/BRIEF.md` sections 1, 3 and 8; `node scripts/ig-lane-stats.mjs --days 7`; `instagram/scout/LATEST.md`; `scripts/.ig-brief-weekly-report.md`.
**Status.** live.

### 2026-09-13  growth is falling while engagement is flat, and the cause cannot be measured
**Decision.** Named as the account's most valuable unknown rather than explained, and the insights scope put in front of my as the fix. No theory was written into the brief.
**Why.** Likes 4,910 against 4,856, comments 239 against 238, output 51 posts against 46, and this week's posts are seven days younger, so at equal age engagement is up. Follows went from +73 to +39 anyway. Every candidate explanation sits between reach and following, and reach, views, saves and shares are not on the Instagram token. It also weakens the first brief's "followers = breakouts x about 20" model: 4 breakouts gave 18 each, 3 gave 13. Writing a cause from likes alone would have been inventing a number, which my own rule forbids.
**What changed.** Nothing in the pipeline. The insights scope is item 3 of `scripts/.ig-brief-weekly-report.md` under "what needs my", and it matters from tomorrow because love-journal is a saves lane that will read as a failure on likes.
**Evidence.** `instagram/BRIEF.md` sections 1 and 7; `node --env-file=.env scripts/ig-insights.mjs --report`.
**Status.** live. Decision made and not acted on: `face-cards-20b-04` is still blocked as a duplicate of the deleted brother post, reported for the second week running and still one line to fix; nothing was changed because this job writes the brief and does not touch the queue.

### 2026-09-14  Monday's mini comes off the calendar, and the drive is cleared of DJI previews
**Decision.** "do you actually like him, or do you just like being chosen?" (NkSqALp52So, due Mon
14 Sep 23:00 UTC) is private with no date. 395 DJI .LRF preview files and 11 byte-identical
duplicate renders were deleted from the TOSHIBA, freeing 40 GB, and the paused renders resumed.
**Why.** My note at the time: cancel whatever goes out tomorrow "because I don't think we'll be ready", and
the DJI side file "if we're not using it, you can delete freely", plus anything that duplicates.
The .LRF is DJI's 720p proxy; only library-grade.py can read it, as an optional speed-up that
falls back to the full clip. Only proxies with their full clip beside them were deleted; 18 with
no clip stay, and the 13 "rough cut.srt" files (mine, not DJI's) stay. The 13 videos that existed
only in the drive's old WATCH-THESE were copied to the SSD before anything there was touched.
**What changed.** YouTube (read back: private, publishAt none); the drive; the render queue.
**Evidence.** riadms-work/_deleted-2026-09-14-dji-lrf.txt and _deleted-2026-09-14-drive-watch-these-duplicates.txt
list every deleted file; riadms-work/_from-drive-watch-these-2026-09-14 holds the copied ones.
**Status.** live. Supersedes the "nothing on the drive was deleted" line of the entry below. Next
scheduled video: alterous-attraction, Sun 20 Sep, which is still waiting on its re-render.

### 2026-09-13  renders stop when the drive is nearly full, and the batch waits for my
**Decision.** edit-queue refuses to start a take when the drive under the long-form folder has
less than 6 GB free, and stops the queue. Tonight's remaining renders are paused rather than
freeing space on my library drive without asking.
**Why.** The drive filled mid-batch (24.5 GB of render copies in one evening) and a copy that hides
its errors wrote 0-byte files over a hand-repaired transcript. Freeing space means deleting on the
drive, which is my call: the last cleanup was approved group by group.
**What changed.** The guard in edit-queue.sh; the running queue and its three waiters stopped; the
five zeroed enemies-to-lovers files restored from the SSD work folder (rescue copy in
riadms-work/_rescue-2026-09-13). Options measured for my: superseded renders 8.6 GB, cache/work
intermediates 13.4 GB, the August WATCH-THESE on the drive 16 GB (older versions, 13 experiment
files only there). "japan+switzerland-videos copy" was checked and is not a duplicate.
**Evidence.** LEARNINGS.md 2026-09-13 evening; render-runner.log in the session scratchpad.
**Status.** live. Decision made and not acted on: nothing on the drive was deleted.

### 2026-09-13  a swallowed retake is found by the sound inside a word, and repaired before render
**Decision.** Before a take renders, every word the transcript made last 1.5s or more is probed for
the total sound inside it; one holding more sound than the word takes to say gets a cold listen,
and a confirmed collapse is repaired with repair-words.py, with every index range re-derived by
its own text.
**Why.** your-best-friend rendered "two psycholo, two sociolo, la la la, two sociologists" and a
sentence said three times, and every gate passed: the word list had one copy, so the cutter could
not cut it, and the doublings listener only reports verbatim repeats. The first probe (longest run
of sound) missed two of the three known cases and was thrown away; the total-sound version caught
all three before it was run on anything else.
**What changed.** Repairs on your-best-friend, am-i-anxious (06:34, which an August read had called a
false positive), and three minis: how-to-know-its-limerence, women-2, the-four-seconds. On
the-four-seconds the restart rule then kept the wrong try and lost the sentence's last word, so a
keep was added; a repair is checked by reading the join, not by the count.
**Evidence.** LEARNINGS.md 2026-09-13 evening; each take's `_repaired_2026_09_13` note; probe and
validation output in the session scratchpad (collapse-probe.mjs, collapse-probe-validate.txt).
**Status.** live. Decision made and not acted on: the probe is not wired into edit-queue yet, so the
next batch relies on someone running it.

### 2026-09-13  a word's start comes from its sound, not from whisper, after a long pause
**Decision.** cut-video.mjs moves a word that follows a gap back to where the silence before it
ends (0.12-0.7s), before any rule plans a cut.
**Why.** Two re-renders dropped a name while captioning it: "Gallup" on how-much-socializing and
"Jude" on a-little-life. Whisper timed each late after a pause, a hand cut and the wordless rule
both trusted that time, and the silent-word check measured the same wrong span.
**What changed.** The cutter; five files cut on the old code re-render after the running chain
(socializing, alterous, a-little-life, types-of-chemistry, asexual-or-repressed), with a
_DONT-CAPCUT-YET note in WATCH-THESE until then. Takes cut later in the chain get it automatically.
**Evidence.** LEARNINGS.md 2026-09-13 evening; transcriptions of the delivered files at 0:25 and 9:39.
**Status.** live. Work thrown away: the first renders of those five.

### 2026-09-13  a BLOCKED verify result is read before the file is called ready
**Decision.** Every re-render's SEAM list is read, line against the raw take, before the file is
treated as done; a file the verifier marked BLOCKED is not handed to my.
**Why.** alterous-attraction rendered at 17:19 and verify-delivered.sh marked it BLOCKED with 26
seams, the first of them "not as much as romance card" at 0:10. The runner went on to the next take,
the file sat in WATCH-THESE, and I watched it and caught the line myself. The cause was an August
decisions entry that cut only the first of my three tries at that clause, so the cutter kept half of
the second. Reading the 26 seams found two more real breaks ("alterous is the other than the two
words", and a "gonna" with no audio behind it); the rest were transcription noise.
**What changed.** alterous-attraction decisions: cut 51-71, keep 797-799 and 1277-1290, the stale
cutText removed. Dry run clean at 8:57, every caption word audible. Re-renders after the chain.
**Evidence.** `assets/decisions/alterous-attraction.decisions.json` `_2026_09_13_romance_card`,
RECUT-BROKEN-JOINS.md.
**Status.** live. Work thrown away: the 17:19 render of alterous-attraction.

### 2026-09-13  the cutter welds short pieces instead of keeping them as flashes
**Decision.** cut-video.mjs welds any piece under 1.2s into a neighbour, giving back up to 1.5s of
pause (option B of three I was shown as numbers).
**Why.** I watched the first re-cut and said it still cut often and cut names. The morning's fix
had kept every scrap of speech as its own shot: 310 pieces and 42 flashes under half a second, against
259 and 10 before, with "Gallup" still clipped. Welded: 239 pieces, 8 flashes, every name whole.
**What changed.** cut-video.mjs defaults; the first re-rendered file is superseded; renders restart.
**Evidence.** LEARNINGS.md 2026-09-13, the dry runs in the session scratchpad (island-A/B/C).
**Status.** live. Work thrown away: the 11:37 render of how-much-socializing.

### 2026-09-13  a publish date also needs every sentence to be one I actually said
**Decision.** The publish gate now blocks on SEAM, a cut that welds two attempts at a sentence into
one I never said, and on NO-TAKE, a long-form scanned without its raw take to compare against.
**Why.** A viewer, @goblinkoma, said the cuts go through the middle of sentences, "places like 7:03".
Seven real welds were found in the uploaded wrong-partner file, three inside ten seconds, on a video
the repeat gate had cleared. Three cheaper detectors were built and measured first and thrown away:
the pipeline's own word lists (missed two of three), whisper confidence (real welds scored the same
as clean speech), and every never-said trigram (54 candidates, 3 real).
**What changed.** scripts/join-scan.mjs, repeat-scan.mjs (--take, SEAM, NO-TAKE), the ship checklist
gate, CLAUDE.md rule 4, LEARNINGS.md. All 17 scheduled long-forms went from clear to blocked and were
matched to their takes; they carry 12 to 37 candidates each to read.
**Evidence.** youtube-mcp/repeat-scans.json, LEARNINGS.md 2026-09-13.
**Status.** live. The same day, listening to the raw take traced most of the lost words to the cutter
discarding short pieces of real speech next to my pauses; cut-video.mjs was fixed to keep any piece
touching a captioned word and to report any caption word with no audio (2 and 3 left on the two takes
tested, from 35 and 46 on the naive count). Restart-rule welds are not changed by it.

### 2026-09-13  a publish date needs a clear scan of the uploaded file
**Decision.** No video gets a publish date until scripts/repeat-scan.mjs has read the file I
uploaded and come back clear, and six scheduled videos were recut and swapped in on that basis.
**Why.** The repeat gate lived in one render path and read the pipeline cut; a viewer found what it
never saw. Scanning the 37 scheduled videos found real doublings in six, and about two thirds of all
flags were my phrasing on purpose, which are ruled in writing rather than skipped.
**What changed.** Gate on every tool that sets publishAt, a 06:45 audit, stemmed run matching, six
recut uploads scheduled into the old slots with the old metadata and shifted chapters, old uploads
private. A race that erased ~30 rulings was found and fixed the same day.
**Evidence.** youtube-mcp/repeat-scans.json, LEARNINGS.md 2026-09-12, commits b0744e84 and d6cbac9d.
**Status.** live.

### 2026-09-13  an absent draft is not a lost draft, so the sent mail is checked first
**Decision.** Before reporting a draft as missing, the run reads the sent mail for that
thread. Supersedes the conclusion recorded on 2026-09-12 that a North Atlantic draft had
vanished from the mailbox.
**Why.** It had not vanished. I sent it on the 12th at 19:33Z, along with the Yasmin
Benoit reply six minutes later. The 12th listed 33 drafts, did not find that one, and
inferred a loss, which was a reasonable inference from an incomplete check and still
wrong. A draft leaves the draft list for two opposite reasons and the list cannot
distinguish them. The cost of getting it wrong is real work: the draft was rewritten and
re-created for no reason, and had I not already sent it, two near-identical emails
would have been sitting in one thread.
**What changed.** `out/inbox/STATE.md` trap 6 rewritten to carry both halves.
`review-copies/STATE.md` records both sends. The 12th's desk entry is corrected by a new
entry above it rather than edited.
**Evidence.** sent messages `1a0971be0f119b50` and `1a09721864a166c8`, both on
2026-09-12.
**Status.** live. Supersedes the missing-draft finding of 2026-09-12.

### 2026-09-12  every audit finding is fixed on main, and the deploy waits for my
**Decision.** My instruction, "fix all of them": every row of /nuuko-audit was fixed on `fix/audit-2026-09-12` and merged to main in nuuko-v1 (`0efea21`). Analytics loads Vercel's own insights script on all 32 pages. The streak popup, the dead `getStreakData` call, the day-streak number and the count badges on save are gone. No mood guess while typing, and the mood question now reads "now it is written, how did it feel?". Home opens on the moment, then the people, then the greeting. The library filters by person. Onboarding is three cards. The sign-in banner waits for the third page. A new person's first prompt is always a noticing one, and my 200 questions display lowercase. On a phone: the landing button is inside the first screen with a sticky button after scrolling, the home tab icon is visible, settings inputs are 16px, and onboarding tap targets are 44px.
**Why.** The audit the same evening, and the decisions of 11 September that the live app still contradicted.
**What changed.** 42 files in `public/`. Two findings were wrong or missed, and both are written down. Wrong: patterns "0 people" was correct, because the test page had nobody filed to it. Missed by the audit and caught by looking at the screenshot of the fix: the save popup still showed "1 day streak" and "welcome to your journal".
**Evidence.** A phone-profile browser check, 21 of 21 passing; `scripts/smoke.cjs` clean; screenshots read by eye.
**Not acted on.** Production deploy. The CLI deploy was refused by the permission check, so www.nuuko.app still serves the earlier build until I run it or allows it. The settings toggles are left under 44px.
**Status.** live on main, not deployed

### 2026-09-12  editing and thumbnails are the priority, not a new strategy
**Decision.** The next stretch of work goes into the quality of the edit and the thumbnail,
starting with a scan of every published long-form for repeats the pipeline never checked, and
a measured study of reading-vlog editing. This replaces the "film one long-form a week" framing
I proposed earlier in the same conversation as the headline priority.
**Why.** I said the strategy numbers already exist and the craft is what is behind. A viewer,
@alipercapita, commented on "being asexual taught me why people pick the wrong partner" that at
about minute 6 I say the same sentence twice, and the next one twice too. Transcribing the file
I actually uploaded confirmed it at 5:59-6:11. That video rendered at 13:39 on 7 September, and
the repeat gate was wired into edit-queue.sh at 22:22 the same day, so nothing rendered before
that night was ever checked. Today's gate blocks it (9 words verbatim, 3.0s apart). Separately,
the gate flagged 9 restarts across five other takes and reading them against the captions, about
one in three was real: "are you in the picture sitting next to them, or are you in the picture
being them" is my parallel on purpose, and a gate that is wrong twice in three gets overridden.
**What changed.** A background scan of all 89 non-Amazon files in
~/Desktop/finished-main-channel-videos. youtube-mcp/ctr.mjs read no CTR at all: it opened the
first CSV alphabetically, which is now Studio's "Chart data.csv", and Studio renamed the column to
"Thumbnail impressions". Both fixed; the 2026-06-14 to 09-11 export replaced the 17 August one,
which is kept in ctr-export/2026-08-17/.
**Evidence.** The comment; queue-wrong-partner-pass5.log (no repeats beat); commit 6ef369dc;
ctr-export/Table data.csv (5.08% channel CTR on 9.87M impressions; hashtag Shorts 2.81% weighted
over 239 videos, long-form 4.16%, sub-4-minute landscape 6.68%).
**Status.** live.

### 2026-09-12  nuuko is on main and actually deployed, and the git trigger is confirmed dead
**Decision.** My instruction, twice: push nuuko to origin main. Everything from the
quality pass, the moment and the circle is on `main` (`8db962e`) and **deployed by
hand from the Vercel CLI**, because a push to GitHub still creates no deployment.
**Why.** The 11 September session left this open: *"what is not settled is why GitHub
pushes still do not trigger a build; the next push will show whether it fixed
itself."* It has now shown. Ten minutes after the push, `www.nuuko.app` still served
the 11 September build, and the Vercel deployment list had no new entry at all, not a
failed one. **The GitHub integration does not fire; the CLI is the route, and that is
now a standing fact rather than a suspicion.** Two things had to be fixed to get the
deploy through: `vercel --prod` needs `--scope maria-dumitrescus-projects` or it
answers "Not authorized", and **the Hobby plan caps a deployment at 12 Serverless
Functions**. The app ships 9; the five `api/circle/*` handlers made it 14 and the
deploy failed outright. They are now one `api/circle.js` dispatching on `do`.
**What changed.** `main` at `8db962e`, production at
`nuuko-3r6bi7te3`. One API function instead of five. The circle page degrades to "the
circle is not open yet" while migration 006 is unapplied, rather than showing a
database error. The dead streak JS and CSS left on home after the card was removed are
gone.
**Verified, not assumed.** The live domain was read, not the push: `/people` carries
the add-someone form, home carries the moment card and no streak pill, `/circle`
returns 200 and says it is not open yet, the landing headline is the new one, the
footer says 2026, and a real browser on `www.nuuko.app` reports zero page errors.
**Still open, and mine to decide.** Migration `006_circles.sql` is not applied, so the circle cannot be
tested end to end until it is run.
**Status.** live

### 2026-09-12  the Yasmin Benoit reply is cut to the same ceiling, and bullets stop reading as one sentence
**Decision.** The second live reply in my drafts was rewritten to the 150-word ceiling: 330 words
down to 148, at 9.9 words a sentence, with the full signature swapped for the short one.
**Why.** Yasmin asked one thing, in 62 words: is this a wider video or a standalone clip. The draft
answered it in the first line and then spent 300 more words on the audience share, the reasoning
for asking my, and a verbatim restatement of the question I had already quoted back in my own
reply. The restated question alone was 38 words of second telling.
**What changed.** The draft. Also `scripts/email-html.mjs`: a bullet has no full stop, so a list
was being glued into one 41-word "sentence" and reported as a fault it was not. Each bullet is now
its own unit.
**Evidence.** Gmail draft on thread `1a07cd48c21cd02e`, 0/100 on `ai-tells.mjs`.
**Status.** live

### 2026-09-12  rewriting a threaded draft means create and trash, not update
**Decision.** `update_draft` is only used on a cold email. To change a reply, `create_draft` with
`replyToMessageId` and then `trash_message` on the old one.
**Why.** `update_draft` has no `replyToMessageId` field, so updating the North Atlantic reply moved
it onto a thread of its own. It kept the `Re:` subject and lost the quoted history, which means it
would have sent as a fresh email. The only visible sign was the `threadId` in the response changing
from `1a07cd483b4e99e0` to the draft's own id. Caught and corrected in the same session.
**What changed.** A warning block in `.claude/skills/draft-email/SKILL.md` under Threading. The
detached draft was trashed and a correctly threaded one created.
**Evidence.** `list_drafts` on `northatlanticbooks` returns one draft, `threadId
1a07cd483b4e99e0`.
**Status.** live

### 2026-09-12  the Project Brief is drafted two weeks early, and the outcome list is over-supplied on purpose
**Decision.** The CP193 Project Brief due Saturday 26 September is drafted in full at
`capstone/PROJECT-BRIEF.md`, carrying 26 HCs and 8 College LOs against caps of 25 and 10, to
be cut down after the first committee meeting rather than padded up to the minimum.
**Why.** It is 10% of the year and the first graded thing in it. The handbook scores this
assignment on `#cp-navigation` for the plan rather than the document, and on
`#cp-outcomeanalysis` for the HC and LO descriptions, so the expensive part is the outcome
list and the definition of success, neither of which improves under deadline. Drafting early
turns the 26th into an edit.
**What changed.** The College LOs are now real hashtags read off my Outcome Index rather
than placeholders: `#ah113-designforwhom`, `#ah113-designlogics`, `#ah113-designagents`,
`#ah166-produceart` on the Arts and Humanities side, and `#cs130-decisiondesign`,
`#IL181003-FoundationalDeepLearning`, `#cs110-ComputationalCritique` plus one statistics LO
on the Computational Sciences side. Section 3 states a falsification condition before the
data arrives. Five questions are written for the first committee meeting, including the one
that matters most, which is where the advisor draws the line between prior work and capstone
work.
**Decided and NOT acted on, recorded because the handbook asks for these by name:** the main
folder is still not organised, and the Cover Sheet itself cannot be copied without my, so
section 10 of the brief is an open item rather than a finished one.
**Evidence.** `capstone/PROJECT-BRIEF.md`, `capstone/CAPSTONE-PLAN.md`, `capstone/hc_lo.txt`,
`Capstone Handbook 2026-2027.pdf` Week 3 section.
**Status.** live.

### 2026-09-11  the nuuko repo carries its own context, and the pre-pivot docs are marked superseded
**Decision.** The seven context files a session needs to change Nuuko now live in
`nuuko-v1/about-nuuko/`: `README.md` (the index), `the-product.md`, `the-evidence.md`,
`build-order.md`, `the-law.md`, `the-business.md`, `how-people-arrive.md`. The three
pre-pivot documents are kept and banner-marked superseded rather than deleted.
**Why.** Every product document in that repo was written for the journaling app, and
after the person pivot each one described a product that does not exist: streaks, a
mood picker before writing, an insights preview behind a sign-up wall, and "create an
account to see the bigger picture". All four now have evidence against them. The
repo's own CLAUDE.md contradicted itself on the same page, opening with the person
pivot and then defining Nuuko two screens later as "an emotion-centered journaling web
app for Gen Z". A session reading top to bottom would have taken the second one,
because it sat under the heading Project Overview. The research, the strategy and the
legal constraints existed only in the riadms repo, so anything about what the law
allows to be built was one directory away from the code that has to obey it.
**What changed.** Seven new files in `nuuko-v1/about-nuuko/`; superseded banners on
`what-is-nuuko.md`, `prd.md` and `site-structure.md`; a delta at the bottom of
`text-and-voice.md` retiring the streak card, the mood mix card and the account-gate
copy; `CLAUDE.md` project overview rewritten and pointed at the folder. One real
correction found on the way: the design system said stone was `#8D877E` in two places
while the CSS has used `#635E5A` since it was darkened for 4.5:1 contrast on cream,
so both documents now say the live value and why.
**Evidence.** `nuuko-v1/about-nuuko/README.md` for the index and the read order.
`node scripts/ai-tells.mjs` passes on all seven at 1/100, HUMAN_ONLY.
`node scripts/smoke.cjs` exits 0, unchanged, because nothing under `public/` or `api/`
was touched.
**Status.** live

### 2026-09-11  the entries are ciphertext at rest, and the flag said they were not
**Decision.** Strategy section 4 is settled: the 349 rows in `entries` are AES-GCM
ciphertext, and the coach never had plaintext to read. The `encrypted` column is
false on every one of them, so a migration sets it to true where the bytes are
base64, and the code keeps its content sniffing as the second line.
**Why.** Counted without reading a word of anyone's journal: 349 of 349 rows match
`^[A-Za-z0-9+/=]{40,}$`, 0 have `encrypted = true`. `encryptEntry` sets the flag
and `sync.js` writes `clientEntry.encrypted || false`, so the flag was lost somewhere
in the earlier client; today's code writes it. The privacy claim the pivot is built
on holds at rest. The coach could not have been reading entries, which also means
the coach has been useless for every synced user, not dangerous.
**What changed.** `nuuko-v1/supabase/migrations/005_mark_ciphertext_entries_encrypted.sql`,
written and **not applied**. The full-text index on `entries.content` indexes
ciphertext and can go when the search question in strategy 3.3 is answered.
**Evidence.** The count query, and `public/scripts/encryption.js` line 241.
**Status.** live as a finding; the migration waits on my hand (see next entry).

### 2026-09-11  the tester numbers, read off the database this time
**Decision.** Quote the database, not the ledger: 25 accounts, all Google sign-in,
17 of them ever synced an entry, 349 entries, and the last entry was 15 April 2026.
By month: December 47 entries from 9 writers, January 169 from 10, February 78 from
8, March 43 from 6, April 12 from 3.
**Why.** The plan says the 40 per cent retention figure and the tester count have no
primary source. This is a primary source, with the caveat that local-only users
never appear in it, which is most of them by design. It is a floor, not the number.
**What changed.** Nothing yet. `src/data/nuuko.ts` and the capstone brief should carry
these with the caveat attached.
**Evidence.** Counts over `users`, `entries`, `auth.users` on 2026-09-11; no content
read.
**Status.** live.

### 2026-09-11  two safety faults fixed on the way through
**Decision.** Encryption failing during sync now throws instead of sending the
entry as plaintext, and the coach excludes encrypted rows in its query and again
in code before anything reaches Gemini.
**Why.** `syncService.js` had a catch that logged "sending unencrypted" and
carried on, which is a downgrade nobody asked for. `api/coach.js` read every row
regardless of the encrypted flag, so a synced user's coach was reading base64.
The honest fix for the coach is client-side decryption with per-request consent;
this is the stop-gap that makes the current behaviour truthful.
**Evidence.** `public/scripts/syncService.js`, `api/coach.js` on the branch.
**Status.** live.

### 2026-09-11  the letters feature is prototyped and tested, not launched publicly
**Decision.** The friend layer is designed, built and tested with a closed consented
group during the capstone year. It does not ship to the public store as an open
feature until someone with authority says the compliance position is sound.
**Why.** A friend-to-friend letters feature is a regulated user-to-user service under
the UK Online Safety Act from the day it ships. There is no size exemption, in-app
text messaging is not in the Schedule 1 exemptions, and all four compliance deadlines
passed between March and July 2025. Penalties run to £18 million or 10% of worldwide
revenue with criminal liability for senior managers on child-safety enforcement
notices. My measured audience is 16.8% aged 13 to 17, which is also the COPPA
exposure that cost Path $800,000 and twenty years of assessments. Under the DSA I
would be a hosting service, and the micro enterprise exemption in Article 19 covers
Section 3 only, so Articles 11, 12, 14, 16 and 17 still apply including notice and
action with no size exemption.
**What changed.** Strategy 3.5a. The spring plan becomes a prototype plus a consented
test plus a written risk assessment, which is a complete work product and better
evidence than a public launch with none.
**Evidence.** `research/08-legal-and-social-risk.md`.
**Status.** live, and it is mine to overrule.

### 2026-09-11  Day One's sharing invariants are adopted wholesale
**Decision.** If sharing is built it copies Day One exactly: a separate container
rather than a toggle, per-journal keys separate from the personal key, a 30 member
cap, invite links that expire after 14 days with owner approval, entries that move in
and never out, and the invariant that no entry in a private journal can ever become
shareable.
**Why.** The most careful company in the category has already solved this and
publishes the mechanics. Adopting them costs nothing and removes the highest
consequence failure mode in the product, which is a private entry becoming visible.
**Evidence.** `research/08-legal-and-social-risk.md` section 6.
**Status.** live.

### 2026-09-11  Nuuko stops being a journaling app
**Decision.** The positioning changes to "where you work out what you feel about one
person". The word journaling comes out of the pitch, the onboarding and the video
titles.
**Why.** The word journal appears zero times in 745 of my YouTube comments. So do
wellness, self care and mindful. What the comments do instead is ask what to call a
feeling about one specific person, at length. Nobody is asking for a journal and a
product sold as one is answering a question nobody asked.
**What changed.** `capstone/NUUKO-STRATEGY.md` section 1. The competitor set, which
is now Paired rather than Day One.
**Evidence.** `capstone/research/04-my-audience.md`.
**Status.** live.

### 2026-09-11  the friend layer is letters, not a feed, and it is capped
**Decision.** The social layer is a written letter, delayed, to a small closed set of
people, with a structured reply rather than a text box. No feed. No thread. No read
receipts.
**Why.** Two independent lines of evidence. Zelic et al. (2017) is the only
experiment on the question and found open venting harmed while structured problem
solving did not, and co-rumination raises friendship quality and symptoms together,
so engagement alone cannot measure success. Separately the app graveyard says the
same: BeReal peaked at 73.5M monthly users with 9% ever opening it daily and sold for
€500M with no revenue, now worth €30M, while Locket survives at 9M DAU, profitable,
with a 20 friend cap.
**What changed.** Strategy 3.5. The shared relationship journal becomes a separate
object that can never be produced by toggling a private entry.
**Evidence.** `research/02-relationship-and-letters-apps.md`, `research/03-literature.md`.
**Status.** live.

### 2026-09-11  mood labelling moves after the writing, and is never sold as regulation
**Decision.** The mood or colour is collected after an entry, for filing and
retrieval. It never sits before a reframing prompt.
**Why.** Ariely et al. (2026), two preregistered studies, N = 226: labelling alone did
not reduce distress, increased unpleasantness at d = .77 and .51, and cancelled the
benefit of reappraisal when it came first. Nook et al. (2021) found the same
direction.
**What changed.** Strategy 3.2. This overturns a mechanic that is in the shipped app.
**Evidence.** `research/03-literature.md`.
**Status.** live.

### 2026-09-11  the prompts are replaced with my own 200 questions
**Decision.** Every generic prompt comes out. Three prompt types only: the concrete
noticing prompt, the observer perspective prompt, and the seven kinds prompt.
**Why.** The app currently ships "what are you grateful for right now?", which is
exactly what my own competitive analysis says makes the category interchangeable.
Meanwhile 200 questions written to my voice about specific people already exist in
`products/seven-kinds/QUESTIONS.md`, and part zero is literally the onboarding for a
person-filed journal. On the prompt types: Watkins shows abstract why-processing is
what harms ruminators and concrete what-happened processing removes it, and observer
perspective reappraisal is the best supported prompt in the literature at g = -0.26
across 48 studies.
**Evidence.** `research/03-literature.md`, `research/06-what-nuuko-is-today.md`.
**Status.** live.

### 2026-09-11  the archive gets the engineering, not the editor
**Decision.** Re-read surfaces, free permanent export and client side search are
first class. The archive is never behind the paywall.
**Why.** Across roughly 2,500 reviews of the three most different apps in the
category the most praised feature is re-reading, and people quit when an app loses or
locks their entries. Two beliefs died with it: streaks are not the churn mechanism,
and polish does not retain (Wasil 2022 found quality scores predict downloads and
revenue but not retention at any horizon).
**Evidence.** `research/01-journaling-market.md`.
**Status.** live.

### 2026-09-11  streak milestones come out of the character
**Decision.** No streak art at 3, 7 and 14 days. The character reacts to the return,
never to the count, and it becomes person aware instead.
**Why.** The shipped `characterActions.js` picks its illustration from streak length,
time of day, season and three keyword themes: cat, workout, work. It notices a cat
and does not notice a person. The README already says aggressive streaks made users
feel guilty, and the market research says streaks are not what makes people churn
anyway, so there is nothing to be gained by keeping them.
**Evidence.** `research/06-what-nuuko-is-today.md`, `research/01-journaling-market.md`.
**Status.** live.

### 2026-09-11  no revenue projection may be built from audience size
**Decision.** Audience size is banned as an input to any financial projection in this
capstone.
**Why.** MKBHD launched Panels to 20 million subscribers, hit number one in photos on
both stores, and shut it down fifteen months later on about $95,000 of lifetime
spend. That is $0.0048 per subscriber, which at 10,300 subscribers is about $49
lifetime. The counter case is Thomas Frank, $1,000,508 in a year off a 110,000
subscriber niche channel while sitting on a 2.9 million subscriber one.
**Evidence.** `research/05-business-model.md`.
**Status.** live.

### 2026-09-11  installs come from long form, not from Shorts
**Decision.** The app is introduced in long form videos only. Shorts advertise the
channel, not the product.
**Why.** Measured 90 days: Shorts produced 480,505 views and 47,467 minutes, which is
5.9 seconds of attention per view, while the subscriber feed produced 1,048,272
minutes, 72% of all attention. And my six journaling long forms get 312 to 936 views
yet convert at 8.65 likes per 100 against my 4.21 average, ranking first of 32 on
subscribers per thousand. The smallest videos convert best.
**Evidence.** `research/07-the-channel-numbers.md`, `research/04-my-audience.md`.
**Status.** live.

### 2026-09-11  two numbers are suspended until they have a source
**Decision.** The ~40% retention figure and the "100+ beta testers" figure are not
used in any capstone document, resume or pitch until a primary source is found or
they are replaced.
**Why.** The retention number has no primary source in either capstone docx, the
README or any analytics file, and "retention" means three incompatible things across
the sources, so it cannot be compared to anything. Median 30 day retention across 93
real world mental health apps is 3.3%, so a 40% claim is extraordinary and will be
challenged. The 59 figure is a post-MVP survey respondent count and not a tester
count. Separately, `src/data/nuuko.ts` claims ~840,000 views a quarter and 96%
unsubscribed, and the measured quarter is 1,459,685 views at 94.3% unsubscribed.
**What changed.** `research/07-the-channel-numbers.md` records the measured figures.
**Status.** live, and the fix is not yet made in `nuuko.ts`.

### 2026-09-11  the encryption and AI contradiction is settled before anything is built
**Decision.** No new feature work starts until one runtime check settles whether
synced entries are ciphertext at rest.
**Why.** `syncService.js:539` encrypts every entry before upload. `api/coach.js`
reads entry content out of the database, keyword matches it and sends it to Gemini,
and `schema.sql:77` puts a full text index on the same column. End to end encryption
and a server side coach that reads entries cannot both be true, and the social layer
has to be built on whichever answer is real.
**Evidence.** `research/06-what-nuuko-is-today.md`.
**Status.** open. This is the next action.

### 2026-09-11  the journaling lane becomes a diagnostic series, not journaling videos
**Decision.** The journaling lane on the channel is filmed as a recurring named
diagnostic series about one specific person, crush first, and the word journaling stays
out of every title. The series doubles as the capstone's recruitment surface and its
prompt corpus.
**Why.** My ask was whether crush and relationship journaling is working. Measured on
2026-09-11 with `yt-dlp` against live YouTube: prompts sold as prompts are small, and
the same prompts sold as questions about a person run 45,317 to 1,850,863. The
`journal with me` lane is stationery creators at 3,000 to 40,000, which is the lane my
four flops were aimed at. The closest analog channel, Oddly Specific Crystal, sits
around 56,000 on diagnostics, and its one journal-titled video is below its own median.
My own six journaling videos already convert best on the channel and reach worst, so
this is packaging and not content.
**What changed.** `JOURNALING-LONGFORMS.md` addendum with the measured table and the
four episodes. `src/data/nuuko.ts` gained LANE, LANE_ROWS, ANALOG, SERIES, SETUP and
LANE_HONEST, rendered on `/nuuko`. Nothing filmed yet.
**Evidence.** `JOURNALING-LONGFORMS.md` addendum 2026-09-11, `/nuuko` on the studio
deploy, `src/data/nuuko.ts`.
**Status.** live. Extends 2026-09-04, which reached the same conclusion from my own
numbers alone.

### 2026-09-11  the series name and the Nuuko hand-off are the two things blocking it
**Decision.** Nothing in the series gets filmed until I pick a series name, and every
episode ends at `/which-one-is-this` handing into Nuuko, which is move 01 and still not
built.
**Why.** The analog channel's twenty-five videos are recognisable as one thing because
the name is in every title, and ria has no series name on anything. And without the
hand-off the lane produces a good engagement number that goes nowhere, which is exactly
what the existing six journaling videos did.
**What changed.** Recorded as a decision, not acted on. The hand-off has been on the
plan since 2026-09-02 and has not moved.
**Evidence.** `src/data/nuuko.ts` MOVES 01 and SETUP.
**Status.** live, blocked on my.

### 2026-09-11  the capstone becomes the venture, not just the app
**Decision.** CP193 and CP194 cover one thing: the channel, the software behind it,
and Nuuko, as a single venture in the niche of human connection. Nuuko v2 is the work
product, the packaged content engine is its second half, this repo is the process
documentation.
**Why.** My call, agreed with my advisor. The two halves are causally connected and
almost nobody has both: the channel is distribution with nothing to send people to,
and the app is a product with no distribution.
**What changed.** `capstone/CAPSTONE-PLAN.md` written. A capstone branch added to the
desk. This log started.
**Evidence.** `capstone/CAPSTONE-PLAN.md`, `src/data/threads.ts`.
**Status.** live. Supersedes 2026-08-16.

### 2026-09-11  the midterm slot goes to the app pivot, not the engine repo
**Decision.** The 31 October midterm deliverable is Nuuko filing entries by person
rather than by date, live and tested with 10 to 15 people. The public engine repo
moves to weeks 9 to 14.
**Why.** The pivot changes the data model, so everything else waits behind it, and
the midterm is the right place to find out it is wrong. The engine repo is the safer
piece and a worse use of a slot that exists to de-risk.
**What changed.** Plan section 10.
**Evidence.** `capstone/CAPSTONE-PLAN.md` §10.
**Status.** live, pending advisor confirmation.

### 2026-09-11  the ML privacy claim gets corrected before it is defended
**Decision.** The sentence in the mini capstone saying the ML layer runs entirely
client side with no external API calls gets rewritten to say which feature runs
where.
**Why.** Reading `nuuko-v1` shows both are true of different things. The emotion
classifier is genuinely on device at `public/client-model/emotions.onnx` with
onnxruntime. The coach is Gemini 2.5 Flash in `lib/gemini.js`, which sends text to
Google. A second reader finds that in one grep.
**What changed.** Nothing in the code. One paragraph in the plan, and the social
layer is now designed against the real architecture.
**Evidence.** `nuuko-v1/public/client-model/`, `nuuko-v1/lib/gemini.js`,
`nuuko-v1/api/coach.js`.
**Status.** live.

---

## Backfill, reconstructed from the repo

Written on 11 September 2026 from files that were dated at the time, not from
memory. Each entry names where it was read. Anything that could not be dated from a
file is left out rather than guessed.

### 2026-09-10  the tester number is 30 to 40, not 100 plus
**Decision.** The true beta tester count is ~30 to 40. Every document saying 100+ is
wrong.
**Why.** My own correction, said out loud. The ledger and six resumes carried the
larger number, and it is the one an interviewer or a second reader asks my to break
down.
**Evidence.** `src/data/nuuko.ts`, `NUUKO_FACTS`.
**Status.** live, and not yet propagated everywhere. See the plan, section 9.

### 2026-09-03  every long-form clears 8:30, targets 12 to 18 minutes
**Decision.** A hard floor on the delivered file, and a target band.
**Why.** 63 per cent of my views were on videos too short to carry a mid-roll, five
videos missed the line by 18 to 58 seconds, and the 12 to 18 band delivers 4.64
minutes watched per view against 3.61 for 8 to 12. Short form is exempt and still
gets filmed, because it is the advertising and is not supposed to earn.
**Evidence.** `CLAUDE.md` rule 17, `RPM-AND-REVENUE.md`.
**Status.** live.

### 2026-08-31 to 09-08  fourteen scheduled jobs were dead and nothing said so
**Decision.** A doctor that reads launchd's own exit codes and log freshness, running
itself every morning.
**Why.** macOS re-stamped the identity owning files in `~/Documents`, launchd opens a
job's log before starting the program, so a job with an unopenable log never ran and
could not report it. The only visible symptom was a missing comment under one video.
**Evidence.** `scripts/employees-doctor.mjs`, `EMPLOYEES.md`.
**Status.** live. This is the worked example for the proposed `#silentfailure`
custom LO.

### 2026-08-30  twenty Shorts a month, and read the last batch first
**Decision.** A gate that counts the month off YouTube, refuses until the previous
batch has been read, and retires any lead hashtag with 8+ posts and a median under
500 views.
**Why.** August published 108 Shorts and 46 of them finished under 500 views, while
net subscribers per 28 days fell from 2,715 in May to 963 in August. No job did that.
It accumulated because every session that could make Shorts made Shorts and none
could see what the last one shipped.
**Evidence.** `scripts/shorts-budget.mjs`, `CLAUDE.md` rule 16.
**Status.** live. The worked example for the proposed `#audienceinstrumentation`
custom LO.

### 2026-08-16  keep Nuuko as the capstone, build the video tool as a business
**Decision.** At the time: do not merge the two. Different vehicles.
**Why.** The switching cost was real two weeks before CP193, and a capstone inherits
a school calendar that a business does not respect.
**Evidence.** `job-apps/grad-school/capstone-decision.md`.
**Status.** **superseded 2026-09-11.** I and my advisor merged them. The risk that
document named is still the live risk, and it is handled by framing rather than by
separation: see the plan, section 3.

### 2026-08-14  the carousel is dropped
**Decision.** No more Instagram carousels.
**Why.** My call.
**Evidence.** the ig-queue slot array, not the run prompt, which still asks for one.
**Status.** live.

### 2026-08-08  short form is exempt from the essay-channel rules, and the look is Playfair
**Decision.** On reels and Shorts, text may repeat what I say, the grade is a
variable, the music is open. I picked Playfair Display by looking at renders over
my own footage.
**Why.** The essay rules were written for a ten-minute horizontal video and forbid the
exact devices the reels I want to imitate are built from.
**Evidence.** `CLAUDE.md` rules 9 and 10, `scripts/lib/looks.mjs`.
**Status.** live.

### 2026-08-08  the new machine, and the three repairs that are easy to reintroduce
**Decision.** ffmpeg-full rather than ffmpeg, a pinned interpreter for anything using
Apple Vision, and fonts installed system-wide and then verified by asking libass
itself.
**Why.** Three separate faults on one day each stopped the pipeline dead, each was
silent until minutes into a render, and each is one line in `doctor.sh`.
**Evidence.** `scripts/doctor.sh`, `scripts/install-fonts.sh`.
**Status.** live.
