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

| page | error |
|:-----|:------|
|p65 | Reference [YGd19]: First author should be "İhsan Yanıkoğlu" |
|p117 | Corollary 5.11: $\Vert\pmb{x}\Vert_p$ should be $\Vert\pmb{v}(\pmb{x})\Vert_p$ |

If you spot further mistakes, please contact us at <marc.goerigk@uni-passau.de>.


## Lecture notes

Below, we make LaTeX sources available for a potential Master's level, one-semester course based on our book. Each lecture represents a 90-minute session. Please feel free to use and adapt to your own needs.

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

* * *

_Last update: 04 October 2024_
