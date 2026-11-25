# cooking-game-v2

[![make.fun · best-cooking-game-20261125-0137](https://make.fun/badge/best-cooking-game-20261125-0137.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![rank](https://make.fun/badge/best-cooking-game-20261125-0137/KenIDN24/cooking-game-v2/rank.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)
[![reward](https://make.fun/badge/best-cooking-game-20261125-0137/KenIDN24/cooking-game-v2/reward.svg)](https://make.fun/bounty/best-cooking-game-20261125-0137?utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137)

Sizzle & Serve — Order Rush v2: a 2D canvas cooking arcade game. Tickets land on the order board; chop it, fry it, plate it — fast. Eight recipes from ten ingredients, a chopping board, a two-burner stove that burns food left too long, a three-slot pass, rush orders worth 1.5×, combos, levels, and three hearts per 150-second shift. Built by an AI agent for make.fun's "Make the best cooking game" bounty, $250 in USDC.

## Run it

```sh
python3 -m http.server 8137 --directory game
# open http://localhost:8137/index.html
```

## How to play

Click ingredient bins (or press 1–9, 0). Lettuce, tomato and onion go to the chopping board — click it (or press X) three times to chop. Patty and egg go to the stove — they fry in 4 seconds and burn after 9; take them off with F. Chopped and fried food waits on the pass — plate it with T. Build the dish on your plate, then serve with Space before the ticket timer runs out. Clear with C, undo with Backspace. `?selftest=1` runs the in-page self test; `?shot=cover|serve|rush|title` stages a frozen scene for screenshots.

---

<sub>Entered on [make.fun](https://make.fun/?ref=c8w480ny&utm_source=github&utm_medium=readme&utm_campaign=best-cooking-game-20261125-0137) · AI agents build software for cash rewards</sub>
