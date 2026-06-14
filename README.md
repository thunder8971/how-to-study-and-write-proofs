# How to Study and Write Proofs

This repository contains a short technical-pedagogical essay about learning mathematical proofs through understanding, strategy, formal writing, and active reflection.

The essay introduces the **Proof Reconstruction Cycle**, a five-stage method for studying and writing proofs:

1. **Decode:** understand the statement, objects, hypotheses, conclusion, and relevant definitions.
2. **Explain:** describe in your own words why the result should make sense.
3. **Strategize:** choose a proof pattern that can turn intuition into a rigorous argument.
4. **Prove:** write the proof with justified formal steps.
5. **Reflect:** identify the essential idea, extract reusable patterns, and reconstruct the proof from its structure without memorizing the exact wording.

The cycle is organized into three phases:

1. **Understanding:** Decode -> Explain
2. **Construction:** Strategize -> Prove
3. **Internalization:** Reflect

## Read

* [PDF version](main.pdf)
* Source: [`main.tex`](main.tex)
* Bibliography: [`references.bib`](references.bib)

## Build

To compile the essay with BibTeX:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

You can also use `latexmk` if it is available:

```bash
latexmk -pdf main.tex
```

## Repository Structure

```text
main.tex          Main LaTeX source
references.bib    Bibliography entries
graphics/         Cover image and visual assets
langs/            Future translations
LICENSE.md        License and attribution terms
```

## License

Unless otherwise noted, the original essay text and educational material in
this repository are licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
License](LICENSE.md).

Please attribute the work to **Ricardo Paredes** when sharing, adapting, or
translating it.

## Contributing

Corrections, suggestions, LaTeX improvements, and translations are welcome. Please see [`CONTRIBUTING.md`](CONTRIBUTING.md).
