# Course Material Conventions

Every course in the series is **self-contained**: its notes, worked examples
and exercises with full solutions are enough to complete it without any other
book. External reading is always optional.

## Layout

```
courses/
  <CODE>/
    README.md                     syllabus: overview, lesson list, status
    lessons/<unit>.<n>-<slug>.md  one file per lesson
```

## Lesson structure

Each lesson has the same sections, in this order:

1. **Goals.** What the learner will be able to do afterwards.
2. **Notes.** The theory: motivation, definitions, theorems and their proofs
   (or an honest proof sketch, saying where the full proof is given).
3. **Worked examples.** Fully solved problems that show the methods.
4. **Common mistakes.** Errors learners typically make, and why they are wrong.
5. **Exercises.** In three tiers:
   - **A**, routine: direct use of the definitions and methods.
   - **B**, standard: needs several steps or a short argument.
   - **C**, challenge: a harder problem or a proof.

   Every exercise has a full solution, hidden in a collapsible block so the
   learner can try the problem first.
6. **Summary.** The key facts in a few lines.

## Formatting

- Mathematics is written in LaTeX between `$...$` (inline) and `$$...$$`
  (display), which GitHub renders.
- Definitions, theorems and proofs are marked with bold labels:
  **Definition 2**, **Theorem 3**, *Proof.* … ∎. Numbering restarts in each
  lesson; a reference to another lesson includes its number (Theorem 3 of
  Lesson 0.1).
- ℕ = {1, 2, 3, …} (zero is not a natural number).
