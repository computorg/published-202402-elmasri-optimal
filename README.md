# Optimal projection for parametric importance sampling in high dimensions

[![build status](https://github.com/computorg/published-202402-elmasri-optimal/workflows/build/badge.svg)](https://github.com/computorg/published-202402-elmasri-optimal/)
[![](https://img.shields.io/github/last-commit/computorg/published-202402-elmasri-optimal.svg)](https://github.com/computorg/published-202402-elmasri-optimal/commits/main)
[![DOI:10.57750/jjza-6j82](https://img.shields.io/badge/DOI-10.57750/jjza-6j82.svg)](https://doi.org/10.57750/jjza-6j82)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202402-elmasri-optimal/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202402-elmasri-optimal/)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202402-elmasri-optimal)
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

Authors:

- Maxime El Masri (ONERA and ISAE)
- Jérôme Morio (ONERA)
- Florian Simatos (ISAE)

We propose a dimension reduction strategy in order to improve the performance of importance sampling in high dimensions. The idea is to estimate variance terms in a small number of suitably chosen directions. We first prove that the optimal directions, i.e., the ones that minimize the Kullback--Leibler divergence with the optimal auxiliary density, are the eigenvectors associated with extreme (small or large) eigenvalues of the optimal covariance matrix. We then perform extensive numerical experiments showing that as dimension increases, these directions give estimations which are very close to optimal. Moreover, we demonstrate that the estimation remains accurate even when a simple empirical estimator of the covariance matrix is used to compute these directions. The theoretical and numerical results open the way for different generalizations, in particular the incorporation of such ideas in adaptive importance sampling schemes.


