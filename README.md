beamer-theme
============

:bar_chart: My sensible LaTeX beamer template for presentations

Inspired by [this post](https://tex.stackexchange.com/a/158657) where by I
wanted a Beamer template that didn't overwhelmingly scream, "I made this with
LaTeX and Beamer."

This repository also contains my notes and resources on how to make good
presentations.

[Experiment Using Overleaf][over]

[over]: https://www.overleaf.com/docs?snip_uri=https://raw.githubusercontent.com/erictleung/beamer-theme/master/present.tex&splash=none

**Table of Contents**

- [Download](#download)
- [Features](#features)
- [Style Guide](#style-guide)
- [Resources](#resources)

Download
--------

```bash
git clone https://github.com/erictleung/beamer-theme
```

Features
--------

- Minimal style
- Ability to add graphics
- Ability to add PGF/TikZ plots
- Add two or three columns to slide
- Slide numbers
- `component.tex` file for common slide arrangements

Style Guide
-----------

See [Beamer User Guide][beamerguide] (Chapter 5 Guidelines for Creating
Presentations) for sensible advice on making presentations.

Some notable points:

1. Think of creating a global structure to presentation depending on length
2. If using a table of contents, make it comprehensible before the talk
3. "Do not inflict pain on other people"

**Make equations brief but understanable**

[BetterExplained][be] has a page on [Colorized Math Equations][colormath],
where an equation is broken up and colorcoded with a corresponding
easy-to-read description with matching colors for references the equation.

I really like this for displaying and explaining equations.

[beamerguide]: http://tug.ctan.org/macros/latex/contrib/beamer/doc/beameruserguide.pdf
[be]: https://betterexplained.com

Resources
---------

Other resources to create Beamer presentations.

- https://texblog.org/2011/05/03/beamer-an-introduction-to-latex-presentations/
- https://texblog.org/2013/01/21/side-by-side-content-in-beamer-presentations/
- https://www.sharelatex.com/learn/TikZ_package
- https://www.sharelatex.com/learn/Pgfplots_package
- https://www.sharelatex.com/learn/Lengths_in_LaTeX
- https://www.uncg.edu/cmp/reu/presentations/Charles%20Batts%20-%20Beamer%20Tutorial.pdf
