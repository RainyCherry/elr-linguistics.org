ELR REFERENCE SYSTEM
====================

This package keeps the original ELR layout unchanged.
Only the bibliography system has been added.

Files added:
- elr-unified.bst
- references.bib
- references-examples.bib
- REFERENCES-README.txt

The original elr-style.sty is unchanged.

Reference setup used in main.tex:

    \usepackage[authoryear,round]{natbib}
    \usepackage{elr-style}
    \bibliographystyle{elr-unified}

At the end of the manuscript:

    \bibliography{references}

The sample line:

    \nocite{alexiadou2006}

is included only so the template preview displays one reference even though the
sample article does not cite it in the body. Remove that line in a real article
once normal \citet{...} or \citep{...} citations are present.

Compile in this order:
1. XeLaTeX
2. BibTeX
3. XeLaTeX
4. XeLaTeX
