# Assignment---Topsis-102303943
# TOPSIS Fund Ranking System

This project implements the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method in Python to rank mutual funds (or any alternatives) based on multiple criteria.

---

##  What is TOPSIS?

TOPSIS is a multi-criteria decision-making (MCDM) technique that ranks alternatives based on their distance from:
- the **ideal best** solution, and
- the **ideal worst** solution.

The best alternative is the one closest to the ideal best and farthest from the ideal worst.

---

##  Dataset Format

Your input CSV file should follow this structure:

| Fund | P1 | P2 | P3 | P4 | P5 |
|------|----|----|----|----|----|
| Fund A | ... | ... | ... | ... | ... |
| Fund B | ... | ... | ... | ... | ... |

If your file already contains columns like `D+`, `D-`, `TOPSIS_Score`, or `Rank`, they will be automatically removed before recalculating.

---

## Requirements

Install required libraries:

```bash
pip install pandas numpy
