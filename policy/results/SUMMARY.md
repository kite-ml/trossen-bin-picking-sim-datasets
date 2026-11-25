# Results, generated from the scorecards

20 runs per test: 10 on the layout of held-out episode 4 (the left arm picks the cup up) and 10 on episode 14's (the right arm does). The same starts for every policy.

| Trained on | Steps | Test | Placed (95% interval) | Episode 4 | Episode 14 | Misses |
|---|---|---|---|---|---|---|
| real recordings | 30,000 | Room light | 9/20 (45%, 26–66%) | 9/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 1 |
| real recordings | 30,000 | Low light (30–60%) | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 12 |
| real recordings | 30,000 | Warm light (2,700–3,500 K) | 9/20 (45%, 26–66%) | 9/10 | 0/10 | never lifted the cup 11 |
| real recordings | 30,000 | Extra objects | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 2 |
| baseline | 30,000 | Room light | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 9 |
| baseline | 30,000 | Low light (30–60%) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 8 |
| baseline | 30,000 | Warm light (2,700–3,500 K) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 13, lifted the cup, not in the tray at the end 7 |
| baseline | 30,000 | Extra objects | 2/20 (10%, 3–30%) | 2/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 6 |
| all seven | 30,000 | Room light | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| all seven | 30,000 | Low light (30–60%) | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| all seven | 30,000 | Warm light (2,700–3,500 K) | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| all seven | 30,000 | Extra objects | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| baseline | 90,000 | Room light | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| baseline | 90,000 | Low light (30–60%) | 1/20 (5%, 1–24%) | 1/10 | 0/10 | never lifted the cup 19 |
| baseline | 90,000 | Warm light (2,700–3,500 K) | 0/20 (0%, 0–16%) | 0/10 | 0/10 | never lifted the cup 20 |
| baseline | 90,000 | Extra objects | 5/20 (25%, 11–47%) | 5/10 | 0/10 | never lifted the cup 12, lifted the cup, not in the tray at the end 3 |
| all seven | 90,000 | Room light | 9/20 (45%, 26–66%) | 9/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 1 |
| all seven | 90,000 | Low light (30–60%) | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |
| all seven | 90,000 | Warm light (2,700–3,500 K) | 8/20 (40%, 22–61%) | 8/10 | 0/10 | never lifted the cup 10, lifted the cup, not in the tray at the end 2 |
| all seven | 90,000 | Extra objects | 10/20 (50%, 30–70%) | 10/10 | 0/10 | never lifted the cup 10 |

## Paired, run by run on the same starts

### real recordings at 30,000 steps against `baseline` at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 8 | 0 | 0.008 |
| Low light (30–60%) | 8 | 0 | 0.008 |
| Warm light (2,700–3,500 K) | 9 | 0 | 0.004 |
| Extra objects | 6 | 0 | 0.031 |

### real recordings at 30,000 steps against all seven at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 1 | 1.0 |
| Low light (30–60%) | 0 | 2 | 0.5 |
| Warm light (2,700–3,500 K) | 0 | 1 | 1.0 |
| Extra objects | 0 | 2 | 0.5 |

### real recordings at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 1 | 1.0 |
| Low light (30–60%) | 7 | 0 | 0.016 |
| Warm light (2,700–3,500 K) | 9 | 0 | 0.004 |
| Extra objects | 3 | 0 | 0.25 |

### real recordings at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 1 | 1 | 1.0 |
| Low light (30–60%) | 0 | 2 | 0.5 |
| Warm light (2,700–3,500 K) | 2 | 1 | 1.0 |
| Extra objects | 0 | 2 | 0.5 |

### `baseline` at 30,000 steps against all seven at 30,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 9 | 0.004 |
| Low light (30–60%) | 0 | 10 | 0.002 |
| Warm light (2,700–3,500 K) | 0 | 10 | 0.002 |
| Extra objects | 0 | 8 | 0.008 |

### `baseline` at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 9 | 0.004 |
| Low light (30–60%) | 0 | 1 | 1.0 |
| Warm light (2,700–3,500 K) | 0 | 0 | 1.0 |
| Extra objects | 0 | 3 | 0.25 |

### `baseline` at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 8 | 0.008 |
| Low light (30–60%) | 0 | 10 | 0.002 |
| Warm light (2,700–3,500 K) | 0 | 8 | 0.008 |
| Extra objects | 0 | 8 | 0.008 |

### all seven at 30,000 steps against `baseline` at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 0 | 0 | 1.0 |
| Low light (30–60%) | 9 | 0 | 0.004 |
| Warm light (2,700–3,500 K) | 10 | 0 | 0.002 |
| Extra objects | 5 | 0 | 0.062 |

### all seven at 30,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 1 | 0 | 1.0 |
| Low light (30–60%) | 0 | 0 | 1.0 |
| Warm light (2,700–3,500 K) | 2 | 0 | 0.5 |
| Extra objects | 0 | 0 | 1.0 |

### `baseline` at 90,000 steps against all seven at 90,000 steps

| Test | Only the first placed | Only the second placed | Exact McNemar p |
|---|---|---|---|
| Room light | 1 | 0 | 1.0 |
| Low light (30–60%) | 0 | 9 | 0.004 |
| Warm light (2,700–3,500 K) | 0 | 8 | 0.008 |
| Extra objects | 0 | 5 | 0.062 |
