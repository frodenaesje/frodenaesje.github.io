---
layout: default
title: Errata
---

```{=html}
<p class="section-label">
```
Corrections
```{=html}
</p>
```
# Errata

Corrections to the English VitalSource Bookshelf edition of *Programming
in Python Fundamentals*, sorted by section. Each entry gives the section
and print page number so you can jump straight to it in Bookshelf, plus
a severity tag - Serious (affects your code), Moderate (a figure or
explanation is wrong), or Minor (a typo). Spotted an error we have not
listed yet? Please email <frode.nasje@gmail.com>.

*Last updated: 2 Oct 2026*

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
     Section       Page        Severity      Reads                                          Should read
  -------------- --------- ----------------- ---------------------------------------------- ----------------------------------------------------------------------------------------------
       2.1          33       [Minor]{.sev    `DateTime`                                     `datetime`
                               .sev-low}                                                    

      2.5.1         40      [Moderate]{.sev  Figure: `a` points to the value 20.            Figure should show the state *before* `a` is reassigned - `a` points to 10. Correct figure
                               .sev-med}                                                    below.`<br>`{=html}[![Correct figure for section
                                                                                            2.5.1](images/immutable-int-before.png)](images/immutable-int-before.png)

      2.5.2         41       [Minor]{.sev    `comparison operator`                          comparison operator (wrong font)
                               .sev-low}                                                    

       4.4          98       [Minor]{.sev    "...it could of course have been any current." "...it could of course have been any currency."
                               .sev-low}                                                    

      4.4.3         105     [Serious]{.sev   Wrong indentation in the code example.         Correct indentation in figure below.`<br>`{=html}[![Correct
                              .sev-high}                                                    indentation](images/correct-indentation.png)](images/correct-indentation.png)

       4.8          111     [Moderate]{.sev  `match_day`                                    `match day`
                               .sev-med}                                                    

        13          465      [Minor]{.sev    tion                                           function
                               .sev-low}                                                    

      5.11.2        139      [Minor]{.sev    The code snippet showing ways to make shallow  Correct code below.`<br>`{=html}[![Correct
                               .sev-low}     copy has a misleading comment (an import       code](images/correct-code-in-section-5-11-2.png)](images/correct-code-in-section-5-11-2.png)
                                             statement is misplaced)                        

      5.15.1        146     [Moderate]{.sev  Omitted values default to                      These defaults apply left-to-right. With a negative step the direction flips: start defaults
                               .sev-med}     `start → 0, stop → len(sequence), step → 1`.   to the last index, stop goes past the beginning.

      5.15.1        147     [Moderate]{.sev  The comment for this code snippet              Correct comment should read: `<br>`{=html}`<code>`{=html}\#"Helloworld" - None means "use the
                               .sev-med}     `print(s[None:])` is not precise               default`<br>`{=html}\# for this position": start defaults to 0 here`</code>`{=html}

      6.12.1        188     [Moderate]{.sev  The numbered list gives the LEGB scopes in the 1\. Local (L): names defined inside the current function.`<br>`{=html}2. Enclosing (E): names
                               .sev-med}     wrong order, and the Local entry is imprecise. defined in enclosing functions when functions are nested.`<br>`{=html}3. Global (G): names
                                                                                            defined at module level.`<br>`{=html}4. Built-in (B): names provided by Python, such as print,
                                                                                            len, and type.

       7.5          231      [Minor]{.sev    `# Counter({'h': 3, 'i': 2, '': 1})`           `# Counter({'h': 3, 'i': 2,})`
                               .sev-low}                                                    

        9           \-      [Moderate]{.sev  The Chapter 9 exercises contain incomplete or  Exercises 9.1-9.4 use `pytest`. Run each test file from a terminal with
                               .sev-med}     outdated instructions for running the pytest   `python -m pytest <test_file>.py -v`. VS Code's **Run Python File** runs the file as an
                                             tests.                                         ordinary Python program and does not perform pytest test discovery. For exercises that test
                                                                                            code from earlier chapters, the simple approach used in the book is to copy the completed
                                                                                            module being tested into the Chapter 9 exercise folder before running pytest.

      13.3.1        463      [Minor]{.sev    "after the colon is ed"                        "after the colon is returned"
                               .sev-low}                                                    
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

{:.errata-table}
