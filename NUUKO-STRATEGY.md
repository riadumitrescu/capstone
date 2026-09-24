# Nuuko: the strategy

Written 2026-09-11 out of `capstone/RESEARCH-SYNTHESIS.md` and the seven research
files under it. Every claim in here traces to one of them. Where something is a
judgement rather than a finding, it says so.

This is the plan for what to build, what to charge, how people arrive, and what has
to be true for it to work.

---

## 1. The decision

**Nuuko stops being a journaling app.**

Not because journaling is wrong, but because the word is. Nobody in 745 of her
comments has ever asked for one. The word journal appears zero times. What they ask,
over and over, is what to call what they feel about one particular person, and then
they write six hundred words into a comment box because there is nowhere else to put
it.

**Nuuko is where you work out what you feel about one person.**

That sentence changes the competitor set, the onboarding, the pricing and the videos.
It stops competing with Day One and Apple Journal, which are archives, and with
Finch, which is self care. Its nearest neighbour is Paired, which is couples only,
like all thirteen relationship apps torn down in the research.

**The category line, for the capstone form:**

> Nuuko is a private journal organised by the people your life is actually about. You
> pick a person, answer a few honest questions, and over months it shows you the
> pattern you were too close to see.

**The line for a viewer, which she will say out loud on camera:**

> Every journaling app asks how your day was. Nuuko asks who it was about.

That second line is already written, in `src/data/nuuko.ts`, and it survives contact
with all of this research. Keep it.

### What this is not

It is not a couples app. It is not a mood tracker. It is not an AI therapist. It is
not a social network. Each of those is a decision with evidence behind it, in section
5 and section 9.

---

## 2. The spine: the person, and the seven kinds

Everything below hangs off two objects.

### 2.1 The person

A first class object, not a tag. Minimum fields:

| field | why |
|---|---|
| handle | never a real name by default. An initial, a nickname, "the one from work". Warmer, and it keeps the privacy promise intact |
| colour | the shelf spine. Her existing visual language |
| kind profile | the seven kinds scores, from the diagnostic, re-runnable over time |
| first entry date | so the app can say how long this has been going on |
| status | current, faded, ended. Chosen by the user, never inferred |

An entry may have one person, several, or none. **Keep the unfiled entry.** Some days
are about nobody, and forcing a person turns the app back into homework, which is the
exact failure her original research identified.

### 2.2 The seven kinds

This is the asset nobody else has and it is already built, tested and published:
sexual, romantic, aesthetic, sensual, intellectual, platonic, alterous, plus the
confusions. It is the framework of her channel, of `/which-one-is-this`, of the 200
questions in `products/seven-kinds/QUESTIONS.md`, and of 44 guide pages.

**Applied per person it becomes something no journal has ever had: a profile of a
relationship rather than a mood of a day.** Mood tracking says you were anxious on
Tuesday. This says you feel four kinds of attraction toward this person and one of
them has been fading since March.

That is the product. Everything else is delivery.

---

## 3. Every feature, in build order

Each one carries the evidence it rests on, and an honest size.

### 3.1 The entry point: the diagnostic IS the onboarding

**Build.** `/which-one-is-this` already takes one specific person and 14 honest
questions and returns which of the seven kinds you feel. It currently ends in a
newsletter box. It should end in a person: the result becomes entry one, dated, with
the person unnamed, and the app opens on their page.

**Why.** It is the highest intent moment anywhere she owns. Somebody has just
answered fourteen questions about one human being. The next thing they want is not an
email in a week. Nobody else can build this funnel, because it needs the diagnostic
and the journal to have the same owner, and they almost never do.

**Evidence.** Her own README says the no sign-up wall was the single biggest
retention lever, with local mode users converting at about 4x. RevenueCat's freemium
counter case names word of mouth products as the exception to hard paywalls.

**Size.** Days, not weeks. The diagnostic exists and the app exists.

### 3.2 The writing surface

**Replace every prompt.** The app currently ships "what are you grateful for right
now?" and "what small joy brightened your day?", which are the generic prompts her
own competitive analysis says are why nobody stays. The replacement is written:
200 questions in her voice, all about specific people. Part zero opens with

> Write down every person currently taking up room in your head. Not the people you
> love. The people you think about.

which is, exactly, the onboarding for a person-filed journal.

**Three prompt types, and only three.**

1. **The noticing prompt.** Concrete, about one event. "What did they actually say."
   Never "why do you feel this way". This is not a style choice: Watkins shows
   abstract why-processing is what harms ruminators and concrete what-happened
   processing removes the harm.
2. **The observer prompt**, used sparingly and at the right moment. Write this week
   from the position of someone who wishes you both well. This is the single best
   supported prompt in the literature, g = -0.26 across 48 studies, and the same
   device as the Finkel marriage hack.
3. **The seven kinds prompt**, drawn from the part matching that person's profile.

**Gate on the ordering.** The mood label may be collected after writing, never
before, because Ariely et al. found labelling first cancels the benefit of
reappraisal.

**Size.** A week, mostly selecting writing that exists.

### 3.3 The archive, which is the actual product

**Evidence.** Across 2,500 reviews of the three most different apps in the category,
the most praised feature is re-reading, and the reason people quit is lost or locked
entries. So the archive gets the engineering, not the editor.

Build:

- **A book per person.** Her own shelf metaphor, finally doing what a shelf is for.
  Open a person and their whole history is one object, in order, colours running down
  the side, with the week the feeling changed visible.
- **Re-read surfaces.** On this day with this person a year ago. The first thing you
  ever wrote about them. The entry you have opened most.
- **Export that always works,** free, forever, in a readable format. This is not
  generosity. It is the direct answer to the number one reason people leave apps in
  this category, and it makes the trust claim provable rather than promised.
- **Search, and be honest about the trade.** Search over encrypted content requires
  client side indexing. That is real work and it is the right kind of work for a CS
  capstone.

### 3.4 The character, and how to make it alive

Today the feather notices cats and does not notice people. `characterActions.js`
picks its picture from streak length, time of day, season, and three keyword themes:
cat, workout, work. Write about the same human for the eleventh time and it flips a
coin between two images.

**Life is continuity, not animation.** Three changes, no new art required for the
first two:

1. **It notices people.** The keyword themes become person aware. Not "you wrote
   about M again", which is surveillance, but the feather turning up holding their
   book when you open the app on a day you usually write about them.
2. **It remembers.** The one thing a companion has that a picture does not is that it
   was there last time. "You have been carrying this one since March" is a sentence
   only this app can say, and it says it because the person object exists.
3. **It is restrained.** No streak art at 3, 7 and 14 days. Her own README says
   aggressive streaks made users feel guilty, and the market research says streaks
   are not the churn mechanism anyway, so there is nothing to be gained by keeping
   them. Replace the milestone with the return: the feather is pleased you came back,
   never counting.

**The one place to spend on motion** is the moment an entry is filed to a person: the
feather putting it into their book. That is the app's whole thesis in one animation,
it already exists as a still (`nuuko-putting-entry-in-book.webp`), and it is the
screenshot people will post.

**Judgement, not a finding:** cap the character investment here. Wasil 2022 found
quality scores predict downloads and revenue but not retention. Charm sells the
install. It does not keep anyone.

### 3.5 The friend layer

This is the part with the most upside and the most ways to go wrong, so it is
specified tightly.

**What the evidence allows:**

- **Small and closed.** Locket survives at 80M downloads and 9M DAU with a 20 friend
  cap. BeReal peaked at 73.5M monthly users with 9% ever opening it daily and sold
  for €500M with no revenue, now worth €30M. Small closed graphs survive, open feeds
  do not.
- **Structured, never a reply box.** Zelic et al. (2017) is the one experiment: open
  venting harmed, structured problem solving did not. A blank reply field between two
  friends discussing a third person is a co-rumination machine.

**So the mechanic is the letter, and it has three rules.**

1. **It is written, not chatted.** One letter, sent whole. No typing indicator, no
   thread, no read receipt.
2. **It is delayed.** Scheduled or slow by design. The research found nothing that
   combines letters, delay and a chosen set of people, across seven documented
   searches. That combination does not exist.
3. **The reply is structured.** Not a text box. A small set of honest responses plus
   one written answer to a prompt the app supplies. The structure is the intervention.

**The shared relationship journal is a separate object,** created deliberately,
visibly different on screen from the private one. A private entry must never become
visible by toggling a setting. This is the single highest consequence rule in the
product.

**Copy Day One's invariants exactly**, because the most careful company in the
category has already solved this and publishes how: a separate container rather than
a toggle, per-journal encryption keys separate from the personal key, a **30 member
cap**, invite links that expire after 14 days and are owner-generated with owner
approval, entries that can move in and **never out**, and the rule stated as an
invariant: "No entry in a private journal will ever be shareable."

**Never touch the address book.** Path's ending was not about what users wrote. The
FTC fined it $800,000 with twenty years of assessments for what it took from
contacts to build the graph. Apple 5.1.2(iv) and (v) forbid building a contact
database and forbid a Select All invite. Building the graph is where the exposure
sits, not the writing.

### 3.5a The regulatory constraint, which may change the plan

**A letters feature makes her a regulated user-to-user service in the UK on the day
it ships.** The Online Safety Act has **no size exemption**, in-app text messaging is
not in the Schedule 1 exemptions, and **all four compliance deadlines passed between
March and July 2025**. Penalties run to £18 million or 10% of worldwide revenue, with
criminal liability for senior managers on enforcement notices about child safety. Her
channel's measured audience is **16.8% aged 13 to 17**, which is also the COPPA
exposure that cost Path its $800,000.

Under the DSA she would be a hosting service. The micro enterprise exemption in
Article 19 covers Section 3 only, so Articles 11, 12, 14, **16 and 17 still apply**,
including a notice and action mechanism with no size exemption at all. Apple
guideline 1.2 separately requires four things for any user-generated content: a
filter, a report mechanism, a block, and published contact information.

**So there is a real decision here and it is hers.** Ship letters publicly and take
on a regulated service as a solo student, or design it, build it, test it with a
closed consented group, and write it up. **The second is the recommendation.** It is a
complete work product, it is defensible at a defence, and it does not put someone on
an F-1 visa on the wrong side of Ofcom. The capstone loses nothing: a prototype
tested under consent with a written risk assessment is better evidence than a public
launch with none.

### 3.5b The finding that cuts against all of this, stated honestly

Radcliffe et al. (2007), N = 165, found that **shared** written disclosure beat
private disclosure on depression and interpersonal sensitivity, and that only shared
disclosure reduced physical symptoms. So "an audience ruins journaling" is not what
the evidence says.

But look at who the audience was: **researchers**. Anonymous, one directional, non
responding, with no ongoing relationship to the writer. That is the opposite of a
shared journal containing your partner, your mother and your friends.

And the audience literature says what a persistent one does. Das and Kramer found
**71% of 3.9 million users self-censored** in 17 days. Pew found 86% would discuss a
topic in person and 42% would post about it. Sleeper et al. found that the messages
people most regret having had an audience for are specifically **the cathartic,
expressive ones**, and that they notice the regret more slowly than for things said
in person. Cathartic expressive writing is the entire point of the product.

**The reconciliation, and it is a design instruction:** the good audience is safe,
one directional and non reciprocal. The letter to one chosen person is close to that.
A feed is the opposite of it. This is why the mechanic is a letter and not a wall.

**And on the private half, the WP29 problem.** Opinion 5/2009 section 3.5 says the
creation of "pre-built profiles of non-members" out of data contributed by users
"lacks a legal basis". Filing a journal by person is, to a regulator, exactly that.
The exposure exists before any social feature and it lands on the provider, not on
the user, because Recital 18 puts the household exemption on the writer and explicitly
not on whoever provides the means. The mitigations: **default to an unnamed handle and
make it the easiest path, never ingest contacts, never infer a person from anything
but what the user typed, offer per-person deletion, and publish an Article 14(5)(b)
position.** No app in the personal-CRM category does any of this, so doing it is novel
and it is cheap.

### 3.6 The safety layer, which is also the research contribution

Because the whole pivot asks people to write about one person repeatedly, and
Sbarra et al. found exactly that harmed high ruminators:

- **Screen for brooding at onboarding**, without naming it, and route brooders to the concrete
  and observer prompts rather than to the blank page.
- **Notice fixation without naming it.** Eleven entries about one person in two weeks
  is a signal. The response is not a warning, it is a different prompt.
- **Never generate the reflection for them.** DiaryMate (N = 24, ten days) found
  users over relying on the LLM and prioritising its emotional language over their
  own. The AI may ask and may notice. It may not write the feeling.

**This is publishable.** Nobody has studied writing about friendships. A capstone that
runs one honest controlled test on person-filed writing would have better evidence
than Paired, whose own marketing claim of "89% see positive changes in 3 months" has
no citation attached to it.

### 3.7 Wrapped, per person

Wrapped is already the most screenshotted thing in the app. Per person it stops being
a summary and becomes a finding.

"You wrote 24 entries in March" is a nice card. **"You wrote about the same person
fourteen times, and in week three the colour changed"** is a card people screenshot
and argue under, which is the only kind that travels.

### 3.8 What not to build

- **A feed.** The graveyard is full of them.
- **Streak counters.** See 3.4.
- **A mood chart dashboard.** Her own research already removed it for being
  overwhelming, and the labelling literature undercuts the premise.
- **Photo attachments.** Already tried, already removed, did not move retention.
- **An AI that writes reflections for you.** See 3.6.
- **A couples mode.** Thirteen apps are already there. The empty space is friends.

---

## 4. The contradiction to settle before any of this

`syncService.js:539` encrypts every entry before upload. `api/coach.js` reads entry
content from the database, lowercases it, keyword matches it and sends it to Gemini.
There is a full text search index on that same column. **These cannot all be doing
what the documentation says.**

One runtime check settles it: sign in, write an entry, look at the row in Supabase.

**Whichever way it resolves, the decision is the same:** the privacy claim is the
retention lever, so the coach moves to the device or it asks for explicit consent per
request and says exactly what leaves. The social layer is built on the answer, so
this happens first.

Related: the key is derived from the user's password with PBKDF2. That works for one
person's own data and cannot work for sharing. Sharing needs an identity keypair
whose private half is wrapped by the password derived key. **That is the real
cryptographic work in the capstone and it is a good piece of it.**

---

## 5. The business model

### 5.1 The rule that governs every number

MKBHD launched Panels to 20 million subscribers, hit number one in photos on both
stores, and shut it down fifteen months later on about $95,000 of lifetime spend.
That is **$0.0048 per subscriber**. At 10,300 subscribers the equivalent is about
**$49, lifetime**.

**No revenue projection in this capstone may be built from audience size.** The
counter case is Thomas Frank, $1,000,508 in a year from Notion templates off a
110,000 subscriber niche channel while sitting on a 2.9 million subscriber one.
**Niche beats reach, and specific beats broad.**

### 5.2 The shape: freemium, and the free tier stays a real product

RevenueCat's data says hard paywalls convert 5x better with the same retention, and
also publishes the counter case, and names the exception as products with network
effects and word of mouth. **Nuuko is the exception**, and her own README says the no
sign-up wall was the biggest retention lever it had.

**Free, forever, and it has to be a real product:** unlimited writing, unlimited
people, the whole archive, export, the diagnostic.

### 5.3 The paid tier

**$4.99 a month, $29.99 a year.** Deliberately under the discovered band of $36 to
$50, because her audience skews young and international and because cheap annual
plans retain better, 36% against 23% in year one. The market clusters at $39.99 and
the evidence on going lower is her own audience, not a benchmark, so this is a
judgement.

What is behind it:

- The deep question sets, the parts of the seven kinds book that are not free.
- The printed book credit (5.4).
- The year view and the long horizon patterns.
- Not the archive. Never the archive. Locking someone's entries is the thing that
  kills apps in this category.

**AI is metered separately or it is not there.** Nobody in the market folds it in.
Day One Gold is +$25 a year for AI alone. AI apps earn 41% more per payer and churn
30% faster. The honest position for a privacy-first product is a small, on-device,
free noticing layer, and any heavy model work as a separate paid thing that names its
cost.

### 5.4 The printed book, which is the best idea in this document

Day One publishes the only clean unit economics in the category: $19.99 plus $0.10 a
page, so a 200 page hardcover is $39.99. Storyworth has printed a million books.

**A printed book of your year with one person.** Not your year. One person. It is the
same price as a year of subscription with no churn attached, it is the emotional
peak of the entire product, and it is the thing her audience, who write six hundred
word comments about one human being, will actually buy.

It is also the perfect object for the channel, because she can hold it up.

### 5.5 The rest, ranked

| what | verdict | why |
|---|---|---|
| digital products on her own site | **do first** | Kajabi: digital downloads up 20% while brand deals fell 52%. Thomas Frank's million. The seven kinds material already exists |
| the printed book | **do** | best margin, best object, best video |
| gifting a year to a friend | **do** | Calm sells a $499.99 gift card. A friend layer makes gifting native |
| cosmetics for the feather | **later** | Finch runs four revenue lines on a free core. It works. It is also a lot of art |
| group and family plans | **later** | acquisition more than revenue. Waffle is free for 29 people |
| in-app ads | **no** | Finch's 2026 complaint wave is advertising |
| lifetime deals | **no** | kills the only reliable revenue line |
| a web checkout to dodge the store fee | **no** | she is a 15% developer under Apple's Small Business Program. Stripe saves about eight cents a month per subscriber and buys a sales tax problem |

### 5.6 The visa, stated precisely and not as advice

From the research, sourced to DHS, SEVP and USCIS: **starting a business constitutes
work.** SEVP guidance explicitly permits a self-employed business owner on
post-completion OPT, and USCIS says a student may start, own and work for their own
business during the initial OPT period. **STEM OPT is where it breaks:** she may not
sign her own I-983 or act as her own employer, and sole proprietorships are named in
8 CFR as failing the bona fide test.

She graduates May 2027. **The revenue window is the OPT year.** Anything that assumes
income after that needs a structure decided in advance.

**This is not legal advice and the authority is Minerva's designated school official.
Ask before switching on a checkout.** For the capstone itself, a priced tier that is
designed, validated with willingness to pay research and left switched off is a
complete and defensible work product.

---

## 6. How people arrive

### 6.1 The numbers that set the strategy

From the measured 90 days: 1,459,685 views, 1,446,858 minutes watched, 11,270 views
from external URLs.

**Shorts are 33% of views and 3.3% of the attention.** 480,505 views produced 47,467
minutes, which is 5.9 seconds per view. **A call to action in a Short reaches someone
who has been present for six seconds.** The subscriber feed produced 1,048,272
minutes, 72% of all attention on the channel.

**So installs come from long form. Shorts are not the funnel, they are the
advertising for the funnel.**

And her strongest signal is already visible: **her six journaling long forms get 312
to 936 views and convert at 8.65 likes per 100 against her 4.21 average, ranking
first of 32 on subscribers per thousand.** The smallest videos on the channel
convert the best. That is the lane.

### 6.2 The video formats, in order of expected effect

1. **The journaling session.** She sits down and works out what she feels about one
   person, on camera, using the app's prompts, in real time. Not a demo. The video is
   the product being used, and the thing being demonstrated is the thinking. This is
   the format her journaling long forms already prove converts.
2. **The seven kinds series.** One long form per kind, each ending on the same
   question: which person did you think of. The diagnostic is the call to action, the
   app is what the diagnostic hands you.
3. **The crush session.** The most asked question in her comments, answered by doing
   it rather than explaining it.
4. **The letter.** She writes one to a friend, on camera, and sends it. This is how
   the friend layer gets explained without a feature tour.

Every one of these is a long form over 8:30, which is already her rule.

### 6.3 The one measurement to start this month

Her own click through from a video to a link, with an n attached, was NOT FOUND
anywhere public. **She can close that gap herself with one tagged link in one video
description.** Until that number exists, every install projection is a guess, and the
capstone should say so.

---

## 7. What success means, and how it is measured

For `#outcomeanalysis`. Each has a baseline and a defined window, which is the thing
the current ~40% claim lacks.

| measure | definition | baseline | target |
|---|---|---|---|
| first entry completion | share of arrivals who write one entry | 78% vs 31% control, source needs finding | hold above 70% with the person step added |
| **day 30 retention** | share writing at least one entry 30 days after first | **market median 3.3%**, ours undefined | **define it first, then beat 10%** |
| person filing | share of entries attached to a person | new | over half |
| second person | share of users who add a second person | new | the real engagement signal, set after first data |
| letters | share of connected users who send one | new | set after the first test |
| channel to app | installs per 1,000 minutes watched | unmeasured, external traffic is 11,270 views per 90 days | any measured number beats none |
| paid conversion | install to paid | market 2.9% in Health and Fitness | measure, do not target |
| the honest one | can a stranger write one entry and say what the app is for, in one sentence, unprompted | new | 8 of 10 |

**And the harm metric, which most products never write down:** co-rumination raises
friendship quality and symptoms together, so engagement on the friend layer cannot be
the only measure of it. If people are writing more and feeling worse, the feature is
failing while the dashboard says it is working.

---

## 8. Build order, against the capstone dates

**Now to 26 September, the Project Brief.**
Settle the encryption contradiction with a runtime check. Find the primary source for
the retention number or retire it. Write the brief around the positioning in section
1.

**To 31 October, the midterm deliverable.**
The person object, the shelf by person, the replaced prompts, the diagnostic handoff.
Live, with 10 to 15 people tested. **The midterm question is the one the research
could not answer: does anyone want a journal filed by person.** Design it as a test
with a real comparison, not a demo.

**November to 11 December, the full draft.**
The archive work: re-read surfaces, export, client side search. The character made
person aware. The first journaling session video, measured with a tagged link.

**Spring.**
The friend layer, the letters, the key exchange, the printed book, and the controlled
test that gives the capstone better evidence than the market leader.

---

## 9. What kills this

1. **Nobody wants it.** Filing by person is empty space, and empty is not proof of
   demand. Find out on 31 October, cheaply, before building the social layer on top
   of it.
2. **The social layer leaks a private entry.** One incident and the trust claim,
   which is the retention lever, is gone permanently. Note that Apple Journal needed a
   PolitiFact fact-check over a feature that shares no identity and no location, so
   the perceived privacy properties and the real ones are two different products and
   only one is under engineering control.

2b. **The regulator, not the market.** A public letters feature is a regulated UK
   service with four passed deadlines, and the person-filing pivot itself sits against
   WP29's pre-built profiles line. See 3.5a.
3. **It hurts the people most likely to use it.** Ruminators are the ones who write
   about the same person eleven times. Design for them or do not ship it.
4. **Scope.** 12 hours a week, two majors, a novel, a channel and a visa. The friend
   layer is the piece to cut if something has to go, and the person pivot is the
   piece that cannot be.
5. **The numbers do not survive checking.** The 40% retention figure and the tester
   count are both unsourced or contradictory today, and a second reader will ask.

---

## 10. What is still hers to decide

1. Does she want the app to be a business during the OPT year, or a portfolio piece
   with a designed and switched-off paid tier.
2. Friends or couples. The research says friends is the white space. It is also the
   harder sell, because couples already pay.
3. Android first, or iOS. Apple Journal is free and good and syncs everywhere since
   September 2025. No first party journal was found on Android, and that finding has
   no primary source yet.
4. Whether the channel and the app share a visual identity on purpose. They are
   close relatives now by accident, cream and serif on both sides.
