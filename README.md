# Fibonacci Practice

Middle school competitive programming practice using Blockly.

**Live site → https://drtechniko.github.io/fibonacci-practice/**

---

## What it is

16 standalone, browser-based problems built with [Blockly](https://developers.google.com/blockly). Each problem has:
- 4 progressive difficulty levels
- Auto-grading with immediate feedback
- Confetti on completion 🎉

No installation needed — students open the live site, click a problem, and start dragging blocks.

---

## Repo structure

```
simulation/
  easy/       backpack-weight, best-score, passing-grade, even-candy-count
  medium/     apple-picking, bank-account, rabbit-colony
  hard/       complete-rectangle
greedy/
  easy/       shop-bargains
  medium/     project-portfolio
  hard/       road-trip-fuel
dp/
  easy/       staircase, coin-change
  medium/     frog-jump, broken-calculator
  hard/       super-frog
index.html    ← GitHub Pages landing page (password-protected)
```

Files are named by problem slug only (e.g. `backpack-weight.html`). Category and difficulty are encoded in the folder path.

---

## Recommended teaching order

### Phase 1 — Foundations
| # | Problem | Pattern |
|---|---------|---------|
| 1 | 🎒 Backpack Weight | Loop + accumulate (sum of array) |
| 2 | 🏆 Best Score | Loop + find max |
| 3 | 🎯 Passing Grade | Loop + count with condition |
| 4 | 🍬 Even Candy Count | Loop + filtered sum + modulo |

### Phase 2 — Core Patterns
| # | Problem | Pattern |
|---|---------|---------|
| 5 | 🍎 Apple Picking | Loop + min-capped sum |
| 6 | 🏦 Bank Account | Running state + peak tracking + validity flag |
| 7 | 🐰 Rabbit Colony | Loop with formula (floor division) |
| 8 | 💼 Project Portfolio | Greedy: sum only positive values |
| 9 | 🏪 Shop Bargains | Greedy: budget management |

### Phase 3 — Challenge (Hard Sim + Greedy)
| # | Problem | Pattern |
|---|---------|---------|
| 10 | 📐 Complete the Rectangle | Pure conditional logic — no loops |
| 11 | ⛽ Road Trip Fuel | Greedy: just-in-time resource management |

### Phase 4 — Intro DP
| # | Problem | Pattern |
|---|---------|---------|
| 12 | 🪜 Staircase Climbing | dp[i] = dp[i−1] + dp[i−2] (count ways) |
| 13 | 🪙 Coin Change | dp[i] = min(dp[i−1], dp[i−3]) + 1 (minimize coins) |

### Phase 5 — DP Mastery
| # | Problem | Pattern |
|---|---------|---------|
| 14 | 🐸 Frog Jump | dp[i] = min cost, 2 jump options + array input |
| 15 | 🔢 Broken Calculator | Work backwards with while loop (÷2 or −1) |
| 16 | 🐸 Super Frog Jump | 3 jump options + forbidden platform checks |

---

## Problem index

| Problem | File | Category | Difficulty |
|---------|------|----------|------------|
| 🎒 Backpack Weight | `simulation/easy/backpack-weight.html` | Simulation | Easy |
| 🏆 Best Score | `simulation/easy/best-score.html` | Simulation | Easy |
| 🎯 Passing Grade | `simulation/easy/passing-grade.html` | Simulation | Easy |
| 🍬 Even Candy Count | `simulation/easy/even-candy-count.html` | Simulation | Easy |
| 🍎 Apple Picking | `simulation/medium/apple-picking.html` | Simulation | Medium |
| 🏦 Bank Account | `simulation/medium/bank-account.html` | Simulation | Medium |
| 🐰 Rabbit Colony | `simulation/medium/rabbit-colony.html` | Simulation | Medium |
| 📐 Complete the Rectangle | `simulation/hard/complete-rectangle.html` | Simulation | Hard |
| 🏪 Shop Bargains | `greedy/easy/shop-bargains.html` | Greedy | Easy |
| 💼 Project Portfolio | `greedy/medium/project-portfolio.html` | Greedy | Medium |
| ⛽ Road Trip Fuel | `greedy/hard/road-trip-fuel.html` | Greedy | Hard |
| 🪜 Staircase Climbing | `dp/easy/staircase.html` | Dynamic Programming | Easy |
| 🪙 Coin Change | `dp/easy/coin-change.html` | Dynamic Programming | Easy |
| 🐸 Frog Jump | `dp/medium/frog-jump.html` | Dynamic Programming | Medium |
| 🔢 Broken Calculator | `dp/medium/broken-calculator.html` | Dynamic Programming | Medium |
| 🐸 Super Frog Jump | `dp/hard/super-frog.html` | Dynamic Programming | Hard |

---

## Not yet built

- **Dynamic Programming:** Stack the Boxes
- **More Simulation:** Ancient Fossils, Wheel of Fortune, Ant Competition, Carrot Monologue, Love Letters, Toy Soldier Field
- **More Greedy:** Share the Chocolate, Dice Counterfeiting, Painting the Wall, Robot Collecting, Asocial Network
