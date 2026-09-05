---
layout: default
title: Errata
---

<p class="section-label">Corrections</p>

# Errata

Corrections to the English VitalSource Bookshelf edition of *Programming in
Python Fundamentals*, sorted by section. Each
entry gives the section and print page number so you can jump straight to it in
Bookshelf, plus a severity tag - Serious (affects your code), Moderate (a figure
or explanation is wrong), or Minor (a typo). Spotted an error we have not listed
yet? Please email [frode.nasje@gmail.com](mailto:frode.nasje@gmail.com).

*Last updated: 4 Sep 2026*

| Section | Page | Severity | Reads | Should read |
|:-------:|:----:|:--------:|-------|-------------|
| 2.1 | 33 | <span class="sev sev-low">Minor</span> | `DateTime` | `datetime` |
| 2.5.1 | 40 | <span class="sev sev-med">Moderate</span> | Figure: `a` points to the value 20. | Figure should show the state *before* `a` is reassigned - `a` points to 10. Correct figure below.<br>[![Correct figure for section 2.5.1](images/immutable-int-before.png)](images/immutable-int-before.png) |
| 2.5.2 | 41 | <span class="sev sev-low">Minor</span> | `comparison operator` | comparison operator (wrong font)|
| 4.4 | 98 | <span class="sev sev-low">Minor</span> | "...it could of course have been any current." | "...it could of course have been any currency." |
| 4.4.3 | 105 | <span class="sev sev-high">Serious</span> | Wrong indentation in the code example. | Correct indentation in figure below.<br>[![Correct indentation](images/correct-indentation.png)](images/correct-indentation.png) |
| 4.8 | 111 | <span class="sev sev-med">Moderate</span> | `match_day` | `match day` |
| 5.11.2 | 139 | <span class="sev sev-low">Minor</span> | The code snippet showing ways to make shallow copy has a misleading comment (an import statement is misplaced) | Correct code below.<br>[![Correct code](images/correct-code-in-section-5-11-2.png)](images/correct-code-in-section-5-11-2.png) ||
| 13 | 465 | <span class="sev sev-low">Minor</span> | tion | function |
{:.errata-table}
