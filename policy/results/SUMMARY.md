# Results, generated from the scorecards

20 runs per test: 10 on the layout of held-out episode 4 (the left arm picks the cup up) and 10 on episode 14's (the right arm does). The same starts for every policy.

| Trained on | Steps | Test | Placed (95% interval) | Episode 4 | Episode 14 | Misses |
|---|---|---|---|---|---|---|
| real recordings | 30,000 | Room light | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| real recordings | 30,000 | Low light (30–60%) | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 9, lifted the cup, not in the tray at the end 3 |
| real recordings | 30,000 | Warm light (2,700–3,500 K) | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 11, lifted the cup, not in the tray at the end 1 |
| real recordings | 30,000 | Extra objects | 7/20 (35%, 18–57%) | 7/10 | 0/10 | never lifted the cup 9, lifted the cup, not in the tray at the end 4 |
| baseline | 30,000 | Room light | 5/20 (25%, 11–47%) | 5/10 | 0/10 | never lifted the cup 11, lifted the cup, not in the tray at the end 4 |
| baseline | 30,000 | Low light (30–60%) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 20 |
| baseline | 30,000 | Warm light (2,700–3,500 K) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 20 |
| baseline | 30,000 | Extra objects | 7/20 (35%, 18–57%) | 7/10 | 0/10 | never lifted the cup 11, lifted the cup, not in the tray at the end 2 |
| all seven | 30,000 | Room light | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 14, lifted the cup, not in the tray at the end 4 |
| all seven | 30,000 | Low light (30–60%) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 15, lifted the cup, not in the tray at the end 5 |
| all seven | 30,000 | Warm light (2,700–3,500 K) | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 16, lifted the cup, not in the tray at the end 1 |
| all seven | 30,000 | Extra objects | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 19 |
| baseline | 90,000 | Room light | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 9, lifted the cup, not in the tray at the end 3 |
| baseline | 90,000 | Low light (30–60%) | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 14, lifted the cup, not in the tray at the end 3 |
| baseline | 90,000 | Warm light (2,700–3,500 K) | 5/20 (25%, 11–47%) | 5/10 | 0/10 | never lifted the cup 15 |
| baseline | 90,000 | Extra objects | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| all seven | 90,000 | Room light | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 5 |
| all seven | 90,000 | Low light (30–60%) | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 5 |
| all seven | 90,000 | Warm light (2,700–3,500 K) | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 15, lifted the cup, not in the tray at the end 4 |
| all seven | 90,000 | Extra objects | 3/20 (15%, 5–36%) | 3/10 | 0/10 | never lifted the cup 15, lifted the cup, not in the tray at the end 2 |

## Paired, run by run on the same starts

### real recordings at 30,000 steps against `baseline` at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 5 | 0 | 0.062 |
| Low light (30–60%) | 8 | 0 | 0.008 |
| Warm light (2,700–3,500 K) | 8 | 0 | 0.008 |
| Extra objects | 1 | 1 | 1.0 |

### real recordings at 30,000 steps against all seven at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 8 | 0 | 0.008 |
| Low light (30–60%) | 8 | 0 | 0.008 |
| Warm light (2,700–3,500 K) | 6 | 1 | 0.125 |
| Extra objects | 6 | 0 | 0.031 |

### real recordings at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 2 | 0 | 0.5 |
| Low light (30–60%) | 6 | 1 | 0.125 |
| Warm light (2,700–3,500 K) | 4 | 1 | 0.375 |
| Extra objects | 0 | 3 | 0.25 |

### real recordings at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 8 | 0 | 0.008 |
| Low light (30–60%) | 5 | 0 | 0.062 |
| Warm light (2,700–3,500 K) | 7 | 0 | 0.016 |
| Extra objects | 4 | 0 | 0.125 |

### `baseline` at 30,000 steps against all seven at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 5 | 2 | 0.453 |
| Low light (30–60%) | 0 | 0 | 1.0 |
| Warm light (2,700–3,500 K) | 0 | 3 | 0.25 |
| Extra objects | 6 | 0 | 0.031 |

### `baseline` at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 1 | 4 | 0.375 |
| Low light (30–60%) | 0 | 3 | 0.25 |
| Warm light (2,700–3,500 K) | 0 | 5 | 0.062 |
| Extra objects | 0 | 3 | 0.25 |

### `baseline` at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 4 | 1 | 0.375 |
| Low light (30–60%) | 0 | 3 | 0.25 |
| Warm light (2,700–3,500 K) | 0 | 1 | 1.0 |
| Extra objects | 5 | 1 | 0.219 |

### all seven at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 6 | 0.031 |
| Low light (30–60%) | 0 | 3 | 0.25 |
| Warm light (2,700–3,500 K) | 0 | 2 | 0.5 |
| Extra objects | 0 | 9 | 0.004 |

### all seven at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 2 | 2 | 1.0 |
| Low light (30–60%) | 0 | 3 | 0.25 |
| Warm light (2,700–3,500 K) | 3 | 1 | 0.625 |
| Extra objects | 1 | 3 | 0.625 |

### `baseline` at 90,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 6 | 0 | 0.031 |
| Low light (30–60%) | 3 | 3 | 1.0 |
| Warm light (2,700–3,500 K) | 5 | 1 | 0.219 |
| Extra objects | 7 | 0 | 0.016 |
