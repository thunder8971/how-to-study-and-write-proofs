# Contributing

Thank you for your interest in contributing.

This repository contains a short educational essay titled **How to Study and Write Proofs**. The goal is to make the study of mathematical proofs more practical and accessible through the Proof Reconstruction Cycle.

## Scope

This is a technical-pedagogical essay, not a formal research paper. Contributions should preserve that style: clear, serious, useful, and readable.

Please avoid changes that:

* turn the essay into a broad literature review;
* make the tone too informal or too academic;
* change the central thesis of the Proof Reconstruction Cycle;
* add unsupported claims or unnecessary citations;
* remove the didactic example without replacing it with something equally clear.

## Useful Contributions

You can contribute by:

* fixing typos, grammar, or formatting issues;
* improving clarity without changing the main argument;
* improving LaTeX structure or compilation;
* suggesting better examples or explanations;
* improving existing references;
* adding translations.

## Writing Guidelines

When editing the essay, please keep the following structure in mind:

* **Decode:** understand definitions, hypotheses, objects, and conclusion.
* **Explain:** give an intuitive explanation in plain mathematical language.
* **Strategize:** choose a proof pattern.
* **Prove:** write a formal proof with justified steps.
* **Reflect:** extract the key idea, identify reusable patterns, and reconstruct the argument from its structure.

The essay should remain accessible to students who are learning how to read and write proofs.

## References

New references are welcome only when they support a real addition to the text. Please do not add citations just to expand the bibliography.

If you add or change citations, update [`references.bib`](references.bib) and make sure the citation keys used in `main.tex` exist in the bibliography.

## Translations

Translations should be placed inside the `langs/` folder using a standard language code.

Examples:

```text
langs/es/
langs/pt/
langs/fr/
```

Each translation should preserve the main meaning of the original essay. Small adaptations are fine when they improve clarity in the target language.

## License and Authorship

By contributing, you agree that your contribution will be distributed under the same license as the project: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).

Please preserve attribution to **Ricardo Paredes** as the original author of the essay. Translations, corrections, and adaptations should clearly indicate when changes were made.

## LaTeX

The main source file is:

```text
main.tex
```

To compile the essay with BibTeX:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Do not commit LaTeX auxiliary files such as `.aux`, `.log`, `.bbl`, `.blg`, `.out`, or `.toc`.

## Pull Requests

When opening a pull request, briefly explain what you changed and why.

Good examples:

```text
Fix typo in the Decode section
Improve explanation of the Reflect stage
Correct citation key in the Strategize section
Add Spanish translation
```
