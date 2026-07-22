# Stud 8 Coaching Notes — worked explanations

Deep-dive explanations for the recurring teaching points. Read the relevant
section when explaining a grade in detail or when the player challenges one.
Each note is written so you can adapt the *reasoning*, not recite a script.

---

## 1. Low pairs are composite hands, not weak hands

The player's instinct (imported from Stud High or Hold'em) is "smaller pair =
weaker." In Stud 8 that axis barely applies. What matters is whether the pair
contributes to **both** high and low.

Two hidden advantages a low pair has that a high pair lacks:

1. **The pair cards double as low cards.** The 4s in 4♠4♦ are pair cards *and*
   low cards — one card, two jobs. If a 4 pairs the board and breaks the pair,
   the 4 still works toward a low. High pairs (KK, 99) have no such duality.
2. **It's concealed.** Down two cards; the opponent sees only the door. A
   completing 5 can't read (4-4) behind a 6 door — the invisibility *is* value.

So a low pair whose rank is in the low zone is a "contest-both" hand → call.

**When the player's "small pair is weak" instinct is actually right:** when the
pair rank is *out* of the low zone (see note 2), or when the pair cards are
mostly dead (kills the trips-improvement and thins the low). Then the small pair
is exposed as weak. The instinct isn't wrong — it's applied at the wrong layer.

226 vs 446 vs 664: all calls. 226 is *strongest for low* (2 is a wheel card, the
best low card to be paired on), 664 is strongest for high (higher trips/two-pair
if it improves), 446 is the balance. Pair size does not decide fold/call among
these — dead cards do (how many of your pair cards are gone).

---

## 2. The dividing line is the low zone, not the number

886 looks like it should behave like 226/446/664 (all low pairs). It does not,
and this is the key non-linearity.

A low needs **five distinct cards, all eight-or-lower.** A pair can't be used in
a low, so of 8♠8♦ only **one 8** is usable low — the other is dead weight. And
even a completed 8-low is the **weakest possible low**. So (8-8)6:

- low-making power: weak (one usable card, and the result is the worst low)
- high-making power: fine (8s can make trips/two-pair)

That's a **high-only hand in disguise**, not a low-contesting composite. Play it
as a mediocre high pair (see note 6), not as a low pair. The clean line: pair
rank **≤6 = low-zone composite** (call), **7 = boundary** (dead-card / position
dependent), **≥8 = out of zone** (fold basis as a low pair). The rules of the
low (five distinct ≤8) create a *jump* between 6 and 8 even though the numbers
look adjacent — 226 and 886 are different categories.

---

## 3. Equity vs the *quality* of that equity

A player will (correctly) observe that a middle-pair-plus-low is ~50% heads-up
against a bare three-card low. **This is true and the source confirms it:**
Haney gives (8♠6♥)5♣ as a **53% favourite over (2♠3♥)4♣** and only a **49%
underdog to (A♠3♥)4♣**. Validate this first — don't wave it away.

The catch is the *composition* of that 50%. Two 50%s are not equal:

- **Scoop-weighted 50%** — win the whole pot when you win. Large realized value.
- **Split-weighted 50%** — win half when you win. Same %, smaller money.

Middle-pair-plus-low tends toward split-weighted (it makes an 8-low that often
loses the low outright, and its high is only a pair). Its wins are frequently
"half," and it has a real "lose outright" tail. A raw all-in equity number does
NOT distinguish these — it just reports showdown %. So an honestly-computed 50%
overstates a hand whose 50% is mostly split-weighted.

**Multiway makes it worse**, not better, for this hand: heads-up it's ~50%, but
with three-plus players the middle pair gets pushed on high and the 8-low loses
to any real low. Low pairs like 226 survive multiway *not* because their raw
equity is high (it isn't) but because a live wheel-card low gives a **floor**
("half via low"); 886's floor doesn't exist (8-low ≈ can't win the low half).

The right lens is **scoop-value / realized money**, not raw showdown equity.
Frame it that way after granting that the equity read itself was correct.

---

## 4. Completed high-only hands WANT multiway (the paradox)

An advanced player may object: "if it's high-only, isn't multiway even *better*?"
For a **completed** high-only hand, yes — and this refutes a naive "high-only
hates crowds" rule. Distinguish two cases:

- **Unmade high-only (bare KK):** hates multiway. Still just a pair; three
  players means someone can improve past it, and it gets jammed off its equity.
  Thin the field.
- **Completed high-only (rolled-up trips):** *welcomes* multiway when the field
  is going low. It already has a near-locked high. More low players →
  (a) still nobody contesting the high, so it scoops the high nearly for free;
  (b) a **bigger pot** on a high half it will almost certainly win. There is no
  "low share" being diluted, because it never had one. The low players even
  cannibalize each other's lows — irrelevant to your high.

So the "split-dilution" worry only applies to **two-way** hands losing their low
portion. A high-only hand has no low portion to lose; growing the pot is pure
upside. When the player raises this, concede it — it's correct — and fold it into
note 5.

---

## 5. Rolled-up trips: attack even high-only; trap-vs-raise branch

Trips (rolled up) is a **completed premium high**, so it attacks even out of the
low zone (9-9-9, 8-8-8) — the rare high-only that's always aggressive, because
it's already made. But *how* it attacks depends on door and field:

- **Low-looking door (≤8) that disguises as a low, AND you can induce multiway
  → TRAP (call).** Two reasons, and a strong player will point out the second:
  1. A low door (e.g. 8) makes you look like a three-card low or a weak low
     pair; nobody reads trips. The disguise is ideal — you can even pretend to
     chase a low on later streets while already made.
  2. Per note 4, a completed high-only *wants* the extra low players and the
     bigger pot. Trapping to induce them is correct, not greedy.
  A **low-pair (rolled-up) door is even better for trapping** than a high door,
  and a *low* rolled-up (e.g. 222) traps better than a high one (9s) because it
  also contests low → scoop-weighted, so slow-playing risks less.
- **High door (no disguise) or heads-up already → RAISE.** If you can't hide the
  trips or grow the field, extract value directly.

Common failure: the player *raises* a monster correctly in one spot, then gets
intimidated by an ace completing and *calls* an identical trips in the next spot.
The trips is the nuts-ish high regardless of the ace — the ace showing is a
reason to *build value*, not to shrink from it. Keep "trips = attack" firm.

---

## 6. High pairs (KK / QQ): fold multiway, but respect the ace kicker

Mirror image of the low pair. A high pair is good **only** when you're the big
favourite for best high AND the pot won't go multiway. Against many low cards it
gets jammed on later streets and folds out its equity.

- Fold to an **ace completing from a non-steal spot** (usually the AA it
  represents); fold **QQ to a king completing** (usually the KK represented).
- BUT an **ace kicker** (or a dead ace) lifts equity to **~57%** — with that,
  don't reflexively fold; **call** to see 4th, especially if the field is going
  low and the high might come back to you. "KKx **rainbow** folds" is correct;
  "**any** ace behind me → fold" is too tight. High-ante, short-handed, only an
  ace + bring-in behind: KK does not fold (it's not throwing away ~57%).
- **Multiway is the disqualifier.** Three low players already in the pot is the
  textbook spot a high pair should *avoid* — even KK+ace-kicker is a call-at-best
  (see 4th), never a raise that bloats the pot on a high-only hand that gets
  outdrawn or jammed. Don't confuse "ace kicker helps" with "now I can raise
  multiway."

---

## 7. Ace-up is a reason to attack by itself

Given the power of the ace up-card, consider a steal whenever the hole cards are
reasonable — opponents tighten against an ace (often too much) and rarely
reraise. So a raggedy holding with an ace showing (e.g. A-K-4, or the
source's steal example (6♣9♣)A♠) is a **complete/steal** in many spots, not a
fold — the door does the work. Don't underweight the door.

The counter-weight is **position**: from early seats with many players behind, a
steal's success rate drops, and a genuinely disconnected ace-high hand
(the K floating uselessly) can be a fine disciplined fold there. So "ace-up →
consider steal" is a strong default that position can override — but the player
should not fold an ace-up on autopilot as if it were a raggy non-ace hand.

---

## 8. The trips-vs-pair line (the most common mix-up)

Everything above rests on one distinction the player will repeatedly blur:

- **Completed trips** → attack (notes 4, 5). Made hand, near-locked high.
- **Mere pair** (middle or high) facing a higher completion or a multiway field
  → fold / call-to-see, never bloat (notes 3, 6).

"I have a pair" and "I have trips" produce opposite actions. When the player
attacks a middle pair into a higher completion, or shrinks a rolled-up trips
away from an ace, the root cause is this conflation. Diagnose it explicitly:
*is the hand made (trips) or merely a pair?* Then apply the matching line.

---

## Method note: re-grading on a valid challenge

The strongest lessons in this game often arrive as the player's objection being
**more right than your initial grade**. Real examples from how this training
runs:

- "886 has high equity vs a three-card low, though" → correct (53% per source);
  the initial "just fold, it's weak" was wrong to dismiss the equity. Re-grade to
  "△, and here's why the 50% is split-weighted" (note 3).
- "high-only wants multiway even more, no?" → correct for *completed* high-only
  (note 4); revise any claim that a rolled-up trips should raise to thin the
  field — trapping to induce multiway can be better.
- "8 can be shown as a low, so trapping disguises the trips" → correct (note 5);
  upgrades the trap line above a reflexive raise.

When this happens: **verify against the source, concede plainly, re-issue the
corrected grade.** Do not defend. The player learns more from an honest reversal,
and the credibility of every *other* grade depends on it.
