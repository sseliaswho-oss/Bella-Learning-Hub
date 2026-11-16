# Bella's Maths Quest v1.6 — Textbook-Aligned Problem Solving

**English-only, single-file website.** No AI, account, server, internet connection or extra files are required.

## What changed?

This version keeps the existing **37 Maths Olympiad chapters** and the separate **8-unit / 16-lesson Problem Solving** programme. All **16 Problem Solving guided examples** and the question generators for **all 16 lessons** have been revised to better match *Problem Solving Beyond the Classroom — Primary 2* (Bernice Lau Pui Wah), including the book's numerical range and multi-step reasoning.

The learning sequence includes:

1. Addition & Patterns — three-digit addition, multi-step part–whole problems and later sequence terms.
2. Subtraction & Diagrams — bar comparisons, sum-and-difference problems, queues and multi-step movements.
3. Multiplication & Lists — proportional comparisons, multiple groups and systematic listing.
4. Division & Working Backwards — equal-part models and reversing operations in order.
5. Money & Check — money comparison, multi-step purchases, score problems and systematic guessing.
6. Fractions & Tables — genuine fraction answers (e.g. `5/12`), table patterns, running totals and combinations.
7. Measures & Gaps — mass comparison, real measurement units and endpoint/loop interval counting.
8. Graphs & Shapes — pictograph keys, comparisons, squares, borders and growing geometry patterns.

Each lesson has a four-stage guided example with hidden help, a fresh transfer question and eight practice questions. Every unit retains two optional Thinking Cap challenges. All questions, text and models in this module are newly written or generated for the website; textbook pages have not been copied.

## Fractions

Questions about fractions accept forms such as `5/12`, `1/2` or equivalent values. For example, if the answer is `6/12`, typing `1/2` also works. Other questions accept whole-number answers.

## How to update the existing GitHub Pages site

**Protect your progress first.** Open the current Maths Quest website, navigate to **Parent Corner → Export progress**, and save the exported backup file somewhere safe.

Then:

1. Open the GitHub repository that currently hosts Bella's Maths Quest.
2. Replace the existing `index.html` in the same folder with the `index.html` in this ZIP.
3. Commit the change and open the **same GitHub Pages URL** once it has deployed.
4. Confirm the older completed lessons and progress still appear. If they do not, go to **Parent Corner → Import progress** and select the backup exported before updating.

The app intentionally keeps its original browser storage key (`bella-maths-quest-v1`) and local save/backup format. It does **not** reset old scores, saved lessons or ongoing sessions. Previously completed guided examples remain completed; press **Repeat guided example** if you would like Bella to try the revised teaching example and then use **Practise with fresh questions**. Do not clear browser site data before confirming the backup.

Progress is per browser/device; it does not automatically sync between devices. Publishing to a different GitHub Pages URL changes the website origin and therefore may require importing the backup.

## Test coverage and limits

- JavaScript syntax checked for all three page scripts.
- 38,400 generated questions tested for valid answers and completeness.
- 4,800 full eight-question practice sets verified without repeated questions after the site's normal retry handling.
- Fraction-equivalence and whole-number marking functions tested.
- All eight two-question Thinking Cap collections verified for structurally valid answers.
- Confirmed the 37 Olympiad chapter definitions and original `localStorage` key remain present.

Automated graphical browser navigation was not available in the current test environment, so a complete end-to-end browser interaction test was **not** performed for this particular build. Please initially test one guided example and one practice set on your device before deleting your old version.
