[claim-verification-protocol.md](https://github.com/user-attachments/files/33604935/claim-verification-protocol.md)
# CLAIM VERIFICATION PROTOCOL (CVP) — v1.1
A pre-publication fact-check discipline for anything written with AI assistance.
Released 2026-10-17 · Sovereign Stack · CC BY 4.0

## What it is
A repeatable way to check every factual claim before it goes public, when any part
of the writing involved an AI system. It is a discipline, not a guarantee: it reduces
the chance of publishing something wrong, not to zero. A protocol that claims
perfection is itself an unverified claim.

## When to use it
Run a claim through the protocol when ALL three are true:
1. It's factual — a number, date, price, ranking, citation, or attributed quote.
2. It's going public — anything a stranger could read.
3. Any part of drafting or research involved an AI system.
If any one is false, the protocol is optional (but cheap — use it anyway).

## The core rule (the publication gate)
Every factual claim entering public material passes through the log first.
Unverified claims are marked [UNVERIFIED] and cannot ship. No exceptions
for "small" claims — a wrong date in a board deck is not a small claim.

## The five verdicts (one per claim — exactly one)
| Verdict | Meaning | Ship? |
|---|---|---|
| A. VERIFIED | Confirmed by at least two independent, current, authoritative sources | Yes — cite normally |
| B. TRUE BUT MISLEADING | The fact is real, but the frame changes its meaning (wrong population, stale data, cherry-picked scope) | Only with the recorded "safe framing" |
| C. METAPHOR ONLY | It's our phrase/label, not an external fact or industry term | Yes — only with explicit "our term" disclosure |
| D. GROUNDED — DECISION REQUIRED | Facts check out, but using them is a business/positioning judgment | Only after a named human records the decision |
| E. UNVERIFIED | Can't confirm it; sources conflict; or it traces only to an AI output | No. Rewrite, verify, or cut |

Verdict B is the most dangerous and the most common: a true number in a
misleading frame survives casual fact-checking and poisons everything built on it.
If evidence is mixed, the verdict is the WEAKER one. If you want to average two
verdicts — that's Verdict E wearing a costume.

## The five steps
1. EXTRACTION — mark every factual claim in the draft, as drafted (not corrected).
2. VERIFICATION — primary sources first, then authoritative secondary. Record WHAT
   you checked and WHEN. Two independent sources beat one.
3. VERDICT — assign exactly one verdict from the table above.
4. SAFE FRAMING — for B, C, and D: write the exact sentence that may appear in
   public, word-for-word, so it can't mislead even out of context.
5. PUBLICATION GATE — ship only if every claim is A, or ships with the recorded
   safe framing for B/C/D. Anything E stays marked [UNVERIFIED].

## The log (one table, one row per claim)
| # | Claim (as drafted) | Verdict | Evidence checked (source + date) | Safe public framing (verbatim) | Owner |
|---|---|---|---|---|---|

Rules: the Claim column holds the claim AS DRAFTED (the gap between drafted and
shipped is audit evidence). Safe framing must be copy-paste ready. Owner is a
human name — AI assists; humans own verdicts.

## Residual risk (stated on purpose)
CVP does not catch: fabricated sources that look real, true-but-stale facts
framed as current, and correct claims in misleading *contexts* it wasn't applied to.
B and C require the writer to recognize their own frames. A log proves the
discipline ran; it does not prove the claim is true. If your work has to be right,
verify twice and log both runs.

---
CVP is one protocol in the Sovereign Stack family. This release is v1.1 — changes
from v1.0 (2026-10-13, private exercise) are logged internally and will publish
with the first external run report.
