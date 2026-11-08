# Results, generated from the scorecards

20 runs per test: 10 on the layout of held-out episode 4 (the left arm picks the cup up) and 10 on episode 14's (the right arm does). The same starts for both policies.

| Trained on | Test | Placed (95% interval) | Episode 4 | Episode 14 | Misses |
|---|---|---|---|---|---|
| baseline | Room light | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 12 |
| baseline | Low light (30–60%) | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 17, lifted the cup, not in the tray at the end 1 |
| baseline | Warm light (2,700–3,500 K) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 20 |
| baseline | Extra objects | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 12 |
| all seven | Room light | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 5 |
| all seven | Low light (30–60%) | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 5 |
| all seven | Warm light (2,700–3,500 K) | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 16, lifted the cup, not in the tray at the end 3 |
| all seven | Extra objects | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 18, lifted the cup, not in the tray at the end 2 |

## Paired, run by run on the same starts

| Test | Only the `baseline` policy placed | Only the all-seven policy placed | Exact McNemar p |
|---|---|---|---|
| Room light | 6 | 0 | 0.031 |
| Low light (30–60%) | 1 | 1 | 1.0 |
| Warm light (2,700–3,500 K) | 0 | 1 | 1.0 |
| Extra objects | 8 | 0 | 0.008 |
