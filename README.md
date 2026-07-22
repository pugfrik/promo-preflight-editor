# The Promo Pre-Flight Editor

An editor for bar and restaurant promos that reviews your drafted promotion
**before it runs** and tells you what will sink it: the work nobody owns,
the "success" you can't measure, the discount that loses money on your
best day. It critiques; you fix. It will not rewrite your promo or invent
one for you. It consistently flags issues until you've got a promo plan that will benefit your business to run.

## Who it's for

Restaurant, bar, café, and taproom operators about to spend
money, staff hours, or reputation on a promotional offer.

## How to use it

**In Claude Code (fastest):** clone this repo, open a terminal in the
folder, launch `claude`, and run:

```
/promo-preflight <paste your drafted promo>
```

The repo ships the skill (`.claude/skills/promo-preflight/`) — no setup.

**In a Claude project:** add every file in this folder to the project's
knowledge. If you're pasting into a plain conversation instead, paste in
this order: `identity.md`, `rules.md`, `examples.md`, then the
`reference/` files, and start your message with "You are the editor
defined in these files."

Either way:

1. Paste your drafted promo. The more detail, the better the editor can
   guide you.
2. You'll get: a one-line verdict (HOLD / FIXABLE / READY), what's most
   likely to sink it, and the questions to answer before you run it.
3. Fix the draft and paste it again. It acknowledges what you resolved
   and re-reviews the whole thing fresh.
4. When it finally says **READY**, it hands you a **launch record**: your
   final draft, every decision made along the way, the numbers you
   agreed to, who owns what, and anything still open — compiled from
   your own words, so the plan isn't living in your memory. (Ask for it
   early anytime: "export what we have.")

## Try it in 30 seconds

Paste any of these:

> "40% off all appetizers during Friday happy hour, 5–7pm. Goal: see if
> more people come in. We'll promote on social."

> "Tuesday Trivia Night, 7–9pm, starting Sept 2. 5 dollar entry per team
> donated to the local food bank; winning team gets a $25 gift card.
> Sarah owns setup + hosting; we'll track covers vs the last 8 Tuesdays
> on the POS."

> "Win free beer for a year! Every purchase this month is an entry.
> Winner drawn Oct 1, announced on Instagram."

## What it checks

**Execution** (does the work have owners?) · **Measurability** (will you
know if it worked?) · **Margin** (does the best case make money?) · and,
when your promo touches alcohol or prizes, a set of **legal smell-tests**
that flag risks for your lawyer, but never gives legal advice.

## What it won't do

- Rewrite your promo or produce a "fixed" version
- Invent promo ideas for you
- Tell you something is legal (that's counsel's job. It flags, they
  clear)

## What's in the folder

| File                                     | Job                                                                             |
| ---------------------------------------- | ------------------------------------------------------------------------------- |
| `identity.md`                            | Who the editor is and what work it reviews                                      |
| `rules.md`                               | How it critiques: the four lenses, the output format, and why it never rewrites |
| `examples.md`                            | Three complete reviews: a bad promo, a decent one, an alcohol giveaway          |
| `reference/stress-questions.md`          | The operator-interview questions a promo must survive                           |
| `reference/claim-tiers.md`               | What a run length can honestly claim, with rewrites                             |
| `reference/margin-gate.md`               | The does-success-actually-pay test                                              |
| `reference/measurement-readiness.md`     | The pre-registration checklist                                                  |
| `reference/alcohol-promo-smell-tests.md` | Alcohol & prize-law traps that route to counsel                                 |

---

Built from the review gates of a working taproom's offer engine.
