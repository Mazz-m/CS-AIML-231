# Lab W03 — Build a Clean Dataset: Mogadishu Rainfall
Pairs · 55 min core (1:15–2:10) + extension to 3:00 · Google Sheets (paper version available)

**Objective:** build a structured, clean, charted rainfall dataset — then honestly judge whether it is enough data to advise a farmer.

## Step 1 — Build the sheet (15 min)
1. Open **Google Sheets** (free, any Google account): sheets.new
2. Columns: `Month | Rainfall (mm) | Season | Notes`
3. **Type the data table below exactly as written** — yes, the traps are in there on purpose. That is the point of the exercise.
4. Save as: `W03_<yournames>_rainfall`

### Data table (type exactly as written — no corrections yet)
| Month | Rainfall | Season |
|---|---|---|
| January | 1 | Jiilaal |
| February | 2 | Jiilaal |
| March | 9 | Jiilaal |
| April | 55 | Gu |
| May | 60 | Gu |
| June | 20 | Xagaa |
| July | 9 | Xagaa |
| September | 999 | Xagaa |
| October | 2.95 | Dayr |
| November | 55 | Dayr |
| Nofembar | 20 | Dayr |
| December | 10 | Jiilaal |

(Note: there is no August row — that is trap #1. Do not add it yet.)

## Step 2 — Clean it (20 min)
Find and fix every planted trap; **log each fix in the Notes column** (your data diary):
- **Missing month?** (August vanished — add it back with a sensible value and note it)
- **Wrong units?** (one cell is in *inches* — convert: × 25.4, then label it mm)
- **Renamed month?** (November appears twice — decide and standardise)
- **Outlier?** (a fat-fingered rainfall of 999 mm — question it, correct it, note it)

Rules: every fix gets a note · no silent fixes · "I don't know the true value" is a valid note.

## Step 3 — Chart and judge (20 min)
1. Select Month + Rainfall columns → Insert → Chart → **Line chart**
2. Read the shape: when are the wet months (Gu ~Apr–May, Dayr ~Oct–Nov)? When dry (Xagaa, Jiilaal)?
3. **Final question (write it down, be honest):** is 12 months of Mogadishu rainfall ENOUGH to advise a farmer? Yes/no + why. No right answer — just thinking.

## Step 4 — Checkpoint (in step 3)
"Which hurt the chart more: the missing August or the inches cell? Why?"
Expected: the missing row — it silently bends the season curve; the units error gets caught and fixed.

## Instructor reference (do not hand out)
**Cleaned series:** Jan 1 · Feb 2 · Mar 9 · Apr 55 · May 60 · Jun 20 · Jul 9 · Aug 10 · Sep 25 · Oct 75 (2.95 in × 25.4 = 74.9 ≈ 75) · Nov 55 (delete duplicated "Nofembar 20") · Dec 10 — this is exactly the chart embedded in the checkpoint slide of the deck.
**Traps:** August missing (silent) · October 2.95 in (loud, findable) · November/Nofembar duplicate (standardise) · September 999 (outlier).
**Shape:** two wet peaks (Apr–May, Oct–Nov) — Gu and Dayr, matching Somali seasons (illustrative teaching values, NOT official climate data — flag this to students).
**Judgement:** 12 months of one city is NOT enough for real farming advice — an honest "no" is the bias lesson landing.

## Deliverable
Clean sheet + chart + one-sentence judgement. Part of Labs 20%.