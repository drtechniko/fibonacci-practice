# Fibonacci Practice

Middle school competitive programming practice using Blockly.

**Live site → https://drtechniko.github.io/fibonacci-practice/**

---

## What it is

11 standalone, browser-based problems built with [Blockly](https://developers.google.com/blockly). Each problem has:
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

### Phase 3 — Challenge
| # | Problem | Pattern |
|---|---------|---------|
| 10 | 📐 Complete the Rectangle | Pure conditional logic — no loops |
| 11 | ⛽ Road Trip Fuel | Greedy: just-in-time resource management |

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

---

## Not yet built

- **Dynamic Programming:** Broken Calculator, SuperBunny Speedrun, Stack the Boxes
- **More Simulation:** Ancient Fossils, Wheel of Fortune, Ant Competition, Carrot Monologue, Love Letters, Toy Soldier Field
- **More Greedy:** Share the Chocolate, Dice Counterfeiting, Painting the Wall, Robot Collecting, Asocial Network
