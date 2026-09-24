# Lanes: which chat does what

Written 2026-09-11. The point is to spend the expensive model where a wrong call
is expensive and the cheaper one where the work is well specified and checkable.
Every lane ends the same way: smoke test, screenshots read, a DECISIONS.md entry,
a push.

## Fable (this kind of chat)

Anything where the decision is the work and a bad one is hard to undo.

- Architecture that touches crypto, sync, the coach, or anything leaving the
  device. The identity keypair for sharing. The consent flow for the coach.
- The capstone documents themselves: the Project Brief, the midterm write-up,
  the full draft. They are argued, not assembled.
- Reading research against research, and changing the strategy when it should
  change.
- Anything the privacy-reviewer flags as BLOCKING.

## Opus

Well specified build and writing, checked by a script and a screenshot.

Paste this at the top of an Opus chat in `nuuko-v1`:

> Read CLAUDE.md, then load the `nuuko-house` skill. Work on the branch
> `capstone/person-filing`. Before saying anything is done, run
> `node scripts/smoke.cjs`, look at the screenshots it writes, and append the
> decision to `../riadms/capstone/DECISIONS.md` in the fixed shape. Then commit
> and push the branch. Never push to main.

Lanes for Opus, one per chat:

1. **Re-read surfaces.** On the person page: "on this day a year ago", "the
   first thing you wrote about them", "the page you have opened most". Strategy
   3.3. Pure UI over `NuukoStorage.getEntriesForPerson`.
2. **Export that always works.** A readable Markdown export per person and for
   everything, from settings and from the person page, free. Strategy 3.3.
3. **Wrapped per person.** "You wrote about the same person fourteen times, and
   in week three the colour changed." Strategy 3.7. Build it over the existing
   wrapped code in `script.js` and `insights.html`.
4. **The character's second illustration.** The moment an entry is filed to a
   person: the feather putting it in their book. Animate the still that exists
   (`nuuko-putting-entry-in-book.webp`), one animation only. Strategy 3.4.
5. **The prompt copy pass.** Read `public/data/questions.json` and
   `public/scripts/people.js`. Every noticing and observer prompt must be
   concrete, one event, no "why". Rewrite the ones that are not, in her voice,
   lowercase. Strategy 3.2 and the literature file.
6. **The capstone assignment drafts from the plan.** The Project Brief in the
   official cover-sheet structure, from `CAPSTONE-PLAN.md`, `RESEARCH-SYNTHESIS.md`
   and `NUUKO-STRATEGY.md`, with `[NEEDS: ...]` where a fact is hers. Run
   `node scripts/ai-tells.mjs` on it in the riadms repo.
7. **The desk.** `src/data/threads.ts` after every lane above, with the date.

## Sonnet or Haiku

Mechanical and fully specified: run the smoke test after a rebase, regenerate
the questions file from `products/seven-kinds/QUESTIONS.md`, update the service
worker precache list, fix a banned word the hook flagged.

## What no lane does alone

- Push to `main` in nuuko-v1. She tests the branch's preview first.
- Switch on a checkout, a paid tier, or public sharing.
- Send anything to a person or a service on her behalf.
