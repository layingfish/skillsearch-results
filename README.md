# SkillSearch Results Explorer

Static retrieval-results explorer for the 75-query SkillRouter official core benchmark.

- Compare five frozen runs on the same 75 rows and 14,551-skill canonical candidate pool:
  LETTER base data (single-SID), LETTER enhanced data (single-SID), LETTER enhanced data
  (multi-SID), our reproduced SkillsRouter SR-Emb, and the official SkillsRouter SR-Emb checkpoint.
- The LETTER base run uses 94,912 source rows. The enhanced runs use 100,078 rows after
  adding 5,166 task-style queries for skills with no multi-skill co-occurrence.
- Inspect ground-truth coverage or every retrieved Top-K skill.
- View Hit, official macro Recall, and Full Coverage at 1/10/50 with formulas and values.
- Expand a result to see only the skill name and description.

The site is published from `index.html` with GitHub Pages.
