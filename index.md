---
layout: default
---

<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.0/MathJax.js?config=TeX-AMS_CHTML">
</script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true},
      jax: ["input/TeX","input/MathML","input/AsciiMath","output/CommonHTML"],
      extensions: ["tex2jax.js","mml2jax.js","asciimath2jax.js","MathMenu.js","MathZoom.js","AssistiveMML.js", "[Contrib]/a11y/accessibility-menu.js"],
      TeX: {
      extensions: ["AMSmath.js","AMSsymbols.js","noErrors.js","noUndefined.js"],
      equationNumbers: {
      autoNumber: "AMS"
      }
    }
  });
</script>



# An Introduction to Robust Combinatorial Optimization

Welcome to this companion page to our book published with Springer, which you can find [here](https://doi.org/10.1007/978-3-031-61261-9).

The purpose of this page is to collect errors in the text, and to provide additional material that may be useful in designing a course around the book.

## How to cite the book

If you find the book useful, please cite us. The following bibtex entry can be used:

```bibtex
@book{robook,
author    = {Marc Goerigk and Michael Hartisch},
year      = {2024},
title     = {An Introduction to Robust Combinatorial Optimization},
subtitle  = {Concepts, Models and Algorithms for Decision Making under Uncertainty},
publisher = {Springer},
series    = {International Series in Operations Research \& Management Science},
volume    = {361}
}
```

## Errata

In addition to the errors that were in our manuscript, it turned out that the publisher's version contains many additional formatting problems. For the sake of completeness, we list each of them as part of the following table.

| page | error |
|:-----|:------|
|p65 | Reference [YGd19]: First author should be "İhsan Yanıkoğlu" |
|p88 | In (4.8), it should say $\min_{\pmb{x}\in\mathcal{X}}$ instead of $\min_{\pmb{x}\in\mathcal{U}}$ |
|p92 | $\Pi$ is sometimes in italics, sometimes not. It is the same symbol. |
|p110ff | $\mathbb{R}^{[n]}\_{\ge 0}$ should be $\mathbb{R}^n\_{\ge 0}$ (multiple cases in Section 5.2.1) |
|p117 | Corollary 5.11: $\Vert\pmb{x}\Vert_p$ should be $\Vert\pmb{v}(\pmb{x})\Vert_p$ |
|p127 | $\mathbb{Z}^{[n]}\_{> 0}$ should be $\mathbb{Z}^n\_{> 0}$ |
|p135 | author in [BGK23] should be Christina Büsing |
|p136 | author in [KZ06] should be Paweł Zieliński |
|p182 | author in [GKZ20], [GKZ22], [KKZ13], [KZ09], [KZ17] should be Paweł Zieliński |
|p205f | author in [KZ06], [KZ07], [KZ09], [KZ17], [KZ18], [Zie04] should be Paweł Zieliński |
|p246ff | $\mathbb{R}^{[n]}\_{\ge 0}$ should be $\mathbb{R}^n\_{\ge 0}$ and $\mathbb{Z}^{[n]}\_{\ge 0}$ should be $\mathbb{Z}^n\_{\ge 0}$ (multiple cases with different variants in Section 9.4 and 9.7) |
|p258 | author in [KKZ12b], [KZ14] should be Paweł Zieliński |
|p268 | $\mathbb{R}^{[K]}\_{\ge 0}$ should be $\mathbb{R}^K\_{\ge 0}$ |
|p272f | $\mathbb{Z}^{[n]}\_{\ge 0}$ should be $\mathbb{Z}^n\_{\ge 0}$ |
|p280ff | $\mathbb{R}^{[n]}\_{\ge 0}$ should be $\mathbb{R}^n\_{\ge 0}$ (multiple cases with different variants in Section 10.4) |

If you spot further mistakes, please contact us at <marc.goerigk@uni-passau.de>.


## Lecture notes

Below, we make LaTeX sources available for a potential Master's level, one-semester course based on our book. Each lecture represents a 90-minute session. Additionally, we provide exercises that can be done in a 90 minute tutorial class corresponding to each lecture. Please feel free to use and adapt to your own needs.

* [all lecture note sources](/notes/all.zip)
* [Lecture 1](/notes/01.zip)
* [Lecture 2](/notes/02.zip)
* [Lecture 3](/notes/03.zip)
* [Lecture 4](/notes/04.zip)
* [Lecture 5](/notes/05.zip)
* [Lecture 6](/notes/06.zip)
* [Lecture 7](/notes/07.zip)
* [Lecture 8](/notes/08.zip)
* [Lecture 9](/notes/09.zip)
* [Lecture 10](/notes/10.zip)
* [Lecture 11](/notes/11.zip)
* [Exercises](/notes/all-exercises.zip)

* * *

_Last update: 21 October 2024_
