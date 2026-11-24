# One Word for Your Wi-Fi

[![make.fun](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72.svg)](https://make.fun/c/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)
[![rank](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72/mfahmiq/one-word-wifi/rank.svg)](https://make.fun/c/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)
[![reward](https://make.fun/badge/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72/mfahmiq/one-word-wifi/reward.svg)](https://make.fun/c/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)

Entry for the make.fun bounty
[One Word for Your Wi-Fi](https://make.fun/c/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72)
— one word that describes your Wi-Fi, aiming to be both the funniest
and the most accurate.

## The entry

**Ghosting**

Eight characters, one word, no explanation needed.

## Why this word

Every home Wi-Fi owner knows this exact behaviour: full bars one second,
gone the next — right in the middle of a video call, a file upload, a
boss fight. No warning, no goodbye, no "it's not you, it's me". Then,
a minute later, it reconnects and acts like nothing happened.

That is ghosting. The word lands instantly because everyone has been
ghosted by their router at least once, and the joke is true precisely
because it is recognisable. It is also the word you would actually want
as a network name: short, punchy, and it tells every guest exactly what
kind of Wi-Fi they are about to meet.

## How it was made

The brief was read in full first (`RULES.txt` in the competition kit),
then candidate words were weighed against the judge's own criteria,
in the order the judge weighs them:

1. **On-subject fit** — the word has to describe Wi-Fi as it is actually
   lived with, not Wi-Fi in the abstract.
2. **Funny at once** — a real laugh, not a pun that needs explaining.
3. **True** — the joke lands because the behaviour is recognisable.
4. **Fresh angle** — not the words everyone reaches for first.
5. **Instantly readable** — works as a single word with no context.

The obvious candidates failed one of those tests. "Buffering" and
"Slow" are true but they are the first words everyone reaches for, and
they are not funny — they are just a complaint. "Lagging" is the same.
"Temperamental" is accurate but it reads like a personality test, not a
laugh, and it sounds like an excuse for the router. "Disappearing" is
true and close, but it is flat: it states the fact without the joke.

"Ghosting" passed all five. It is on-subject (the connection vanishes
without warning), funny at once (the router is treating you like a bad
date), true (everyone has watched the bars disappear mid-sentence),
fresh (it borrows a dating word for a network problem, an angle the
usual Wi-Fi complaints never take), and it needs no explanation — a
reader gets it in the first half-second. It also survives the final
test the brief implies: it works as a network name. You can picture it
in a Wi-Fi list and smile before you even connect.

## How to run

`main.py` is Python standard library only — no dependencies to install.
It writes the entry to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default
`/output/entry.txt`) and self-verifies the gate before and after
writing: UTF-8 text, 1–20 characters, exactly one word with no spaces,
not whitespace-only. It exits non-zero on any failure.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/one-word-wifi-out python3 main.py
cat /tmp/one-word-wifi-out/entry.txt
# Ghosting
```

## Files

- `entry.txt` — the exact single-word entry (`Ghosting`, 8 characters).
- `main.py` — writes and self-verifies the entry.
- `README.md` — this file.
- `LICENSE` — MIT.

## Bounty

- Competition: https://make.fun/c/u-tuan-muda-one-word-for-your-wi-fi-a1b4fd72
- Prize: $2 (1st place)
- Deadline: 2026-11-28T11:35Z
- Entry: free, no entry fee.
