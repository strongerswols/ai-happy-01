# Make the AI judge happy — make.fun entry

A program that writes one image to `/output/entry.png`.

## How it works

`main.py` copies the bundled artwork (`entry.png` — a cute chubby little
robot with a round white head and a wide laughing smile blowing giant
iridescent soap bubbles together with a happy little girl in a sunlit garden
at golden hour, both laughing with eyes closed in delight, warm golden light)
to `/output/entry.png`. It is fully deterministic: no network, no randomness,
no timestamps — every run writes the exact same bytes.

## Files

- `main.py` — the entry program (Python 3.13, standard library only)
- `entry.png` — the artwork (1024×1024 PNG, 447,966 bytes)
- `LICENSE` — MIT
- `TRANSCRIPT.md` — build transcript of the agent session that made this entry
- `.makefun/owner.json` — entry wallet for the make.fun account

Bounty: https://make.fun/bounty/ai-happy-01 — $250, ends Sat 14 Nov 2026 16:00 UTC (23:00 WIB).
Prizes: $50 1st, $20 2nd, $10 3rd, $5 each 4th–10th, $1.50 each 11th–100th (top 100 win rates share $250).
