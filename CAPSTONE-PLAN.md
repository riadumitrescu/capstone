# Capstone: the map

Written 2026-09-11, after she said the capstone is now the venture: the YouTube
channel and everything behind it, plus Nuuko, as one business in one niche.

Advisor: Prof Gloria Tam. Track: independent and self-designed, weighted to
Computational Sciences. Design is not a major or a minor, which changes the LO
arithmetic below.

Read this first. `Capstone Handbook 2026-2027.pdf` is the rules. This file is what
the rules mean for her project, what is already built, and what happens next.

Sources read, not remembered: the handbook (all 37 pages), Prof Sheskin's three
emails (1, 9 Sep and 17 Aug), `Nuuko_Mini_Capstone_FINAL (3).docx` (the CP192 mini),
`CP191 assignmet 3 - process documentation.docx`, `src/data/nuuko.ts` (the product
plan already on her site), `job-apps/grad-school/capstone-decision.md`,
`job-apps/profile/master-profile.md`, and this repo.

---

## 1. What is actually required

Four parts to a finished capstone:

1. **Three summaries.** Executive summary, one page, general audience, at least one
   visual. Academic abstract, max 250 words, target 150 to 200, no pictures.
   **Capstone video**, about 10 minutes, technical, for the committee. First
   submission is Fall week 15, revised in spring, cut to 3 minutes for Manifest.
2. **The work product.** One focused thing with a real-world audience and no
   Minerva jargon in it.
3. **The process documentation.** Usually longer than the work product. Navigation,
   AI use, HC and LO descriptions, timeline, the dead ends.
4. **Manifest (CP195, May).** A class she designs and teaches about it.

**The outcome arithmetic, which is the thing she asked about.** The minimum is
**24 outcomes**:

| what | how many | notes |
|---|---|---|
| HCs | **15 to 25** | described in detail. Must almost certainly include `#professionalism` and `#organization` |
| College LOs | at least 5 (5 to 10) | At least 5 from any college, and at least 2 from each major she has. She has one independent track, weighted to Computational Sciences, and design is not a major, so no second major sends two. The brief carries 4 from Computational Sciences, 2 from courses taken in other colleges, and 3 custom, which count toward the same total. Three more in reserve |
| Capstone LOs | **4** | `#qualitydeliverables`, `#outcomeanalysis`, `#navigation`, `#curation` |

**The four capstone LOs are what she is graded on.** Every assignment is scored on
those four, and HC use is now clustered inside them. Specifically: the HC work lands
inside **`#outcomeanalysis`**, which the handbook defines as identifying and using
appropriate measures and rubrics. So the HC and LO list is not paperwork sitting
next to the project. It is one quarter of the grade.

M27 has no time-travelling HC scores, so an HC score here does not touch her Year 1
transcript. It still sets the capstone grade.

**Custom LOs are allowed and they count toward the 5.** Drafted in the fall,
reviewed and approved by **end of spring week 7**. Guidelines are linked in
Appendix A of the handbook. Proposed ones are in section 6 below.

**Human subjects.** Anything that collects information from living people goes
through Minerva's HSR committee. Her mini capstone already ran a 25 person survey,
three interviews and a 59 person post-MVP survey, and the new plan needs more. This
is a gate with a queue in front of it, not a formality. See section 9.

---

## 2. The dates

Week 1 was the week of 7 September 2026 (Prof Sheskin's 9 September email says
"Week 1"). Everything below is computed from that and **should be checked against
myMinerva** before anything is planned around it. Fall holidays are weeks 6 and 12.

| week | date | what | weight |
|---|---|---|---|
| 1 | Sep 7 to 13 | advising group meeting, be in contact with advisor | |
| **3** | **Sat 26 Sep** | **Project Brief** | 10% |
| 4 to 5 | early Oct | first committee meeting, 30 min, 5 to 10 min deck | ungraded, but feeds `#navigation` |
| 7 | Oct 19 | advising group meeting | |
| **8** | **Sat 31 Oct** | **Midterm Deliverables**, one substantial finished piece | 10% |
| 11 | Nov 16 | 1:1 check-in | |
| **14** | **Fri 11 Dec** | **Full Draft**, every section present even if bracketed | 15% |
| **15** | Dec 14 to 18 | **Fall Oral Defense** plus the 10 minute capstone video, uploaded 48h before | 5% |
| spring 3 | | Revision Plans | 10% |
| spring 8 | | Revised Full Draft | 10% |
| spring 10 | | Oral Defense | 10% |
| spring 12 | | **Final Capstone** | 30% |

Firm deadlines, 24 hour submission window, and missing one is a 0 on every HC and
LO attached to it. Spring carries 60% of the grade.

Weekly: **12 hours**, plus the Thursday async check-in form due Saturday end of day
UTC, plus co-working sessions. The check-in form is not admin. It is the raw
material for the process documentation, which is graded, so filling it in badly is
throwing away `#navigation` marks.

---

## 3. The framing, and the one risk in it

She wants one project: the channel and its software, plus Nuuko, as a venture in the
niche of human connection. Her advisor is on board. That is the decision, and the
work below is built on it.

**The risk to handle, not to argue about.** The handbook wants one narrow work
product with a real-world audience, separated from all the process behind it. A
capstone that is two products reads as two capstones, and `#curation` is the LO that
punishes exactly that. The fix is not to drop a half. The fix is that the work
product is **one thing with two halves that are causally connected**:

> **A vertically integrated consumer venture: an audience engine that reaches about
> 840,000 people a quarter, and a product it feeds them into.** The claim being
> tested is that owning both halves converts attention into retained users at a rate
> a normal app cannot buy.

That sentence is what makes it one project. Nobody else building a journaling app
has the distribution; nobody else with the distribution owns the product. The link
between them is the capstone, and the funnel is measurable, which hands
`#outcomeanalysis` something real to measure.

**Say what each piece is:**

| piece | role in the capstone | who the audience is |
|---|---|---|
| Nuuko v2, person-filed and social | **the work product** | its users |
| the content engine (this repo, packaged) | **the work product's second half**, the distribution, shipped as an open source tool other creators can run | creators |
| everything else in this repo | **process documentation**: how the system was built, what broke, what was cut | the committee |

**What the channel numbers are for.** They are not a vanity slide. They are the
evidence that the distribution half works, and they are already instrumented.

---

## 4. What already exists, and what it counts as

This matters because `#qualitydeliverables` asks what a year of 12 hour weeks looks
like, and because work done before September is **prior work**, not capstone work.
Be honest about the line. Ask the advisor where they draw it.

**Already built, before the capstone year:**

- Nuuko v1, live at nuuko.app. Vanilla JS, IndexedDB, AES-GCM client side, Vercel
  functions, Supabase, offline PWA. A Tiny Transformer, 4.2M parameters, distilled
  from a multitask BERT teacher, 0.89 validation accuracy, running on device.
- The research behind it. 25 person survey, 500+ coded app store reviews, three
  interviews with co-design moodboards, thematic analysis in Dovetail, a 59 person
  post-MVP survey. 78% first entry completion against 31% for a blank page control.
- This repo. 2,597 commits, 319 node scripts, 56 shell scripts, 79 skills. A cutting
  engine, a caption and overlay system, an ML matte pipeline through Apple Vision, a
  scheduler posting to Instagram, TikTok, YouTube and a podcast feed off R2, a
  launchd fleet of 14 jobs with its own doctor, and a measured house style with
  numeric gates on length, repetition and Shorts volume.

**To be built during the capstone year:** section 7 and 8.

The honest framing for the brief: the venture exists, the capstone year is the year
it is connected, launched and measured. That is a stronger story than pretending it
starts from zero, and it is the truth.

---

## 5. Model deliverables

`#qualitydeliverables` explicitly asks which real-world work she is aiming to match.
Name them in the brief, say what makes each one good, and say which parts she is
matching.

**For the app:** Finch (cosy, emotionally safe, enormous retention), How We Feel
(research-backed, free, built by a foundation, emotion-granularity as the core idea),
Day One (the polish bar), Stoic. For the social layer: Locket and BeReal for the
friend-shaped mechanic, Marco Polo for the letter-shaped one.

**For the engine:** Remotion (programmatic video, the closest real analogue to what
this repo is), auto-editor, yt-dlp, and Descript and Opus Clip as the commercial
versions. Remotion is the one to study, because it is the model of how to package a
programmatic video system so strangers can run it.

**For the venture writeup:** the handbook says a capstone should look like a
professional piece of work in her field, not something unprecedented.

**And the AI question, which the handbook asks directly.** She uses AI heavily and
visibly. The handbook's third option is the honest one: work that benefits from AI,
where skilful use of it is part of what is documented, at a scope larger than a 2020
capstone. This repo is an unusually good artifact for that, because it contains the
rules that were learned the hard way about where AI fails, written down at the time,
with the failures attached. `LEARNINGS.md` and the 100 or so memory files are
process documentation that already exists and was not written to be graded.

---

## 6. The outcomes: HCs, LOs, custom LOs

### The measures that are not HCs

The handbook asks for the outcomes she actually cares about, quantitative and
qualitative, clear enough that a third party could evaluate her. Proposed:

**Quantitative, the funnel.** Every one of these has a baseline already measured.

| measure | baseline | target by May |
|---|---|---|
| channel to app: installs attributable to the channel | 0, there is no link in either direction today | a real number, set after the first month of data |
| first entry completion | 78% Nuuko vs 31% control | hold above 70% with the person-filing step added |
| retention | ~40% (against ~12% estimated industry) | hold at 40% with 10x the users |
| entries filed to a person | new | over half of entries |
| social: users who send one letter | new | set after first test |
| long-form delivered length | 5 videos missed 8:30 by 18 to 58 seconds | 100% over 8:30, median in the 12 to 18 band |
| minutes watched per view | 3.61 in the 8 to 12 band, 4.64 in 12 to 18 | above 4.6 |
| net subscribers per 28 days | 963 in August, down from 2,715 in May | back above 2,000 |
| the engine as a tool | nobody outside has run it | 3 to 5 creators run it end to end and report back |

**Qualitative.** One: a stranger who has never seen the channel can install the app,
write one entry and describe what it is for, unprompted, in one sentence. Two: the
process documentation lets a reader rebuild the pipeline's architecture without
opening the code.

### HC candidates

Twenty two, drawn from the official HC list. Each needs a planned application in the
brief, phrased as intent, then updated with what actually happened. These are
candidates, not the final list. Cut to 20 after the advisor meeting.

**Required**

- `#professionalism`: firm deadlines, committee meetings, the weekly check-in, and
  the standing rule in this repo that a shipped thing is verified by looking at what
  the viewer sees rather than at an exit code.
- `#organization`: the repo, the working pages, the desk, and the curation of 2,597
  commits into a readable process document.

**Navigation and project management**

- `#breakitdown`: the work breakdown for a two-product year on 12 hours a week.
- `#strategize`: sequencing the app pivot ahead of everything downstream of the
  data model.
- `#responsibility`: the parts done alone versus with an advisor, TAs and testers.
- `#selfawareness`: the planning fallacy, documented against her own August record
  of publishing 108 Shorts when the budget was 20.
- `#constraints`: 12 hours a week, one encoder, an F-1 visa, a Hobby tier that
  suspended the media store for two days.
- `#gapanalysis`: the gap between what the app does and what the research said
  people need.
- `#rightproblem`: the pivot from "people forget to journal" to "people cannot see
  what they feel about a specific person".
- `#purpose` and `#audience`: the three summaries, each for a different reader, and
  the split between work product and process documentation.

**Research and evaluation**

- `#hypothesisdevelopment`: person-filing raises retention, stated before building.
- `#testability`: defining what would falsify it before the data arrives.
- `#comparisongroups`: the blank-page control already used, and the A/B design for
  the person-filing feature.
- `#sampling`: who the testers are, and the fact that they are drawn from an
  audience that is 51% women and 41% under 25, which is a sampling frame, not a
  neutral population.
- `#biasidentification`: recruiting testers from her own audience selects for people
  who already like her.
- `#descriptivestats`, `#significance`, `#confidenceintervals`: the retention and
  completion numbers, reported with intervals rather than as headline percentages.
- `#interviewsurvey`: the instruments, and what was wrong with the first ones.
- `#sourcequality`: the literature behind expressive writing, and the AI-generated
  syntheses in the mini capstone, which need re-checking against primary sources.

**Building**

- `#algorithms` and `#optimization`: the cutter, the on-device transformer, the
  distillation that bought 15 points of accuracy.
- `#modeling` and `#systemmapping`: the pipeline as a system with silent failure
  modes, and the doctor scripts written to see them.
- `#designthinking`: emotional friction as the design constraint.
- `#ethicalconsiderations`: a social feature on a private journal. People will write
  about people who did not consent to being written about. This one is real and it
  should be argued in the work product, not just tagged.
- `#dataviz`: Wrapped, and the figures in the capstone document.

### College LOs

**[NEEDS: her LO catalogue.]** These have to be the real hashtags and rubrics from
the courses she took. The handbook points at the Outcome Index and a student-kept
sheet. Give me the course list or the sheet and this section gets filled in
properly. The shape it has to satisfy:

- 2+ from **Arts and Humanities / Design Across the Humanities**. Likely sources:
  Human-Centered Design, HCI, Interaction Design, Visual Design, Prototyping, UX
  Research, Marketing and Product Design.
- 2+ from **Computational Sciences / Data Science and Statistics**. Likely sources:
  Formal Analyses, Statistics, Data Visualization, Data Analytics, the ML course.
- 1+ from anywhere.

### Custom LOs, proposed

Four, rewritten 2026-09-22 after she asked for ones that come out of what she actually
built. Each has a rubric a third party could score from. The full text is in the
Project Brief, section 7.

1. `#silentfailure`: verification that checks the artifact a person will see rather than
   the success signal a step reports. Evidence: nine days of dead launchd jobs where the
   thing that failed was the logging (exit 78), twelve videos uploaded from the wrong
   folder with every check green, and a preview tool that drew YouTube's duration badge
   at a quarter of its real size. Scored on whether each stage checks its own output,
   whether a check's model of the world was measured or guessed, whether the check
   predated the fault, and whether a shipped fault produced a new check.
2. `#voicefidelity`: measuring one person's writing as a distribution and holding
   machine-assisted text to it, rather than trying to detect machine writing. Evidence:
   the detector was the wrong question, because her most conversational pages score most
   machine-like; `her-voice.mjs` measures against 54,469 words of manuscript and 72,145
   published, two registers apart, and found the contraction gap of 28,969 per million
   against 2,232.
3. `#autonomyboundary`: deciding where automation stops and a person has to look, and
   writing that into the system. Evidence: 30 scheduled jobs each with a written line
   saying what it may not do, the split between jobs that make judgements and jobs that
   do not, emails that only ever become drafts, and a Shorts gate that exits non-zero
   rather than advising, because advice in a file is what let 108 go out against 20.
4. `#guaranteepreservation`: adding a capability without weakening a guarantee the system
   already makes. Evidence: the circle built beside the local-first journal rather than
   on top of it, plus two real faults, sync sending plaintext when encryption threw and
   the coach sending encrypted rows to Google, and one wording fault in the mini capstone.

**Two that were dropped, and why.** `#audienceinstrumentation` is already the worked
example under `#cs130-decisiondesign`, so it would mark the same work twice.
`#emotionalsafety` sits close enough to `#designthinking` that it is better argued there.

---

## 7. Nuuko v2

The product direction is already written and already on her site at `/nuuko`
(`src/data/nuuko.ts`). Short version: **file entries by the person they are about,
not by the date.** "Every journaling app asks how your day was. Nuuko asks who it
was about." A book per person on the shelf instead of a book per month.

Her new addition, from this conversation: **make it social.** Connect with friends,
send letters, journal on the relationship itself, get a prompt about it, reflect on
where it is going. Freemium.

**The tension, and it has to be resolved before any of it is built.** The thing that
made Nuuko retain is that nothing leaves the device and there is no sign-up wall.
Local-first IndexedDB with client-side encryption is not an implementation detail, it
is the product promise, and the research says privacy failures are why people quit
competitors. A social layer requires accounts, a server, sync, and moderation. Built
carelessly, the social feature destroys the finding the app was built on.

**The shape that keeps both**, as the proposal to take to the advisor:

- The private journal stays exactly as it is. Local, no account, no server.
- **Sharing is opt-in per object and end-to-end encrypted.** A letter to one friend
  is encrypted to that friend's key. The server stores ciphertext and routes it. It
  never holds a readable entry.
- A shared relationship journal is a second, separate object, created deliberately,
  visibly different from the private one on screen. Never a setting on an existing
  entry, because the one thing that must never happen is a private entry becoming
  visible by accident.
- The consent problem gets an answer in the product, not a footnote: a person can be
  written about without being named, and the app should make the unnamed version the
  default and the easy path.

That is a real computer science deliverable. E2E key exchange, an offline-first
sync model with conflict resolution, and a threat model, on top of an on-device ML
layer that already exists. It is enough CS for the CS half of the degree on its own.

**Freemium, and the visa.** She is on an F-1 and graduates May 2027. Taking revenue
is an immigration question before it is a product question, and it is the kind that
is answered by Minerva's international student office, not by me. The capstone does
not need revenue to be a venture: a priced tier that is designed, validated with
willingness-to-pay research and left switched off is a legitimate and defensible
work product. Ask before building a checkout.

**What is actually in the repo**, read on 11 September at
`~/Documents/vs-code-projects/nuuko-v1`. 322 commits. Vanilla JS with no build step,
47 HTML pages, IndexedDB, a service worker, AES-GCM in `public/scripts/encryption.js`
and `localEncryption.js`, Vercel functions under `api/`, and Supabase Postgres with
row level security behind them. Thirteen tables including entries, summaries,
insights cache, coach sessions, referrals and rewards. The on-device model is real
and it is in the repo: `public/client-model/emotions.onnx` with an onnxruntime
wrapper beside it. There is also a server-side coach on Gemini 2.5 Flash in
`lib/gemini.js` and `api/coach.js`.

**One wording problem to fix before a defense, because a second reader will find
it.** The mini capstone says the ML layer runs entirely client-side with no external
API calls. That is true of the emotion classifier and not true of the coach, which
sends text to Google. The fix is one sentence, not a code change: say which feature
runs where, and say what leaves the device and when. It also matters for the
privacy claim in section 7, because the social layer has to be designed on top of
the real architecture rather than the described one.

**And accounts already exist.** There is auth, refresh tokens, sync and a server
that holds entries for signed-in users. So the social layer is less of a departure
than it looked: the sync path is built. What it needs is the key handling, so that
what the server holds for a shared object is ciphertext it cannot read.

---

## 8. The content engine as a product

She wants the YouTube and Instagram side copied out into its own repo, packaged as a
product. Agreed, and it is the right call for the capstone: an open source tool with
strangers running it is a work product with a real-world audience, which is exactly
what the handbook asks for.

**Copy, never move, and never the git history.** This repo holds her novel, her
private pages, her keys, her personal planning and 2,597 commits that have touched
all of it. The new repo starts empty with a fresh history and gets a clean-room copy
of chosen files.

The plan, once she says go:

1. New public repo, fresh `git init`. Candidate names: `quietcut`, `longform`,
   `studio`. Recommendation: **`quietcut`**, because it is available-sounding, it
   says what it does, and it is not her handle, which matters if it is ever a
   product rather than a portfolio piece.
2. Copy: the cutting engine, `scripts/lib/`, the caption and overlay system, the
   matte pipeline, the scheduler, the doctor scripts, and the skills that drive them.
   Not: media, `.env`, `book-writing/`, `src/`, anything under `out/`, the memory
   files, the creator research.
3. Secret scan before the first push. gitleaks or trufflehog over the working tree,
   plus a read of every file for a hardcoded path or a private name.
4. A README that a stranger can follow: what it does, the architecture diagram, the
   one-command install, a sample take, and the house rules with the reasons attached.
5. A 2 minute demo video, which is free for her and is the thing that makes a repo
   get used.
6. MIT, and a decision about whether the house style rules ship with it or stay hers.

This repo keeps working exactly as it does now. The copy is a release, not a
migration, and it gets re-synced deliberately rather than continuously.

---

## 9. The gates that have queues in front of them

Start these now, not when they block something.

- **HSR approval.** Any new survey, interview or user test with people needs it.
  Check whether the mini capstone's approval covers the new work. It probably does
  not, because the population and the instrument both change. `hsr@minerva.edu`.
- **Second reader.** Suggested in the Project Brief, matched centrally, no guarantees
  on who or when. Name three, ranked, in the brief.
- **Custom LO approval.** Drafted this fall, approved by spring week 7. Get the
  rubrics in front of the advisor at the first committee meeting.
- **The F-1 question** about taking revenue, if the freemium tier is ever switched on.
- **The tester number.** Documents in the repo say 100+, 59 and 30 to 40. Three
  different numbers for the same thing, and one of them will be asked about at a
  defense. Pick the true one and correct it everywhere before the brief goes in.

---

## 10. What happens next

**Before 26 September, in order:**

1. Confirm the framing in section 3 with the advisor. Everything else depends on it.
2. Fill in the college LOs from the real catalogue.
3. Draft the three custom LOs with rubrics.
4. Write the Project Brief into the official cover sheet copy.
5. Fix the tester number.
6. Email HSR.

**Then:**

- Weeks 4 to 8: build toward the midterm deliverable. Recommendation: **Nuuko v2's
  person-filing core, live, tested with 10 to 15 people**, because it is the riskiest
  build and the midterm is the right place to find out it is wrong. The engine repo
  is the safer alternative and a worse use of the slot.
- Weeks 9 to 14: the packaged engine repo, the channel-to-app link, and the full
  draft with every section present.
- Week 15: the 10 minute video. She makes videos for a living. This should be the
  easiest 5% on the board and it should be conspicuously better than everyone else's.
