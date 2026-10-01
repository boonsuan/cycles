# Decomposing a graph into linearly many cycles and edges

An expository write-up of a proof of the Erdős–Gallai cycle decomposition
conjecture (Erdős Problem #184): every graph on `n` vertices decomposes into
`O(n)` cycles and edges.

**Status: this write-up is entirely AI-generated (author: Claude Opus 5.5).
At the time of posting, 1 October 2026, no human has read or understood this
proof.** It is meant as a stopgap: an intermediate artifact between Ryan
Coffey's proof claim and a final proof that humans have read, understood and
digested. It has not been refereed or formally verified, and it should not be
cited as an established result.

The argument reorganises and simplifies the proof claimed by Ryan Coffey
(<https://github.com/steelwheel01/erdos-gallai-lean>), which builds on the
method of Bucić and Montgomery (arXiv:2211.07689). Section 7 of the paper lists
the source of every ingredient.

## Files

- `erdos-gallai.tex`: the paper, a single self-contained LaTeX file with TikZ figures.
- `erdos-gallai.pdf`: the compiled paper.
- `archive/astra-draft.tex`: the earlier condensed draft that this version rewrites.

## Building

```sh
pdflatex erdos-gallai.tex && pdflatex erdos-gallai.tex
```

This needs a standard TeX Live installation, including the `tikz`, `cleveref`,
`enumitem`, `booktabs` and `lmodern` packages.
