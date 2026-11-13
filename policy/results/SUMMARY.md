# Results, generated from the scorecards

20 runs per test: 10 on the layout of held-out episode 4 (the left arm picks the cup up) and 10 on episode 14's (the right arm does). The same starts for every policy.

| Trained on | Steps | Test | Placed (95% interval) | Episode 4 | Episode 14 | Misses |
|---|---|---|---|---|---|---|
| baseline | 30,000 | Room light | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 12 |
| baseline | 30,000 | Low light (30–60%) | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 17, lifted the cup, not in the tray at the end 1 |
| baseline | 30,000 | Warm light (2,700–3,500 K) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 20 |
| baseline | 30,000 | Extra objects | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 12 |
| all seven | 30,000 | Room light | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 5 |
| all seven | 30,000 | Low light (30–60%) | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 5 |
| all seven | 30,000 | Warm light (2,700–3,500 K) | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 16, lifted the cup, not in the tray at the end 3 |
| all seven | 30,000 | Extra objects | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 18, lifted the cup, not in the tray at the end 2 |
| all seven | 90,000 | Room light | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 2 |
| all seven | 90,000 | Low light (30–60%) | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 5 |
| all seven | 90,000 | Warm light (2,700–3,500 K) | 4/20 (20%, 8–42%) | 4/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 4 |
| all seven | 90,000 | Extra objects | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 5 |

## Paired, run by run on the same starts

### `baseline` at 30,000 steps against all seven at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 6 | 0 | 0.031 |
| Low light (30–60%) | 1 | 1 | 1.0 |
| Warm light (2,700–3,500 K) | 0 | 1 | 1.0 |
| Extra objects | 8 | 0 | 0.008 |

### `baseline` at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 2 | 2 | 1.0 |
| Low light (30–60%) | 2 | 3 | 1.0 |
| Warm light (2,700–3,500 K) | 0 | 4 | 0.125 |
| Extra objects | 5 | 0 | 0.062 |

### all seven at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 6 | 0.031 |
| Low light (30–60%) | 2 | 3 | 1.0 |
| Warm light (2,700–3,500 K) | 1 | 4 | 0.375 |
| Extra objects | 0 | 3 | 0.25 |
