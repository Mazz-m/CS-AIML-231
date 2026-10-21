# Lab W04 — Be the AI: train a paper model
Pairs · 55 min core (1:15–2:10) + extension to 3:00 · worksheet + oral share

**Objective:** train a tiny model on paper. Pick features, build a rule from the training set ONLY, then test it on unseen tomatoes and compute its accuracy — exactly how real models are trained and honestly tested.

## The rules of honesty (read aloud)
1. **The training set is your textbook.** Build your rule ONLY from these 9 tomatoes.
2. **The test set is your exam — closed book.** You may NOT look at the 3 test answers until after you have predicted them. Cover the answer column with a folded paper.
3. No peeking = no cheating yourself. Peeking is testing on training data (W04's big sin).

## Dataset card — 12 tomatoes
| ID | Colour (1=green · 2=light · 3=red) | Firmness (1=hard · 2=soft) | Size | **Ripe? (do NOT read until step 3)** |
|---|---|---|---|---|
| A1 | 1 | 1 | S | no |
| A2 | 1 | 2 | M | no |
| A3 | 2 | 1 | S | no |
| A4 | 2 | 2 | L | no |
| A5 | 3 | 1 | M | no |
| A6 | 3 | 1 | L | no |
| A7 | 3 | 2 | S | yes |
| A8 | 3 | 2 | M | yes |
| A9 | 2 | 2 | S | no |
| **U1** | **3** | **2** | **L** | **?? — TEST** |
| **U2** | **1** | **2** | **L** | **?? — TEST** |
| **U3** | **3** | **1** | **S** | **?? — TEST** |

Rows A1–A9 = **training**. Rows U1–U3 = **test** (their answers are on the last line of this sheet, upside down).

## Steps (timeboxed)
1. **Study the training set (10 min):** what makes a tomato ripe? Colour alone? Firmness alone? Both? Write your best rule as ONE sentence: *"Ripe IF … "*. Test it against ALL 9 training rows — it must get all 9 right.
2. **Lock the rule (2 min):** cover the test column. Announce your rule to your partner. No changes after this point.
3. **Predict the test (8 min):** apply your rule to U1, U2, U3. Write your predictions first, THEN reveal the answers.
4. **Score it (5 min):** accuracy = correct predictions ÷ 3. Whole-class scoreboard: how many pairs got 3/3?
5. **Reflect (20 min, with checkpoint):** show the checkpoint chart; answer the judge's question in writing.

## The rule worth finding
Ripe = **colour 3 AND firmness 2**. Everything else is not ripe. (Check it against all 9 training rows — it fits; a rule like "colour 3 = ripe" does NOT fit, because A5 and A6 are hard and unripe.)

## Deliverable
Your written rule + the 3 test predictions with scores (e.g. "2/3 correct"). Earns the week's lab mark (Labs 20%).

---
**Test answers (fold this line):** U1 = yes · U2 = no · U3 = no. Correct rule: **colour 3 AND soft → ripe.**